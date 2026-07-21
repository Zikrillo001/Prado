# Kod loyihasi strukturasi (reja)

Bu — kelajakdagi kod loyihasining rejalashtirilgan tuzilishi. Kod hali yozilmagan;
u alohida qadamda yaratiladi. Stack: `../docs/08-texnik-arxitektura.md`.

## Rejalashtirilgan tuzilish
```
project/
├── frontend/          Next.js (React, TS) — SSR sayt + admin panel
│   ├── app/           sahifalar (landing, katalog, e'lon, profil, admin)
│   ├── components/    UI komponentlar
│   ├── lib/           API klient, utils
│   └── locales/       uz / ru
├── backend/           NestJS (TS) — REST API
│   ├── modules/       auth, listings, users, payments, promotions, admin, club
│   ├── entities/      ma'lumotlar modeli (07-hujjatga mos)
│   └── integrations/  payme, click, telegram, sms, storage
├── db/                migratsiyalar, seed (Dilshod inventari)
└── docs/              texnik hujjatlar (API, setup)
```

## Modullar (backend) — 06/07 hujjatlarga mos
auth · users · listings · categories · promotions · payments · verification ·
favorites · saved-search · reports · admin  ·  (Faza 1) club: events, tickets, membership, gallery, reviews

## Keyingi qadam
Kod loyihasini yaratish — dizayn (UI) tasdiqlangach va stack yakunlangach boshlanadi.
