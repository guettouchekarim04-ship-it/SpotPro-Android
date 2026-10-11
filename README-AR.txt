محلل SPOT PRO - مشروع Android APK

هذا مشروع أندرويد يحتوي نسخة HTML داخل WebView، مع صلاحية الإنترنت لجلب بيانات السوق.
لم يتم بناء APK داخل هذه البيئة؛ يتم بناؤه تلقائياً عبر GitHub Actions.

الخطوات:
1) فك ضغط SpotPro-Android-Project.zip.
2) ارفع محتويات المجلد إلى مستودع GitHub جديد باسم SpotPro، على الفرع main.
3) افتح تبويب Actions في المستودع.
4) اختر Build Android APK ثم Run workflow.
5) بعد انتهاء البناء، افتح التشغيل الناجح ونزّل Artifact باسم SpotPro-debug-APK.
6) فك ضغط ملف Artifact ثم ثبّت app-debug.apk على هاتف Android.

ملاحظة: هذه نسخة Debug للتثبيت الشخصي وليست موقعة للنشر في Google Play. التطبيق يراقب السوق فقط ولا ينفذ صفقات.
