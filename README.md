# Direct Link ADS to Popup

**Ubah Iklan Direct Link Anda menjadi popup dengan mudah menggunakan script sederhana ini!**

## Konten

Tambahkan kode berikut ke website Anda:

```html
<script type="text/javascript">
	$(document).ready(function()
	{
	  $('body').addClass('xepo_ads');
	});

	$(document).on('click','.xepo_ads',function(e)
	{
	    $(this).removeClass('xepo_ads');
	    window.open('LINK_ADS_KALIAN', '_blank');
	});
</script>
```

### Langkah-langkah:
1. Ganti `LINK_ADS_KALIAN` dengan link direct Ads Anda.
2. Tempelkan script ini ke dalam website atau tema Anda.

---

### Catatan Penting:

**Untuk Tema Lite atau platform lainnya:**
Pastikan Anda menambahkan plugin jQuery. Gunakan script berikut:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js" integrity="sha512-v2CJ7UaYy4JwqLDIrZUI/4hqeoQieOmAZNXBeQyjo21dadnwR+8ZaIJVT8EE2iyI61OV8e6M8PP2/4hpQINQ/g==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

<script type="text/javascript">
	$(document).ready(function()
	{
	  $('body').addClass('xepo_ads');
	});

	$(document).on('click','.xepo_ads',function(e)
	{
	    $(this).removeClass('xepo_ads');
	    window.open('LINK_ADS_KALIAN', '_blank');
	});
</script>
```

**Untuk Pengguna Blogspot:**
Tambahkan tag DATA seperti berikut:

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js" integrity="sha512-v2CJ7UaYy4JwqLDIrZUI/4hqeoQieOmAZNXBeQyjo21dadnwR+8ZaIJVT8EE2iyI61OV8e6M8PP2/4hpQINQ/g==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

<script type="text/javascript">
//<![CDATA[
	$(document).ready(function()
	{
	  $('body').addClass('xepo_ads');
	});

	$(document).on('click','.xepo_ads',function(e)
	{
	    $(this).removeClass('xepo_ads');
	    window.open('LINK_ADS_KALIAN', '_blank');
	});
//]]>
</script>
```

---

### Informasi Tambahan:
- **Bypass Adblocker**: Script ini dapat membantu Anda melewati ad blocker untuk link iklan direct Anda.
- **Kustomisasi**: Silakan modifikasi sesuai kebutuhan.

---

Selamat mencoba bypass Adblock!

## Detail Repository

**Nama Repository:** `direct-link-ads-popup`

**Deskripsi:** Script untuk mengubah iklan direct link menjadi popup, dengan dukungan untuk Tema Lite dan Blogspot.

---

**README.md**

```markdown
# Direct Link ADS to Popup

Ubah iklan direct link Anda menjadi popup yang efektif! Script ini menyediakan cara sederhana untuk meningkatkan strategi iklan Anda dengan melewati ad blocker dan menarik pengguna secara efektif.

## Cara Menggunakan
1. Ganti `LINK_ADS_KALIAN` dalam script dengan URL iklan Anda.
2. Tambahkan script yang diperlukan (plugin jQuery dan logika popup) ke platform Anda.
3. Nikmati performa iklan yang lebih baik!

## Petunjuk Khusus Platform
- **Tema Lite**: Pastikan Anda menambahkan plugin jQuery sebelum script popup.
- **Blogspot**: Bungkus script popup dengan tag DATA untuk kompatibilitas.

## Kompatibilitas
- Bekerja di sebagian besar website dan platform.
- Sudah diuji pada Blogspot dan Tema Lite.

## Lisensi
Proyek ini dilisensikan di bawah Lisensi MIT - lihat file LICENSE untuk detail.

## Dukungan
Jangan ragu untuk membuka issue jika Anda menemukan masalah.
```

**.gitignore**

```
# Node modules
node_modules/

# File sementara
*.tmp
*.log

# Pengaturan editor
.vscode/
.idea/
.DS_Store

# File build
/dist/
```

**LICENSE**

```plaintext
MIT License

Hak Cipta (c) 2024

Izin diberikan, tanpa biaya, kepada siapa saja yang memperoleh salinan
perangkat lunak ini dan file dokumentasi terkait ("Perangkat Lunak"), untuk berurusan
dengan Perangkat Lunak tanpa batasan, termasuk tanpa batasan hak
untuk menggunakan, menyalin, memodifikasi, menggabungkan, menerbitkan, mendistribusikan, melisensikan, dan/atau menjual
salinan Perangkat Lunak, dan untuk mengizinkan orang-orang kepada siapa Perangkat Lunak
diberikan, tunduk pada ketentuan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus dimasukkan dalam semua
salinan atau bagian substansial dari Perangkat Lunak.

PERANGKAT LUNAK INI DIBERIKAN "SEBAGAIMANA ADANYA", TANPA JAMINAN APA PUN, TERSURAT MAUPUN
TERSIRAT, TERMASUK NAMUN TIDAK TERBATAS PADA JAMINAN KELAYAKAN BARANG DAGANGAN,
KESESUAIAN UNTUK TUJUAN TERTENTU, DAN NONPELANGGARAN. DALAM KEADAAN APA PUN PENULIS ATAU
PEMILIK HAK CIPTA TIDAK BERTANGGUNG JAWAB ATAS KLAIM, KERUSAKAN, ATAU KEWAJIBAN LAIN,
BAIK DALAM TINDAKAN KONTRAK, KESALAHAN ATAU LAINNYA, YANG TIMBUL DARI, DARI ATAU DALAM HUBUNGAN DENGAN
PERANGKAT LUNAK ATAU PENGGUNAAN ATAU TRANSAKSI LAIN DALAM PERANGKAT LUNAK.
```
