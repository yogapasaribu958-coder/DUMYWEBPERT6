# Pawly

Landing page statis berbahasa Indonesia untuk toko perlengkapan hewan peliharaan fiktif. Tidak memerlukan proses build atau dependensi; Netlify menyajikan `index.html` langsung.

## Deploy ke Netlify

1. Buat repository GitHub baru dan push branch utama ke sana.
2. Di Netlify, pilih **Add new site → Import an existing project** lalu hubungkan repository.
3. Biarkan **Build command** kosong dan isi **Publish directory** dengan `.`.
4. Pilih **Deploy site**. Pengaturan yang sama sudah dicatat di `netlify.toml`.

Alternatif untuk demo cepat: seret folder ini ke Netlify Drop. Untuk deploy otomatis setiap ada perubahan, hubungkan repository Git.

## Fitur demo

- Layout responsif untuk desktop dan ponsel.
- Filter kategori produk, penghitung keranjang, dan navigasi ponsel.
- Formulir newsletter hanya simulasi dan tidak mengirim atau menyimpan data.

Foto produk dan font dimuat dari Unsplash dan Google Fonts, sehingga memerlukan koneksi internet.
