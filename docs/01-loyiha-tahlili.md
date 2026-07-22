> **SCOPE O'ZGARISHI (v2):** Qamrov endi **hamma mashina** (umumiy marketplace) — premium nisha emas. Pozitsiya: umumiy avto marketplace; differensiatsiya nisha orqali emas, **ishonch + jamoa + brend + UX** orqali. Batafsil: `planning/qarorlar-jurnali.md`.

# Dilshod Prado — Loyiha strukturasi, ma'lumotlar va muammolar

**Ishchi hujjat · 2026-yil iyul**
*Planlashtirish bosqichi uchun asos. Hali bosqichlar/ishga tushirish emas — faqat yig'ilgan tahlil.*

---

## 0. Muhim tuzatish — loyiha modeli aniqlandi

Ramazon dekidan farqli o'laroq, model quyidagicha aniqlandi:

- Bu **klassifayd (e'lon) platformasi** — OLX kabi. Platforma **xaridor bilan sotuvchini bog'laydi**, xolos.
- Platforma **mashinani sotmaydi** va **mashina pulini qabul qilmaydi**. Mashina bo'yicha bitim xaridor va sotuvchi o'rtasida **oflayn** (platformadan tashqarida) bo'ladi.
- Payme/Click/Uzum/Visa **faqat e'lon haqi** (tarif) uchun ishlatiladi — bu kichik summa (10 000–50 000 so'm), qonuniy va oddiy.
- Shu sababli **2026-yil naqdsiz/eskrou qonuni platformaga to'g'ridan-to'g'ri to'siq emas** — u faqat mashina savdosiga tegishli, e'lon haqiga emas. (Bu qonun loyiha uchun *kontent/foyda* bo'lishi mumkin: kelajakda foydalanuvchilarni notarial/eskrou jarayonidan o'tkazishga yordam beruvchi funksiya.)
- **Ehtiyot qismlar marketpleysi** — loyiha ichida qoladi (avval unutilgan edi, endi kiritildi).

> Natija: dekdagi "To'lov Tizimi" slaydidagi 50 000 so'm — bu mashina narxi emas, **e'lon haqi**. Ya'ni ilovadagi to'lov oqimi aslida to'g'ri va soddaroq. Avvalgi "85 000 $ ni ilovada to'lash" degan e'tiroz — noto'g'ri o'qishdan chiqqandi, bekor qilinadi.

---

## 1. Loyihaning mohiyati

**Nima:** Premium yo'ltanmas avtomobillarga ixtisoslashgan (yoki keng — ochiq savol, 5-bo'limga qarang) e'lon platformasi. Foydalanuvchi e'lon joylaydi, tarif bo'yicha pul to'laydi; xaridor qidiradi, topadi, sotuvchi bilan Telegram/telefon orqali bevosita bog'lanadi.

