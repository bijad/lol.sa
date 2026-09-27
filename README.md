# lol.sa

صفحة انتظار بسيطة بخلفية بيضاء ونص رمادي في المنتصف: **Coming soon...**

تُنشر عبر GitHub Pages من الفرع `main` والمجلد الجذر.

## ربط الدومين

| النوع | الاسم | القيمة |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | bijad.github.io |

TTL: `3600` أو القيمة الافتراضية. هذه سجلات DNS وليست Nameservers.

على Cloudflare استخدم **DNS only** (السحابة الرمادية) أثناء ربط الدومين وإصدار شهادة HTTPS.

استبدل سجلات A المتعارضة للدومين الرئيسي، وأزل أي سجل AAAA قديم يوجّه إلى استضافة أخرى. حافظ على سجلات البريد MX وTXT.

بعد انتشار DNS وإصدار الشهادة، فعّل **Enforce HTTPS** في إعدادات Pages إن لم يكن مفعّلًا.

[توثيق GitHub الرسمي](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
