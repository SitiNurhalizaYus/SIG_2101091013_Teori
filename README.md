# SIG-TEORI-2101091013
Tutorial Latihan :
- [Modul 1](README.md#modul-1) Membuat Peta (QGIS3)
- [Modul 2](README.md#modul-2) Bekerja dengan Atribut (QGIS3)
- [Modul 3](README.md#modul-3)
- [Modul 4](README.md#modul-4)
- [Modul 5](README.md#modul-5)

## Modul 1
# `Membuat Peta (QGIS3)`
1. Unduh dan ekstrak data Kit Mulai Cepat Natural Earth. Buka QGIS. Temukan folder di panel Browser . Perluas folder untuk menemukan proyek. Ini adalah file proyek yang berisi lapisan bergaya dalam format Dokumen QGIS. Klik dua kali proyek untuk membukanya.Natural Earth quick startNatural_Earth_quick_start_for_QGIS_v3
![1](https://user-images.githubusercontent.com/114122090/194772783-e133c99b-a385-4346-9062-4fbba6b8c30e.png)

2. Gunakan kontrol geser dan zoom di Bilah Alat Navigasi Peta dan perbesar ke pulau sumatera, Indonesia.
![2](https://user-images.githubusercontent.com/114122090/194772831-f4c239ea-e69a-496d-91f5-87490ec76ea2.png)

3. Kita dapat menonaktifkan beberapa lapisan peta untuk data yang tidak kami perlukan untuk peta ini. Perluas folder dan hapus centang pada kotak di sebelah dan lapisan. Sebelum kita membuat peta yang cocok untuk dicetak, kita perlu memilih proyeksi yang sesuai. CRS default untuk proyek diatur ke . Ini adalah CRS yang populer digunakan untuk pemetaan web dan merupakan pilihan yang layak untuk tujuan kita, sehingga kita dapat membiarkannya pada nilai defaultnya. Pergi ke Proyek Tata Letak Cetak Baru .z5 - 1:18mne_10m_geography_marine_polysne_10m_admin_0_disputed_areasEPSG:3857 Pseudo-Mercator

4. Kita akan diminta untuk memasukkan judul untuk tata letak. Kita dapat membiarkannya kosong, disini saya akan mengisi dengan nama 'kota_padang_2101091013' dan klik Ok .

      ![3](https://user-images.githubusercontent.com/114122090/194772847-6299964a-2b59-4b2a-b58e-cfd392ce0376.png)

5. Di jendela Print Layout, klik tombol Zoom full untuk menampilkan seluruh Layout.
![4](https://user-images.githubusercontent.com/114122090/194772864-90781ba7-6a82-4269-963d-72b7f3f0aaa1.png)

6. Sekarang kita harus membawa tampilan peta yang kita lihat di Kanvas QGIS ke tata letak. Pergi ke Tambah Item Tambah Peta .
![5](https://user-images.githubusercontent.com/114122090/194772868-1ea15a32-937b-423c-9452-5b26cae091e9.png)

7. Setelah mode Tambah Peta aktif, tahan tombol kiri mouse dan seret persegi panjang di mana Anda ingin menyisipkan peta.
![6](https://user-images.githubusercontent.com/114122090/194772874-d07fdc4d-e931-497c-ab47-5bd981e8b583.png)

8. Kita akan melihat bahwa jendela persegi panjang akan ditampilkan dengan peta dari kanvas QGIS utama. Peta yang diberikan mungkin tidak mencakup seluruh area minat kami. Gunakan opsi Edit Pilih/Pindahkan item dan Edit Pindahkan Konten untuk menggeser peta di jendela dan memusatkannya di komposer. Atau bisa disesuaikan juga dengan menggeser pada bagian sudut peta.
![7](https://user-images.githubusercontent.com/114122090/194772880-593c1de9-3d37-4c17-82f7-e93ee6412813.png)

9. Beralih ke jendela QGIS utama. Matikan grup layer dan aktifkan grup. Grup lapisan ini memiliki gaya yang lebih sesuai untuk tampilan yang diperbesar. Gunakan kontrol pan dan zoom di Map Navigation Toolbar dan zoom di sekitar Padang .
![8](https://user-images.githubusercontent.com/114122090/194778080-be564126-0acf-47b1-8924-9acc617d9016.png)

10. Kami sekarang siap untuk menambahkan inset peta. Ganti jendela Print Layout . Pergi ke Tambah Item Tambah Peta .
![9](https://user-images.githubusercontent.com/114122090/194779094-29f86f4a-b9a4-41a3-810e-9e3de1173aa8.png)

11. Seret persegi panjang di tempat Anda ingin menambahkan inset peta. Anda sekarang akan melihat bahwa kami memiliki 2 objek peta di Tata Letak Cetak. Saat membuat perubahan, pastikan Anda memilih peta yang benar.
![10](https://user-images.githubusercontent.com/114122090/194779112-9740060c-d74a-4294-b9e1-5e7ea24d5d19.png)

12. Pilih objek yang baru saja kita tambahkan dari panel Items . Pilih tab Properti item . Gulir ke bawah ke panel Frame dan centang kotak di sebelahnya. Anda dapat mengubah warna dan ketebalan batas bingkai sehingga mudah dibedakan dengan latar belakang peta.Map 2
![11](https://user-images.githubusercontent.com/114122090/194779126-3e0e3593-1960-4485-bdfe-f4bf2795eb1f.png)

13. Salah satu fitur rapi dari Tata Letak Cetak adalah ia dapat secara otomatis menyorot area dari peta utama yang diwakili di sisipan. Pilih objek dari panel Item . Di tab Properti item , gulir ke bawah ke bagian Ikhtisar . Klik tombol Tambahkan ikhtisar baru .Map 1
![12](https://user-images.githubusercontent.com/114122090/194779139-c01f640d-4831-4008-8249-4036f1d97189.png)

14. Pilih sebagai Bingkai Peta . Ini memberitahu Tata Letak Cetak untuk menyorot objek saat ini dengan tingkat peta yang ditampilkan di objek.Map 2Map 1Map 2.
![13](https://user-images.githubusercontent.com/114122090/194779150-4ec556dd-77ab-4b99-8253-b7a0d536756d.png)

15. Sekarang setelah kita menyiapkan inset peta, kita akan menambahkan grid ke peta utama. Pilih objek dari panel Item . Di tab Properti item , gulir ke bawah ke bagian Kisi . Klik tombol Add a new grid , diikuti dengan Modify grid... .Map 1
![14](https://user-images.githubusercontent.com/114122090/194779160-e9220099-f4b4-4d36-9174-1f9daae8ed2c.png)

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

## Modul 2
# `Bekerja dengan Atribut (QGIS3)`
## Prosedure
1. Cari ne_10m_populated_places_simple.zip file di QGIS Browser dan perluas. Pilih ne_10m_populated_places_simple.shpfile dan seret ke kanvas.
![1](https://user-images.githubusercontent.com/114122090/196235613-2cf07634-bd2c-4e69-9360-5a7049cd9d83.png)

2. Lapisan baru ne_10m_populated_places_simple sekarang akan dimuat di QGIS dan Anda akan melihat banyak titik yang mewakili tempat-tempat berpenduduk di dunia. Tampilan default di kanvas QGIS menunjukkan geometri lapisan GIS. Setiap titik juga memiliki atribut terkait. Mari kita lihat mereka. Temukan Bilah Alat Atribut . Toolbar ini berisi banyak alat yang berguna untuk memeriksa, melihat, memilih, dan memodifikasi atribut dari sebuah lapisan.
![2](https://user-images.githubusercontent.com/114122090/196236082-0d8c425b-f22a-45c9-a7b8-1ae57a46b7e0.png)

> Catatan :
> Jika  tidak melihat toolbar, Anda dapat mengaktifkannya dari View Toolbars Attributes Toolbar .

3. Klik tombol Identifikasi pada Bilah Alat Atribut . Setelah alat dipilih, klik titik mana pun di kanvas. Atribut terkait dari titik itu akan ditampilkan di panel Identifikasi Hasil baru. Setelah  selesai menjelajahi atribut dari titik yang berbeda, Anda dapat mengklik tombol Tutup .
![3](https://user-images.githubusercontent.com/114122090/196237857-4058634a-cc71-4281-9ee3-c6a585006453.png)

4. Daripada melihat atribut satu fitur pada satu waktu, kita dapat melihat semuanya bersama-sama sebagai sebuah tabel. Klik tombol Buka Tabel Atribut pada Bilah Alat Atribut . Dan juga dapat mengklik kanan ne_10m_populated_places_simplelayer dan memilih Open Attribute Table .
![4](https://user-images.githubusercontent.com/114122090/196238296-e9c61098-2a21-4f05-983e-4f7e2bf96ec9.png)

5. Kemudian dapat menggulir secara horizontal dan menemukan kolom pop_max . Bidang ini berisi populasi tempat terkait. Dan dapat mengklik dua kali pada tajuk bidang untuk mengurutkan kolom dalam urutan menurun.
![5](https://user-images.githubusercontent.com/114122090/196238912-01213179-d835-4abc-aebf-8be58f7a5db6.png)

6. Sekarang kita siap untuk melakukan query kita pada atribut-atribut ini. QGIS menggunakan ekspresi seperti SQL untuk melakukan query. Klik Pilih fitur menggunakan tombol ekspresi.
![6](https://user-images.githubusercontent.com/114122090/196244271-70c28e37-0b64-4531-b1f2-a760e87e35df.png)

7. Di jendela Select By Expression , perluas bagian Fields and Values dan klik dua kali pop_maxlabelnya. Anda akan melihat bahwa itu ditambahkan ke bagian ekspresi di bagian bawah. Jika Anda tidak yakin tentang nilai bidang, Anda dapat mengklik tombol Semua Unik untuk melihat nilai atribut apa yang ada dalam kumpulan data. Untuk latihan ini, kami mencari semua fitur yang memiliki populasi lebih dari 1 juta. Jadi lengkapi ekspresi seperti di bawah ini dan klik Select Features lalu Close .
```
      "pop_max" > 1000000
``` 
![7](https://user-images.githubusercontent.com/114122090/196244307-0df0c33f-dfab-4861-b0d4-58f9304ea0dc.png)

> Catatan
> Dalam mesin Ekspresi QGIS, teks dengan tanda kutip ganda mengacu pada bidang dan teks dengan tanda kutip tunggal mengacu pada nilai string.

8. Kemudian akan melihat bahwa beberapa baris dalam tabel atribut sekarang dipilih. Jendela label juga berubah dan menunjukkan jumlah fitur yang dipilih.
![8](https://user-images.githubusercontent.com/114122090/196244328-3f005b8f-c6e0-4e92-bc42-a1ec75a038d0.png)

9. Tutup jendela tabel atribut dan kembali ke jendela utama QGIS. Anda akan melihat bahwa subset poin sekarang dirender dengan warna kuning. Ini adalah hasil dari kueri kami dan titik yang dipilih adalah titik yang memiliki pop_maxnilai atribut lebih besar dari 1000000.
![9](https://user-images.githubusercontent.com/114122090/196244364-f70f36f5-1131-4e35-a4cb-8b811ed53845.png)

10. Mari kita perbarui kueri kita dengan menyertakan syarat bahwa tempat itu juga harus menjadi ibu kota selain memiliki populasi lebih dari 1 juta. Untuk membuka editor ekspresi dengan cepat, Anda dapat menggunakan tombol Select Features by Expression di Attributes Toolbar .
![10](https://user-images.githubusercontent.com/114122090/196244422-dae840c4-86e7-472a-b486-1d88a526da65.png)

11. Bidang yang berisi data tentang huruf kapital adalah adm0cap . Nilai tersebut 1menunjukkan bahwa tempat tersebut adalah ibukota. Kita dapat menambahkan kriteria ini ke ekspresi kita sebelumnya menggunakan operator and . Masukkan ekspresi seperti di bawah ini dan klik Select Features lalu Close .
```
  "pop_max" > 1000000 and "adm0cap" = 1
```
![11](https://user-images.githubusercontent.com/114122090/196244447-69fb2c9e-1ab9-43cb-8f22-45daa8da2b73.png)

12. Kembali ke jendela utama QGIS. Sekarang Anda akan melihat subset yang lebih kecil dari poin yang dipilih. Ini adalah hasil dari kueri kedua dan menunjukkan semua tempat dari kumpulan data yang merupakan ibu kota negara serta memiliki populasi lebih dari 1 juta.
![12](https://user-images.githubusercontent.com/114122090/196244464-fcaf6477-7768-41db-9df0-9cc7acbabb58.png)

13. Sekarang kita akan mengekspor fitur yang dipilih sebagai layer baru. Klik kanan ne_10m_populated_places_simplelayer dan pergi ke Export Save Selected Features As...
![13](https://user-images.githubusercontent.com/114122090/196244479-9a4ba926-259e-4928-8e4b-77a883210f40.png)

14. Selanjutnya dapat memilih format apa pun yang Anda sukai sebagai Format . Untuk latihan ini, kita akan memilih GeoJSON. GeoJSON adalah format berbasis teks yang digunakan secara luas dalam pemetaan web. Klik tombol ... di sebelah Nama file dan masukkan populated_capitals.geojsonsebagai file output.
![14](https://user-images.githubusercontent.com/114122090/196244505-6ab5ef9e-21ab-46fe-8093-3fab7aa902ac.png)

15. Data input memiliki banyak kolom. Anda hanya dapat memilih sebagian dari kolom asli untuk diekspor. Perluas bagian Pilih bidang yang akan diekspor dan opsi ekspornya . Klik Deselect All dan centang kolom nameand pop_max. Klik Oke .

16. Sebuah layer baru populated_capitalsakan dimuat di QGIS. Anda dapat menghapus centang pada ne_10m_populated_places_simplelayer untuk menyembunyikannya dan melihat poin dari layer yang baru diekspor.

## Modul 3
#  

## Modul 4
#

## Modul 5
#
