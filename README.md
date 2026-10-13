# AI Influencer Project — Rafa Duarte

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
│   ├── face/                    ← base face + approved reference images
│   ├── photos/                  ← generated post images (by batch/date)
│   └── videos/                  ← generated reels
├── content/
│   └── calendar.md              ← posting calendar + caption drafts
├── docs/
│   └── setup-accounts.md        ← everything to connect / sign up for
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
- Nothing posts without the tattoo check and the palette check.
- Rafa is openly virtual, always.
