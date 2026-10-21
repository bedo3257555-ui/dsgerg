# شرقاوي – المتابعة الغذائية والعلاجية والرياضية

نسخة محوّلة من المشروع الأصلي (TypeScript) إلى JavaScript/JSX.

| النوع | الملفات |
|---|---|
| HTML | `index.html`, `scripts/install-page.html` |
| CSS | `src/styles.css` (المصدر, Tailwind v4), `styles.compiled.css` (المبني) |
| JS | `src/lib/*.js`, `src/routeTree.gen.js`, `server/`, `vite.config.js`, `scripts/*.mjs` |
| JSX | `src/routes/*.jsx`, `src/components/*.jsx`, `src/router.jsx`, `src/lib/**/*.jsx` |
| JSON | `package.json`, `jsconfig.json`, `data/dossier.json`, `data/app-env.json` |

## التشغيل
```
npm install
npm run dev      # http://localhost:8080
```
التحويل آلي (إزالة الأنواع فقط) فمنطق الكود كما هو. الاختبارات والـ lint محتاجة `npm install` فمجربتهاش هنا.
