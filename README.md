# سَعْي — صفحة العرض (Landing Page)

هذه نسخة ثابتة (static) من صفحة "سَعْي" جاهزة للنشر عبر GitHub Pages.

محتويات:
- index.html — الصفحة الرئيسية (RTL، عربي).
- styles.css — أنماط خارجية.
- .github/workflows/deploy.yml — إعداد GitHub Actions لنشر تلقائي إلى gh-pages.

نشر سريع:
1. أنشئ مستودعًا على GitHub أو استخدم المستودع الموجود (مثال: mohamed293006-code/sa3y).
2. انسخ الملفات (index.html, styles.css, README.md, .github/workflows/deploy.yml) إلى جذر المستودع.
3. نفّذ الأوامر محلياً:
   - git init
   - git add .
   - git commit -m "Initial site"
   - git branch -M main
   - git remote add origin git@github.com:<username>/<repo>.git
   - git push -u origin main
4. GitHub Actions في المسار `.github/workflows/deploy.yml` سيبني وينشر إلى الفرع `gh-pages` تلقائيًا عند كل دفع إلى `main`.
5. بعد نجاح التشغيل، افتح Settings → Pages لترى رابط النشر أو استخدم:
   https://<username>.github.io/<repo>/

ملاحظات:
- النماذج الحالية تستخدم mailto: (البريد المستلم: sa3y.network@gmail.com). إن أردت حفظ الطلبات أو إرسال بريد سيرفر، سأجهّز مثال Node.js/Express أو تكامل مع Formspree.
- لأضافة نطاق مخصص، ضع ملف CNAME في جذر المستودع بقيمة النطاق ثم عدّل سجلات DNS عند المسجل.
