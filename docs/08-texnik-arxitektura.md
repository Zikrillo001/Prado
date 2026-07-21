# Texnik arxitektura va stack

## Asosiy prinsip: SEO birinchi
Loyihaning strategik nuqtasi — Google'da ko'rinish (hozir Dilshod ko'rinmaydi).
Shuning uchun sayt **server-rendered (SSR)** bo'lishi shart.

## Stack (tavsiya)
- **Frontend:** Next.js (React, TypeScript) — SSR/SSG, i18n (uz/ru), mobil-first responsive, PWA imkoni. Native ilova keyin.
- **Backend:** Node.js + NestJS (TypeScript). *Muqobil:* Laravel/PHP — agar jamoa PHP bilsa (dek shuni ham taklif qilgan).
- **Ma'lumotlar bazasi:** PostgreSQL (+ Redis — kesh/sessiya).
- **Qidiruv:** boshida PostgreSQL FTS, keyin Meilisearch/Elasticsearch.
- **Rasm/fayl:** S3-mos object storage + CDN (Cloudflare).
- **Auth:** Telegram Login + telefon OTP (Eskiz.uz kabi SMS provayder).
- **To'lov:** Payme + Click merchant API (faqat e'lon/ko'tarish haqi).
- **Hosting:** VPS/cloud + Cloudflare (CDN + himoya).

## SEO amaliyoti
SSR, sitemap.xml, JSON-LD (Vehicle/Product schema), semantik URL (/toyota/land-cruiser-prado/...),
meta teglar, tez yuklash. Bu Dilshodni Google qidiruvda ko'rsatadi.

## Arxitektura (soddalashtirilgan)
Client (Next.js) <-> API (NestJS) <-> PostgreSQL / Redis
API tashqi xizmatlar bilan: Payme/Click · Telegram · SMS · S3/CDN
Admin panel — himoyalangan bo'lim (rol asosida), xuddi shu API'dan.

## Qism/bosqichlar
- MVP: web (SSR) + admin + Payme/Click + Telegram auth
- Faza 1: Club modullari, promo chuqurligi
- Faza 2: ehtiyot qism, diler paketlari; ehtimol native ilova
