# Dekdan namunalar (build reference)

Ramazon dekidan chiqarilgan aniq UI/ma'lumot namunalari. Bularni qurishda
reference sifatida ishlatamiz. DIQQAT: strategiya o'zgarishlari baribir amal
qiladi (masalan, "har e'lon pullik" o'rniga freemium — `../planning/qarorlar-jurnali.md`).

## 1. Marketplace kategoriyalari (marka)
Barcha avtomobillar · Toyota Prado · Lexus · Jeep · Land Cruiser · Nissan Patrol ·
Pajero · Chevrolet Tahoe · Ehtiyot qismlar · Aksessuarlar

## 2. E'lon detali maydonlari
Yili · Probeg · Dvigatel · Uzatma · Yoqilg'i turi · Rangi · Komplektatsiya · Holati

**Xususiyat ikonlari:** Kamera 360 · Lyuk · Start/Stop · Kruiz nazorat ·
Elektr o'rindiqlar · 4WD

**E'lon holatlari:** Faol · Yakunlanish arafasida · Bugun yakunlanadi · Arxivda

**E'lon belgilari:** VIP · TOP · YANGI · PREMIUM

## 3. E'lon joylash oqimi (4 bosqich)
1. Avtomobil haqida ma'lumot: Marka, Model, Yili, Motor, Yoqilg'i turi, Uzatma
2. Qo'shimcha ma'lumot: Probeg, Rangi, Holati, Joylashuv, Narxi
3. Rasmlar yuklash
4. Tarifni tanlash

## 4. Admin panel menyu (marketplace)
Dashboard · Foydalanuvchilar · E'lonlar · Sotilganlar · To'lovlar · Statistikalar ·
Ehtiyot qismlar · Kategoriyalar · Tarif rejalar · Bannerlar · Sozlamalar · Xabarlar ·
Sharhlar · Qo'llab-quvvatlash · Tizim sozlamalari · Chiqish

**Dashboard kartalari:** Jami foydalanuvchilar · Jami e'lonlar · Aktiv e'lonlar ·
Sotilgan e'lonlar · Jami daromad. Grafiklar: daromad, foydalanuvchi o'sishi,
e'lonlar holati (donut), eng ko'p sotilgan kategoriyalar, foydalanuvchi geografiyasi.

## 5. Club admin menyu
Dashboard · Events · Orders/Zakazlar · Clients · Vehicles · Members · Reviews ·
Gallery · Reports · Notifications · Sponsors · Calendar · Settings · Users ·
Roles & Permissions · Audit Logs · System Settings · Chiqish

## 6. Ehtiyot qism kategoriyalari
Motor qismlari · Kuzov qismlari · Elektronika · Salon qismlari · Disklar · Shinalar ·
Faralar · Aksessuarlar · Boshqalar

## 7. Narx anchorlari (egangizning niyati — freemiumga o'zgaradi)
Egangiz nazarda tutgan narx nuqtalari (reference sifatida saqlanadi):
- Tarif rejalar: 1 kun 10 000 · 3 kun 25 000 · 5 kun 35 000 · 7 kun 50 000 (VIP) so'm
- Alohida xizmatlar: E'lon 50 000 · VIP e'lon 100 000 · TOP e'lon 150 000 so'm
- Daromad prognozi (oyiga): 1-3 oy 1.5-7.5 mln · 3-6 oy 7.5-22.5 mln · 6-12 oy 22.5-75 mln
> ESLATMA: bu "har e'lon pullik" model. Bizning qaror — freemium: e'lon bepul,
> VIP/TOP/ko'tarish pullik (dinamik narx). Yuqoridagi raqamlar faqat narx tuyg'usi uchun.

## 8. Daromad manbalari (dekda)
E'lon joylashtirish · VIP e'lon · TOP e'lon · Event chipta (100-500k) ·
Club a'zolik (oylik/yillik 50-300k) · Reklama va hamkorlik (kelishilgan narx)

## 9. To'lov
**Usullar:** Click · Payme · Uzum Bank · Visa/Mastercard · UZCARD · HUMO

**Foydalanuvchi oqimi:** e'lon/xizmatni tanlaydi -> "To'lov qilish" -> to'lov tizimini tanlaydi

**Jarayon:** Foydalanuvchi talabi -> To'lov tizimi (server) -> Bank/protsessor ->
Tasdiqlandi (SSL/HTTPS)

**Tizim tomoni:** To'lov tasdiqlandi -> e'lon avto-faollashadi -> foydalanuvchi va
admin bildirishnoma -> daromad statistikasiga qo'shiladi

**Xavfsizlik:** SSL/HTTPS · PCI DSS · ma'lumot himoyasi · refund imkoniyati

## 10. Club strukturasi
- Tadbirlar: joy soni (masalan 45/60), tadbir detali, to'lov, chipta (QR)
- A'zolik: Gold darajasi, ballar, qatnashilgan tadbirlar soni
- A'zo profili: ism, joylashuv, avtomobil (masalan Prado VX 2021), tranzaksiyalar
- Boshqaruv: events, members, gallery, sponsors, calendar, reviews

## 11. Servis hamkorligi strukturasi
**Hamkorlik jarayoni:** 1. Ariza yuborish -> 2. Shartnoma tuzish ->
3. Platformaga qo'shish -> 4. A'zolarga xizmat

**Servis xizmatlari:** texnik xizmat · kompyuter diagnostika · dvigatel/transmissiya ·
xodovoy ta'mir · elektrika/elektronika · konditsioner · moy almashtirish

**Hamkor imtiyozlari:** a'zolarga chegirma · reklama · xaritada ko'rinish ·
tavsiya nishoni · doimiy mijozlar oqimi

**Namunaviy hamkorlar (dekda):** Prado Service, Tashkent Motors, Avto Oil Center,
UzParts, Japan Parts, AutoZone

## 12. Texnologiya (dekning taklifi — keyin tasdiqlanadi)
Backend: Node.js / Laravel · Integratsiya: Click API, Payme API, Paynet (Visa)
> Bu dekning taklifi. Yakuniy stack kod loyihasi bosqichida tanlanadi.
