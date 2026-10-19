# Easy Home — easyhome.ps

Static website ready for Cloudflare Pages.

## أهم تعديلين قبل النشر
1. افتح `assets/script.js` وضع رقم واتساب بصيغة دولية بدون + أو مسافات:
`const WHATSAPP_NUMBER="97059XXXXXXX";`
2. افتح `assets/products.js` وعدّل أسماء المنتجات والأسعار والأوصاف.

## Cloudflare Pages
ارفع هذه الملفات إلى مشروع Pages، ثم من Workers & Pages > مشروعك > Custom domains أضف `easyhome.ps`.
للنطاق الأساسي `easyhome.ps` يجب أن يكون النطاق Zone على Cloudflare وأن تشير الـ nameservers إلى Cloudflare.
