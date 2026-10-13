# Halo, saya Agus Supriadi

**IoT & Automation Engineer (Junior)** · Yogyakarta, Indonesia

Saya belajar IoT secara otodidak sejak 2019 dan membangun mesin ATM Sampah berbasis IoT: dari kelistrikan, software mesin, website, server, sampai dashboard. Saat ini saya mencari posisi entry level di bidang IoT dan automation.

**Portofolio:** [agussupriadiaria.github.io](https://agussupriadiaria.github.io)

---

## Project utama

### ATM Sampah IoT
Mesin penukar botol bekas dengan poin, dikembangkan bersama iLitterless Indonesia. Pernah dipasang di tiga lokasi di Malang.

- Raspberry Pi 4 menjalankan logika mesin, Arduino Nano mengatur servo dan IR sensor.
- Barcode transaksi dienkripsi dengan AES-256-CBC + HMAC-SHA256.
- Website mendekripsi data, mengecek transaksi ganda, menambah poin, dan membuat voucher saat withdraw secara otomatis.
- Di UB Greencampus (1 Sep – 12 Okt 2026): 42 hari beroperasi, 1 gangguan, 148 user terdaftar.

**Kode:** [atm-sampah-iot](https://github.com/agussupriadiaria/atm-sampah-iot)
**Website sistem:** [pilahsampah.com](https://pilahsampah.com) (WordPress, Ultimate Member, MySQL, Cloudflare, dikelola sendiri di VPS dengan CloudPanel)

### Deteksi Botol dengan YOLO + GPIO (prototype)
YOLO11n di Raspberry Pi 4 mendeteksi botol dan menyalakan lampu lewat GPIO. Masih tahap uji, belum terhubung ke mesin.

**Kode:** [yolo-botol-gpio](https://github.com/agussupriadiaria/yolo-botol-gpio)

---

## Dashboard dan project web pendukung

| Project | Isi | Stack | Demo | Kode |
|---------|-----|-------|------|------|
| Metabase (self-hosted) | Dashboard monitoring status pembayaran (data dummy) | Metabase, Docker Compose, PostgreSQL, VPS | [metabase.portofolio.sbs](https://metabase.portofolio.sbs) | - |
| Appsmith (self-hosted) | Form input saran, tabel monitoring, dan chart (data dummy) | Appsmith, Docker Compose, PostgreSQL, VPS | [appsmith.portofolio.sbs](https://appsmith.portofolio.sbs) | - |
| Prodash | Dashboard produk: CRUD, filter, sortir, grafik | React 19, TypeScript, Supabase, Recharts | [prodash.portofolio.sbs](https://prodash.portofolio.sbs) | [repo](https://github.com/agussupriadiaria/product-dashboard-react-tw) |
| Prodash API | Versi Prodash dengan REST API eksternal (GET, POST, PUT, DELETE) | React 19, TypeScript, Fetch API, DummyJSON | [prodashapi.portofolio.sbs](https://prodashapi.portofolio.sbs) | [repo](https://github.com/agussupriadiaria/prodash-dummyjson-api-react-tw) |

Project web lain: [Taskly](https://github.com/agussupriadiaria/todo-app-react-tw2), aplikasi to-do dengan tampilan kanban, Supabase Auth, dan Row-Level Security ([demo](https://taskly.portofolio.sbs)).

### Login demo

Semua data di project ini adalah data dummy, tidak ada data pribadi.

| Project | Username | Password |
|---------|----------|----------|
| Prodash | admin@example.com | admin123 |
| Prodash API | emilys | emilyspass |

---

## Tech stack

- **IoT & Embedded:** Raspberry Pi, Arduino, IR sensor, servo, GPIO, C++, Python
- **Data & Backend:** MySQL, PostgreSQL, WordPress, REST API, Supabase
- **Dashboard & Infra:** Appsmith, Metabase, Docker Compose, Linux (Ubuntu), SSH, VPS, CloudPanel, Cloudflare, Git
- **Web:** React, TypeScript, Tailwind CSS

Saya memakai AI (Claude, ChatGPT, Gemini, Hugging Face) untuk mempercepat penulisan dan review kode. Desain sistem, kelistrikan, dan debugging saya kerjakan sendiri.

---

## Kontak

- Email: agus.supriadi.aria@gmail.com
- Lokasi: Kalasan, Sleman, Yogyakarta
- [LinkedIn](https://www.linkedin.com/in/USERNAME)
- [YouTube](https://www.youtube.com/@ariajogja_3035)
