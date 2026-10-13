# KRYSEC — kiberxavfsizlik o'quv markazi sayti

Statik sayt + bitta Vercel serverless funksiya. Build talab qilinmaydi.

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Sahifalar
- `index.html` — scroll orqali 3D hikoya: Hero (jonli hujumlar globusi) → Markaz → 16 kurs → O'quv yo'li → Mentor → Yozilish

## Sozlash
- **Kontaktlar:** `assets/js/data.js` → `CONFIG` (telegram, telefon, manzil)
- **Kurslar, sertifikatlar:** `assets/js/data.js` → `COURSES`, `CERTS`
- **Mentor rasmi:** `assets/mentor/dovudbek.webp` (foni olib tashlangan). Yo'q bo'lsa "DK" monogrammasi chiqadi
- **Logo:** `assets/brand/` (mark.png, logo.jpg, favicon.png)
- **Sertifikat rasmlari:** `assets/certs/cpts.jpg`, `ejpt.jpg`, `cjca.jpg`

## Arizalar Telegram'ga
`api/enroll.js` arizani Telegram botga yuboradi. Vercel → Settings → Environment Variables:
- `BOT_TOKEN` — @BotFather token
- `CHAT_ID` — arizalar keladigan chat ID (botni guruhga qo'shib, ID ni oling)

Sozlanmaguncha forma "yuborilmadi" xabarini va Telegram havolasini ko'rsatadi.

Teksturalar: NASA Blue Marble / Black Marble (public domain).
