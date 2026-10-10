# MASTER HANDOVER — Omri Gitter / Gita Agency → Instinct and Grok Bot

**Compiled:** Saturday 10 October 2026, ~17:30 Asia/Jerusalem, by Perplexity Computer at Omri Gitter's instruction.
**Purpose:** let a new AI operator (Instinct, Grok Bot, or any other) take over every live system, project, rule and open item from the last three months (10 July → 10 October 2026) from one prompt, with no questions back to Omri.
**Public link:** https://github.com/gitteromri-ux/handover-instinct-grok/blob/main/MASTER-HANDOVER-2026-10-10.md
**Raw (paste into any tool):** https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/MASTER-HANDOVER-2026-10-10.md

Evidence labels used throughout: **VERIFIED** = read from a system of record in this session (Meta Graph API v25, GitHub API, Vercel API, live HTTP, DNS, Gmail/Calendar/Drive connectors). **DOCUMENTED** = from the handover-master repo or the operator's memory pages (written in earlier sessions, not re-checked today). **USER-STATED** = Omri's words. **ASSUMED** = interpretation. Nothing marked VERIFIED should be acted on without a fresh pull; Meta numbers move hourly.

---

## 0. One-prompt takeover (copy this into the new tool first)

### 0.1 Prompt for Instinct (WhatsApp / iMessage / email agent)

> You are now Omri Gitter's operator for Gita Agency. Read, in this order: (1) https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/MASTER-HANDOVER-2026-10-10.md (this document, the index), (2) https://raw.githubusercontent.com/gitteromri-ux/handover-master/main/_global-rules.md, (3) https://raw.githubusercontent.com/gitteromri-ux/handover-master/main/projects/julie-tracking-freeze/README.md, (4) https://raw.githubusercontent.com/gitteromri-ux/handover-master/main/julie-masterclass-handover-2026-10-09.md, (5) https://raw.githubusercontent.com/gitteromri-ux/handover-master/main/_today-log.md (newest entries at the bottom). Apply the rules in section 3 of the master document to every reply. Never touch anything listed under GOLDEN tracking (section 4) before 26 Oct 2026. Before any live change on Meta, a website, DNS, Vercel, Cloudflare, ActiveCampaign or checkout, write the four Army General gate answers and wait for Omri's explicit "go". Label every statement VERIFIED / USER-REPORTED / ASSUMED. Report in short, number-led messages with entity names and IDs. Omri writes in English and Hebrew; answer in the language he uses. Confirm you have read all five files by replying with: the live daily budgets of masterclass sets 1, 3, 4, 5; the pixel ID; the CAPI relay URL; the freeze end date; and the three things you still need from Omri (section 12).

### 0.2 Prompt for Grok Bot (always-on agent with its own cloud computer)

> You are Omri Gitter's always-on operator for Gita Agency (Longevity Life Academy, French Atelier, Club Italia, Gita clients). Start by cloning https://github.com/gitteromri-ux/handover-master and reading MASTER-HANDOVER-2026-10-10.md, _global-rules.md, projects/julie-tracking-freeze/README.md, julie-masterclass-handover-2026-10-09.md and _today-log.md. Then sign in, with the credentials Omri gives you in your secure vault (never in chat), to: GitHub (accounts gitteromri-ux and org Longevity-Academy), Vercel (team "GITTER", slug gitter1), Cloudflare (account with Pages project `longevitylifeacademy` and Workers `eteacher-leads-proxy`, `lla-checkout`), Meta Business Suite / Ads Manager (ad account act_1459085242361281 under eTeacher Group LTD business 1545475089051742), Gmail gitter.omri@gmail.com, Google Drive, ActiveCampaign (eteachergroup.api-us1.com), Google Tag Manager (container GTM-PMRKXXJV). Verify each login read-only and report what you can and cannot see. Standing jobs: (a) every morning 09:00 Israel, pull Meta campaign 52668266203628 by ad set for yesterday and today (spend, impressions, CPM, LPV, ATC, IC, Purchase, Purchase value, learning status, last significant edit) excluding QA orders, and post it; (b) watch GitHub Pages builds for Longevity-Academy/julie-masterclass and Longevity-Academy/Longevity-Academy.github.io and alert on failure; (c) append a dated entry to handover-master/_today-log.md after any change you make (repo, SHA, rollback). Hard rules: section 3 and 4 of the master document. No live change without Omri's explicit written go per item. Never change optimization goal, pixel, attribution, url_tags, or anything in the GOLDEN list before 26 Oct 2026. Never show a number that can include test/QA orders.

### 0.3 Reading order for a human taking over

1. This file (index, access, rules, current state).
2. `_global-rules.md` (house rules, verbatim).
3. `projects/julie-tracking-freeze/README.md` + `golden.json` (what is frozen and why).
4. `julie-masterclass-handover-2026-10-09.md` (Julie campaign, hour by hour, with the 9 Oct reliability warning).
5. `projects/julie-meta-handover-20260930/HANDOVER-JULIE-BLUEPRINT-20260930.md` (Blueprint campaign + checkout tracking truth table).
6. `_today-log.md` (every change since September, newest at bottom).
7. `HANDOVER.md` + `_inventory.md` + `projects/*.md` (older projects, June–September).

---

## 1. Who is who

