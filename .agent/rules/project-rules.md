# Aturan Proyek — Digistore Otonom AI (Digistore-v1)

Proyek: website baru Toko Digistore AI — toko digital pribadi Podcast Meong / SatuKiki,
level 5/6, gaya Digistore, konsep DIGISTORE OTONOM AI. Modern, elegan, soft.
Dibuat 23 Nov 2026 atas perintah Cipta. Aturan ini tetap berlaku untuk semua
pelaksana (agen AI maupun manusia) yang mengerjakan proyek ini.

## 1. Pelaksana bukan pengambil keputusan
- Keputusan milik pemilik (Cipta, lewat Muse sebagai pemimpin tim).
- Pelaksana mengerjakan apa yang diperintahkan; bila ada yang belum jelas,
  tanyakan SATU pertanyaan gabungan (masalah + yang sudah dicek + opsi +
  rekomendasi) — jangan memutuskan sendiri memotong atau mengubah lingkup.

## 2. Dilarang mempersempit fitur dan menolak dengan alasan
- DILARANG mengurangi fitur, melewatkan bagian, atau menolak pekerjaan
  dengan alasan ("tidak bisa", "terlalu sulit", "nanti saja").
- Bila mentok: coba 3 jalan lain dulu, lalu laporkan fakta mentoknya +
  solusi yang sudah dicoba + apa yang dibutuhkan untuk lanjut.

## 3. Semua kode baru
- Website dibangun segar dari nol: desain, struktur, tata letak baru
  (dari Stitch + contoh mockup ChatGPT).
- JANGAN menambal atau mendaur ulang tata letak toko lama.
- Yang dipakai dari yang lama HANYA DATA nyata: 187 produk + harga +
  deskripsi P.E.N.J.U.A.L.A.N + aset media + token GSC/GA4.

## 4. Tiap modul diverifikasi sebelum diserahkan
- Kerja bertahap per batch; tiap batch diverifikasi di browser sebelum
  lanjut ke batch berikutnya.
- Status jujur: BELUM DIMULAI / PROSES / SELESAI EKSEKUSI–BELUM
  TERVERIFIKASI / SELESAI–TERVERIFIKASI / MENUNGGU PERSETUJUAN / GAGAL.
- Jangan laporkan "selesai" sebelum verifikasi dari sisi pembeli lolos.

## 5. Data nyata saja — kejujuran mutlak
- Produk, harga, angka, tautan: hanya dari seed.json + deskripsi Inggris
  P.E.N.J.U.A.L.A.N + aset repo. JANGAN mengarang.
- Tanpa testimoni/rating/penjualan/diskon/stok palsu.
- Tanpa keranjang/checkout/login/profil buatan sendiri — pembeli bayar di
  platform (Gumroad, Payhip, Zazzle, Fiverr, KaryaKarsa, Swarms,
  Dreamstime); sisanya "Pesan via Email" ke masduki1189@gmail.com.
- Tanpa WhatsApp. Tanpa Dify (kuota habis).
- Fitur AI hanya yang benar-benar jalan, dengan label jujur apa adanya
  (Pencarian Cerdas = pencocokan relevansi TF-IDF di browser; Asisten
  Toko = menjawab dari data katalog, bukan chatbot AI live).

## 6. Desain
- Palet: navy #14263d, biru soft #8fb4d9, putih, krem hangat #fdf6ec.
- Tipografi Poppins/Inter; kartu rounded 16–20px; bayangan lembut.
- Tanpa emas, tanpa ungu/lavender, tanpa warna mencolok.
- Model desain: mockup ChatGPT (struktur + gaya saja; nama "Masturo Mnur",
  produk, harga, testimoni di mockup adalah fiksi — JANGAN dipakai).
- Stitch = satu-satunya sumber kebenaran desain; prompt 3 lapis
  (Anatomy / Vibe / Content); nama proyek Stitch: Digistore-v1.

