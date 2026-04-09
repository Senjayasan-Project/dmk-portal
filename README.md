# DMK Group — Customer & Admin Portal

Portal manajemen order aspal terintegrasi untuk PT. Dhisa Manunggal Karya.

## Stack
- **Frontend**: Single-file HTML + Vanilla JS
- **Database**: Supabase (PostgreSQL)
- **Hosting**: Vercel

## Cara Deploy

### 1. Clone / Download project ini
```bash
git clone https://github.com/USERNAME/dmk-portal.git
cd dmk-portal
```

### 2. Isi konfigurasi Supabase
Edit `index.html`, cari bagian ini dan isi dengan nilai dari Supabase Dashboard → Settings → API:
```javascript
const SUPABASE_URL      = 'https://YOUR_PROJECT_ID.supabase.co';
const SUPABASE_ANON_KEY = 'YOUR_ANON_PUBLIC_KEY';
```

### 3. Deploy ke Vercel
```bash
npm install -g vercel
vercel
```

## Login Demo
| Role       | Username  | Password  |
|------------|-----------|-----------|
| Customer 1 | customer1 | demo123   |
| Customer 2 | customer2 | demo123   |
| Admin      | admin     | admin123  |

## Struktur File
```
dmk-portal/
├── index.html      ← Seluruh aplikasi (HTML + CSS + JS)
├── vercel.json     ← Konfigurasi Vercel
├── package.json    ← Project metadata
└── .gitignore
```