| Person / entity | Role | Contact (as seen in Omri's mailbox/calendar) |
|---|---|---|
| **Omri Gitter** | Owner of Gita Agency; marketing/project owner for eTeacher's Longevity Life Academy (LLA) and French Atelier; builds and operates sites, funnels, Meta ads, tracking, reporting | gitter.omri@gmail.com (primary, all connectors), Omri.Gitter@eteachergroup.com (eTeacher mailbox), GitHub `gitteromri-ux`, Meta user "Gitter Omri" 10165945960459853, WhatsApp channel used for LLA support 12015023701 (DOCUMENTED, assumed also for FA) |
| **eTeacher Group LTD** | Client/parent company (Ramat Gan IL; eTeacher Inc. NY). Owns LLA, French Atelier (with Acadomia), Club Italia, Rosen School of Hebrew, Israel Bible Center. Owns Meta business 1545475089051742, the CRM (webapi2.eteacherapps.com), Airwallex, ActiveCampaign account | — |
| **Harel Tayeb** | eTeacher CEO; recipient of CEO reports/board decks; requested the Support page and app-store package (7 Oct) | via WhatsApp (DOCUMENTED) |
| **Keren Ziv** | eTeacher; organizes "Status Meeting – Eteacher/Acadomia" (next: Wed 14 Oct 2026, 11:30–12:00 Israel, Microsoft Teams); on Longevity Score App privacy-policy thread | keren.ziv@eteachergroup.com |
| **Eyal Feldman, Ehud Ashkenazi, Shemi Fester** | eTeacher; privacy policy for Longevity Score App thread (24–27 Sep) | eyal.feldman@, ehud.a@, shemi.fester@eteachergroup.com |
| **Gabriella Nemeti** | eTeacher; "Longevity Ecommerce Reminder Email" / Blueprint reminder emails (18–22 Sep); attends Acadomia status | gabriellan@eteachergroup.com |
| **Roberto Alvo, Meshi Meiselmann** | eTeacher; on Blueprint reminder-email thread; Roberto named as CRM/IT contact in logs | Robertoa@, meshim@eteachergroup.com |
| **Sandra Kwiecien (Aviv)** | eTeacher; ActiveCampaign owner — the AC field model (`LGV_checkout_events`, `LGV_Product_Event`) is "Sandra's"; approved masterclass email names | Avivs@eteachergroup.com |
| **Anant** | eTeacher CRM reporting contact (reports by `adGroupID`) | DOCUMENTED, no email seen |
| **Ayelet Rund Kolnik, Daneal du Plessis** | eTeacher; Acadomia status attendees | ayeletr@, daneal.p@eteachergroup.com |
| **Philippe Hernandez, Craig Taylor** | Acadomia (French Atelier partner); status meeting attendees; Philippe reviews FA checkout/capsules | philippe.hernandez@, craig.taylor@acadomia.fr |
| **Julie Gibson Clark** | LLA founding faculty; "2nd slowest-aging woman" (Rejuvenation Olympics); presenter of the Oct 27 live masterclass | — |
| **Courtney Donofrio** | LLA presenter (Blueprint films/banners) | — |
| **Uri Livne** | Daily 10:00 Israel "Uri/Omri" Google Meet (recurring) | urilivne1971@gmail.com |

Brands and products:
- **Longevity Life Academy (LLA)** — www.longevitylifeacademy.com. Products: **The Longevity Blueprint** (full course, $279/mo list, $179/mo in ad copy, $249 credit code for VIP; CRM `PreferredCourseId 168663`, Oct 2026 cohort) and **Julie Gibson Clark Live Masterclass** (live Zoom event **27 Oct 2026, 7:00 PM ET**; Standard $49 / VIP $79; CRM course "Longevity Masterclass" $79; Standard is a discount on it).
- **French Atelier by Acadomia** — www.frenchatelierlive.com (live-online French school). Culture Capsules (3 packs × 10 live conferences). Checkout exists on staging only.
- **Club Italia by eTeacher** — https://gitteromri-ux.github.io/club-italia/ (CEO-review site, v16 on `main`).
- **Gita Agency** — Omri's agency brand (Meta business "Gita Agency" 1489173449541995; Facebook page "Gita Marketing agency" 834843056374699).

---

## 2. Access matrix — every system, how it was connected, what the next operator needs

No secrets are in this document. Every connection below was an OAuth connector or platform-issued token inside Perplexity Computer; none of those tokens transfer. Omri must issue new credentials to the new tool (preferably into its vault, never in chat).

| System | Account / identifiers (VERIFIED today unless noted) | How Perplexity was connected | Status today | What the new tool needs |
|---|---|---|---|---|
| **GitHub** | User `gitteromri-ux` (139 repos; 95 pushed since 10 Jul). Org `Longevity-Academy` (repos `julie-masterclass`, `Longevity-Academy.github.io`, `lla-checkout-live`). Pages hosting for www.longevitylifeacademy.com and www.frenchatelierlive.com | OAuth connector → `gh`/`git` CLI; commits via git-agent-proxy | Working | Fine-grained PAT or GitHub App with repo+pages+workflow on both accounts |
| **Vercel** | Team **GITTER**, slug `gitter1`, team id `team_QsIIEvdvnmtyD40s3mcnka6k`; 52 projects (list §9). Critical: `lla-ac-events` (prj_3v7g4Xwve6OmXrcPCVQOWJOiN2SK, CAPI relay), `fa-leads-proxy` (prj_byAoWWUN5aXdGDrGRb7PJ25hINlI, FA lead/ecomm relay), `fa-staging-checkout` (prj_xluo8z01uYC5bnbHzgWZpxVozk6I), `fa-staging-light` (prj_VL9P72MT1ZQ5nsb6rdbITX90BzED) | Vercel connector token (project list readable; `project inspect` denied) | Working, limited. "New sign-in detected" 9 Oct; "Approaching your limits" warning 7 Oct (Hobby plan) | Vercel token scoped to team gitter1 with deployments+env read; note runtime logs needed a higher scope (403 before) |
| **Cloudflare** | Account `gitter-omri` (workers.dev subdomain `gitter-omri.workers.dev`). Pages project **`longevitylifeacademy`** → https://longevitylifeacademy.pages.dev (Blueprint checkout surface; production deployment `fbb15ba2` on 7 Oct). Workers: `eteacher-leads-proxy` (CRM lead/order proxy), `lla-checkout` (`lla-checkout.gitter-omri.workers.dev`, checkout worker; `_worker.js` sets `_fbc/_fbp` 90 d) | Pipedream connector with API token | **Broken**: connector expects Global API Key, token was supplied ("Invalid format for X-Auth-Key") | API token with Pages:Edit, Workers Scripts:Edit, Workers KV, Account Analytics:Read — or Global API key + email. Note DNS is NOT at Cloudflare (see Hosting §5) |
| **Meta (Ads/Business)** | User "Gitter Omri" 10165945960459853. Ad accounts: **act_1459085242361281 "Longevity Life Academy"** (business **ETeacher Group LTD 1545475089051742**, tz Asia/Jerusalem, USD) — the only live one; act_1188017096669618 "French Atelier" (eTeacher, NY tz); act_1358975119724184 "French Atelier v2"; act_950981877715538 "LLA – Old" (Gita Agency); act_570542045255370 "Gitter Omri" personal. Pages: Longevity Life Academy **1179505785236150**, French Atelier 677053902156593, Gita Marketing agency 834843056374699, Keren Or Farm 1350914481603601. Pixel/dataset **1440305917310328** (last fired 10 Oct 02:49 IDT, first-party cookies on, advanced matching em/fn/ln/ge/ph/ct/st/zp/db/country/external_id). Permissions granted: ads_management, ads_read, business_management, pages_show_list, pages_read_engagement, pages_manage_ads, leads_retrieval | Meta Ads connector (Meta's Ads MCP `ads_*` tools) + `meta` CLI + Graph API v25 through a credential proxy, all under Omri's user token | Working | Marketing API system-user token on business 1545475089051742 with ads_management + business_management, or Omri's own login for the new tool; Events Manager access for the dataset; Page admin for 1179505785236150 (needed to delete videos / read posts) |
| **Gmail + Google Calendar** | gitter.omri@gmail.com | Google connector (search/draft/send; calendar read/write) | Working | Google OAuth for the new tool. Work mailbox Omri.Gitter@eteachergroup.com was never connected |
| **Google Drive / Sheets / Docs** | gitter.omri@gmail.com Drive | `gws` CLI connector | Working | Same Google OAuth |
| **ActiveCampaign** | Account `eteachergroup.api-us1.com` (eTeacher-wide, shared with other schools). Fields used: `LGV_checkout_events` (206), `LGV_Product_Event` (Regular/VIP), order id (216), student id (217), product (223), `LGV_Masterclass_Session_Date` (224, Date, `YYYY-MM-DD`). Masterclass relay writes stage field only to existing contacts | Pipedream connector; API key was also used directly in Vercel relay env | **Broken** connector today ("Invalid URL" — base URL not set). API key lives in Vercel env of `lla-ac-events` (`AC_API_KEY`) | AC API URL + key from Sandra/eTeacher. Scope rule: AC tactics need Omri's explicit reopening |
| **Google Tag Manager** | Container **GTM-PMRKXXJV** on the Blueprint checkout (pages.dev) | Pipedream connector | Connected but **sees zero accounts** (connected Google identity has no GTM access) | GTM access for the right Google account (likely eTeacher's) |
| **eTeacher CRM API** | `webapi2.eteacherapps.com` behind Cloudflare Access (CF-Access id/secret + Authorization token). Reached only through Worker `eteacher-leads-proxy` (LLA) and Vercel `fa-leads-proxy` (FA, staging creds only: `FA_CRM_STG_*`; production `FA_CRM_PROD_CF_ID/CF_SECRET/TOKEN` missing) | Never direct; via relays | LLA production path working; FA production path = reserve mode | Production CF-Access pair + token for FA from eTeacher IT (August pair was rejected) |
| **Airwallex** | eTeacher's account; drop-in on masterclass + Blueprint checkout; `card`, `applepay`, `googlepay` active (9 Oct read); Apple domain file served on www | None (client-side only) | Working | Nothing unless refunds/settlement reconciliation is needed → eTeacher finance |
| **Resend** | Sends FA Bastille callback emails (`onboarding@resend.dev`) | None (account emails only) | — | Resend login if FA transactional mail is touched |
| **Higgsfield** | Image/video generation (UGC, capsule clips) | Connector | Working | Optional |
| **Facebook Pages (Pipedream)** | Posting/reading page posts | Connector | Working | Optional |
| **DocuSign, Jotform, Wix, Finance, PitchBook, EBSCO, Midpage** | Connected but unused in the last 3 months (Wix/Jotform temporarily unavailable today) | — | — | Not needed for current work |
| **Dub Links, Metaview, Metabase, Microsoft 365, Pipedrive, Smartsheet** | Disconnected | — | — | Not needed |
| **Perplexity itself** | Memory wiki (`memory/knowledge/*`), user skills `omri-operator-os`, `gita-design`, `ui-ux-pro-max`, `viral-design-director`; threads listed in §11 | — | Ends with this handover | The rules are reproduced in §3 so nothing depends on Perplexity |

---

## 3. The rules (most current; apply to every task and every reply)

Source of truth: `_global-rules.md` in handover-master and Omri's "Operator OS" skill (set 2026-09-25 → 2026-10-03). Verbatim essentials:

### 3.1 Army General (2026-10-03, overrides everything else)
Mission = Omri winning the overall campaign, never the sub-task. Named failure: **"Screwing Me Over"** — recommending or executing a decision that cannot absorb a mistake (live ad sets, budgets, placements, tracking, checkout, client deliverables) without having looked at the data that could prove it wrong (2026-10-03: an overlay placement copied into four live sets without a placement breakdown bought 190 visits, 0 sales, then removing it sent every set into review). Before any recommendation or change on a decision-critical system, answer in writing, in the reply:
1. Does this make Omri win the overall mission for sure? Yes/no with evidence pulled this session.
2. Cost of error: what breaks, time to undo, spend, learning, review time, target slippage.
3. Every factor: history of previous attempts, tomorrow's behaviour, effect on targets/commitments, where it hurts, where it wins, interaction with every connected system.
4. Recommendation with risk level. Never a menu without a recommendation.
If anything is unverified: pull data first; if impossible, say what is missing and the cost of deciding blind.

### 3.2 Rule zero (2026-09-30): every answer costs money
Hold the whole picture before replying; reply once, complete. State nothing as fact that is not verified in this session; predictions carry certainty, basis and check time. Never write a sentence that will need a correction. Proactively name what Omri is about to miss. When live changes are made on his word, report the result the moment the system of record shows it, and report daily for every live set he pays for (spend, CPM, visits, checkouts, purchases, with names and IDs).

### 3.3 GitaWinMode (always on)
Never Lie · No Loop (a failed attempt needs a materially stronger method) · Best Tool First (search for and use the strongest specialist tool/API; name the missing connector once) · #Critical (widest investigation, check prior failed attempts and current live changes first) · No test data in any number · Hardest decision-critical item first · no apology loops, no progress narration.

### 3.4 Change safety (production-affecting = live site, main branch, DNS, Cloudflare, Vercel prod, Meta pixel/CAPI/dataset, ad sets or budgets, AC automations/lists, payment/checkout, emails to real people)
Classify read-only / reversible draft / production-affecting. For production: snapshot before (JSON/commit/tag), explicit approval per item ("go" for this exact item, not a general "yes"), one change at a time, read-back verification, rollback path written, then a `_today-log.md` entry (repo, what, SHA, rollback). Isolated review surfaces (branch + Vercel preview/staging) before anything touches live. Never merge a review branch to main without "publish"/"approve".

### 3.5 Definition of done
"Done/live/fixed" only with proof produced this session: URL + HTTP status, screenshots desktop + 390 px mobile, commit SHA, Meta Test Events/Events Manager result, AC contact state, or command output. Label each claim VERIFIED / USER-REPORTED / ASSUMED.

### 3.6 Meta ads rules (Omri's, firm — USER-STATED 9 Oct + playbook)
- Purchase optimization stays. No change of optimization goal or "intent level". No broad audiences. No Instagram feed. No untested UGC in the main sets. Do not pause live ad sets. Budget edits: desktop Ads Manager only, one save (the Android app produced phantom saves and resets).
- Plain set names ("set 3", "set 5"); no code words. Every number excludes QA/test orders.
- No live change without an explicit, item-specific go; timing matters (20:44 on 3 Oct).
- Playbook (`references/meta-ecom-playbook.md`): Andromeda creative-first delivery; 50-event learning floor; cost-cap zero-delivery rule; placement price benchmarks; daily read mandatory; pull Meta's own guidance via `meta ... guidance list`. Meta "Add music"/enhancements stay OFF (not Reels-only). One banner = separate static-feed ad + 15 s 9:16 Reels video ad.
- Reporting contract: ad account runs on Israel time; same-period economics (don't move early-morning purchases to yesterday's spend); whole-campaign CPA includes paused-set spend; Meta-attributed purchases ≠ unique paid buyers ≠ CRM-settled orders.
- Scope: recommendations limited to Meta direct purchases; ActiveCampaign and other tactics need explicit reopening.

### 3.7 Design and copy bar
Premium, brand-aligned, never template-looking; render and inspect before sharing; mobile 390 px check; type floors (LLA/FA: no text under 15 px mobile; FA staging bullets ≥1.15 rem). Copy names product, provider, price and date; no invented scarcity or asks. Exact brief fidelity; locked assets; only selected finals uploaded. Hebrew RTL when he writes Hebrew. Excel: LTR, large upright fonts, fixed-layout fallback.

### 3.8 Working style
Hebrew or English as he writes. Short, number-led, plan/actual/forecast labelled. Public links + WhatsApp-copyable raw URLs. Warn proactively when a thread is slowing down or losing context. Isolated review and explicit agreement before anything external. He rejects "learning phase" as an explanation without new data.

---

## 4. GOLDEN tracking and CAPI — frozen until 26 Oct 2026

Source: `projects/julie-tracking-freeze/README.md` + `golden.json` (tag `tracking-golden-20260928` on `Longevity-Academy/julie-masterclass`), `references/tracking-capi.md`, §3A/3B of the 9 Oct handover. Frozen 28 Sep 15:30 IDT → **26 Oct 2026**; extend only on Omri's explicit word; release only per named item.

**Frozen (do not change, redeploy, duplicate-and-edit, "optimize", or re-tag):**
- Pixel/dataset **1440305917310328** on all masterclass + Blueprint sets; optimization OFFSITE_CONVERSIONS/PURCHASE; attribution 7-day click / 1-day view (set 2 also 1-day engaged view).
- Ad links `https://www.longevitylifeacademy.com/julie-masterclass/?preview=zoom-link-sample` and the "golden" `url_tags`: `cid=118149&adGroupID=<CRM set id>&utm_source=Facebook&utm_medium=Topic&utm_campaign={{campaign.id}}&utm_term={{adset.id}}&…`. Known defect, repair NOT authorized: set 3 Ad#12 `52670183445628` and set 5 copies carry `adGroupID=108813` (set 1's id).
- Site tracking files in `Longevity-Academy/julie-masterclass`: `index.html` pixel gate, `assets/julie-meta-tracking.js` (release `julie-meta-20260927-4`), `assets/julie-payment-safety.js` (price validation; 9 Oct appearance change was approved separately), `assets/julie-international-checkout*.js`.
- CAPI relay **`https://lla-ac-events.vercel.app/api/meta/capi`** (Vercel `lla-ac-events`; env `META_PIXEL_ID`, `META_CAPI_TOKEN`/`META_ACCESS_TOKEN`, `AC_API_KEY`, `RELAY_URL`): refuses `qa=1` traffic (`qa_excluded`), sends `event_id` = order id so browser and server Purchase dedupe.
- Blueprint checkout (`gitteromri-ux/lla-course-checkout` → Cloudflare Pages `longevitylifeacademy`): `_worker.js` re-issues `_fbc/_fbp` 90 d; PageView/ATC/IC/Purchase fire fbq + relay with shared `event_id`; `fbclid` sent byte-exact (no URL-decoding); IC fires after CRM staging (`eteacher-leads-proxy /api/lead/ecomm`) or 7 s fallback; GTM `GTM-PMRKXXJV`.
- Custom conversions on the pixel (VERIFIED): LLA Julie Masterclass Purchase 1426010666308623 / InitiateCheckout 1099790382424644 / AddToCart 1417373073897207; LLA Blueprint (pages.dev) Purchase 1786158289389247 / IC 1434992078766510 / ATC 1125972029763023.

**Known tracking facts (VERIFIED/DOCUMENTED):**
- 4 Oct: Ads Manager "Pixel issue / Event not deduplicated". Diagnosis: every Purchase arrived Browser 1 + Server 2, because Meta's business-level "Conversions API with Meta" (opted in 30 Apr 2026, auto-connected 24 Jun) sent a third copy. Omri toggled the LLA dataset row to Connected: No in Business Manager → web_conversions_api → Manage datasets (14:11 IDT). Since 5 Oct Purchases read Browser 1 / Server 1. Rollback = same toggle. Not caused by any site code.
- Events Manager warning "Server sending modified fbclid value in fbc parameter" was fixed on the Blueprint checkout (byte-exact fbclid). AddToCart/IC match quality reported 9.3. ~80% of masterclass Purchases carry fbc, 100% fbp (code audit; no release to "repair" the 20%).
- The ViewContent click-ID percentage cannot be applied to Purchase; Purchase dedup and settled-order attribution are separate proofs.
- A live $49 purchase + refund end-to-end test was offered twice; Omri never supplied a card. No end-to-end paid Purchase has been traced from a real ad click to a settled CRM order by the operator.

**QA / test identifiers that must be excluded from every business number (DOCUMENTED):**
- Masterclass unpaid QA orders: 8046536, 8046537 (students 11665235/11665236), 8046603, 8046609, 8046670, 8046672, 8046729, 8046742, 8046744, 8046748, 8046749, 8046753, 8046755; QA emails `gitter.omri+qa-*@gmail.com` (AC still sends abandoned-cart mails to them — visible in Gmail today).
- Paid-status orders used as evidence (real paid, not tests): Regular 8045443, VIP 8045550; Reston order 8044247 double-counted once.
- Meta test sets (PAUSED since 28 Sep): `TEST_controlled-purchase_TLV…` 52668956239228, `TEST2_…` 52668961777228.
- FA staging orders are in eTeacher **staging** CRM only (e.g., 8041844–8041863).

**Verification matrix before reporting any tracking claim:** Events Manager source split per event (Browser/Server/dedup) → pixel `/stats` by `event_source` → relay response (accepted/rejected/excluded) → CRM order id → Airwallex/PayPal settlement → Ads Manager ad-set attribution. A synthetic replay, a 202 from the relay, or a Test Events hit is not proof of any of the later stages.

---

## 5. Live production map (hosts, repos, deploy, rollback) — VERIFIED today where marked

| Surface | URL (status today) | Source repo / branch | Hosting | Deploy | Rollback |
|---|---|---|---|---|---|
| LLA marketing site | https://www.longevitylifeacademy.com/ (200, server GitHub.com) | `Longevity-Academy/Longevity-Academy.github.io` main (133 commits since 10 Jul; last 7 Oct "Blog: In the press fold") | GitHub Pages; DNS **AWS Route 53** (ns-*.awsdns-*, eTeacher-managed), apex A → GitHub IPs, www CNAME → longevity-academy.github.io | push to main (~1 min build, 600 s cache) | `git revert` |
| Julie masterclass page + checkout | https://www.longevitylifeacademy.com/julie-masterclass/ (200) | `Longevity-Academy/julie-masterclass` main @ `058c1f0` (9 Oct payment-form appearance). 196 commits since 10 Jul | GitHub Pages (project site under the org domain) | push to main | `git revert 058c1f0 86a4751`; golden tag `tracking-golden-20260928` |
| Blueprint sales page + 3-step checkout | https://longevitylifeacademy.pages.dev/ (200, Cloudflare) and mirror `/blueprint` on www | `gitteromri-ux/lla-course-checkout` (private, 213 commits; live build = branch `fix/privacy-20260927`/`fix/support-20261007`); org mirror `Longevity-Academy/lla-checkout-live` | Cloudflare Pages project `longevitylifeacademy` (prod deployment `fbb15ba2` 7 Oct; previous `3d77867f`) | `wrangler pages deploy dist` | promote previous deployment |
| Support pages (CEO request 7 Oct) | /support/ on www, /julie-masterclass/support/, pages.dev/support (all 200, white shell) | the three repos above (`df1d457`, `18956f3`, `83bd1e6`) | as above | — | revert commits |
| CAPI relay | https://lla-ac-events.vercel.app/api/meta/capi (405 on GET = alive) | source in Vercel project `lla-ac-events` (not in a GitHub repo as far as the records show — ASSUMED; check Vercel "Source") | Vercel team gitter1 | Vercel dashboard/CLI | promote previous deployment |
| eTeacher CRM proxy (LLA) | Worker `eteacher-leads-proxy` (routes `/api/lead/ecomm`, `/api/checkout/details`, `/api/checkout/payments/crm` — DOCUMENTED) | Cloudflare account gitter-omri | Workers | `wrangler deploy` | previous version in dashboard |
| French Atelier live site | https://www.frenchatelierlive.com/ (200, GitHub.com) | `gitteromri-ux/french-atelier` main @ `c5f6111` (7 Oct capsules.html syllabus alignment; checkout reverted at `34f7601`); backup tag `backup/20261007-capsules-syllabus` | GitHub Pages; DNS **Porkbun** (ns.porkbun.com), www CNAME → gitteromri-ux.github.io | push to main | revert `c5f6111` |
| FA checkout staging (dark "Midnight") | https://fa-staging-checkout-gitter1.vercel.app (noindex) | `gitteromri-ux/french-atelier` branch `staging-checkout` (also mirrored as `fa-staging` in logs) | Vercel `fa-staging-checkout` | `/tmp/redeploy.sh` pattern = `vercel deploy --prod` from branch | redeploy from `ad6346e` (v3) |
| FA checkout staging (light "Paper & Gold") | https://fa-staging-light-gitter1.vercel.app | same branch, hostname selects theme | Vercel `fa-staging-light` | same | same |
| FA lead + ecomm relay | https://fa-leads-proxy.vercel.app (`/api/ecomm/health` 200; `/leads/production`, `/api/lead/ecomm`, `/api/checkout/*`, `/staging/*`) | Vercel `fa-leads-proxy` (prod deployment `dpl_DgtqCgtqQLpzs6gwaCfJKpKKMBYk`; `api/leads.js` unchanged sha 8c6c454…) | Vercel | — | promote `dpl_HuwYWu2CXwQABrS69gQzmqtQ7hpZ` |
| Club Italia CEO review | https://gitteromri-ux.github.io/club-italia/ | `gitteromri-ux/club-italia` — `main` @ `a5c163f` (v16) vs default `master` (v1) | GitHub Pages | — | — |
| Handover repo | https://github.com/gitteromri-ux/handover-master (public; Pages index 404 — read files on GitHub/raw) | main | — | push | — |
| CEO report | https://gitteromri-ux.github.io/julie-ceo-launch-report/ (+ `today.html`, `weekly-2026-10-06/`, `board-deck-2026-10-06/`) | `gitteromri-ux/julie-ceo-launch-report` | GitHub Pages | push | revert |
| Marketing dashboard / creative master | https://gitteromri-ux.github.io/lla-marketing-dashboard/ (`adsets.html`, `masterclass-adsets.html`, `julie-banners/slides/slides.html`, board PPTX 5 Oct) | `gitteromri-ux/lla-marketing-dashboard` | GitHub Pages | push | revert |

Other live review surfaces (GitHub Pages, all under gitteromri-ux.github.io): `final-versions` (approved UGC ads), `lla-julie-ugc-ads`, `lla-masterclass-assets` (Julie film v6 + cutdowns), `lla-meta-ig-ad-sizes`, `lla-masterclass-emails-3tier`, `french-atelier-lifecycle-emails`, `french-atelier-jv-deck`, `french-atelier-social-kickstart`, `lla-gal-september-2026`, `julie-500-launch-plan`, `lla-funnel-analysis-sep9-15`, `lla-pr-kit`, `lla-master-deck`, `lla-promo-emails`, `in-venture-website`, `olga`, `hana`, `kerenor-adoption-en`, `vj-magic-site(-v2)`, `cartoon-circular-portraits-1783953556`. Vercel: `julie-masterclass-ads.vercel.app` (UGC finals CDN), `win-paris-fa.vercel.app`.

---

## 6. Meta account — state at 10 Oct 2026 ~15:00 Israel (VERIFIED, Graph v25)

### 6.1 Campaigns on act_1459085242361281
| Campaign | ID | Objective | Status | Role |
|---|---|---|---|---|
| LGV_EN_PPC_ecomm-02_2026-09-02_#118149 | 52668266203628 | OUTCOME_SALES | ACTIVE | **Julie masterclass** (sets 1–6 + 2 paused TEST sets) |
| LGV_EN_PPC_ecomm-01_2026-09-02_#118148 | 52663511211628 | OUTCOME_SALES | ACTIVE | **Blueprint e-commerce** (sets 2/4/5 live, 1/2-old/3/5-old paused) |
| LGV_EN_FB_Demographics_LLA_2026-05-04_#116622 | 52658911188428 | OUTCOME_SALES (ADD_TO_CART opt.) | ACTIVE | Blueprint ATC sets #108775 $33, #108776 $21 (eTeacher-run) |
| LGV_EN_FB_Demographics_FB Leads_2026-08-03_#117186 | 52655032034228 | OUTCOME_LEADS | ACTIVE | Lead-gen sets #108777 $33, #108778 $30, #108779 $39 (eTeacher-run) |
| two older campaigns | 52604761655628, 52596364713028 | — | PAUSED | — |

### 6.2 Masterclass ad sets (campaign 118149) — all Purchase-optimized on pixel 1440305917310328, LOWEST_COST_WITHOUT_CAP
| Set | Ad set ID | CRM adGroupID | Status | Daily budget now | Learning (conv.) | Audience (DOCUMENTED 8–9 Oct) | Live ads now |
|---|---|---|---|---|---|---|---|
| 1 | 52668330533628 | 108813 | ACTIVE | **$231** | LEARNING 0 | US 44–65+, all genders, 41 interests AND (Engaged Shoppers OR income top 10% OR 10–25%), A+ off, FB feed + Reels only | Ad#19 Woman "Deadlier" 52671564228228, Ad#20 Woman "33 years" 52671564250028 (W1/W4 test approved 9 Oct) |
| 2 (retargeting + 3×1% LAL) | 52668268711228 | 108814 | PAUSED (6 Oct, Omri) | $44 | — | warm audiences + lookalikes | — |
| 3 | 52668330165828 | 108815 | ACTIVE | **$309** | LEARNING 0 | US 35–65+, 41 interests AND Engaged Shoppers | Ad#17 Woman "Five habits" 52670355336628, card-gold Reels 52670313921028 (Ad#12 paused 9 Oct 17:32) |
| 4 | 52668330870828 | 108816 | ACTIVE | **$420** | LEARNING 9 | US 35–65+, interests AND (Shoppers OR top-10% OR 10–25%) | Ad#17 52670065101028, card-gold Reels 52670313942228 |
| 5 | 52668330871228 | 108817 | ACTIVE | **$499** (approved 10 Oct 14:26) | LEARNING 3 | US 35–65+, interests AND income top 10% only | Ad#17 52670277632228 |
| 6 | 52668330871028 | 108818 | PAUSED (6 Oct) | $69 | — | US 45–64 | — |
| TEST / TEST2 | 52668956239228 / 52668961777228 | — | PAUSED | $60 / $500 | — | TLV 1 km controlled-purchase tests | — |

Budgets were edited by Omri today (sets 1, 3, 4 updated 07:11–09:35 UTC; set 5 at 11:26 UTC). Omri's stated daily objective: 20 purchases/day, max $150 CPA, 500+ paid enrollments for the 27 Oct event (USER-STATED).

### 6.3 Masterclass results 28 Sep → 10 Oct (Meta-attributed, campaign 118149, VERIFIED pull 10 Oct)
| Set | Spend | LPV | ATC | IC | Purchases | Purchase value |
|---|---|---|---|---|---|---|
| 1 | $3,711 | 189 | 8 | 8 | 5 | $335 |
| 2 | $814 | 38 | 0 | 0 | 0 | — |
| 3 | $5,215 | 605 | 21 | 17 | 13 | $847 |
| 4 | $4,634 | 611 | 14 | 13 | 13 | $827 |
| 5 | $3,183 | 434 | 13 | 13 | 10 | $490 |
| 6 | $1,024 | 142 | 0 | 1 | 0 | — |
| **Total** | **$18,581** | **2,020** | **56** | **52** | **41** | **$2,499** |
Campaign CPA ≈ $453 per Meta-attributed purchase. These are pixel/CAPI events (QA traffic excluded by the relay), **not** unique paid buyers and not CRM-settled orders; the 7 Oct order list showed 10 masterclass seats + 1 Blueprint sale behind 11 events. Blueprint campaign 118148 in the same window: $3,155 spend, 971 LPV, 11 ATC, 2 IC, 0 purchases.

### 6.4 Approved vs not approved (as of 10 Oct, DOCUMENTED)
- Approved and executed: W1/W4 woman-presenter test in set 1 for all genders (not women-only); set 5 $399→$499; set 3 Ad#17 reactivation + $499→$425 (8 Oct); 10% raises on 03/04 (7 Oct 01:53); pausing Ad#18 and reactivating card-gold Reels in set 4; Ad#12 65 s post retained (replacement storyboard rejected); Instagram removed from set 1 (Facebook feed/Reels only); payment-form appearance + 2× header logo published (9 Oct 18:08).
- **Not approved** (do not execute): set 3 placement change/Ad#12 reactivation ("YES 3" never given); one-set consolidation / set 6 Advantage+ lifetime-budget plan ("No"); compact-pricing mobile redesign branch `change/20261009-mobile-compact-checkout` @ `729ee03` (review only); any GOLDEN repair including the adGroupID mismatch; Meta "Add music" enhancement; splitting men/women sets; blanket 65+ exclusion.
- Creative inventory: approved finals live at https://gitteromri-ux.github.io/final-versions/ and `julie-masterclass-ads.vercel.app`; Julie film v6 + 12 cutdowns at `lla-masterclass-assets`; thumbnails T1/T2/T3 and "Thumbnail B"; banners card-gold/card-blue/zoom-blue (static + 15 s Reels with Julie-film music). Non-final UGC (Ad#15 man "33 years", Ad#16, Ad 2/4 "8 weeks DNA"/"Not moving") were deleted/paused on Omri's order.
- Audiences: seeds 52670046140828 (checkout starters 180 d www), 52670046280628 (masterclass viewers 180 d top-25% time), 52670046220628 (Julie video 75% 365 d); lookalikes 1% US 52670046286828 / 52670046324628 / 52670046355428; older CAs 52666964616028 (video viewers 365 d), 52666079297628 (ATC 90 d), 52666963633828 (form openers 90 d).

---

## 7. What was done, 10 July → 10 October 2026 (by brand, then project)

### 7.1 Longevity Life Academy — Julie Gibson Clark Live Masterclass (core of Sep–Oct)
- **Landing + self-service checkout** (`Longevity-Academy/julie-masterclass`, personal mirror `gitteromri-ux/lla-julie-masterclass` 61 commits to 2 Sep, private `julie-masterclass-3tier`, `julie-launch-review-20260923`): cinematic hero, press proof, full film, three-step on-page modal (`?plan=standard|vip`), Airwallex + PayPal, international phone/state validation, CRM-originated `stid/orderid/RequestId` links, AC event enrichment, CAPI relay, floating Enroll CTA, WhatsApp floater, Support page and nav links (7 Oct), payment-form light appearance + 1314×596 header logo (9 Oct). Memory: `projects/julie-live-masterclass`, `projects/julie-mobile-checkout`.
- **Tracking freeze (GOLDEN)** 28 Sep → 26 Oct; dedup fix via Business Manager toggle 4 Oct (§4).
- **Acquisition campaign** (24 Sep → now): six-set structure, targeting iterations 1–4 Oct (Advantage+ test failed: $96/133 imp/CPM $719; reverted to 45–64 hard + buyer signals; then 41 interests AND signals), placements FB feed + Reels (+IG stream, later removed on set 1), UGC uploads (M1/W2/W3/M4 → Ad#15–#20), banner Reels with music, lookalikes, budget raises/cuts, daily/weekly reads. Memory: `projects/julie-masterclass-acquisition`. Dashboard: `lla-marketing-dashboard` (adsets.html, masterclass-adsets.html, slides). Launch plan: `julie-500-launch-plan`.
- **Creative production**: Julie film masterclass edit v3→v6 + 12 captioned cutdowns (`lla-masterclass-assets`), UGC AI-presenter ads (`ugc-prod`, `final-versions` v11/v12, `lla-julie-ugc-ads`), thumbnails, banners (`lla-meta-ig-ad-sizes` 52 commits, `julie-meta-banners`, `lla-meta-banners-gallery`), press articles (`lla-masterclass-press`), syllabus site (`lla-masterclass-syllabus`), communications plan + letter to Julie (`lla-julie-communications-plan(-v2)`, `lla-julie-letter`). Memory: `projects/julie-ugc-production`, `projects/lla-julie-launch-communications`, `projects/lla-meta-ig-ad-sizes`.
- **Lifecycle emails**: `lla-masterclass-emails` (20 emails, Sandra's 3 approved names) → `lla-masterclass-emails-3tier` (Standard 9 / VIP 9 / Full Course); AC relay field model.
- **Organic distribution**: Facebook-group posting plan (`julie-groups-uplift`, private, 115 groups/6.42M), affiliate same-day growth thread (30 Sep). Memory: `projects/julie-organic-distribution`.
- **CEO reporting**: `julie-ceo-launch-report` (report, `today.html` CEO plan/actual/forecast, weekly 6 Oct with Excel packs, board deck 5–6 Oct PPTX+PDF, morning briefing drafts), `lla-gal-september-2026` (GAL board report Excel/PDF), funnel analyses (`lla-funnel-analysis-sep9-15`, `-sep14`, `lla-funnel-deck`). Memory: `projects/julie-ceo-launch-report`.
- **October turnaround / investor pilot** (draft, not sent): three channels (masterclass + upsell, direct e-commerce rebuild week of 12 Oct, bounded call-center), 31 Oct stop boundary, $90 masterclass CPA milestone, whole-month economics required. Memory: `projects/lla-october-turnaround`.
- **In-event enrollment** (design goal, no implementation chosen): Zoom-compatible full-course buying during the live event. Memory: `projects/julie-in-event-enrollment`.

### 7.2 Longevity Life Academy — Blueprint e-commerce and site
- **Course checkout** (`gitteromri-ux/lla-course-checkout`, 213 commits, private; Cloudflare Pages `longevitylifeacademy`; org mirror `lla-checkout-live`): Rosen-pattern 3-step checkout, Airwallex drop-in + PayPal, CRM order creation only at checkout stages, AC single-field events, byte-exact fbclid, server-set `_fbc/_fbp`, Purchase dedup, delivery receipts, test exclusion, privacy (`fix/privacy-20260927`) and support (`fix/support-20261007`) pages; release audit found five blocker-class issues (buyer-linked $249 credit/VIP fulfilment unproven, AC stage discrimination, rejected payments showing enrollment, USD guard, CRM order before payment) — **not approved as fixed**. Memory: `projects/lla-course-checkout`. 30 Sep Blueprint/Julie Meta handover: `projects/julie-meta-handover-20260930/`.
- **Blueprint Meta sets**: copies set 2 (52669013718628, #108808) and set 5 (52669048300628, #108811) + retargeting set 4 (52666232368428, #108810); intent rules copied from masterclass set 1 (2 Oct); placements manual feed/Reels/IG stream (4 Oct); 3-format Ad#12 added. Today: $19 / $15 / $24 daily, 0 purchases since 28 Sep.
- **Marketing site** (`Longevity-Academy.github.io`, 133 commits): homepage video fit, `/blueprint` mirror, privacy policy update for Longevity Score App health data (`lla-privacy-policy`, thread with Shemi/Keren/Ehud/Eyal 24–27 Sep), Support page + nav (7 Oct), blog "In the press" fold (7 Oct).
- **Earlier LLA work (Jul–Aug)**: PR kit and master deck (`lla-pr-kit`, `lla-master-deck`, `lla-final-5-articles`, `lla-articles-deck`, `lla-chapter1-pr-coverage`, `lla-julie-pr-articles`, `lla-pr-article-ads`), promo emails + LPs (`lla-promo-emails` v8.17), employee referral (`lla-employee-referral`), Courtney/Julie films and cuts (`lla-s09-s10-downloads` 371 commits, `lla-julie-animations`, `lla-courtney-final`, `courtney-banners`, `lla-90s-review/final`, `lla-v25-recut`, `lla-julie-cuts`, `lla-courtney-cuts`, `courtney-review`, `longevity-assets`), social go-live pack (`lla-social-golive`), delta-force activation hub (`lla-delta-force`), growth engine (`lla-growth-engine`), turnaround plan, handoff pack (`lla-handoff-pack`), Gita Machine (organic reach). Memory pages: `projects/longevity-life-academy`, `projects/longevity-productions-courtney-julie`, `projects/lla-marketing-dashboard`.

### 7.3 French Atelier by Acadomia
- **Live site** (`gitteromri-ux/french-atelier`, 116 commits since Jul): Mapstr neon map, capsules.html aligned to the Cultural Capsules syllabus (7 Oct, live), nav still says "Coming Soon" for capsules (out of scope). Lead forms (`js/eteacher-leads.js`, `js/enroll-modal.js`) untouched by checkout work.
- **Self-service checkout — STAGING ONLY** (branch `staging-checkout`, two Vercel builds): register → course/capsule → pay; approved price structure (website 5×$292=$1,460 or one payment $1,240; online offer $99 then 4×$189=$855; capsules 1/2/3 at $99/$89/$79 per capsule per month ×3, the +$10 tier reading is ASSUMED); promo engine (CAPSULE20), WhatsApp floater, emphasis layer, type-readability pass, Midnight/Paper/Ivory/Split themes, Culture Capsules sales page v3 with Veo-generated clips and 33 keyframes. Pushed to live by mistake on 6 Oct and reverted the same day (main `34f7601`). Blockers for real charging: FA courses/price plans in CRM (MainAbroadCourseId/AbroadCourseId/PreferredCourseId), production CF-Access + token, FA Meta pixel id. Memory: `projects/french-atelier-checkout`.
- **Lifecycle emails** gallery (`french-atelier-lifecycle-emails`, scripted from the LLA 3-tier set — draft quality), **JV deck** for Acadomia + eTeacher CEOs (`french-atelier-jv-deck`, 9 slides, 21 videos), **Culture Capsules teaching decks** Pack 3 Cinema & Music (`cultural-capsules-pack3`, 10 decks; "Replicate Culture Capsule Decks" threads 7–8 Oct), **organic social kickstart** Sep–Oct (`french-atelier-social-kickstart`, 36 commits, Sprout drafts), **WhatsApp batches** (`french-atelier-wa-8-briefs`, `french-atelier-wa-batch-2`), **client demographics** board, **June results** correction (22 Sep), **ACQ drip** (`french-atelier-acq-drip`, 12 emails/12 LPs), **Win Paris** contest site (Jul). Memory: `projects/french-atelier`, `french-atelier-cinema-music-decks`, `french-atelier-jv-deck`, `french-atelier-social-kickstart`, `french-atelier-lead-contact-analysis`, `french-atelier-ceo-deck`.

### 7.4 Club Italia
- `gitteromri-ux/club-italia`: v1 on `master` (10 Sep, 24 core + 11 course + 11 blog pages + 11 syllabus PDFs); CEO-review v16 "LAW OF OMRI REBUILD" on `main` @ `a5c163f`, live at the Pages URL. No rebuild authorized. Memory: `projects/club-italia`.

### 7.5 Gita Agency — other clients and internal (Jul–Sep)
- **IN Venture** website rebuild (`in-venture-website`, Playfair/dark keynote v2, 1 Sep) + programme (`in-venture-programme`).
- **Abraham Tel Aviv GM** 100-day/autumn plan decks (`abraham-tlv-gm`, `-v2`, `abraham-tel-aviv-gm`, 15–16 Sep).
- **Brown Hotels Greece / PLAY Paros** redesign + F&B brief (`play-paros-redesign`, `brown-hotels-greece-briefing`, Aug).
- **Keren Or Farm** English adoption page (`kerenor-adoption-en`, Jul).
- **Enneagram** assessments `olga`, `hana`, `enneagram-8w7-4w3` (Jul).
- **Personalix** recruitment site (Jul), **Ziv book cover** directions (private, 28 Sep), **cartoon circular portraits** (Jul), **Amy Squishy**, **Apt Furniture Deck**, **VJ Magic** (earlier, see `_inventory.md`).
- **Internal evidence logs** (private/public): `serious-claims` (cases where deliveries did not match written requests), `lawsuit` (service-performance audit of the AI operator, Jun–Aug). The owner's 9 Oct reliability warning in `julie-masterclass-handover-2026-10-09.md` §0 applies to all AI-written material here.

---

## 8. Repository inventory — all repos pushed since 10 July 2026 (VERIFIED via GitHub API)

Format: repo · commits since 10 Jul · last commit date · default branch · private?

**Longevity-Academy (org):** julie-masterclass · 196 · 2026-10-09 · main · public | Longevity-Academy.github.io · 133 · 2026-10-07 · main · public | lla-checkout-live · 1 · 2026-09-09 · main · public

**gitteromri-ux — LLA:** handover-master · 138 · 10-09 · main | lla-marketing-dashboard · 32 · 10-07 | julie-ceo-launch-report · 25 · 10-06 | lla-julie-ugc-ads · 30 · 10-02 · master | final-versions · 26 · 10-01 | ugc-prod · 3 · 10-01 | lla-masterclass-assets · 42 · 10-01 | julie-groups-uplift · 3 · 09-30 · master · **private** | serious-claims · 4 · 09-30 · **private** | julie-500-launch-plan · 16 · 09-29 | lla-gal-september-2026 · 11 · 09-28 | lla-course-checkout · 213 · 09-25 · master · **private** | lla-julie-communications-plan · 4 · 09-24 · master | lla-masterclass-emails-3tier · 24 · 09-24 | lla-meta-ig-ad-sizes · 52 · 09-24 | julie-launch-review-20260923 · 12 · 09-24 · review · **private** | lawsuit · 26 · 09-22 | gita-machine · 1 · 09-17 | julie-masterclass-3tier · 1 · 09-17 · master · **private** | lla-funnel-analysis-sep14 · 3 · 09-16 | lla-funnel-analysis-sep9-15 · 11 · 09-15 | lla-privacy-policy · 3 · 09-15 | lla-funnel-deck · 1 · 09-06 · master | lla-handoff-pack · 3 · 09-02 · master | lla-julie-masterclass · 61 · 09-02 | lla-masterclass-syllabus · 4 · 09-02 | lla-julie-videos · 1 · 09-02 | lla-julie-communications-plan-v2 · 4 · 09-01 | lla-masterclass-press · 1 · 09-01 | lla-julie-letter · 4 · 09-01 | lla-masterclass-emails · 19 · 08-27 | lla-delta-force · 21 · 08-26 | courtney-review · 18 · 08-24 | lla-social-golive · 7 · 08-24 · master | lla-meta-ad-sizes · 1 · 08-12 | lla-courtney-cuts · 10 · 08-10 | lla-julie-cuts · 5 · 08-10 | lla-s09-s10-downloads · 371 · 08-07 | lla-julie-animations · 57 · 08-07 | lla-courtney-final · 11 · 08-07 | lla-julie-pr-articles · 17 · 08-07 | longevity-life-academy · 5 · 08-06 | courtney-banners · 34 · 08-06 | lla-90s-review · 2 · 08-06 | lla-ceo-delivery · 1 · 08-05 · master | lla-90s-final · 5 · 08-05 | longevity-assets · 11 · 08-05 | lla-v25-recut · 8 · 08-05 | julie-meta-banners · 2 · 08-05 | lla-meta-banners-gallery · 17 · 08-05 | lla-growth-engine · 6 · 08-04 | lla-pr-article-ads · 1 · 07-30 | lla-employee-referral · 10 · 07-30 | julie-onset-banners · 1 · 07-28 | lla-campaign-chapters · 1 · 07-28 | lms-image-pack · 5 · 07-28 | lla-chapter1-pr-coverage · 6 · 07-27 | lla-final-5-articles · 9 · 07-22 | lla-promo-emails · 34 · 07-21 | lla-master-deck · 38 · 07-21 | lla-pr-kit · 42 · 07-21 | lla-homepage-demo · 2 · 07-20 | lla-turnaround-plan · 4 · 07-20 | courtney-master-production · 2 · 07-19 · master | lla-articles-deck · 2 · 07-19 | courtney-lla-masterclass · 4 · 07-13

**gitteromri-ux — French Atelier / Club Italia:** cultural-capsules-pack3 · 5 · 10-08 | french-atelier · 116 · 10-07 | french-atelier-lifecycle-emails · 7 · 10-07 · master | french-atelier-jv-deck · 8 · 10-07 | french-atelier-wa-batch-2 · 10 · 09-22 | french-atelier-june-results · 2 · 09-22 · master | french-atelier-social-kickstart · 36 · 09-16 | french-atelier-wa-8-briefs · 3 · 09-15 | club-italia · 1 · 09-10 · master (main = v16) | french-atelier-client-demographics · 3 · 08-06 | french-atelier-wa-ret-acq · 3 · 08-06 | french-atelier-acq-drip · 11 · 08-05 | french-atelier-ceo-deck · 3 · 07-14

**gitteromri-ux — Gita clients / other:** ziv-book-cover-directions · 6 · 09-28 · **private** | abraham-tlv-gm · 2 · 09-16 | abraham-tlv-gm-v2 · 2 · 09-16 | abraham-tel-aviv-gm · 2 · 09-15 | in-venture-website · 13 · 09-01 | in-venture-programme · 3 · 08-09 | play-paros-redesign · 12 · 08-17 · master | brown-hotels-greece-briefing · 7 · 08-17 · master | hana · 5 · 07-23 · master | personalix · 5 · 07-23 | enneagram-8w7-4w3 · 2 · 07-16 · master | kerenor-adoption-en · 6 · 07-14 · master | cartoon-circular-portraits-1783953556 · 2 · 07-13 · master

Older repos (June and earlier) are listed in `_inventory.md` (62 referenced) and `HANDOVER.md`.

---

## 9. Vercel projects (team gitter1, VERIFIED list 10 Oct)

Production-relevant: **lla-ac-events** (CAPI + AC relay), **fa-leads-proxy** (FA lead/ecomm relay), **fa-staging-checkout**, **fa-staging-light**, **julie-masterclass-ads** (UGC finals), julie-masterclass, julie-masterclass-mockup, win-paris-fa, lla-gal-september-2026.
Full list (52): lla-gal-september-2026, fa-staging-light, fa-staging-checkout, french-atelier-mockup, julie-masterclass-mockup, julie-masterclass-ads, julie-masterclass, lla-ac-events, fa-leads-proxy, win-paris-fa and ~42 earlier review deployments (names in the Vercel dashboard; most are static preview copies of GitHub Pages repos). Hobby-plan limit warning received 7 Oct 2026 — upgrade or prune before relays are throttled.

---

## 10. Google Drive — key assets (VERIFIED list, modified since 10 Jul)

- Spreadsheets: **Master Manager** (6 Oct), **Longevity Daily Report** (17 Sep), **Longevity Media Plan** (2 Sep), **French Atelier Daily Report.** (2 Sep), **Longevity Life Academy – August 2026 Strategy** (20 Aug), **10 Days (All 3 Level Data for Ad Analysis)** (18 Aug).
- Docs: **Presentation JGC** (5 Oct), **Longevity Life Academy – Ad Copy** (2 Sep).
- Video folders: `FINAL VIDEOS MASTERCLASS HAREL`, `JULIE FINAL TAKES`, `COURTNEY FINAL TAKES`, `COURTNEY REVIEW`, `UPLOAD 12.8`, `UPLOAD GUAROV`, `Use with julie and lla logo`, `Use these for website`, `STILS`, `additions blitz`, `aa` (Artlist stock, 4 Sep); masters `Julie 90s V2.mov`, `COURTNEY FIONAL MASTER USE.mov`, `FINAL JULIE_65s_Final_TO_UPLOAD_RONEN_9_16_V2.mp4`, `CORTNEY_65_JUSTIN_9_16.mp4`, `PR FROM HERE.mp4`.
- `GITHUB ECOM HAREL` folder (12 Aug: github.md, support.js, banner/lead-card HTML exports).
Links are in the Drive of gitter.omri@gmail.com; search by the names above.

---

## 11. Open items as of 10 Oct 2026 (what the next operator inherits)

1. **Julie masterclass acquisition** — daily operating: 20 purchases/day at ≤$150 CPA target vs. ~$453 Meta-attributed CPA since 28 Sep; sets 3/4/5 are the sellers, set 1 is the W1/W4 test, 2/6 paused. Daily 09:00 read required. Event 27 Oct 7 PM ET; freeze ends 26 Oct.
2. **Order-level reconciliation** never completed: Meta purchases vs CRM paid orders vs Airwallex/PayPal settlements vs refunds (Houston signal, Reston double count, Blueprint buyer inside masterclass numbers). Needs eTeacher CRM export (Anant/Roberto) + Airwallex report.
3. **adGroupID mismatch** on set 3 Ad#12 / set 5 copies (108813 instead of 108815/108817) — known, repair not authorized (GOLDEN).
4. **Mobile checkout** — compact-pricing redesign branch in review; no physical-iPhone/Facebook-in-app Purchase proof; recaptcha 401 / third-party script error observed, not cleared.
5. **Blueprint checkout release audit** — five blocker-class findings open; direct e-commerce rebuild proposed for week of 12 Oct (investor pilot draft, not accepted/sent).
6. **support@longevitylifeacademy.com** — page live on three sites; mailbox/alias creation and monitoring owner still to be confirmed to Harel.
7. **French Atelier checkout** — staging approved for presentation only; needs CRM course/price plans, production CF-Access credentials, FA pixel; Philippe/Omri acceptance; capsule pricing tiers (+$10) to confirm; lifecycle emails are scripted drafts.
8. **French Atelier status meeting** Wed 14 Oct 11:30 Israel (Teams, Keren Ziv).
9. **Cultural Capsules decks** — Pack 3 Cinema & Music delivered (8 Oct); other packs' screen recordings for the JV deck pending.
10. **Connectors broken**: Cloudflare (wrong key type), ActiveCampaign (base URL), GTM (no account access). Vercel on Hobby limits.
11. **Credits refund request** for the 1 Oct UGC thread (~$320) to be filed with Perplexity support (Omri's request).
12. Nav label "Coming Soon" for Culture Capsules on FA live is out of date vs the rebuilt capsules page.

---

## 12. Pre-defined gaps — what the new tool will need and should ask Omri for once, up front

1. **Credentials (vault, not chat):** GitHub PAT (both accounts), Vercel team token, Cloudflare API token (Pages/Workers/Analytics) or Global key, Meta system-user token or Business Manager invite to 1545475089051742 + Page admin on 1179505785236150, Google OAuth (Gmail/Calendar/Drive), ActiveCampaign URL + key, GTM access, Airwallex read access (eTeacher), eTeacher CRM production CF-Access + token for FA.
2. **Standing daily job** (09:00 Israel): Meta read per set, excluding QA; alert on learning resets (`last_sig_edit_ts` change), review status (IN_PROCESS/WITH_ISSUES), and Pixel issue badges.
3. **Change log discipline:** append to `handover-master/_today-log.md` after every change; snapshots in `projects/.../data/` as JSON before/after.
4. **Decision registry** to maintain: the "approved vs not approved" list in §6.4 — update it the moment Omri says go/no.
5. **The three things to ask Omri at kickoff:** (a) which GOLDEN items, if any, he releases and when (default: none before 26 Oct); (b) whether the compact-pricing mobile branch is approved for publish; (c) a card for one live $49 purchase + refund so Purchase can finally be proven end to end (offered twice, never provided).
6. **Do not inherit these withdrawn claims** (from the 9 Oct §9 list): "learning phase" as the explanation for CPA; "all purchases come from feed" beyond the 4-purchase window; "ten CRM matches" without ledger rows; CPM being account-wide rather than masterclass-specific; a relay 202 or Test Events hit as proof of a sale.

---

## 13. Source files and threads behind this document

Repo files: `_global-rules.md`, `projects/julie-tracking-freeze/README.md`, `golden.json`, `julie-masterclass-handover-2026-10-09.md`, `projects/julie-meta-handover-20260930/HANDOVER-JULIE-BLUEPRINT-20260930.md`, `_today-log.md`, `HANDOVER.md`, `_inventory.md`, `_supporting-knowledge.md`, `projects/*.md`.
Operator memory pages (Perplexity): projects/julie-live-masterclass, julie-mobile-checkout, julie-masterclass-acquisition, julie-ceo-launch-report, lla-october-turnaround, lla-course-checkout, french-atelier-checkout, french-atelier, club-italia, handover-master, julie-ugc-production, julie-organic-distribution, julie-500-launch-plan, lla-marketing-dashboard, julie-in-event-enrollment and the full index.
Recent Perplexity Computer threads (from Gmail notifications, 30 Sep–9 Oct): Immediate Fix for Repeated Performance Failures (9 Oct), Turning Around Sets 4 and 5 Today (9 Oct), Improve Enroll CTA Event Matching (9 Oct), Replicate Culture Capsule Decks (7–8 Oct), Audit French Atelier Website Backend (7 Oct), Find First CAPI Coding Thread (5 Oct), Sales and Budget Spend vs CEO Plan (5 Oct), Comparing Julie Ad Sets and Testing Strategy (4 Oct), Download Julie's 2:20 Ad MP4 (1 Oct), Longevity Masterclass UGC Ad Scripts (1 Oct), Same-Day Affiliate Growth for Masterclass Signups (30 Sep).
Live pulls today: Meta Graph v25 (accounts, pages, pixel, custom conversions, campaigns, ad sets, ads, insights 28 Sep–10 Oct), GitHub API (repo list + commit counts), Vercel API (team + projects), DNS over HTTPS (NS/CNAME/A), HTTP HEAD on every live host, Gmail (last 3 months), Calendar (10 Oct–15 Nov), Drive (modified since 10 Jul).
