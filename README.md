# web-scraper-berita
```
web-scraper-berita/
│
├── src/                 # Direktori utama untuk kode
│   ├── client/          # Frontend React
│   │   ├── components/
│   │   │   ├── ScraperForm.tsx
│   │   │   ├── ScraperResults.tsx
│   │   │   └── LoadingSpinner.tsx
│   │   │
│   │   ├── interfaces/
│   │   │   └── Scraper.ts
│   │   │
│   │   ├── services/
│   │   │   └── scraperService.ts
│   │   │
│   │   ├── pages/
│   │   │   └── Dashboard.tsx
│   │   │
│   │   ├── styles/
│   │   │   └── index.css
│   │   │
│   │   ├── App.tsx
│   │   └── index.tsx
│   │
│   ├── server/          # Backend Node.js
│   │   ├── controllers/
│   │   │   └── scraperController.ts
│   │   │
│   │   ├── services/
│   │   │   └── scraperService.ts
│   │   │
│   │   ├── models/
│   │   │   └── ScrapedItem.ts
│   │   │
│   │   ├── routes/
│   │   │   └── scraperRoutes.ts
│   │   │
│   │   ├── utils/
│   │   │   └── scraperUtils.ts
│   │   │
│   │   ├── config/
│   │   │   └── database.ts
│   │   │
│   │   ├── app.ts
│   │   └── server.ts
│   │
├── public/              # Aset publik
│   ├── index.html
│   └── favicon.ico
│
├── package.json         # Manajemen dependensi dan skrip
└── tsconfig.json        # Konfigurasi TypeScript
```
