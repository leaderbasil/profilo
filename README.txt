ملفات موقع باسل عياد — جاهزة للرفع
=====================================

محتوى المجلد:
- index.html                  الصفحة الرئيسية (هي الملف الذي يفتح أولاً)
- assets/                     الصور (11 ملف)
- og-image.png                صورة المشاركة على LinkedIn / واتساب
- BasilHazem_CV_Updated.pdf   السيرة الذاتية (زر التحميل)
- robots.txt                  ملف بسيط لمحركات البحث

طريقة الرفع:
1) Netlify (الأسهل):
   افتح app.netlify.com ثم اسحب هذا المجلد كاملاً إلى صفحة "Deploy".
2) GitHub Pages:
   ارفع محتويات المجلد إلى المستودع، ثم Settings > Pages > Branch: main / root.
3) أي استضافة عادية:
   ارفع محتويات المجلد إلى مجلد public_html.

بعد النشر (مهم):
1) افتح index.html وابحث عن og:image و twitter:image
   واستبدل "og-image.png" بالرابط الكامل، مثال:
   https://your-domain.com/og-image.png
2) أنشئ حساباً على goatcounter.com ثم استبدل YOURCODE
   في سطر data-goatcounter برمز حسابك.
3) تأكد أن الصفحة تُفتح عبر HTTPS.

ملاحظة:
لا تفصل الصور عن ملف index.html — يجب أن يبقى مجلد assets بجانبه.
