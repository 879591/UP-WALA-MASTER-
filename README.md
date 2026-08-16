# UP Wala Master — Premium Website

यह एक responsive, premium-style education website starter है जो user-provided UP Wala Master images और public channel information पर आधारित है।

## Included
- Premium responsive landing page
- Class 10 & Class 12 sections
- Vimal Sir founder/educator section
- YouTube, Telegram, Instagram, WhatsApp quick links
- Student Login modal
- Firebase Phone OTP integration scaffold
- Mobile-first navigation
- User-provided images in `/assets`

## Real Phone OTP चालू करने के लिए
1. Firebase Console में नया project बनाइए।
2. Authentication → Sign-in method → Phone enable कीजिए।
3. Web App register कीजिए।
4. Firebase से मिले `firebaseConfig` को `app.js` में `PASTE_...` वाली values की जगह डालिए।
5. Authentication → Settings → Authorized domains में अपनी Vercel/custom domain add कीजिए।
6. Website deploy कीजिए। Firebase reCAPTCHA + SMS OTP flow काम करेगा।

## Deploy on Vercel
इस folder को GitHub repository में upload करके Vercel में Import करें, या Vercel CLI से deploy करें।
कोई build command जरूरी नहीं है; यह static site है।

## Important
- Website में दिए गए phone/social links वही हैं जो supplied screenshots/public channel information से उपलब्ध हुए।
- Paid courses, tests, notes download, student dashboard और admin panel के लिए backend/database अलग से जोड़ना होगा।
- OTP UI real Firebase credentials के बिना केवल setup-ready है; fake OTP नहीं बनाया गया है।
