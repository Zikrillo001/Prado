# Prado — Loyiha ish papkasi va qo'llanma

**Dilshod Prado** uchun premium yo'ltanmas (SUV) **ishonchli jamoa + marketplace** loyihasi.
Bu repozitoriy — loyihaning **barcha tahlili, rejasi, qarorlari va materiallari**. Kod hali yozilmagan; u kelajakda `project/` ichida bo'ladi.

> Bir jumlada: Prado e'lonlarini takrorlash emas (ular hamma joyda) — egallanmagan **"ishonch + jamoa"** maydonini olish. Langar: Dilshodning ~63 ming auditoriyasi.

---

## Joriy holat

| Bosqich | Holat |
|---|---|
| Tahlil va strategiya | ✅ Tugadi |
| Reja (Blueprint v1) | ✅ Tayyor — [`docs/02-reja-blueprint.md`](docs/02-reja-blueprint.md) |
| MVP qamrovi belgilangan | ✅ [`planning/mvp-qamrovi.md`](planning/mvp-qamrovi.md) |
| Dilshoddan raqamlar/qarorlar | ⏳ Kutilyapti — [`planning/ochiq-savollar.md`](planning/ochiq-savollar.md) |
| Kod loyihasi | ⛔ Hali boshlanmagan (`project/` bo'sh) |

**Keyingi qadam:** Dilshoddan raqamlar/qarorlar → MVP detallash → kod loyihasi.

---

## Hujjatlar xaritasi (qayerdan boshlash)

Tartib bilan o'qing — har biri GitHub'da bosiladigan havola:

**1. Strategiya va reja**
- [`docs/01-loyiha-tahlili.md`](docs/01-loyiha-tahlili.md) — to'liq tahlil: raqobat, muammolar, model, research
- [`docs/02-reja-blueprint.md`](docs/02-reja-blueprint.md) — **asosiy reja** (Blueprint v1): model, modullar, monetizatsiya, ishga tushirish, risklar
- [`docs/03-prezentatsiya-tahlili.md`](docs/03-prezentatsiya-tahlili.md) — boshlang'ich dizayn dekining tahlili va qaror
- [`docs/04-funksiya-inventari.md`](docs/04-funksiya-inventari.md) — dekdan funksiyalar ro'yxati (yadro / farqlash / keyin belgilari bilan)
- [`docs/05-dekdan-namunalar.md`](docs/05-dekdan-namunalar.md) — aniq UI/ma'lumot namunalari (kategoriya, maydon, ikon, holat — build reference)

**2. Planlashtirish**
- [`planning/mvp-qamrovi.md`](planning/mvp-qamrovi.md) — birinchi versiyada aynan nima bo'ladi (P0 checklist)
- [`planning/ochiq-savollar.md`](planning/ochiq-savollar.md) — Dilshoddan so'raladigan savollar (byudjet, jamoa, raqamlar…)
- [`planning/qarorlar-jurnali.md`](planning/qarorlar-jurnali.md) — qabul qilingan strategik qarorlar va sabablari

**3. Research**
- [`research/global-modellar-va-koreya.md`](research/global-modellar-va-koreya.md) — uch biznes model taqqoslash, global namunalar, Koreya bozori

**4. Brend va materiallar**
- [`brand/brend-yonalishi.md`](brand/brend-yonalishi.md) — rang, logo, nom yo'nalishi (qora + oltin, premium)
- [`assets/prezentatsiya/`](assets/prezentatsiya/) — original prezentatsiya (`Prezentatsiya1.pptx`)
- [`assets/reference-mockups/`](assets/reference-mockups/) — reference mockup rasmlar (8 ta)

---

## Papka tuzilishi

```
Prado/
├── README.md          ← shu qo'llanma
├── docs/              tahlil, reja, dek tahlili, funksiya inventari, namunalar
├── planning/          MVP qamrovi, ochiq savollar, qarorlar jurnali
├── research/          global modellar, model taqqoslash, Koreya
├── brand/             brend yo'nalishi (rang, logo, nom)
├── assets/            original prezentatsiya + reference mockup rasmlar
└── project/           kelajakdagi kod loyihasi (hozircha bo'sh)
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

To'liq tafsilot: [`docs/02-reja-blueprint.md`](docs/02-reja-blueprint.md).

---

## Kod loyihasi boshlanganda

`project/` bo'sh. Kod yozilganda shu yerda haqiqiy ilova quriladi va bu bo'lim setup ko'rsatmalari (stack, o'rnatish, ishga tushirish buyruqlari) bilan yangilanadi. Hozircha MVP qamrovi: [`planning/mvp-qamrovi.md`](planning/mvp-qamrovi.md), UI namunalari: [`docs/05-dekdan-namunalar.md`](docs/05-dekdan-namunalar.md).

---

## Dilshoddan kerak (bloklovchi qarorlar)

Loyihaning keyingi shakli shu javoblarga bog'liq — [`planning/ochiq-savollar.md`](planning/ochiq-savollar.md):
byudjet · jamoa · real raqamlar (hajm, o'rtacha bitim, marja) · yuridik tuzilma (YTT/MChJ, STIR) · brend nomi · til (o'zbek+rus) · geografiya.
