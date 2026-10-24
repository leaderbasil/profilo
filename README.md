# Basil Ayyad — Portfolio

موقع شخصي (صفحة واحدة) لباسل عياد: Backend · AI Agents · ERP Systems.

## المحتوى
- `index.html` — الصفحة كاملة (HTML/CSS/JS)
- `assets/` — الصور (الهيرو، لقطات المشاريع، الأفاتار)
- `og-image.png` — صورة المشاركة (Open Graph / Twitter)
- `BasilHazem_CV_Updated.pdf` — السيرة الذاتية
- `sitemap.xml` + `robots.txt` — لمحركات البحث
- `.nojekyll` — لمنع معالجة GitHub Pages عبر Jekyll

## النشر على GitHub Pages
1. Settings ← Pages
2. Source: **Deploy from a branch**
3. Branch: **main** — Folder: **/ (root)**
4. Save، وانتظر دقيقة، ثم افتح:
   https://leaderbasil.github.io/profilo/

> ملاحظة: إذا غيّرت اسم المستودع أو استخدمت دوميناً مخصّصاً،
> حدّث الروابط المطلقة في `index.html`:
> `og:url` · `og:image` · `twitter:image` · `canonical` · `sitemap.xml` · `robots.txt`

## بعد النشر
1. **GoatCounter**: أنشئ حساباً على goatcounter.com ثم استبدل `YOURCODE`
   في سطر `data-goatcounter`.
2. تحقق من ظهور المعاينة عند مشاركة الرابط على LinkedIn
   (استخدم: https://www.linkedin.com/post-inspector/).

## محلياً
افتح `index.html` مباشرة، أو شغّل خادماً محلياً:
```bash
python -m http.server 8000
```
