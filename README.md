Sen senior dasturchi va texnik yozuvchisan. "Bolajon Olami" loyihasi uchun GitHub'ga mos, professional README.md yoz. README o'zbek tilida (lotin yozuvi) bo'lsin; oxirida qisqa inglizcha "English summary" bo'limi qo'sh.

LOYIHA HAQIDA
- Nomi: Bolajon Olami
- 2–6 yoshli bolalar uchun o'zbek tilidagi ta'limiy o'yinlar sayti.
- Texnologiya: bitta HTML fayl (HTML + CSS + vanilla JavaScript), framework va build tizimi yo'q.
- Ma'lumotlar (yulduzlar, natijalar, sovg'alar, sozlamalar) brauzer localStorage'ida saqlanadi. Boshqa qurilmaga ko'chmaydi.
- Oflayn/o'rnatiladigan ilova uchun manifest.json va sw.js bor (HTTPS yoki localhost kerak).

IMKONIYATLAR (faqat shularni yoz)
- 20 dan ortiq o'yin: Sanash, Harflar, Qaysi harf?, Ranglar, Xotira, Sharlar, Shakllar, Hayvon ovozi, Raqamlar, Katta-kichik, Mevalar, Qo'shamiz, Ayiramiz, Boshqachasi, Rasm chizish, Harf yozish, Mening tanam, Kasblar, Milliy taomlar, Fasllar, Keyingisi nima?, Soyasini top, Birinchi tovush, Ertaklar.
- 3 qiyinlik darajasi (oson / o'rtacha / qiyin) bir qator o'yinlarda.
- O'rganish dunyosi xaritasi (yulduz bilan ochiladigan hududlar), yosh guruhlari (2–3, 3–4, 4–5, 5–6), kunlik reja.
- Yutuqlar va nishonlar, yulduzlar uchun sovg'alar (ota-ona tasdiqlaydi, tahrirlash mumkin).
- Ota-onalar hisoboti: mavzular bo'yicha natija, takrorlash tavsiyalari, vaqt, tanaffus eslatmasi.
- Savollarni ovoz chiqarib o'qish (brauzerning speech synthesis'i; o'zbekcha ovoz hamma qurilmada yo'q).
- Chop etiladigan mashq varaqlari, kun/tun mavzusi, bolalar xavfsizligi uchun ota-ona tekshiruvi va 20 daqiqalik dam olish eslatmasi.
- Obuna tizimi (20 000 so'm) faqat Claude muhitidagi claude.use('user') va claude.use('db') integratsiyasi bilan ishlaydi; oddiy hostingda ishlamaydi.

README BO'LIMLARI
1. Sarlavha, qisqa tavsif va 3–4 ta mantiqli badge (faqat haqiqiy narsalar uchun: HTML5, JavaScript, PWA; soxta build/test badge'lari qo'shma).
2. Skrinshotlar uchun joy (rasmlar yo'q bo'lsa, TODO izoh qoldir; soxta havolalar yozma).
3. Imkoniyatlar (jadval yoki ro'yxat).
4. Tezkor boshlash: faylni brauzerda ochish; `python3 -m http.server 8000` bilan lokal sinash.
5. Hostingga joylash: GitHub Pages, Netlify, Cloudflare Pages (index.html, manifest.json, sw.js bitta papkada, HTTPS).
6. Fayllar tuzilmasi.
7. Ma'lumotlar va maxfiylik: bola ismi/joyi yig'ilmaydi, hammasi qurilmada; "Natijalarni o'chirish" tugmasi bor.
8. Ma'lum cheklovlar: obuna/admin faqat Claude muhitida; to'lovni serverda tekshirish yo'q (backend kerak); ota-ona tekshiruvi oddiy ko'paytirish savoli, haqiqiy autentifikatsiya emas; ovoz sifati qurilmaga bog'liq.
9. Yo'l xaritasi (hali qilinmagan): serverda to'lov tekshiruvi, bir nechta bola profili, PNG ikonkalar, ko'proq ertaklar.
10. Hissa qo'shish (Contributing) va litsenziya (litsenziya turini men keyin tanlayman, shuning uchun "LICENSE: TBD" deb qoldir).

QOIDALAR
- Shaxsiy ma'lumotlarni (telefon, email, Telegram, karta raqami) README'ga yozma; "Aloqa" bo'limida faqat "GitHub Issues orqali yozing" de.
- Mavjud bo'lmagan imkoniyatni yoki test natijasini va'da qilma.
- Matn aniq, qisqa va do'stona bo'lsin; haddan tashqari emoji ishlatma (bo'lim sarlavhalarida bittadan bo'lsa bo'ladi).
- Natijani bitta Markdown blok ko'rinishida ber.
