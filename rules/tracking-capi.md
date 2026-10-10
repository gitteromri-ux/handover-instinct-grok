# Meta pixel + CAPI verification

## Required invariants
- Every browser event and its CAPI twin share the same `event_name` and `event_id` (dedup). Purchase event_id = order ID.
- `fbc`: use `_fbc` cookie; if missing and URL has `fbclid`, build `fb.1.<ms_timestamp>.<fbclid>` and persist it as `_fbc` (90 days). Never read only the cookie. `fbp` from `_fbp`.
- Send `client_ip_address`, `client_user_agent`, `event_source_url`, `action_source=website`, and hashed (SHA-256, normalized) em/ph/fn/ln/external_id when known.
- Purchase fires only after confirmed payment (not on click/redirect), with numeric `value` equal to the charged amount and correct `currency`.
- One pixel/dataset ID per brand; confirm the ID against handover-master before editing.

## Verification matrix (run and report every row)
| Check | Method | Pass |
|---|---|---|
| Pixel loads | browser network: `facebook.com/tr` | 200, correct pixel ID |
| Browser events | PageView, ViewContent, AddToCart, InitiateCheckout, Purchase | each fires once |
| CAPI events | server logs / Events Manager Test Events with test_event_code | each received |
| Dedup | Events Manager "deduplicated" | same event_id both sides |
| fbc coverage | land with `?fbclid=TEST123` then AddToCart | fbc present on browser + CAPI |
| Match quality | Events Manager EMQ | >= 6 for Purchase |
| Attribution | ad set settings | window matches plan across ad sets |

Report as a table with VERIFIED / FAILED / NOT TESTED. Never infer CAPI health from the browser side alone.
