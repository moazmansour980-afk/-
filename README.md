# أركان المندي — الموقع

موقع قائمة طعام ثابت (Static) جاهز للنشر على GitHub Pages. الصفحة الرئيسية هي `index.html` وهي في جذر المستودع.

## النشر على GitHub Pages

1. أنشئ مستودعًا جديدًا (Repository) على GitHub، ويُفضّل أن يكون Public.
2. افتح المستودع واختر **Add file ← Upload files**، ثم اسحب **محتويات** المجلد بعد فك الضغط (`index.html` ومجلد `assets` وباقي الملفات)، وليس ملف الـ zip نفسه، ثم اضغط **Commit changes**.
3. ادخل **Settings ← Pages**، وفي **Build and deployment** اختر **Source: Deploy from a branch**، ثم الفرع `main` والمجلد `/ (root)`، واضغط **Save**.
4. بعد دقيقة أو دقيقتين يظهر الرابط في نفس الصفحة بهذا الشكل: `https://USERNAME.github.io/REPO-NAME/`

## ملاحظات

- جميع المسارات نسبية، فالموقع يعمل من مسار فرعي مثل `/REPO-NAME/` بدون أي تعديل.
- لا تُغيّر أسماء الملفات أو مكان مجلد `assets`.
- زر واتساب يحتاج اتصالًا بالإنترنت.
