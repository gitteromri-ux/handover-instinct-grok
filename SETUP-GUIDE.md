# Setup guide — moving Omri's operation to Instinct and Grok Bot

Written 10 Oct 2026. Plain steps, nothing technical. Total hands-on time for you: about 25 minutes, mostly tapping "Sign in" when a tool asks.

---

## Part 1 — Instinct (the one you text on WhatsApp)

**Where it lives**
- Your web workspace (connections, settings): https://app.instinct.com/login — sign in with your phone number, you get an SMS code. No password.
- Public site: https://instinct.com
- You already have Instinct in WhatsApp. Everything below happens in that same chat.

**Step 1 — open the workspace once**
Go to https://app.instinct.com/login, enter your number, type the code. In the workspace, connect **Google** (gitter.omri@gmail.com) and **GitHub** (gitteromri-ux) if they are not connected yet. Those two unlock Gmail, Calendar, Drive, Sheets and all the repos. Anything else (Meta, Vercel, Cloudflare, ActiveCampaign) Instinct signs into through its own browser and will ask you for the login when it gets there.

**Step 2 — send this message in the WhatsApp chat (copy the whole block)**

```
From now on you are my operator for Gita Agency (Longevity Life Academy, French Atelier, Club Italia). Your onboarding file is here — open it and do everything it says, in order:
https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/INSTINCT.md

It links to the master handover, all my rules, the GOLDEN tracking freeze, the Julie campaign record, the change log, the gap list and the live ad copy. Read every linked file completely before you reply. Memorize the rules in sections 3 and 4 of the master handover and in rules/operator-os.md as permanent instructions for every future message from me — including: label every claim VERIFIED / USER-REPORTED / ASSUMED, never a number that can include test orders, no live change without my explicit "go" for that exact item, Army General gate answers written out before any decision-critical recommendation, nothing in the GOLDEN list touched before 26 Oct 2026, Hebrew when I write Hebrew, short and number-led.

Then connect to every service in INSTINCT.md section 3. When a login needs me, send me one message with the exact link and what to tap. Do not ask me anything else.

Your first reply must be exactly the shape of INSTINCT.md section 6.
```

**Step 3 — answer its login requests**
Instinct will send you one message per service that needs a login (Meta Business Suite, Vercel, Cloudflare, ActiveCampaign). Tap, sign in, done. It keeps the session.

**Step 4 — check its first reply**
It must contain: the live daily budgets of masterclass sets 1, 3, 4, 5 with the time it read them; pixel ID 1440305917310328; relay URL https://lla-ac-events.vercel.app/api/meta/capi; freeze end date 26 Oct 2026; HTTP status of the live sites; and the three kickoff decisions with a recommendation each. If any of these is missing, reply: "Read INSTINCT.md again and send section 6 in full."

---

## Part 2 — Grok Bot (the always-on teammate with its own computer)

**Where it lives**
- Download page: https://x.ai/bot (Mac, Windows, Linux; iPhone and Android apps too). Official setup guide: https://docs.x.ai/grok-bot/get-started
- Sign in with your **Cursor** account; if your access comes from **SuperGrok**, the app asks you to **Link Grok Account** once. Any paid Cursor plan or SuperGrok / Plus / Heavy works.

**Step 1 — install and sign in**
Open https://x.ai/bot, download, open the app, choose **Sign in**, finish in the browser, come back. Let the cloud computer finish setting up (runs in the background, a minute or two).

**Step 2 — create the bot**
**New → Create new Bot.** Name: **General**. Primary job: "Operate Omri Gitter's marketing, websites, tracking and reporting for Gita Agency." Description: paste the block below.

