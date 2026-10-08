# تطبيق الاستحقاقات — Android

هذا المشروع يحوّل لوحة Cloudflare الحالية إلى تطبيق Android مستقل باستخدام WebView.

الرابط المضمّن:
https://old-glitter-fc22.pay-departement.workers.dev/

## أسهل طريقة لإخراج APK
1. ارفع هذا المشروع إلى GitHub كمستودع جديد.
2. افتح تبويب Actions.
3. شغّل workflow باسم **Build Android APK** عبر Run workflow.
4. بعد انتهاء البناء، افتح Artifacts وحمّل **AlEstihqaqat-debug**.
5. فك الضغط وثبّت `app-debug.apk` على الهاتف.

لا يحتاج التطبيق إلى تغيير رابط Cloudflare؛ إذا تغيرت لوحة الموقع لاحقاً، سيعرض التطبيق النسخة الجديدة عند فتحه.
