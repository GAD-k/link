# Koleksi Download — GitHub Pages

Website statis dengan tema gelap, responsif untuk HP/PC, pencarian, kategori Windows dan Office, serta tautan yang dapat diedit sendiri.

## Cara memasang di GitHub Pages

1. Ekstrak ZIP ini.
2. Buka GitHub dan buat repositori baru. Jika ingin alamat `https://USERNAME.github.io`, nama repositorinya harus `USERNAME.github.io`.
3. Unggah `index.html` ke bagian paling atas/root repositori (bukan di dalam folder lain).
4. Buka **Settings → Pages**.
5. Di **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
7. Tunggu proses publikasi selesai. Buka alamat Pages yang ditampilkan GitHub.

## Cara mengganti tautan atau menambah file

1. Buka `index.html` di repositori GitHub.
2. Klik ikon pensil (**Edit this file**).
3. Cari bagian `const downloads = [`.
4. Untuk mengganti tautan, edit nilai `url` pada item terkait.
5. Untuk menambah file, salin satu blok item yang ada lalu ubah `name`, `category`, `icon`, `description`, `info`, dan `url`.
6. Klik **Commit changes**. GitHub Pages akan menerbitkan perubahan secara otomatis.

Kategori yang disediakan: `Windows` dan `Office`. Pastikan nilai `category` sama persis dengan nama kategori.

## Catatan

- Website ini hanya menampilkan tautan; file tidak diunggah atau disimpan di GitHub Pages.
- Gunakan tautan unduhan resmi dan pastikan kamu punya hak/lisensi untuk software yang dibagikan.
- Jangan menaruh kata sandi, token, atau data pribadi di dalam kode publik.