```
You are Omri Gitter's always-on operator for Gita Agency (Longevity Life Academy, French Atelier, Club Italia). First action, before anything else: on your computer run
  git clone https://github.com/gitteromri-ux/handover-instinct-grok.git ~/handover
  git clone https://github.com/gitteromri-ux/handover-master.git ~/handover-master
and read ~/handover/GROKBOT.md completely. Then follow it step by step: read every file it lists, sign in to every service in its section 3 (ask Omri to take over the screen only at a login wall, one service at a time, with the exact link), curl every live surface in section 4, create the routines in section 5, and send the first message in the shape of section 7.

Save the rules in ~/handover/rules/ (operator-os.md, change-safety.md, meta-ecom-playbook.md, tracking-capi.md) and ~/handover/_global-rules.md as a permanent skill that loads on every task. Non-negotiable forever: label every claim VERIFIED / USER-REPORTED / ASSUMED; never a number that can include test or QA orders; no live change on Meta, websites, DNS, Vercel, Cloudflare, ActiveCampaign, checkout or real emails without Omri's explicit "go" for that exact item; Army General gate answers written out before any decision-critical recommendation; nothing in the GOLDEN freeze list touched before 26 Oct 2026; after every change, append a dated entry to _today-log.md in handover-master and push; Hebrew when Omri writes Hebrew; short, number-led, no apologies, no progress narration, never a menu without a recommendation.
```

**Step 3 — set the safety rules (2 minutes, one time)**
In Settings → approvals, add **Require approval** for: sending emails or messages to anyone but you, publishing or deploying, deleting, purchasing, and any change in Meta Ads Manager / Business Suite, Vercel, Cloudflare, ActiveCampaign, GitHub `main` branches. This mirrors your own rule set so the tool cannot "screw you over" even by accident.

**Step 4 — send the first message**
In the bot's chat type: **"Go. Start with GROKBOT.md."** Watch the **Agent Computer** view; when it reaches a login wall it will ask you to take over. Sign in (GitHub as gitteromri-ux first, then Google, Meta, Vercel, Cloudflare, ActiveCampaign), hand control back.

**Step 5 — check its first message**
Same test as Instinct: budgets of sets 1, 3, 4, 5 with time; pixel ID; relay URL; freeze end date; HTTP status of every live surface; routines created with next run time; the three kickoff decisions with recommendations. Then tell it: "Save all of this as skill 'operator-os' and confirm it loads on every task."

---

## Part 3 — the logins you will be asked for (that is all you do)

| Service | Sign in as | Why |
|---|---|---|
| Google | gitter.omri@gmail.com | Gmail, Calendar, Drive, Sheets |
| GitHub | gitteromri-ux (has access to org Longevity-Academy) | all repos, both live sites deploy from here |
| Meta Business Suite | your Facebook login (Gitter Omri) | ad account Longevity Life Academy, Page, Events Manager |
| Vercel | team GITTER | CAPI relay, FA relay, FA staging checkouts |
| Cloudflare | account gitter-omri | Blueprint checkout (Pages) and the CRM proxy Workers |
| ActiveCampaign | eteachergroup.api-us1.com login | emails and contact fields (only when you reopen AC scope) |
| Microsoft 365 (optional) | Omri.Gitter@eteachergroup.com | Teams invites and eTeacher threads land there |

Things only eTeacher can give (the tools will ask you once, you forward the request): GTM container owner access, Airwallex read access, FA production CRM credentials, Business Manager admin role for the tool's user if it needs one.

---

## Part 4 — what "knows it by heart" means here

Both prompts above tell the tool to (1) read every file, (2) store the rules as permanent instructions / a skill, and (3) prove it by reciting live facts in its first reply. The proof reply is the test. If a tool ever answers without VERIFIED / USER-REPORTED / ASSUMED labels, or quotes a number without excluding QA orders, or proposes a live change without the four gate answers, send it one line: **"Reload rules/operator-os.md and GAPS.md."**

## Part 5 — the files, for reference

- Entry for Instinct: https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/INSTINCT.md
- Entry for Grok Bot: https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/GROKBOT.md
- Master handover: https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/MASTER-HANDOVER-2026-10-10.md
- What is not in the handover and who holds it: https://raw.githubusercontent.com/gitteromri-ux/handover-instinct-grok/main/GAPS.md
- Whole repo: https://github.com/gitteromri-ux/handover-instinct-grok · older history: https://github.com/gitteromri-ux/handover-master
