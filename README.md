# Prado — Loyiha ish papkasi va qo'llanma

**Dilshod Prado** (platforma) + **Dilshod Prado Club** (jamoa) — premium yo'ltanmas (SUV) uchun **ishonchli jamoa + marketplace** loyihasi.
Bu repozitoriy — loyihaning **barcha tahlili, rejasi, spetsifikatsiyasi, qarorlari va materiallari**. Kod hali yozilmagan; u kelajakda `project/` ichida bo'ladi.

> Bir jumlada: Prado e'lonlarini takrorlash emas (ular hamma joyda) — egallanmagan **"ishonch + jamoa"** maydonini olish. Langar: Dilshodning ~63 ming auditoriyasi.

---

## Joriy holat

| Bosqich | Holat |
|---|---|
| Tahlil va strategiya | ✅ Tugadi |
| Reja (Blueprint v1) | ✅ Tayyor — [`docs/02-reja-blueprint.md`](docs/02-reja-blueprint.md) |
| Detal planlashtirish (MVP spec, model, arxitektura, GTM, KPI) | ✅ Tugadi — [`docs/06`](docs/06-mvp-spetsifikatsiya.md)–[`10`](docs/10-kpi-va-muddatlar.md) |
| Dilshod qarorlari (byudjet, jamoa, brend, til…) | ✅ Qabul qilindi — [`planning/qarorlar-jurnali.md`](planning/qarorlar-jurnali.md) |
| Kod loyihasi | ⛔ Hali boshlanmagan — reja: [`project/STRUKTURA-REJASI.md`](project/STRUKTURA-REJASI.md) |

**Keyingi qadam:** dizayn + stack tasdig'i → **kod loyihasini yaratish** (`project/` ichida).

---

## Hujjatlar xaritasi (qayerdan boshlash)

Tartib bilan o'qing — har biri GitHub'da bosiladigan havola:

**1. Strategiya va reja**
- [`docs/01-loyiha-tahlili.md`](docs/01-loyiha-tahlili.md) — to'liq tahlil: raqobat, muammolar, model, research
- [`docs/02-reja-blueprint.md`](docs/02-reja-blueprint.md) — **asosiy reja** (Blueprint v1): model, modullar, monetizatsiya, ishga tushirish, risklar
- [`docs/03-prezentatsiya-tahlili.md`](docs/03-prezentatsiya-tahlili.md) — boshlang'ich dizayn dekining tahlili va qaror
- [`docs/04-funksiya-inventari.md`](docs/04-funksiya-inventari.md) — dekdan funksiyalar ro'yxati (yadro / farqlash / keyin belgilari bilan)
- [`docs/05-dekdan-namunalar.md`](docs/05-dekdan-namunalar.md) — aniq UI/ma'lumot namunalari (kategoriya, maydon, ikon, holat — build reference)

