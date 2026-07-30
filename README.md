# הצעת מחיר — ערד | כהן מערכות אנרגיה

אתר הצעת מחיר אינטראקטיבי (מבנה אפליקציה, GSAP) למסלול כוחות הביטחון במתחם המגורים בערד.

- קובץ יחיד: `index.html` — ללא build, GSAP מוצמד מ-CDN.
- דומיין: `arad.cohen-energy.com` (קובץ `CNAME`, GitHub Pages).
- עריכת תוכן: כל המספרים והטקסטים הדינמיים באובייקט `DATA` בראש ה-`<script>`.

## הרצה מקומית

```bash
py -3 -m http.server 8137
```

ואז לפתוח `http://localhost:8137`.

## DNS

רשומת CNAME אצל רשם הדומיין: `arad` → `barbossaaa.github.io`.