**Nima emas:** Reseller emas (o'zi mashina sotib olib qayta sotmaydi); mashina bitimini qayta ishlamaydi; bank/eskrou operatori emas.

**O'xshashi:** OLX.uz / Avtoelon.uz, lekin premium yo'nalishga fokuslangan va **Dilshodning brendi/ishonchi langar** sifatida.

**Farqlash nuqtasi (dastlabki gipoteza):** Dilshodning tayyor auditoriyasi + shaxsiy ishonchi + premium nisha + (ixtiyoriy) jamoa/klub. Aynan shu uni anonim OLX-nusxadan ajratib turishi kerak.

---

## 2. Loyiha strukturasi (modullar)

### A — Marketplace (yadro)
- E'lon katalogi, kategoriyalar (Toyota Prado, Lexus, Land Cruiser, Jeep, Nissan Patrol, Pajero, Tahoe...)
- Qidiruv va filtr (marka, model, yil, probeg, narx, yoqilg'i, uzatma, holat...)
- E'lon sahifasi (detal): rasmlar, xususiyatlar, tavsif, sotuvchi bilan bog'lanish (Telegram/telefon)
- Foydalanuvchi profili + "Mening e'lonlarim" (Faol / Yakunlanadi / Arxiv)
- E'lon hayot sikli: faol → muddati tugaydi → arxivga o'tadi (avtomatik)
- Tariflar va ko'tarish: VIP / TOP / oddiy; muddat bo'yicha (1/3/5/7 kun)

### B — Ehtiyot qismlar marketpleysi
- Kategoriyalar: motor qismlari, kuzov qismlari, elektronika, salon qismlari, disklar, shinalar, boshqalar
- Qism e'lonlari (rasm, narx, sotuvchi)
- (Ochiq savol: alohida oqimda emas, boshidanmi yoki keyinroqmi)

### C — Club (ixtiyoriy / kelajak qatlami)
- Prado egalari jamoasi, tadbirlar (Chimgan Trip, BBQ, City Meetup)
- Chipta sotish, a'zolik darajalari (masalan Gold), a'zo profillari
- Mantiq: jamoa mijozlar bazasini bir joyga jamlaydi va sotuvni oshiradi ("BYD-klub" misoli)

### D — Admin panel
- Dashboard (statistika, daromad, foydalanuvchi/e'lon o'sishi, geografiya)
- Foydalanuvchilar, e'lonlar, to'lovlar boshqaruvi
- Tariflar, bannerlar, kategoriyalar
- Moderatsiya (e'lonlarni tekshirish/tasdiqlash)
- Sozlamalar, tizim loglari

### E — Autentifikatsiya va to'lov
- Telegram orqali kirish (tasdiqlash kodi)
- To'lov — **faqat e'lon haqi uchun**: Payme, Click, Uzum Bank, Visa/Mastercard/UZCARD

### F — Ishonch qatlami (qo'shilishi kerak — dekda yo'q)
- Tekshiruv/tasdiq: "Dilshod Prado tasdiqlagan" belgisi
- Ishonchli sotuvchi/rasmiy do'kon belgilari
- Kuratsiya (Dilshodning shaxsiy langari)

---

## 3. Mavjud ma'lumotlar

### Biznes (Dilshod Prado)
- Yo'nalish: Toyota Land Cruiser (Prado 120/150, LC 200/250/300), ayrim Lexus
- Model: aralash — bir qism o'ziniki (sotib olib qayta sotadi), bir qismi boshqa egalarniki (vositachilik/konsignatsiya), buyurtmaga mos mashina topadi
- Auditoriya: Instagram ~63 ming, Telegram ~2,5 ming, YouTube ~3 ming (raqamlar o'zgaruvchan; telefondan tasdiqlash kerak)
- Kanallar: Instagram (birlamchi), Telegram, YouTube
- Telefon: +998 97 402 25 50 / +998 33 402 25 50
- Manzil: Toshkent, Yangi ToshMI / PETROL zapravkasi yaqinida (2GIS: Farobiy 459B)
- Faoliyat: internetda kamida 2023-yildan
- **Yo'q:** rasmiy sayt, biznes katalogda yo'q, Google'da ko'rinmaydi, ochiq yuridik nom/STIR ko'rinmaydi

### Bozor konteksti (O'zbekiston)
- 2026-yil aprel: ikkilamchi bozorda 43,7 ming haydalgan yengil avtomobil sotildi (o'tgan yilga nisbatan −15%)
- Xorijiy yangi avtomobillar sotuvi 32% dan ko'proqqa kamaydi (~3600 dona)
- Toshkent shahri: yil boshidan bozor +11,8% o'sgan (eng yuqori dinamika)
- Eskrou: aprelda ~19,7 ming avtomobil oldi-sotdi shartnomasi eskrou orqali rasmiylashtirilgan (yangi tizim ishlayapti)
- Qonun (PF-246, 2025-yil 10-dekabr): 2026-yil 1-apreldan 10 yoshgacha bo'lgan mashina savdosi naqdsiz, eskrou/notarius orqali (faqat *mashina bitimiga* tegishli — e'lon haqiga emas)

### Prezentatsiya (Ramazon deki) tarkibi
- 12 slayd, asosan mockup
- Tariflar: 1 kun 10 000, 3 kun 25 000, 5 kun 35 000, 7 kun 50 000 (VIP) so'm — **hammasi pullik ko'rsatilgan**
- Daromad prognozi (soxta/namuna raqamlar): 1–3 oy 1,5–7,5 mln; 3–6 oy 7,5–22,5 mln; 6–12 oy 22,5–75 mln so'm/oy
- Admin panel namunaviy raqamlari: 12 458 foydalanuvchi, 8 756 e'lon, 248 450 000 so'm daromad (haqiqiy emas, mockup)
- Ikki brend yo'nalishi aralash: "Prado Club" va "Dilshod_Prado"
- To'lov: Payme/Click/Visa/Uzum/HUMO; Telegram orqali kirish
- Texnologiya (dekda yozilgan): Backend Node.js / Laravel

### Raqobatchilar / namunalar
- Mahalliy: Avtoelon.uz (ixtisoslashgan avto klassifayd), OLX.uz (umumiy), Avto.uz, UzAuto Motors (rasmiy)
- Mintaqa: Kolesa.kz (Qozog'iston), Avito Auto / Auto.ru / Drom.ru (Rossiya), sahibinden.com / arabam.com (Turkiya)
- Global: AutoTrader (UK), Cars.com / CarGurus (AQSh), mobile.de / AutoScout24 (Yevropa), Encar (Koreya), dubizzle (Fors ko'rfazi)

---

## 4. Asosiy muammolar (strategik)

1. **Sovuq start / tovuq-tuxum:** sotuvchi yo'q bo'lsa xaridor kelmaydi; xaridor yo'q bo'lsa sotuvchi joylashtirmaydi.
2. **Kuchli raqobat:** Avtoelon.uz va OLX.uz'da tarmoq effekti allaqachon shakllangan.
3. **Ishonchni o'tkazish:** Dilshodning shaxsiy ishonchini anonim platformaga qanday ko'chirish (yo'qotmasdan).
4. **Bitta odam bo'g'ini:** Dilshod hammasini o'zi qilyapti — platforma buni yechishi kerak, kuchaytirmasligi.
5. **Monetizatsiya:** OLX/Avtoelon (ba'zi joyi bepul) turgan holda, sotuvchilar har e'lon uchun pul to'laydimi? Dekdagi "hammasi pullik" modeli xavfli.
6. **Firibgarlik/moderatsiya:** soxta e'lonlar, aldov — tekshirish tizimi kerak.
7. **Qamrov:** bir vaqtda nechta mahsulot (marketplace + qism + klub)?
8. **Brend:** "Prado Club" yoki "Dilshod_Prado" — nom/yo'nalish hali qaror topmagan.
9. **Auditoriyani ko'chirish:** mavjud ~63 ming Instagram obunachini saytga qanday olib o'tish.

---

## 5. Ochiq savollar (siz javob berasiz)

*Bularni aniqlaganda loyiha real shakl oladi.*

- **Qamrov:** platforma faqat premium yo'ltanmasmi, yoki hamma mashinami?
- **Inventar:** faqat boshqalarning e'lonlarimi, yoki Dilshodning o'z mashinalari ham (rasmiy do'kon sifatida)?
- **Club:** qamrovda qoladimi yoki keyinroqqa qoldiriladimi?
- **Ehtiyot qismlar:** boshidan ishga tushadimi yoki keyinroq?
- **Monetizatsiya:** faqat e'lon haqimi? Yoki bepul e'lon + pullik ko'tarish (VIP/TOP)? Diler obunasi? Reklama?
- **Geografiya:** faqat Toshkentmi yoki butun O'zbekistonmi?
- **Bepul tarif:** bepul e'lon imkoni bo'ladimi, yoki hammasi pullikmi?
- **Auditoriya ko'chirish:** Instagram/Telegram obunachilarni saytga qanday jalb qilamiz?
- **Yuridik:** loyihani kim yuritadi (YTT/MChJ, STIR)? Dilshodning o'zimi yoki alohida tuzilmami?
- **Brend nomi:** Dilshod Prado / Dilshod_Prado / Prado Club / boshqami?
- **Til:** o'zbek + rus (ikkalasi)mi?
- **Sotuvchi kim:** faqat jismoniy shaxslarmi, yoki dilerlar/avtosalonlar hammi?

---

## 6. Bu muammolar boshqa platformalarda qanday hal qilingan

*Bilimga asoslangan (2026-boshigacha). Aniq bugungi tafsilotlarni web qidiruv bilan tekshirish mumkin.*

### Sovuq start / tovuq-tuxum
- **Kolesa.kz** avval bosma jurnal ("Kolesa") bo'lgan, keyin raqamlashgan — ya'ni **tayyor auditoriya bilan** kirgan. Bu Dilshodning holatiga aynan mos: uning ~63 ming auditoriyasi — bu uning "jurnali", ya'ni sovuq startni yechadigan asosiy aktivi.
- **OLX / Avito** umumiy klassifayd sifatida boshlab, katta trafik yig'ib, keyin vertikallarga (avto, ko'chmas mulk) bo'lingan.
- **Craigslist / mahalliy marketpleyslar:** bitta shahar/hududni to'liq egallab, keyin kengaygan (geografik fokus).
- **Umumiy qoida:** boshida **bepul joylashtirish** bilan taklifni (sotuvchini) yig'ib, keyin monetizatsiya qilingan.
- **Xulosa:** Dilshod nol emas — auditoriyasi va diler aloqalari sovuq startni allaqachon yarim yechgan. Bu uning eng katta ustunligi.

### Klassifaydda ishonch
- **Encar (Koreya):** tekshiruv hisoboti + sertifikatlangan e'lon + qaytarish kafolati.
- **Avito / OLX:** tasdiqlangan profil, reyting, "xavfsiz bitim"/yetkazib berish (tovarlar uchun eskrouga o'xshash), xaridor himoyasi.
- **dubizzle:** tekshirilgan dilerlar, "ishonchli sotuvchi" belgilari.
- **Bring a Trailer / Cars & Bids:** kuratsiya + jamoa moderatsiyasi + to'liq shaffoflik (kamchiliklar ochiq yoziladi).
- **Xulosa:** Dilshod uchun — "tasdiqlangan/verified" belgilari + uning shaxsiy kuratsiyasi langar bo'ladi. Ishonchni to'liq avtomatlashtirib bo'lmaydi; real inson tekshiruvi kerak (bu Club/brendning kuchi).

### Monetizatsiya (bepul raqobatchilar turganida)
- **Standart model — freemium:** bepul oddiy e'lon + pullik ko'tarish (VIP/TOP/yuqoriga chiqarish). OLX, Avito, Avtoelon aynan shunday ishlaydi.
- **Har e'lon uchun pul olish** (dekdagi model) — agressiv; taklifni (sotuvchini) qochirishi mumkin. Ko'pchilik boshida bepul joylashtirishga ruxsat berib, faqat ko'rinishni sotadi.
- **Dilerlardan obuna/paket:** AutoTrader va mobile.de daromadining kattasini jismoniy sotuvchidan emas, **dilerlardan** oladi (oylik paketlar).
- **Lead-gen / featured joylashuv / reklama** — qo'shimcha daromad manbalari.
- **Xulosa:** boshida bepul e'lon + pullik ko'tarish + dilerlar uchun paket — sotuvchi bazasini o'stirib, keyin monetizatsiya qilish xavfsizroq.

### Firibgarlik / moderatsiya
- Qo'lda + avtomatik moderatsiya; telefon/ID tasdiqlash; "shikoyat" tugmasi; qimmat e'lonlar uchun qo'shimcha tekshiruv.
- Telegram orqali kirish (dekda bor) — bu allaqachon oddiy anonimlikni kamaytiradi.

### Raqobatchilardan farqlanish
- **Vertikal fokus:** tor, chuqur nisha marketpleysi umumiy platformani o'sha nishada yengadi. Dilshodning premium yo'ltanmas fokusi + ishonchi — bu uning farqi.
- **Jamoa/kontent qal'asi:** bu yerda Club mantiqiy o'rin egallaydi — raqobatchi nusxa ko'chira olmaydigan aktiv.

### Bitta odam bo'g'ini
- Bu platforma-funksiya muammosi emas, **tashkiliy tuzilma** muammosi. Platformalar buni operatsion/moderatsiya jamoasini yollash va jarayonlarni avtomatlashtirish bilan yechadi.
- Admin panel + avtomatlashtirish (to'lovda e'lon avto-faollashadi, muddat tugaganda avto-arxivlanadi) — bu bo'g'inni kamaytirishning bir qismi.

---

## 7. Qisqa xulosa va keyingi qadam

- **Model aniqlashgach soddalashdi:** klassifayd vositachilik — mashina puli platformada emas, shuning uchun eskrou/qonun to'sig'i yo'q. To'lov faqat e'lon haqi.
- **Asosiy janglar:** (1) sovuq start — asosan Dilshodning auditoriyasi bilan yechilgan; (2) Avtoelon/OLX'dan farqlanish — ishonch + nisha + jamoa orqali; (3) monetizatsiya dizayni — "har e'lon pullik" emas, **freemium** (bepul e'lon + pullik ko'tarish + diler paketlari) xavfsizroq.
- **Dekdan saqlanadigan:** vizual identifikatsiya, Club g'oyasi, ehtiyot qismlar, ambitsiya.
- **Almashtiriladigan:** anonim OLX-nusxa → ishonchga langarli model; soxta raqamlar → real go-to-market; "hammasi pullik" → freemium.

**Keyingi qadam:** yuqoridagi 5-bo'limdagi ochiq savollarga javob berasiz — shundan so'ng loyihaning haqiqiy strukturasini (muammo→yechim asosida) birga quramiz.

---

## 8. Deep research topilmalari (web orqali tasdiqlangan)

*Quyidagilar endi bilimga emas, ochiq web manbalariga asoslangan.*

### 8.1 Asosiy raqib — Avtoelon = Kolesa = Kaspi.kz
- Avtoelon.uz Qozog'istonning **Kolesa Group**'iga tegishli, u esa **Kaspi.kz** (NASDAQ'da listing qilingan, Markaziy Osiyoning eng yirik fintech/marketplace giganti) nazoratida.
- Kolesa Qozog'istonda onlayn avto klassifaydda **~94% ulush**ga ega (Forbes Kazakhstan), 4 mln+ oylik foydalanuvchi, 2,5 mln faol e'lon.
- Kolesa qo'shni xizmatlarni allaqachon qurgan: **Kolesa Zapchasti** (ehtiyot qism marketpleysi) va **Kolesa Finans** (avtokredit).
- **Ma'nosi:** Dilshod "generic OLX-nusxa" sifatida chuqur cho'ntakli, tajribali gigant bilan yuzma-yuz keladi. Bu yo'lda yutish deyarli imkonsiz. Yagona yo'l — nisha + ishonch + jamoa.

### 8.2 Monetizatsiya — "har e'lon pullik" model ishlamaydi
- OLX.uz ham, Avtoelon.uz ham **freemium**: bepul e'lon + pullik ko'tarish (VIP, TOP, ko'tarish, ranglash, paketlar).
- Avtoelon'da hatto **ro'yxatdan o'tmasdan, pul to'lamasdan** e'lon berish mumkin; e'lon 14 kundan keyin avtomatik o'chadi.
- **Ma'nosi:** Ramazon dekidagi "har e'lon 10–50 ming so'm" modeli sotuvchini bepul Avtoelon/OLX'ga qochiradi. Freemium — majburiy, ixtiyoriy emas.

### 8.3 Ehtiyot qismlar — o'zi farqlash bermaydi
- Avtoelon'da ehtiyot qismlar + xizmatlar bo'limi allaqachon bor (Kolesa Zapchasti KZ'da ham). Ya'ni qism bo'limi raqib allaqachon qilgani uchun, o'zicha ustunlik emas — faqat to'liqlik uchun.

### 8.4 Eng muhim namuna — Bring a Trailer (Dilshodning aynan yo'li)
- 2007-da **oddiy avto blog** sifatida boshlangan — avval ishqibozlar jamoasini qurgan (2007–2014).
- Jamoa mashinalar ustida "talashardi" — shu muammoni yechish uchun 2014-da auksion/marketplace qo'shildi.
- Bugun: $1 mlrd+ savdo hajmi, Hearst sotib olgan.
- Asosiy aktivi — **ishonch**: kuratsiya, batafsil halol e'lonlar (kamchiliklar yashirilmaydi), ochiq kommentlar, shaffof auksion arxivi; jamoa e'lonlarni o'zi tekshiradi (900k+ foydalanuvchi).
- Daromad: e'lon haqi + xaridor haqi (spam emas).
- **Ma'nosi:** Dilshodning holati aynan shu — u avval jamoa/auditoriyani qurgan (BaT blog kabi). Uning jamoasi + ishonchi — bu ham sovuq start yechimi, ham raqib nusxa ko'chira olmaydigan qal'a. Marketplace va monetizatsiya keyin keladi.

### 8.5 Ishlaydigan ishonch mexanizmlari (ko'chirish mumkin)
- Kuratsiya + tekshirilgan sotuvchi belgilari
- Halol e'lon (kamchiliklarni ochiq ko'rsatish), shaffof narx/tarix
- "A'lo narx" turidagi belgilar (Avtoelon; CarGurus'da Instant Market Value)
- Telegram/telefon tasdiqlash bilan anonimlikni kamaytirish

### Strategik xulosa (yangilangan)
- Generic marketplace = Kaspi/Kolesa bilan yutqaziladigan jang.
- Dilshodning yagona real yo'li: **tor premium nisha + shaxsiy ishonch + jamoa (Club)** — Bring a Trailer modeli, mahalliy sharoitga moslashtirilgan.
- Monetizatsiya: bepul e'lon + pullik ko'tarish + (kelajakda) diler paketlari; "har e'lon pullik" emas.
- **Club endi "yon funksiya" emas — u strategiyaning markazi** (raqib nusxa ololmaydigan yagona narsa).

---

## 9. Deep research — 3-bo'lim (promo narxi, bo'sh maydon, klub)

### 9.1 Raqobatchi promo narxlari — dinamik, sobit emas
- Avtoelon va OLX'da ko'tarish (VIP/TOP) narxi **sobit emas** — kategoriya, hudud, muddat va rubrika mashhurligiga qarab o'zgaradi.
- Avtoelon: 1,5 mln+ foydalanuvchi, 4.9 reyting, 92k+ sharh; ro'yxatdan o'tmasdan bepul e'lon; har e'londa bozor narxi ko'rsatiladi; rasmiy dilerlardan yangi mashina + ehtiyot qism/xizmat bo'limi bor.
- OLX: bepul e'lon + pullik xizmatlar (Yengil start, Tez sotish, Turbo sotish, VIP, TOP, ko'tarish, paketlar).
- **Ma'nosi:** Dilshod uchun ham dinamik promo narxi (nisha/hudud bo'yicha) mantiqiy — sobit "har e'lon X so'm" emas.

### 9.2 Bo'sh maydon — premium nisha egallanmagan
- O'zbekistonda premium yo'ltanmasga bag'ishlangan **alohida platforma yo'q**. Prado/Land Cruiser'lar faqat:
  - umumiy klassifaydlarda (Avtoelon, OLX, Auto.uz — 24+ Prado e'loni)
  - rasmiy Toyota dilerlarida (Toyota Center Tashkent City, A-Auto, Royal Motors) — yangi mashina, shaxsiy menejer, kredit/sug'urta, lekin faqat yangi va diler narxida
  - AutoUzbek (inglizcha, GCC-import e'lonlari)
- Ya'ni "kurator, ishonchli, jamoaga langarli premium brend" maydoni haqiqatan bo'sh. E'lon (Prado ro'yxati) hamma joyda bor; ishonch + jamoa + brend yo'q.

### 9.3 Klub — kuchli regional pretsedent
- Prado egalari jamoasi real, o'rnashgan hodisa: xalqaro **Prado-Club (prado-club.su) 2008-yildan** ishlaydi — yangi a'zolar, foto/video, shaharlararo uchrashuvlar, texnik bo'limlar (styling, ta'mir, sug'urta, o'g'irlikdan himoya).
- Boku Prado Club va boshqa regional klublar ham mavjud.
- **Ma'nosi:** Prado egalari klubga tabiiy tortiladi — Club g'oyasi bo'sh gap emas, real talab bor. Va O'zbekistonda bunday jamoa-savdo platformasi yo'q — bu ham ochiq nisha.

### Strategik xulosa (3-bo'lim)
- Uch topilma bir yo'nalishni ko'rsatadi: Dilshodning haqiqiy imkoni — Prado e'lonlarini takrorlash emas (ular hamma joyda), balki egallanmagan **"ishonchli premium jamoa + kurator marketplace"** maydonini olish.
- Monetizatsiya: bepul e'lon + dinamik pullik ko'tarish (raqobatchilar modeli).
- Club — validatsiyalangan: regional Prado klublari uzoq yillardan beri gullab-yashnaydi; O'zbekistonda bo'sh.

---

## Umumiy holat: research yetarli

Strategik yo'nalish uchun ma'lumot **yetarli**. Qolgan yagona muhim bo'shliq — Dilshodning ichki raqamlari va qarorlari (byudjet, jamoa, real hajm), bu internetdan emas, undan keladi. Keyingi qadam — shu model asosida real strukturani loyihalash.
