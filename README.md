# SIG-TEORI-2101091013
Tutorial Latihan :
- [Modul 1](README.md#modul-1))
- [Modul 2](README.md#modul-2)
- [Modul 3](README.md#modul-3)
- [Modul 4](README.md#modul-4)
- [Modul 5](README.md#modul-5)

## Modul 1
# Membuat Peta (QGIS3)
1. Unduh dan ekstrak data Kit Mulai Cepat Natural Earth. Buka QGIS. Temukan folder di panel Browser . Perluas folder untuk menemukan proyek. Ini adalah file proyek yang berisi lapisan bergaya dalam format Dokumen QGIS. Klik dua kali proyek untuk membukanya.Natural Earth quick startNatural_Earth_quick_start_for_QGIS_v3

2. Gunakan kontrol geser dan zoom di Bilah Alat Navigasi Peta dan perbesar ke pulau sumatera, Indonesia.

3. Kita dapat menonaktifkan beberapa lapisan peta untuk data yang tidak kami perlukan untuk peta ini. Perluas folder dan hapus centang pada kotak di sebelah dan lapisan. Sebelum kita membuat peta yang cocok untuk dicetak, kita perlu memilih proyeksi yang sesuai. CRS default untuk proyek diatur ke . Ini adalah CRS yang populer digunakan untuk pemetaan web dan merupakan pilihan yang layak untuk tujuan kita, sehingga kita dapat membiarkannya pada nilai defaultnya. Pergi ke Proyek Tata Letak Cetak Baru .z5 - 1:18mne_10m_geography_marine_polysne_10m_admin_0_disputed_areasEPSG:3857 Pseudo-Mercator

4. Kita akan diminta untuk memasukkan judul untuk tata letak. Kita dapat membiarkannya kosong, disini saya akan mengisi dengan nama 'kota_padang_2101091013' dan klik Ok .

5. Di jendela Print Layout, klik tombol Zoom full untuk menampilkan seluruh Layout.

6. Sekarang kita harus membawa tampilan peta yang kita lihat di Kanvas QGIS ke tata letak. Pergi ke Tambah Item Tambah Peta .

7. Setelah mode Tambah Peta aktif, tahan tombol kiri mouse dan seret persegi panjang di mana Anda ingin menyisipkan peta.

8. Kita akan melihat bahwa jendela persegi panjang akan ditampilkan dengan peta dari kanvas QGIS utama. Peta yang diberikan mungkin tidak mencakup seluruh area minat kami. Gunakan opsi Edit Pilih/Pindahkan item dan Edit Pindahkan Konten untuk menggeser peta di jendela dan memusatkannya di komposer. Atau bisa disesuaikan juga dengan menggeser pada bagian sudut peta.

9. Beralih ke jendela QGIS utama. Matikan grup layer dan aktifkan grup. Grup lapisan ini memiliki gaya yang lebih sesuai untuk tampilan yang diperbesar. Gunakan kontrol pan dan zoom di Map Navigation Toolbar dan zoom di sekitar Padang .

10. Kami sekarang siap untuk menambahkan inset peta. Ganti jendela Print Layout . Pergi ke Tambah Item Tambah Peta .

11. Seret persegi panjang di tempat Anda ingin menambahkan inset peta. Anda sekarang akan melihat bahwa kami memiliki 2 objek peta di Tata Letak Cetak. Saat membuat perubahan, pastikan Anda memilih peta yang benar.

12. Pilih objek yang baru saja kita tambahkan dari panel Items . Pilih tab Properti item . Gulir ke bawah ke panel Frame dan centang kotak di sebelahnya. Anda dapat mengubah warna dan ketebalan batas bingkai sehingga mudah dibedakan dengan latar belakang peta.Map 2

13. Salah satu fitur rapi dari Tata Letak Cetak adalah ia dapat secara otomatis menyorot area dari peta utama yang diwakili di sisipan. Pilih objek dari panel Item . Di tab Properti item , gulir ke bawah ke bagian Ikhtisar . Klik tombol Tambahkan ikhtisar baru .Map 1

14. Pilih sebagai Bingkai Peta . Ini memberitahu Tata Letak Cetak untuk menyorot objek saat ini dengan tingkat peta yang ditampilkan di objek.Map 2Map 1Map 2.

15. Sekarang setelah kita menyiapkan inset peta, kita akan menambahkan grid ke peta utama. Pilih objek dari panel Item . Di tab Properti item , gulir ke bawah ke bagian Kisi . Klik tombol Add a new grid , diikuti dengan Modify grid... .Map 1

16. Pilih nilai Interval sebagai 5derajat dalam arah X dan Y. Kita dapat menyesuaikan Offset untuk mengubah tempat munculnya garis kisi.

17. Gulir ke bawah ke bagian Bingkai kisi dan centang kotak Gambar koordinat . Format defaultnya adalah Degrees tetapi muncul sebagai angka. Kita dapat menyesuaikan adalah dengan menambahkan simbol °. Pilih Customdan klik tombol Ekspresi di sebelahnya.

18. Masukkan ekspresi berikut untuk membuat string yang mengambil nomor grid dan menambahkan simbol ° ke dalamnya. 

         concat(to_string(@grid_number), '°    ')


19. Perhatikan bahwa kisi sekarang memiliki label khusus dari ekspresi. Sesuaikan pengaturan posisi untuk Kiri , Kanan , Atas dan Bawah sesuai keinginan Kita.

20. Sekarang kita akan menambahkan bingkai Rectangluar untuk menampung elemen peta lainnya seperti panah utara, skala, dan label. Pergi ke Add Item Add Shape Add Rectangle .

21. Kita dapat mengubah Gaya persegi panjang agar sesuai dengan latar belakang peta

22. Sekarang kita akan menambahkan Panah Utara ke peta. QGIS hadir dengan koleksi gambar terkait peta yang bagus - termasuk banyak jenis Panah Utara. Klik Tambah Item Tambah Gambar .

23. Sambil menahan tombol kiri mouse Anda, gambarlah sebuah persegi panjang. Di panel sebelah kanan, klik pada tab Item Properties dan perluas bagian Search directory dan pilih gambar yang kita sukai.

24. Sekarang kita akan menambahkan bilah skala. Klik Add Item Add Scalebar .

25. Klik pada tata letak tempat Anda ingin bilah skala muncul. Di tab Properti Item , pastikan Anda telah memilih elemen peta yang benar untuk menampilkan bilah skala. Pilih Gaya yang sesuai dengan kebutuhan Anda. Di panel Segmen , ubah Lebar tetap menjadi satuan dan sesuaikan segmen sesuai keinginan Anda.Map 1200

26. Saatnya memberi label pada peta kita. Klik Tambah Item Tambah Label .

27. Klik pada peta dan gambar kotak di mana label seharusnya berada. Di tab Properti Item , perluas bagian Label dan masukkan label untuk peta. Demikian pula, tambahkan label lain untuk data dan kredit perangkat lunak.

28. Setelah Anda puas dengan peta, Anda dapat mengekspornya sebagai Gambar, PDF, atau SVG. Untuk tutorial ini, mari kita ekspor sebagai gambar. Klik Tata Letak Ekspor sebagai Gambar .

29. Simpan gambar dalam format yang Anda sukai. Di bawah ini adalah gambar PNG yang diekspor.
![kota_padang_2101091013](https://user-images.githubusercontent.com/114122090/193393792-461887f7-2536-4c9a-8c5e-03f07829806c.png)

# Modul 2
## 
##
##

# Modul 3
## 
##
##

# Modul 4
## 
##
##

# Modul 5
## 
##
##