**2. Detal spetsifikatsiya (build uchun)**
- [`docs/06-mvp-spetsifikatsiya.md`](docs/06-mvp-spetsifikatsiya.md) — MVP ekran + oqim darajasida (landing, qidiruv, e'lon detali, profil, admin…)
- [`docs/07-malumotlar-modeli.md`](docs/07-malumotlar-modeli.md) — entity / ma'lumotlar modeli (User, e'lon, to'lov, Club…)
- [`docs/08-texnik-arxitektura.md`](docs/08-texnik-arxitektura.md) — stack va arxitektura (SEO-birinchi, SSR)
- [`docs/09-ishga-tushirish-rejasi.md`](docs/09-ishga-tushirish-rejasi.md) — go-to-market (pre-launch → launch → o'sish)
- [`docs/10-kpi-va-muddatlar.md`](docs/10-kpi-va-muddatlar.md) — KPI va taxminiy muddatlar

**3. Planlashtirish**
- [`planning/mvp-qamrovi.md`](planning/mvp-qamrovi.md) — birinchi versiyada aynan nima bo'ladi (P0 checklist)
- [`planning/ochiq-savollar.md`](planning/ochiq-savollar.md) — Dilshoddan so'raladigan savollar
- [`planning/qarorlar-jurnali.md`](planning/qarorlar-jurnali.md) — strategik qarorlar + **Dilshod qarorlari** (qabul qilingan)

**4. Research**
- [`research/global-modellar-va-koreya.md`](research/global-modellar-va-koreya.md) — uch biznes model taqqoslash, global namunalar, Koreya bozori

**5. Brend, kod rejasi va materiallar**
- [`brand/brend-yonalishi.md`](brand/brend-yonalishi.md) — rang, logo, nom yo'nalishi (qora + oltin, premium)
- [`project/STRUKTURA-REJASI.md`](project/STRUKTURA-REJASI.md) — kelajakdagi kod loyihasining rejalashtirilgan tuzilishi
- [`assets/prezentatsiya/`](assets/prezentatsiya/) — original prezentatsiya (`Prezentatsiya1.pptx`)
- [`assets/reference-mockups/`](assets/reference-mockups/) — reference mockup rasmlar (8 ta)

---

## Papka tuzilishi

```
Prado/
├── README.md          ← shu qo'llanma
├── docs/              tahlil, reja, spetsifikatsiya (01–10)
├── planning/          MVP qamrovi, ochiq savollar, qarorlar jurnali
├── research/          global modellar, model taqqoslash, Koreya
├── brand/             brend yo'nalishi (rang, logo, nom)
├── assets/            original prezentatsiya + reference mockup rasmlar
└── project/           kelajakdagi kod loyihasi (hozircha reja: STRUKTURA-REJASI.md)
```

---

## Repozitoriyni ishlatish (setup)

Bu hozircha **hujjat repozitoriyasi** — ishga tushirish uchun dasturiy talab yo'q. Ko'chirib olish:

```bash
git clone https://github.com/Zikrillo001/Prado.git
cd Prado
```

Hujjatlar oddiy Markdown (`.md`) — GitHub'da bevosita o'qiladi yoki istalgan muharrirda (VS Code, Obsidian) ochiladi. O'zgartirish kiritish:

```bash
git add -A
git commit -m "Xabar: nima o'zgardi"
git push
```

---

## Model (qanday ishlaydi)

- **Klassifayd vositachilik** — xaridor ↔ sotuvchini bog'laydi; mashina puli platformada emas (oflayn).
- **Freemium** — bepul e'lon + pullik ko'tarish (VIP / TOP), "har e'lon pullik" emas.
- **Ishonch** — kuratsiya + tekshirilgan sotuvchi belgilari (raqibda anonimlik).
- **Jamoa (Club)** — nusxa ko'chirib bo'lmaydigan qal'a (Faza 1).

---

## Yo'l xaritasi (roadmap)

- **Faza 0 — MVP:** marketplace yadrosi (kategoriya, qidiruv/filtr, e'lon detali, profil, 4-bosqichli e'lon oqimi) + ishonch qatlami (tekshirilgan sotuvchi, Telegram login, moderatsiya) + Dilshod inventari + ko'tarish to'lovi (Payme/Click).
- **Faza 1:** Club (tadbirlar, chipta, a'zolik) + promo chuqurligi + retention (sevimlilar, saqlangan qidiruv).
- **Faza 2:** ehtiyot qismlar + servis hamkorligi + diler paketlari.
- **Faza 3:** moliya / eskrou yordami + geografik kengayish.

To'liq tafsilot: [`docs/02-reja-blueprint.md`](docs/02-reja-blueprint.md) · muddatlar: [`docs/10-kpi-va-muddatlar.md`](docs/10-kpi-va-muddatlar.md).

---

## Kod loyihasi boshlanganda

`project/` hozircha bo'sh — faqat rejalashtirilgan tuzilish bor: [`project/STRUKTURA-REJASI.md`](project/STRUKTURA-REJASI.md).
Kod yozilganda shu yerda haqiqiy ilova quriladi (stack: [`docs/08-texnik-arxitektura.md`](docs/08-texnik-arxitektura.md)) va bu bo'lim o'rnatish/ishga tushirish buyruqlari bilan yangilanadi. Build reference: [`docs/06-mvp-spetsifikatsiya.md`](docs/06-mvp-spetsifikatsiya.md) + [`docs/07-malumotlar-modeli.md`](docs/07-malumotlar-modeli.md).

---

## Dilshod qarorlari

Planlashtirishni davom ettirish uchun asosiy bandlar qabul qilingan (ish faraz sifatida; Dilshod tasdig'idan keyin aniqlashtiriladi) — [`planning/qarorlar-jurnali.md`](planning/qarorlar-jurnali.md):
byudjet yetarli · kichik jamoa yollanadi · MChJ/YTT + STIR · brend "Dilshod Prado" + "Dilshod Prado Club" · til o'zbek+rus · Toshkentdan boshlanadi · premium yo'ltanmasdan boshlanadi.
