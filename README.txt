Mini Project: Responsive Dashboard Layout
Deskripsi

Buatlah sebuah layout dashboard yang responsif menggunakan CSS Flexbox dan Grid. 
Dashboard ini harus mencakup beberapa elemen berikut:

    Header: Berisi judul dashboard dan menu navigasi horizontal.
    Sidebar: Menu vertikal di sisi kiri untuk navigasi tambahan.
    Konten Utama: Bagian tengah untuk menampilkan informasi utama.
    Card Section: Sekumpulan card (4 buah) yang berisi informasi singkat.
    Footer: Bagian bawah untuk copyright atau informasi tambahan.

Spesifikasi

    Header:
        Gunakan Flexbox untuk membuat menu navigasi horizontal.
        Header tetap di bagian atas saat halaman di-scroll.

    Sidebar:
        Gunakan Grid untuk membuat menu vertikal dengan ikon dan teks.
        Sidebar harus tetap terlihat di layar besar tetapi tersembunyi (dapat diakses dengan tombol) 
        di layar kecil.

    Konten Utama:
        Bagian ini menggunakan Grid untuk menampilkan konten dalam dua kolom di layar besar dan satu kolom di layar kecil.

    Card Section:
        Gunakan Grid untuk menampilkan 4 card dengan layout 2x2 di layar besar dan 1x4 di layar kecil.
        Card memiliki bayangan, padding, dan border radius.

    Footer:
        Gunakan Flexbox untuk menyusun elemen di tengah.

Responsif

    Gunakan media query untuk menyesuaikan layout untuk perangkat dengan lebar layar kecil (< 768px).
    Sidebar harus tersembunyi dan dapat muncul menggunakan tombol di layar kecil.

Tambahan

    Gunakan placeholder image dan teks dummy (Lorem Ipsum) untuk mengisi konten.
    Tambahkan beberapa efek hover pada card dan tombol.
    Pastikan tata letak terlihat menarik dengan jarak yang konsisten.

Output Akhir

Dashboard yang terlihat seperti:

    Layar Besar:

-------------------------------------------
| Header                                  |
-------------------------------------------
| Sidebar |      Konten Utama             |
|         |-------------------------------|
|         |  Card 1   |  Card 2           |
|         |  Card 3   |  Card 4           |
-------------------------------------------
| Footer                                  |
-------------------------------------------

Layar Kecil:

    -------------------------------------------
    | Header                                  |
    -------------------------------------------
    | Konten Utama                            |
    |-----------------------------------------|
    | Card 1                                  |
    | Card 2                                  |
    | Card 3                                  |
    | Card 4                                  |
    -------------------------------------------
    | Footer                                  |
    -------------------------------------------

Tantangan Tambahan

    Gunakan variabel CSS untuk warna tema.
    Tambahkan animasi sederhana pada transisi sidebar.