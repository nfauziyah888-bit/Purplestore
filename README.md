purple-store-buyer-finder/
├── index.html                    # halaman utama
├── package.json                  # daftar paket & perintah
├── vite.config.js                # konfigurasi Vite
├── netlify.toml                  # konfigurasi build Netlify
├── .env.example                  # contoh env untuk tes di komputer
├── netlify/functions/search.mjs  # BACKEND: satu-satunya tempat yang memakai TWITTERAPI_KEY
└── src/
    ├── main.jsx                  # pintu masuk React
    ├── App.jsx                   # state, refresh, test koneksi
    ├── lib.js                    # data default, klasifikasi tweet, pembuat query, localStorage
    ├── styles.css                # semua tampilan
    └── components/
        ├── Dashboard.jsx         # statistik, filter, kartu tweet
        ├── Templates.jsx         # kelola template balasan
        └── Settings.jsx          # status API, interval, hashtag/keyword/aplikasi
