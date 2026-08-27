# AI Desainer UMKM PRO v2

Upgrade lengkap dari MVP: AI gambar, hapus background lokal, adapter image-to-video Veo, adapter TTS, template spanduk, login demo, draft tersimpan, export PNG/PDF, serta backend aman untuk Gemini.

## Jalankan
Node.js 20+ → `npm install` → salin `.env.example` ke `.env` → isi `GEMINI_API_KEY` → `npm start` → buka `http://localhost:3000`.

## Produksi
Aktifkan Firebase Authentication, Firestore, dan Storage. Gunakan backend/Cloud Functions untuk secret API. Terapkan `firebase.rules`.

## Catatan
Image generation memakai `gemini-3.1-flash-image`. Veo dan TTS sengaja berupa adapter karena proses video asynchronous dan model/availability TTS dapat berbeda menurut akun/region. Jangan memasukkan secret Gemini key ke frontend.
