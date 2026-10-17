# AI Influencer Project — Bia Duarte

> **Status:** retired — the tech-format influencer content has been retired in favor of the personality-driven approach. Kept for reference; do not present as current.


One repo for the whole virtual creator: the character, the prompts, the
assets, the content plan, and the setup docs. One persona = one repo.

## Layout

```
ai-influencer/
├── README.md                    ← you are here
├── character/
│   └── CHARACTER_BIBLE.md       ← source of truth for the persona
├── prompts/
│   └── base-prompts.md          ← copy-paste generation prompts
├── assets/
│   ├── face/                    ← locked face + 360 sheets
│   ├── photos/                  ← generated post images (by batch/date)
│   ├── audio/                   ← voiceovers (ElevenLabs)
│   └── videos/                  ← generated reels (by video)
├── content/
│   ├── calendar.md              ← posting calendar + caption drafts
│   ├── hook-playbook.md         ← viral formats that work
│   ├── profile-kit.md           ← bio, handle, highlights, 9-grid
│   ├── scripts/                 ← reel scripts (48s format)
│   ├── agent-instructions/      ← paste-ready Flow director briefs
│   └── lead-magnets/            ← comment-CTA assets (Bia's voice)
├── docs/
│   ├── setup-accounts.md        ← everything to connect / sign up for
│   └── workflows.md             ← continuity, fact-check, publishing gates
└── scripts/                     ← automation later (generation, scheduling)
```

## Quickstart

1. Read `docs/setup-accounts.md` — connect Instagram, sign up for the free
   generation tiers.
2. Read `character/CHARACTER_BIBLE.md` — the persona rules.
3. Generate the base face with `prompts/base-prompts.md`, save the winner
   in `assets/face/` and use it as the reference for everything after.
4. Plan the week in `content/calendar.md`. Post daily.

## Rules

- The bible wins every argument.
- Nothing posts without the face-lock check, the glam-palette check, and
  the IG-safe check (sexy, never explicit).
- Bia is openly virtual, always.

---

Built by **Naman Parmar** ([nx9161](https://github.com/nx9161)).
