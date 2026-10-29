# DaisoGel C18 Calculator (PWA)

מחשבון העמסת פפטיד לקולונת DaisoGel C18 (SP-120-15-ODS-RPS · 15 µm · 120 Å), כאפליקציית רשת מתקינה שעובדת גם בלי אינטרנט.

## 👉 [פתיחת האפליקציה](https://abedassadi-wq.github.io/daiso-c18-calculato/)

https://abedassadi-wq.github.io/daiso-c18-calculato/

## התקנה בטלפון
1. פותחים את הקישור למעלה בדפדפן.
2. **iPhone (Safari):** שיתוף ← "הוסף למסך הבית". **Android (Chrome):** תפריט ← "התקן אפליקציה".

## קבצים
- `index.html` – המחשבון
- `manifest.webmanifest` – הגדרות האפליקציה
- `sw.js` – Service Worker לעבודה אופליין
- `icons/` – אייקונים

## עדכונים
עובדים רק על `main`. בכל דחיפה ל-`main` הפעולה `.github/workflows/deploy.yml` מעתיקה את הקבצים לענף `gh-pages` (שממנו GitHub Pages מציג את האתר) ומחתימה את גרסת ה-cache ב-`sw.js` לפי הקומיט, כך שהאפליקציה בטלפון מתעדכנת לבד. אין לערוך את `gh-pages` ידנית.
