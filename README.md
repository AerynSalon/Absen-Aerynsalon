# One-Host (Apps Script HtmlService) — v1.5.0
Build: 2025-08-24 05:17:43

Semua frontend + backend disatukan di **Apps Script** → tidak ada CORS.
## Cara pasang
1. Buka Google Sheet tujuan → **Extensions → Apps Script**.
2. Buat 2 file:
   - `Code.gs` → isi dengan file Code.gs pada paket ini.
   - `Index.html` → isi dengan file Index.html pada paket ini.
3. (Opsional) Buat Sheet **"Karyawan"** dengan header `ID | Nama | Jabatan | Divisi | Aktif` untuk database karyawan.
4. **Deploy** → **Deploy as Web App**:
   - Execute as: **Me**
   - Who has access: **Anyone**
5. Buka URL Web App → aplikasi siap digunakan.

## Fitur
- Picker **database karyawan** (ambil dari sheet "Karyawan").
- **Scan QR** (html5-qrcode).
- **Riwayat Absensi** sinkron server.
- **Teks berjalan**: “jangan lupa berdoa sebelum bekerja, tetap semangat team AerynSalon”.
- Tidak butuh `config.js` ataupun fetch — semua RPC via `google.script.run`.

Selamat mencoba!