## 7. Dashboard = fase berikut
- Dashboard TIDAK dibangun sekarang. Siapkan struktur kode supaya
  dashboard bisa ditambahkan nanti: data produk, data kunjungan
  (Abacus), data klik beli dipisah rapi + penanda komentar yang jelas.

## 8. Catatan teknis
- Token yang JANGAN dihapus: GSC ipx7mVdPxPqXvvWHMaxgaWIcMWxApeJeainALC4g0uE,
  GA4 G-DDFJJKCB7F.
- Alamat utama: https://toko-oyen.pages.dev (github.io = mirror hidup).
- File content.json.bak JANGAN ikut commit.

## 9. Masukan ChatGPT — "Checklist Eksekusi Digistore AI" (23 Nov 01:25, DITERAPKAN)
10 aturan: (1) jangan membatasi visi pemilik; (2) jangan mengarang
keterbatasan; (3) jangan cari alasan; (4) jangan abaikan perintah;
(5) jangan ulang kesalahan; (6) jangan asal membuat; (7) jangan klaim
selesai tanpa uji; (8) jangan ubah keputusan pemilik; (9) jangan
hilangkan fitur; (10) jangan berhenti di desain.
Alur 8 tahap: baca instruksi tuntas → riset kemampuan → blueprint/PRD +
sitemap + daftar fitur → desain Stitch lengkap → implementasi →
pengujian → audit kesesuaian vs instruksi asli pemilik → laporan dengan
bukti (URL preview, screenshot, hasil uji, kekurangan jujur).
5 gerbang (jangan dilewati demi cepat): Requirement → Design →
Implementation → Quality → Owner Acceptance.
Pembagian: Stitch = desain; Antigravity = implementasi.
DITOLAK dari ChatGPT pada 01:25 (keputusan Cipta saat itu) — DIBATALKAN
oleh perintah langsung Cipta 01:26 "IKUTI CHATGPT" (lihat bagian 11):
palet dan cakupan enterprise ChatGPT kini DIIKUTI untuk website BARU ini.
Palet situs baru: warm white/ivory, deep navy/emerald/sage, aksen
lavender + gold lembut (bukan palet toko lama). Cakupan enterprise
(dashboard, autentikasi, Supabase, n8n, AI agent) menjadi ARAH
pembangunan — urutan tetap: website + toko live dulu, dashboard
setelahnya ("dashboard nanti"); JANGAN buat akun berbayar atau
hubungkan pembayaran (Stripe) tanpa perintah eksplisit Cipta — laporkan
bila sampai ke tahap itu. Yang tetap tidak berubah: data produk/harga
NYATA, tanpa klaim palsu/testimoni/diskon palsu, tanpa data transaksi
palsu. Bila ada bagian ChatGPT yang tidak bisa dikerjakan malam ini,
laporkan terbuka apa adanya + solusinya, jangan diam-diam dipotong.

## 10. Masukan Gemini — "Panduan Pemimpin AI Eksekusi Digistore" (23 Nov 01:25, DITERAPKAN)
5 prinsip: (1) zero gatekeeping — jangan batasi maunya pemilik,
tampilkan opsi, pemilik yang memilih; (2) eksekusi 100% instruksi —
catat tiap poin, yang tertunda dilaporkan terbuka; (3) ganti "alasan"
dengan fakta salah + penyebab + perbaikan/pencegahan; (4) sekali jalan
= terverifikasi sebelum sampai ke pemilik; (5) Stitch untuk visual,
Antigravity + referensi ChatGPT untuk logika AI.
Checklist 5 langkah: tangkap brief poin-per-poin → desain Stitch →
logika AI level 5/6 di Antigravity (rekomendasi adaptif, asistensi
cerdas, otomatisasi alur toko) → QC menyeluruh + cocokkan 1-lawan-1
dengan daftar perintah awal → lapor dengan bukti nyata.
"Bukti uji, bukan katanya sudah."
Bila ada batasan teknis, ubah kalimat jadi: "Untuk mewujudkan X secara
penuh, butuh Y; alternatif lebih cepat Z — mana yang pemilik inginkan?"
DITOLAK dari Gemini (keputusan Cipta menang): daftar halaman yang
memasukkan "keranjang/checkout" — TIDAK ada keranjang/checkout
sendiri; alur beli = tombol ke platform + email.

