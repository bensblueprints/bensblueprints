# Benjamin Boyce

Building **OneTimeSuite**: software you buy once, with the source on GitHub so "lifetime" isn't a promise you have to trust me to keep.

Da Nang, Vietnam (UTC+7) · Advanced Marketing Limited

---

## The thesis

Software used to come in a box. You paid once, you owned it, and nobody raised the price at renewal or locked your files behind an expired card.

Now there's a monthly fee to take notes. A monthly fee to edit a PDF. A monthly fee for software already sitting on your hard drive doing math your machine could do in 1998.

So I'm building the replacements. **100 apps. One-time prices from $19. Local-first. Nearly all MIT licensed, right here.**

Buy one app because it fixes one thing you're sick of paying for. Buy the whole catalog if you want the whole exit. Both are fine.

The code is free. The signed installer is what you pay for. If you'd rather clone the repo and build it yourself, do that. I'd genuinely rather you fork it than rent from Loom.

---

## Shipped (4)

Real, downloadable, in people's hands right now.

| App | What it does | Replaces | Price |
|---|---|---|---|
| **[Linkleaf](https://onetimesuite.com)** | Self-hosted link-in-bio: themes, scheduling, email capture, analytics | Linktree ($5–9/mo) | $19 once |
| **[Captionly](https://onetimesuite.com)** | Local Whisper auto-captions, karaoke word-highlight, ffmpeg burn-in | Submagic ($18–39/mo) | $34 once |
| **[BloomRecorder](https://onetimesuite.com)** | Screen + camera recording, 100% local, unlimited length, MP4/GIF | Loom ($15/user/mo) | $29 once |
| **[WisperTalk](https://onetimesuite.com)** | Desktop AI dictation for Win/macOS, Groq Whisper + Llama cleanup | Wispr Flow ($15/mo) | $49 once |

---

## Planned (96)

Not shipped. Not "almost shipped." Planned.

The full catalog is public at [onetimesuite.com](https://onetimesuite.com) with intended pricing, because I'd rather commit to the number in advance than discover it later. PDF tools, background removal, transcription, self-hosted analytics, invoicing, uptime monitoring, e-signature, the rest.

Every one lands here as a repo the day it ships. Watch me hit the number or watch me miss it. Both are useful data.

---

## Why this exists as open source

Every objection to one-time pricing is the same objection: *lifetime means the lifetime of the company, not mine.*

Fair. Everyone who has bought a lifetime deal has watched one die.

MIT source is the only real answer to that, and it's the whole reason the license is what it is. If I get hit by a bus on day 47, the software doesn't go with me. You keep the code, the build instructions, and the right to do whatever you want with both. No support contract required, no escrow clause, no trusting my roadmap.

That's not generosity. It's the only version of "buy once, own forever" that's actually true.

---

## What I'm building with

**Desktop:** Electron / Tauri, local Whisper, ffmpeg, Piper, on-device OCR
**Web-hosted:** Node, Next.js, SQLite (FTS5), Postgres, Supabase, Docker
**Infra:** Contabo VPS, Redis / BullMQ, Cloudflare, local GPU inference on an RTX 5060 Ti
**Design principle:** your hardware does the work, so why are you paying rent on it

---

## Fair warnings

- 100 apps means some will be thin. Thin is fine. Broken is not. If I ship broken, open an issue and be loud about it.
- Some of these repos are scaffolding ahead of a real release. If a repo has no tagged release, treat it as unfinished.
- Code signing, notarization, and auto-updates across Windows and macOS at this volume is the unglamorous part that will quietly eat me alive. If you've done it, I'm listening.

---

## Elsewhere

Buy any app on its own, from $19. Or take the whole catalog, including everything I ship later, in one receipt.

[Browse every app](https://onetimesuite.com) · [Buy on Whop](https://whop.com/onetime-suite) · The $997 everything bundle · [advancedmarketing.co](https://advancedmarketing.co)

**Pay once. Own it forever.**
