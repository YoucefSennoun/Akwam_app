# Akwam TV Lite — Mortal TX1-S (1GB RAM / 8GB Storage · Android 10)

## الطريقة الأولى (الأسرع والأخف على ذاكرة 8GB — بدون كمبيوتر):
1. افتح متصفح **Chrome** أو **TV Bro** على جهاز **Mortal TX1-S**.
2. ادخل إلى الرابط: `https://ais-dev-pzc2kbcbmy6soqn6ukeiny-637113962636.europe-west2.run.app`
3. اضغط بالريموت على زر **"تثبيت على الرسيفر"** في الشريط العلوي لإضافته كتطبيق مستقل على الشاشة الرئيسية بحجم أقل من 1 ميجابايت!

## الطريقة الثانية (بناء ملف APK أصلي بحجم ~400 كيلوبايت فقط):
تم ضبط هذا المشروع خصيصاً لمعالج **Allwinner H313** ونظام **Android 10 (API 29)** وذاكرة **1GB DDR3**:
- **بدون تثبيت Android Studio**: ارفع ملفات هذا المجلد إلى مستودع جديد على GitHub، وسيقوم ملف `.github/workflows/build-apk.yml` ببناء ملف `app-debug.apk` تلقائياً خلال دقيقتين في تبويب **Actions**.
- **باستخدام Android Studio**: افتح هذا المجلد واضغط **Build > Build Bundle(s) / APK(s) > Build APK(s)** ثم انقل ملف APK إلى فلاشة USB وثبّته على جهاز TX1-S.
