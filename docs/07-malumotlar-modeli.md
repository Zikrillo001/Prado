# Ma'lumotlar modeli (entity)

MVP uchun asosiy entity'lar (+ Faza 1 Club). Aniq maydonlar dev bosqichida kengayadi.

## Asosiy (MVP)
**User** — id, phone, telegram_id, name, role[user/admin], seller_type[individual/dealer/official], is_verified, created_at

**Category** — id, name, slug, type[car/part], parent_id

**Listing** — id, user_id, category_id, brand, model, year, mileage, engine, transmission, fuel, color, trim, condition, price, currency, description, features(json), status[active/expiring/archived], region, created_at, expires_at

**ListingPhoto** — id, listing_id, url, sort_order

**Promotion** — id, listing_id, type[VIP/TOP/boost], starts_at, ends_at, price, payment_id

**Payment** — id, user_id, target[listing/promotion], provider[payme/click], amount, status, created_at

**SellerVerification** — id, user_id, type[verified/official_store], status, verified_at

**Favorite** — user_id, listing_id

**SavedSearch** — id, user_id, filters(json), created_at

**Report** — id, listing_id, user_id, reason, status (moderatsiya uchun)

**AdminRole / Permission** — rol asosida (User.role + ruxsatlar)

## Munosabatlar (asosiy)
- User 1—* Listing
- Listing 1—* ListingPhoto
- Listing 1—* Promotion
- Promotion 1—1 Payment
- User 1—* Favorite / SavedSearch / SellerVerification
- Category *—* Listing (category_id + brand/model)

## Faza 1 — Club
**Event** — id, title, date, location, seats, price, description
**EventTicket** — id, event_id, user_id, qr_code, status
**Membership** — id, user_id, tier[gold/...], points, joined_at
**GalleryItem** — id, event_id/listing_id, url, type
**Review** — id, user_id, target, rating, text
**Sponsor** — id, name, logo, link
