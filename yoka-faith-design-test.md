
# Yoka — UI/UX Design Take-Home Test
### Faith / Foi Vertical

Thank you for taking the time to work through this. It's meant to reflect real work you'd do in the role, not a trick test — take the time you need within the window below, and use whatever tools you're fastest in.

---

## 1. Context: what Yoka is

Yoka is an audio content platform — think "Spotify-like," but purpose-built for Central Africa, launching first in DR Congo, where mobile data is expensive and connections are often slow or unreliable.

This role is focused on the **Faith / Foi** section of the platform — sermons, teachings, and short morning prayers, published by independent preachers and churches.

Two kinds of people use the platform:
- **Listeners** — consumers, on a mobile app (React Native/Expo). Mostly free, with some paid content, and a free ad-free trial period.
- **Creators** — publish content inside a "workspace" (their own branded portal). In Faith, a workspace might be a church with multiple staff uploading, or a single independent preacher working alone.

---

## 2. What "Faith / Foi" needs to support

Keep these real constraints in mind while you design — they're not optional context, they should visibly shape your decisions:

- **Content types**: sermons, teachings, short morning prayers, and announcements. Sermons are sometimes grouped into a series (e.g. a multi-week teaching).
- **Creators range widely in size**: a single independent preacher recording on a phone, up to a church with a small media team uploading weekly.
- **Donations/offerings**: listeners can give directly to a church or preacher from within the app. This has to feel *trustworthy and simple* — this is often a first-time digital giving experience for a lot of users.
- **Religious/denominational diversity**: the platform hosts many independent churches and preachers, not one institution. Nothing in the design should assume a single denomination, liturgical style, or visual iconography as "the" default.
- **Low-bandwidth, low-connectivity reality**: many listeners are on slow or intermittent connections. Downloading content for offline listening is a core behavior, not an edge case. The design needs to make offline/downloaded state, data usage, and "still loading" states feel intentional — not like something broken.
- **Range of digital literacy**: listeners span from very tech-comfortable to people for whom this might be one of the first apps they use regularly. Clarity beats cleverness.

---

## 3. Your task

Design the following. Treat it as one coherent product — screens should feel like they belong to the same app and the same design system, even though you're only asked to produce a subset of screens.

### A. Listener-facing (mobile app)

1. **Faith home / browse screen** — where a listener lands when they open the Faith section. Needs to work for someone browsing with a specific preacher/church in mind, *and* someone just exploring.
2. **Church or preacher profile page** — the public page for a workspace. Show what it publishes (sermons, series, prayers, announcements), and include a clear, trustworthy entry point to give/donate.
3. **Sermon/episode detail + player screen** — playback controls, and a visible, clear treatment of offline/download state (downloaded vs. streaming vs. no connection).
4. **Donation/offering flow** — from tapping "Give" through to confirmation. 2–3 screens. This should feel calm and trustworthy, not like a checkout funnel.

### B. Creator-facing (web portal)

5. **Workspace setup/branding screen** — where a church or preacher sets up how their public page looks (name, photo/logo, short bio, links).

### C. Your choice — one more screen

6. Pick **one** additional screen that shows how the app behaves in a degraded-connectivity state — for example: a "downloaded/offline library" view, a "no connection" state on the home screen, or a low-data upload flow for a creator on a slow connection. Tell us briefly why you picked this one.

**You do not need to design:** onboarding/signup, the full creator content-upload flow, admin tooling, or anything outside the Faith section. If something outside this list feels necessary to explain a screen, a quick sketch or note is fine — a full design isn't needed.

---

## 4. What to submit

- A **Figma file** (shared link, view access is fine) with your screens. Mobile screens at a standard mobile frame size; the web screen at a standard desktop width.
- A **short written rationale** (a single page is plenty — bullet points are fine, this doesn't need to be a formal document) covering:
  - The key decisions you made for the donation flow, and why.
  - How your designs communicate offline/downloaded/low-connectivity state, and why you chose that approach.
  - Anything you deliberately left open, or would want to validate with real users before finalizing.

We're not expecting a production-ready component library or pixel-perfect polish on every state — we care more about your reasoning and your judgment on the specific constraints above than about exhaustive coverage.

---

## 5. Timeline & logistics

- **You have 5 days** from receiving this to submit. This is intentionally not meant to consume a full workweek — most candidates spend somewhere in the range of half a day to a day of focused work; take what you need within the window.
- Submit the Figma link and your rationale write-up by replying to the email/message this was sent in.
- If anything in this brief is ambiguous, make a reasonable assumption, state it in your rationale, and move on — deciding under ambiguity is part of what we're looking at.

---

## 6. How we'll evaluate this

Shared here so there are no surprises:

| Area | What we're looking for |
|---|---|
| **Clarity & usability** | Can someone with limited app experience use this without confusion? |
| **Handling of connectivity constraints** | Does offline/downloaded/low-data state feel like a first-class part of the design, not an afterthought? |
| **Trust in the donation flow** | Does giving money feel safe, transparent, and calm — not like a generic e-commerce checkout? |
| **Respect for diversity of faith practice** | Does the visual language stay neutral/adaptable rather than assuming one denomination's aesthetic? |
| **Visual craft** | Typography, spacing, hierarchy, consistency across the screens as a set. |
| **Reasoning** | The rationale write-up — do your decisions hold up when you explain them? |

---

## 7. Optional — if you want to go further

Not required, and won't count against you if skipped: a short note (even just a few bullet points) on how you'd think about **visual differentiation between a large church workspace and a single independent preacher** — should they look and feel different, or consistent? There's no single right answer here; we're interested in how you think about it.

---
<img width="1080" height="488" alt="WhatsApp Image 2026-09-14 at 16 55 28" src="https://github.com/user-attachments/assets/7f3a4dcc-1170-41ad-88db-45201679953a" />
<img width="1080" height="734" alt="WhatsApp Image 2026-09-14 at 17 04 43 (3)" src="https://github.com/user-attachments/assets/e9dfbdb2-048f-4eaa-a03e-19459d653903" />
<img width="948" height="1028" alt="WhatsApp Image 2026-09-14 at 17 04 43 (2)" src="https://github.com/user-attachments/assets/160086b7-0602-4ac9-97a5-c27242bbd8ff" />
<img width="645" height="1080" alt="WhatsApp Image 2026-09-14 at 17 04 43 (1)" src="https://github.com/user-attachments/assets/283a4c77-7020-4a81-9188-fc8fdc0107f5" />
<img width="1080" height="961" alt="WhatsApp Image 2026-09-14 at 17 04 43" src="https://github.com/user-attachments/assets/db141455-f086-4251-b28e-f39a29ddc8f0" />
<img width="1001" height="815" alt="WhatsApp Image 2026-09-14 at 16 55 42" src="https://github.com/user-attachments/assets/93ec863c-31d8-4c29-9744-a4b0b79dfa2f" />
<img width="742" height="778" alt="WhatsApp Image 2026-09-14 at 16 55 35" src="https://github.com/user-attachments/assets/c2a78ede-7171-468a-9e14-b36e57a0cf83" />



*Questions about this brief? Reach out any time before the deadline — asking a good clarifying question is a perfectly good use of the process.*
