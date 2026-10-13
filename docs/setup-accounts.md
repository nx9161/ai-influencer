# Setup: everything to connect and sign up for

Two groups: things connected **to the assistant** (so I can do the work),
and accounts **you hold yourself** (you use these directly).

## A. Connected to me (current status, 2026-10-13)

| # | Service | Why | Status |
|---|---|---|---|
| 1 | **Instagram** | Post reels/carousels for Bia, read comments, check insights | Connected (@internationalf1guy — rename to @bia.duarte in the app) |
| 2 | **GitHub** | Push this repo, version everything | Connected |
| 3 | **ElevenLabs** | Bia's voice (Adriane — Brazilian female, warm/friendly) | Connected via API key. Skill: `~/workspace/skills/elevenlabs/` |

**Already available, no connection needed:** I generate Bia's face and
content images in chat, write prompts/captions/scripts, synthesize
voiceovers through ElevenLabs, organize files, and use Notion.

## B. Your own accounts (you drive these, I guide)

| Service | For | Plan |
|---|---|---|
| **Google Flow** | Veo video clips, Bia's locked character | Included in your Gemini subscription (credit-limited) |
| **P-Video Avatar Generator** | Talking-head lip-sync from Bia's face + voiceover (Mac app) | Free, open-source |
| **CapCut** | Editing, auto-captions, no watermark | Free app |
| Instagram | Bia's account — @bia.duarte (rename in the app) | Free |

Alternates for stills (not currently used): Leonardo AI (150 tokens/day),
APOB AI (free credits refill daily).

## API limits (read before you ask the assistant)

- The assistant posts, reads comments, and checks insights through the
  Instagram API on the connected account. Bio and profile picture are
  settable; **the username can only be changed in the Instagram app**
  (Edit profile → Username → @bia.duarte).
- Scheduling runs through the assistant (direct API + scheduled jobs) —
  no separate scheduler needed.
- **Flow is NOT connected** (owner's call, 2026-10-13): no public API
  exists; Veo API is pay-per-clip ($0.40–3.20/8s) and the subscription
  allowance doesn't transfer. You generate clips in Flow; I handle
  everything around them.