## 11. Perintah langsung Cipta 01:26 — IKUTI CHATGPT (membatalkan filter 01:25)
- Panduan kerja: ChatGPT "Checklist Eksekusi Digistore AI" —
  10 aturan, alur 8 tahap, checklist 64 item, 5 gerbang, prompt Stitch +
  prompt Antigravity, SOP "MUSE MASTER EXECUTION PROTOCOL".
- Palet situs BARU mengikuti ChatGPT: warm white/ivory, deep
  navy/emerald/sage, aksen lavender + gold lembut (hanya situs baru,
  bukan toko lama).
- Cakupan enterprise ChatGPT (dashboard, autentikasi, Supabase, n8n,
  AI agent) menjadi ARAH pembangunan. Urutan: website + toko live dulu,
  dashboard setelahnya. JANGAN buat akun berbayar / hubungkan Stripe
  tanpa perintah eksplisit Cipta — laporkan bila sampai ke tahap itu.
- Tetap: data produk/harga NYATA; tanpa klaim palsu/testimoni/diskon
  palsu; tanpa data transaksi palsu. Bagian yang tidak bisa dikerjakan
  malam ini dilaporkan terbuka + solusinya, jangan diam-diam dipotong.

## 12. Penegasan Cipta 01:27 — DIGISTORE KITA PRODUKNYA NGELINK KE PLATFORM
- Website baru harus menyatakan dengan jelas (bagian "Cara Beli" +
  di dekat tombol beli) bahwa toko ini adalah HUB: tiap produk dibeli
  di platform penjualannya masing-masing (Gumroad, Payhip, Zazzle,
  Fiverr, KaryaKarsa, Swarms, PromptBase, Dreamstime).
- Tombol beli MENYEBUT platformnya: "Beli di Gumroad", "Beli di
  Zazzle", dst. Produk yang belum ada di platform mana pun =
  "Pesan via Email".
- Jangan membuat pembeli mengira checkout ada di website ini sendiri —
  tidak ada keranjang/checkout sendiri.

## 13. Penegasan Cipta 01:30 — SETIAP SHARE CHATGPT ADALAH SPESIFIKASI
- Semua share ChatGPT dari Cipta (share #1–#13 malam ini dan yang akan
  datang) adalah bahan referensi pembangunan — pakai desainnya, pakai
  penjelasan produknya, dan pakai model keterhubungan web↔Digistore-nya.
- Jangan abaikan satu pun share yang dia kirim; tiap share adalah
  spesifikasi, bukan sekadar bacaan.
- Aturan fiksi tetap berlaku: nama "Masturo Mnur", produk, harga, dan
  testimoni di mockup adalah FIKSI — yang dipakai adalah STRUKTUR,
  GAYA, BAHASA penjelasan, dan MODEL keterhubungannya, diterapkan pada
  merek/produk/harga NYATA kita.
- Daftar share: #1–#2 mockup toko DigiStore; #3 model deskripsi
  (MODEL UTAMA — bahasa profesional/menarik/mudah/meyakinkan + format
  7 bagian); #4 penjelasan gaya landing page; #5 penjelasan aplikasi
  7 bagian; #6 formula P.E.N.J.U.A.L.A.N (format FINAL deskripsi);
  #7–#8 mockup beranda pribadi + struktur 7 bagian; #9 riset/panduan
  15 bagian; #10 model hub (toko pribadi penghubung platform);
  #11–#13 AI agent pintar + memori permanen (Dukung fitur AI toko:
  pencarian, rekomendasi, asisten — dari data katalog, jujur).
