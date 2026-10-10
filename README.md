# بناء APK لمنصة المسابقة المدرسية

## الطريقة 1: بدون Android Studio (عبر GitHub)
1. أنشئ حساباً على github.com ثم مستودعاً جديداً (New repository).
2. ارفع كل محتويات هذا المجلد (بما فيها المجلد المخفي .github) إلى المستودع.
3. افتح تبويب Actions وانتظر انتهاء "Build APK" (3-5 دقائق).
4. ادخل على آخر عملية ونزّل الملف school-contest-apk من قسم Artifacts، فك الضغط وستجد app-debug.apk.
5. انقله للهاتف وثبّته (فعّل "التثبيت من مصادر غير معروفة").

## الطريقة 2: على جهازك (يلزم Node.js و Android Studio)
npm install
npx cap add android
npx cap sync android
npx cap open android
ثم Build > Build APK(s)

## تعديل التطبيق لاحقاً
عدّل الملف www/index.html ثم أعد الرفع/البناء.
