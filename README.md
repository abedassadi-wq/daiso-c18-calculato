# DaisoGel C18 Calculator (PWA)

מחשבון העמסת פפטיד לקולונת DaisoGel C18 (SP-120-15-ODS-RPS · 15 µm · 120 Å), כאפליקציית רשת מתקינה שעובדת גם בלי אינטרנט.

## התקנה בטלפון
1. מפעילים GitHub Pages לריפו (Settings → Pages → Deploy from branch).
2. פותחים את https://abedassadi-wq.github.io/daiso-c18-calculato/.
3. **iPhone (Safari):** שיתוף ← "הוסף למסך הבית". **Android (Chrome):** תפריט ← "התקן אפליקציה".

## קבצים
- `index.html` – המחשבון
- `manifest.webmanifest` – הגדרות האפליקציה
- `sw.js` – Service Worker לעבודה אופליין
- `icons/` – אייקונים

כשמעדכנים קבצים, יש להעלות את `CACHE` ב-`sw.js` (למשל `daiso-c18-v2`).
