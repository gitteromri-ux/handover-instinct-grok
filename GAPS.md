# GAPS — what is NOT in this handover, who holds it, and what the new operator must do about it

Written 10 Oct 2026 18:00 Israel. This is the honest list. Everything below is either impossible for the previous operator to hand over (secrets, logins, other people's inboxes), or was never captured. The new tool should work this list in the first 48 hours and report each line as closed / open / blocked.

## A. Secrets and logins (never transferable through a document; must be re-issued by the holder)
| # | Item | Holder | Why it matters |
|---|---|---|---|
| A1 | Vercel env values of `lla-ac-events` (`META_PIXEL_ID`, `META_CAPI_TOKEN`/`META_ACCESS_TOKEN`, `AC_API_KEY`, `RELAY_URL`) and of `fa-leads-proxy` (`FA_CRM_STG_*`, missing `FA_CRM_PROD_*`) | Vercel dashboard (Omri's team) | CAPI Purchase/IC/ATC server events and AC enrichment stop if the token expires; nobody has recorded the token's expiry |
| A2 | Meta CAPI access token's owner and expiry (system user vs Omri's user token) | Meta Business Manager 1545475089051742 → System users / Events Manager → Settings | If it is Omri's personal token it dies with a password change |
| A3 | ActiveCampaign API URL + key | Sandra Kwiecien / eTeacher (Avivs@eteachergroup.com) | AC connector was broken at handover |
| A4 | eTeacher CRM production credentials for French Atelier (CF-Access id/secret + Authorization token for webapi2.eteacherapps.com) | eTeacher IT (Roberto Alvo named in logs) | FA checkout cannot charge until supplied |
| A5 | Cloudflare login / API token for account `gitter-omri` | Omri (Cloudflare dashboard) | Pages project `longevitylifeacademy`, Workers `eteacher-leads-proxy`, `lla-checkout` cannot be read or redeployed otherwise |
| A6 | Airwallex dashboard access (payments, refunds, settlements) and PayPal business account | eTeacher finance | Order-level reconciliation (B4) is impossible without it |
| A7 | GTM container GTM-PMRKXXJV owner identity | eTeacher (Google account unknown) | gitter.omri@gmail.com has zero GTM accounts |
| A8 | Registrar logins: Porkbun (frenchatelierlive.com) — Omri; AWS Route 53 (longevitylifeacademy.com) — eTeacher | as named | DNS changes |
| A9 | Resend account for FA Bastille/transactional mail | Omri | Only if FA emails are touched |
| A10 | Zoom account and webinar links for 27 Oct / 14 Nov sessions | eTeacher / Julie's team | Attendee emails, reminders, in-event upsell plan (master §7.1) |

| A11 | GitHub login for `gitteromri-ux` — passkey-only account; passkey lives on Omri's Windows PC (Chrome 22 Jul, Edge 14 Jun 2026); no password, no phone passkey, no usable 2FA app. Workaround in place since 10 Oct 22:50: write deploy keys on 94 personal repos (private Drive folder "PRIVATE — GitHub deploy keys 2026-10-10"). Org repos (live LLA site + masterclass) still need the PC login or an approved mirror-sync workflow. First time at the PC: github.com/login → Sign in with a passkey → settings/security → add password + phone passkey + download recovery codes | Omri | Without it, no change can be deployed to www.longevitylifeacademy.com or /julie-masterclass/ |

## B. Data and records never captured by the previous operator
| # | Item | Where it should come from | Status |
|---|---|---|---|
| B1 | Source code of the Cloudflare Workers `eteacher-leads-proxy` and `lla-checkout` — not found in any GitHub repo in the inventory (the Blueprint `_worker.js` lives in `lla-course-checkout`; the leads proxy may only exist in the Cloudflare dashboard) | Cloudflare dashboard → Workers → quick edit / `wrangler download` | OPEN — download and commit to a repo on day one |
| B2 | Source of the Vercel relays `lla-ac-events`, `fa-leads-proxy` — Vercel "Git repository" field was not readable with the connector token; may be CLI-deployed from a local folder with no repo | Vercel dashboard → project → Settings → Git; else `vercel pull` + download the deployment source | OPEN — same action as B1 |
| B3 | ActiveCampaign automations, lists, tags and the live masterclass/Blueprint email sequences as they actually run in AC (names, triggers, send counts) — only the field model (206/216/217/223/224) is documented | AC dashboard once A3 is solved | OPEN |
| B4 | Order-level truth table: Meta-attributed purchases ↔ CRM paid orders ↔ Airwallex/PayPal settlements ↔ refunds, for 24 Sep → today, QA orders removed | CRM export (Anant/Roberto), Airwallex (A6) | OPEN — never completed; all Meta "purchase" counts in the handover are events, not money |
| B5 | CRM course / price-plan IDs used by the masterclass checkout (`PreferredCourseId`, `MainAbroadCourseId`, `AbroadCourseId`, price-plan ids for $49/$79) — embedded in `Longevity-Academy/julie-masterclass` JS and `lla-course-checkout` code (Blueprint uses 168663), not extracted into a table | grep the two repos: `PreferredCourseId`, `AbroadCourseId`, `pricePlan` | OPEN — 20-minute task |
| B6 | WhatsApp history with Harel Tayeb, Julie Gibson Clark's team, Philippe Hernandez, Sandra, Roberto — the operator never had access; all "Harel asked for X" items came through Omri | Omri's phone | NOT TRANSFERABLE — the new tool starts cold on relationships |
| B7 | eTeacher work mailbox Omri.Gitter@eteachergroup.com — never connected; Teams invites, CRM exports and internal threads land there | Omri (Microsoft 365 login) | OPEN — connect it in the new tool |
| B8 | Perplexity thread transcripts (≈ 60 task threads Jul–Oct) — only their outcomes are summarised in `handover-master` and `memory-pages/`; the 30 Sep "428-file Claude migration ZIP" was described but its location is unknown | Perplexity library (Omri's account) | PARTIAL — if needed, export from perplexity.ai/computer |
| B9 | Full placement/age/gender/device breakdowns per ad set for the whole 24 Sep → 10 Oct window — only the 7–9 Oct iPhone/age reads are in the 9 Oct handover | Meta insights with breakdowns (new tool can pull) | OPEN — pull on day one, it is the basis of every targeting argument |
| B10 | Facebook Page post performance (reach/reactions/comments) for the 9 ad posts — connector permissions blocked reactions/comments | Page admin in Meta Business Suite | OPEN |
| B11 | Meta Business Manager roles: who is admin on 1545475089051742, 1489173449541995; which users/partners have access to act_1459085242361281 | Business settings | OPEN — the new tool must be added by an admin |
| B12 | Julie Gibson Clark's contract/approval scope for ads and the "approval letter" status (lla-julie-letter) | Omri / eTeacher | USER-HELD |
| B13 | French Atelier production Meta pixel — none exists; FA accounts act_1188017096669618 / act_1358975119724184 history not reviewed since August | Meta | OPEN |
| B14 | Blueprint release-audit fixes (5 blocker-class items in master §7.2) — findings exist, fixes were not approved or built | `lla-course-checkout` (private) | OPEN |
| B15 | Investor / CEO October turnaround email — drafted in a Perplexity thread, not in any repo, not sent | Perplexity thread "Sales and Budget Spend vs CEO Plan" (5 Oct) and memory page `lla-october-turnaround` | PARTIAL |

## C. Known weaknesses of the master document itself
- Numbers are time-stamped reads, not a live feed: set 5's budget moved from $499 (14:26) to $619 (17:40) during the writing of this handover. Re-pull before quoting anything.
- "Purchases" everywhere = Meta pixel/CAPI events after QA exclusion by the relay, not unique buyers, not settled money (see B4).
- French Atelier capsule price tiers (+$10 per level) are ASSUMED from a staging read, not confirmed by Philippe/Omri.
- The relay source location (B2) and worker source (B1) are ASSUMED to be outside GitHub.
- `github.com/.../blob/...` pages returned 503 from the previous operator's sandbox; raw URLs and `git clone` were verified. If a tool cannot open a blob page, use raw.
- The repo-activity list (master §8) counts commits since 10 Jul per repo via the GitHub API; force-pushes and squashes make some counts low (e.g., `club-italia` shows 1 on `master` while `main` carries v16).
- The 36-project June–August inventory lives in `handover-master/_inventory.md` and was not re-verified today.
- The previous operator's own reliability record is in `julie-masterclass-handover-2026-10-09.md` §0 and §9 and in `gitteromri-ux/serious-claims` / `lawsuit`; read them before trusting any ASSUMED line.

## D. First-48-hours checklist for the new operator (in this order)
1. Sign in everywhere (INSTINCT.md §3 / GROKBOT.md §3); report one line per service.
2. B1 + B2: download and commit the Worker and relay sources; record token expiries (A1, A2).
3. B9: pull full breakdowns for 24 Sep → today; publish the first daily read at 09:00.
4. B5: extract CRM course/price-plan IDs into a table in this repo.
5. B4: request the CRM order export and Airwallex settlement report; build the truth table; replace every "purchases" figure in the CEO report with settled orders.
6. B7: connect the eTeacher mailbox. B11: get added to Business Manager.
7. Before 26 Oct: prepare (do not execute) the post-freeze list — adGroupID repair on set 3 Ad#12 / set 5 copies, compact-pricing mobile branch decision, Blueprint audit fixes — each with Army General gate answers for Omri.
8. 27 Oct 7 PM ET and 14 Nov 1 PM ET: event-day plan (Zoom links, reminders, in-event enrollment, post-event upsell to the Blueprint) — none of this exists yet beyond the design goal in master §7.1.
