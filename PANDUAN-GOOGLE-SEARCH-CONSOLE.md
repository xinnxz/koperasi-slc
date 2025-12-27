# Panduan Verifikasi Google Search Console
## Website: koperasislc.xyz

---

## Langkah 1: Buka Google Search Console
1. Buka browser → https://search.google.com/search-console
2. Login dengan akun Google

---

## Langkah 2: Tambahkan Property
1. Klik **"Add Property"** (pojok kiri atas)
2. Pilih **"URL prefix"** (lebih mudah untuk pemula)
3. Masukkan: `https://koperasislc.xyz`
4. Klik **Continue**

---

## Langkah 3: Verifikasi Kepemilikan

### Opsi A: HTML File (Recommended)
1. Download file HTML yang diberikan Google
2. Upload ke root folder hosting (sejajar dengan index.html)
3. Klik **Verify**

### Opsi B: HTML Meta Tag
1. Copy meta tag yang diberikan Google, contoh:
   ```html
   <meta name="google-site-verification" content="KODE_UNIK_ANDA" />
   ```
2. Tambahkan ke `index.html` di bagian `<head>` (setelah line 5)
3. Upload ke hosting
4. Klik **Verify**

### Opsi C: DNS Record
1. Login ke panel domain (contoh: Rumahweb, Niagahoster)
2. Tambahkan TXT record yang diberikan Google
3. Tunggu propagasi (5-10 menit)
4. Klik **Verify**

---

## Langkah 4: Submit Sitemap
1. Di Search Console → klik menu **"Sitemaps"**
2. Di kolom "Add a new sitemap", ketik: `sitemap.xml`
3. Klik **Submit**
4. Status akan berubah jadi "Success" jika berhasil

---

## Langkah 5: Request Indexing
1. Klik menu **"URL Inspection"**
2. Di kolom pencarian, masukkan: `https://koperasislc.xyz`
3. Tunggu Google mengecek URL
4. Klik **"Request Indexing"**
5. Tunggu proses selesai (1-2 menit)

---

## Estimasi Waktu
| Proses | Waktu |
|--------|-------|
| Indexing homepage | 2-7 hari |
| Muncul di pencarian "koperasislc.xyz" | 3-7 hari |
| Ranking untuk "koperasi slc" | 2-4 minggu |

---

## Tips Tambahan
- Pastikan website bisa diakses (tidak error 404/500)
- Pastikan HTTPS aktif (bukan HTTP)
- Share link website di social media untuk mempercepat indexing
- Submit juga ke Bing Webmaster Tools: https://www.bing.com/webmasters

