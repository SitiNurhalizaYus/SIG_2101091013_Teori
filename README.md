# SIG-TEORI-2101091013
Tutorial Latihan :
## #Basic GIS operations
- [Modul 1](README.md#modul-1) Membuat Peta (QGIS3)
- [Modul 2](README.md#modul-2) Bekerja dengan Atribut (QGIS3)
- [Modul 3](README.md#modul-3) Mengimpor file Spreadsheet atau CSV (QGIS3)
- [Modul 4](README.md#modul-4) Vektor Dasar (QGIS3)
- [Modul 5](README.md#modul-5) Menghitung Panjang Garis dan Statistik (QGIS3)
- [Modul 6](README.md#modul-6) Styling dan Analisis Raster Dasar (QGIS3)
- [Modul 7](README.md#modul-7) Mosaik dan Kliping Raster (QGIS3)
- [Modul 8](README.md#modul-8) Bekerja dengan Data Medan (QGIS3)
- [Modul 9](README.md#modul-9) Bekerja dengan Data WMS (QGIS3) 
- [Modul 10](README.md#modul-10) Bekerja dengan Proyeksi (QGIS3)
- [Modul 11](README.md#modul-11) Lembar Topo Georeferensi dan Peta yang Dipindai (QGIS3)
- [Modul 12](README.md#modul-12) Citra Udara BasisGeo
- [Modul 13](README.md#modul-13) Digitalisasi Data Peta (QGIS3)
- [Modul 14](README.md#modul-14) Mencari dan Mengunduh Data OpenStreetMap (QGIS3)

## #Intermediate GIS operations
- [Modul 1](README.md#modul-1-1) Performing Table Joins (QGIS3)
- [Modul 2](README.md#modul-2-1) Performing Spatial Joins (QGIS3)
- [Modul 3](README.md#modul-3-1) Performing Spatial Queries (QGIS3)
- [Modul 4](README.md#modul-4-1) Nearest Neighbor Analysis (QGIS3)
- [Modul 5](README.md#modul-5-1) Sampling Raster Data using Points or Polygons (QGIS3)
- [Modul 6](README.md#modul-6-1) Calculating Raster Area (QGIS3)
- [Modul 7](README.md#modul-7-1) Creating Heatmaps (QGIS3)
- [Modul 8](README.md#modul-8-1) Animating Time Series Data (QGIS3)
- [Modul 9](README.md#modul-9-1) Handling Invalid Geometries (QGIS3)


## Modul 1
# `Membuat Peta (QGIS3)`
file : [modul1.qpt](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/05819c8059b8f05da157974393e37be8fa84bc17/kota_padang_2101091013.qpt)

## Prosedure
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

28. Setelah Kita puas dengan peta, Anda dapat mengekspornya sebagai Gambar, PDF, atau SVG. Untuk tutorial ini, mari kita ekspor sebagai gambar. Klik Tata Letak Ekspor sebagai Gambar .

29. Simpan gambar dalam format yang Kita sukai. Di bawah ini adalah gambar PNG yang diekspor.
![kota_padang_2101091013](https://user-images.githubusercontent.com/114122090/193393792-461887f7-2536-4c9a-8c5e-03f07829806c.png)

## Modul 2
# `Bekerja dengan Atribut (QGIS3)`
file : [modul2.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/af1283f530067d27baf4cd0e9015e668a32626df/siti%20nurhaliza%20yus_2101091013%20(Attributes%20).qgz)

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

> Catatan :
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

12. Kembali ke jendela utama QGIS. Sekarang kita akan melihat subset yang lebih kecil dari poin yang dipilih. Ini adalah hasil dari kueri kedua dan menunjukkan semua tempat dari kumpulan data yang merupakan ibu kota negara serta memiliki populasi lebih dari 1 juta.
![12](https://user-images.githubusercontent.com/114122090/196244464-fcaf6477-7768-41db-9df0-9cc7acbabb58.png)

13. Sekarang kita akan mengekspor fitur yang dipilih sebagai layer baru. Klik kanan ne_10m_populated_places_simplelayer dan pergi ke Export Save Selected Features As...
![13](https://user-images.githubusercontent.com/114122090/196244479-9a4ba926-259e-4928-8e4b-77a883210f40.png)

14. Selanjutnya dapat memilih format apa pun yang Anda sukai sebagai Format . Untuk latihan ini, kita akan memilih GeoJSON. GeoJSON adalah format berbasis teks yang digunakan secara luas dalam pemetaan web. Klik tombol ... di sebelah Nama file dan masukkan populated_capitals.geojsonsebagai file output.

    ![14](https://user-images.githubusercontent.com/114122090/196244505-6ab5ef9e-21ab-46fe-8093-3fab7aa902ac.png)

15. Data input memiliki banyak kolom.Disini hanya dapat memilih sebagian dari kolom asli untuk diekspor. Perluas bagian Pilih bidang yang akan diekspor dan opsi ekspornya . Klik Deselect All dan centang kolom nameand pop_max. Klik Oke.
![14](https://user-images.githubusercontent.com/114122090/196988098-5645208b-9124-4b1c-a3a0-e105cf333ac8.png)

16. Kemudian klik overwrite file untuk meberikan layer baru nantinya.

     ![15](https://user-images.githubusercontent.com/114122090/196988651-9e06eabd-b5ac-4284-84f1-cbd43f22a4b5.png)

17. Sebuah layer baru populated_capitalsakan dimuat di QGIS. 
![16](https://user-images.githubusercontent.com/114122090/196988932-5cd1dd70-b91f-406b-8196-3b47ffd94cb6.png)

18. Kita dapat menghapus centang pada ne_10m_populated_places_simplelayer untuk menyembunyikannya dan melihat poin dari layer yang baru diekspor.
![17](https://user-images.githubusercontent.com/114122090/196988331-da232258-ec2c-43fa-9737-798685d32b11.png)


## Modul 3
# `Mengimpor file Spreadsheet atau CSV (QGIS3)`
file : [modul3.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/af1283f530067d27baf4cd0e9015e668a32626df/1900_2000_earthquakes_2101091013.qgz)

Untuk tutorial ini kita akan mendownload dataset gempa bumi antara tahun 1900-2000 dari National Geophysical Data Center NOAA menghasilkan dataset besar dari semua gempa bumi signifikan sejak 2150 SM. Kunjungi portal NOAA NCEI dan masukkan Min as 1900dan Max as 2000. Ini akan mengembalikan semua insiden gempa yang terjadi dan dicatat oleh NOAA antara tahun-tahun itu. Untuk hasil spesifik lainnya, Anda dapat memfilter dengan parameter berbeda. Klik Cari .
![01](https://user-images.githubusercontent.com/114122090/196248107-d2b9009f-fa3f-4b85-92ca-c4a353d8354c.png)

Hasilnya, kami mendapat 2585 insiden gempa. Klik pada ikon Unduh TSV .
![02](https://user-images.githubusercontent.com/114122090/196248277-3b5fd44f-b347-4997-a94e-45edb5511b5d.png)

## Procedure
1. Periksa sumber data tabular Anda. Basis data gempa yang diunduh berisi Latitudedan Longitudebidang yang menunjukkan lokasi episentrum gempa dan atribut terkait lainnya. Kami akan menggunakan bidang ini untuk mengimpor file sebagai lapisan titik. Buka data dalam editor teks seperti Notepad/TextMate untuk melihat isinya. Kita akan melihat bahwa TAB memisahkan setiap bidang.
![03](https://user-images.githubusercontent.com/114122090/196248805-ffbee728-6eb7-49e9-a399-8a856ead8392.png)

> Catatan :
> Jika Anda memiliki spreadsheet, gunakan fungsi Save As di program Anda untuk menyimpannya sebagai File Tab Delimited atau file Comma Separated Values (CSV) .

2. QGIS hadir dengan pengelola data terpadu yang memungkinkan Anda memuat semua berbagai format data yang didukung. Klik tombol Buka Pengelola Sumber Data pada Bilah Alat Sumber Data . Kita juga dapat menggunakan pintasan keyboard.Ctrl + L
![1](https://user-images.githubusercontent.com/114122090/196249024-a0898b23-2b6a-4d8f-a4aa-f3a2c7e71d3c.png)

3.Dalam kotak dialog Pengelola Sumber Data , alihkan ke tab Teks Dibatasi . Klik tombol ... di sebelah nama File .
![2](https://user-images.githubusercontent.com/114122090/196249073-ca89c1dd-e73a-4d44-aea8-2707334bf97b.png)

4. Tergantung pada sistem operasinya, Anda mungkin atau mungkin tidak melihat file di lokasi yang diunduh. Dalam format File, alihkan ke untuk melihat file tsv .All files (*; *.*)
![3](https://user-images.githubusercontent.com/114122090/196249208-a963e1ce-3643-4d47-907f-20e9342fd4f0.png)

5. Sekarang Anda akan melihat file yang diunduh. Pilih itu dan klik Buka .
![4](https://user-images.githubusercontent.com/114122090/196249284-f020716e-5a9e-45b1-a579-3cd22ca76ed6.png)

6. Di kotak dialog Pengelola Sumber Data , jalur ke file akan tersedia di Nama File . Ubah nama Lapisan menjadi 1900_2000_earthquakes. Di bagian Format file , pilih Pembatas khusus dan centang Tab. Di bagian Definisi geometri , pilih Koordinat titik . Secara default , nilai bidang X dan bidang Y akan terisi secara otomatis jika menemukan bidang nama yang sesuai di input. Dalam kasus kami, mereka adalah Longitudedan Latitude. Anda dapat mengubahnya jika impor memilih bidang yang salah. Anda dapat membiarkan Geometry CRS ke defaultEPSG:4326 - WGS 84CRS. Jika file Anda berisi koordinat dalam CRS yang berbeda, Anda dapat memilih CRS yang sesuai di sini. Klik Tambahkan .
![5](https://user-images.githubusercontent.com/114122090/196249392-66c20839-3cb0-4a9a-b8e5-87bc96e8dfff.png)

> Catatan :
> Sangat mudah untuk bingung antara koordinat X dan Y. Lintang menentukan posisi utara-selatan suatu titik dan karenanya merupakan koordinat Y. Demikian pula Bujur 
> menentukan posisi timur-barat suatu titik dan itu adalah koordinat X.

7. Kita sekarang akan melihat bahwa data akan diimpor dan ditampilkan di kanvas QGIS sebagai layer baru yang disebut 1900_2000_earthquakesdengan CRS EPSG:4326.
![6](https://user-images.githubusercontent.com/114122090/196249524-c03f20b9-b358-443f-bda6-64c524489bf8.png)

## Modul 4
# `Vektor Dasar (QGIS3)`
file : [modul4.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/3801a0cb4f18889488feec9b11a05cb52da89181/Vektor%20Dasar%20(QGIS3)_2101091013_Siti%20Nurhaliza%20Yus.qgz)

## Procedure
1. Buka zip kedua kumpulan data ke folder di komputer . Di Panel Browser QGIS, temukan direktori tempat  mengekstrak data. Perluas ne_10m_landfolder dan pilih ne_10m_land.shplayer. Seret layer ke kanvas.
![1](https://user-images.githubusercontent.com/114122090/197017499-74746247-7898-4fb1-ab72-2245ad510bd9.png)

2. Selanjutnya akan mendapatkan layer baru yang ne_10m_land ditambahkan ke panel Layers . Basis data pembangkit listrik global hadir sebagai file CSV, jadi kita perlu mengimpornya. Klik tombol Buka Pengelola Sumber Data pada Bilah Alat Sumber Data .  juga dapat menggunakan pintasan keyboard. Ctrl + L
![2](https://user-images.githubusercontent.com/114122090/197017515-9fc1f427-d772-4d72-8f47-2536ec25dea0.png)

3. Di jendela Pengelola Sumber Data , alihkan ke tab Teks Dibatasi . Klik tombol ... di sebelah Nama file dan telusuri direktori tempat  mengekstrak globalpowerplantdatabasev120.zipfile. Pilih global_power_plant_database.csv. QGIS akan otomatis mendeteksi bidang pembatas dan geometri. Biarkan Geometri CRS ke nilai default . Klik Tambah diikuti oleh Tutup .EPSG:4326 - WGS84
![3](https://user-images.githubusercontent.com/114122090/197017530-2bac06e4-6e21-4d16-923e-ac407900a8c0.png)

4. Sebuah layer baru global_power_plant_databaseakan ditambahkan ke panel Layers dan  akan melihat titik-titik yang mewakili pembangkit listrik di kanvas. Sekarang kita siap untuk menata kedua lapisan ini. Klik tombol Open the Layer Styling panel di bagian atas panel Layers .
![4](https://user-images.githubusercontent.com/114122090/197017595-1941c4c7-df81-4e2d-9116-a0b639744203.png)

5. Panel Layer Styling akan terbuka di sebelah kanan. Pilih ne_10m_land lapisannya terlebih dahulu. Ini akan menjadi lapisan dasar kami sehingga kami dapat menjaga gaya minimalis agar tidak mengganggu. Klik dan gulir ke bawah. Pilih warna Fill sesuai keinginan . Klik drop-down di sebelah Stroke color dan pilih . Ini akan mengatur garis besar poligon tanah menjadi transparan.  akan melihat hasil seleksi  diterapkan segera ke lapisan.Simple fillTransparent Stroke
![5](https://user-images.githubusercontent.com/114122090/197017638-c34c771c-b4fc-4b78-91d0-a97e3f67f9a6.png)

6. Selanjutnya pilih global_power_plant_database lapisan. Klik dan gulir ke bawah. Pilih pen segitiga.Simple marker
![6](https://user-images.githubusercontent.com/114122090/197017673-e685795f-63f2-43e8-b9b7-e9f6edf6fa16.png)

7. Gulir ke atas dan pilih warna Isi sesuai keinginan . Teknik kartografi yang berguna adalah memilih versi warna isian yang sedikit lebih gelap sebagai warna Stroke . Daripada mencoba memilihnya secara manual, QGIS menyediakan ekspresi untuk mengontrol ini dengan lebih tepat. Klik tombol Penimpaan yang ditentukan data dan pilih Edit .
![7](https://user-images.githubusercontent.com/114122090/197017705-319f8079-435f-4638-a7ec-711ef9a9cdfa.png)

8. Masukkan ekspresi berikut untuk mengatur warnanya menjadi 30% lebih gelap dari warna isian dan klik OK .
```
      darker(@symbol_color, 130)
```
   ![8](https://user-images.githubusercontent.com/114122090/197017812-ed24e0a2-4147-4bed-b1f7-10b8ae6c56a4.png)

>Catatan
>Perhatikan bahwa ekspresi ini tidak tergantung pada warna isian yang  pilih.  akan melihat bahwa ini sangat berguna dalam langkah-langkah berikut di mana secara >otomatis mengatur warna batas berdasarkan warna isian yang disediakan.


9. Kita akan melihat bahwa tombol Override yang ditentukan Data di sebelah Warna Stroke telah berubah menjadi kuning - menunjukkan bahwa properti ini dikendalikan oleh override. Render simbol tunggal dari lapisan pembangkit listrik tidak terlalu berguna. Itu tidak menyampaikan banyak informasi kecuali lokasi pembangkit listrik. Mari kita gunakan penyaji yang berbeda untuk membuatnya lebih berguna. Klik drop-down Symbology dan pilih Categorizedrenderer.
![9](https://user-images.githubusercontent.com/114122090/197017861-e0bc6689-8472-4318-a3c1-e3353cb87be2.png)

10. Lapisan tersebut global_power_plant_database berisi atribut yang menunjukkan bahan bakar utama yang digunakan di setiap pembangkit listrik. Kita dapat membuat gaya di mana setiap jenis bahan bakar yang unik ditampilkan dalam warna yang berbeda. Pilih primary_fuelsebagai Kolom . Klik Klasifikasi . Kita akan melihat beberapa kategori dan rendering peta berubah sesuai.
![10](https://user-images.githubusercontent.com/114122090/197017888-84a5cca2-a94d-4d19-be58-5bf0c28b7f4a.png)

11. Meskipun tampilan Terkategori berguna, lapisan ini berisi terlalu banyak kategori untuk dapat ditafsirkan peta secara bermakna. Pendekatan yang lebih baik adalah mengelompokkan jenis kategori bahan bakar tertentu dan mengurangi jumlah kelas. Mari kita coba buat 3 kategori - Bahan bakar terbarukan , Bahan bakar tidak terbarukan , dan Lainnya . Pilih Rule-basedpenyaji. Pilih semua kecuali satu aturan dengan menahan Ctrltombol dan mengklik setiap baris. Setelah dipilih, klik tombol Hapus aturan yang dipilih untuk menghapusnya.
![11](https://user-images.githubusercontent.com/114122090/197017980-54555322-20e9-41cd-a605-8aa2ab60b857.png)

12. Pilih aturan yang tersisa dan klik Edit aturan saat ini .
![12](https://user-images.githubusercontent.com/114122090/197018015-a5b14dec-ea2b-4ff6-bc84-790a07c8df21.png)

13. Masukkan sebagai Label . Klik tombol Ekspresi di sebelah Filter .Renewable fuel
![14](https://user-images.githubusercontent.com/114122090/197018149-0e0e50f1-df7d-4570-9d4b-a017133678ec.png)

14. Dalam dialog Pembuat String Ekspresi , masukkan ekspresi berikut dan klik OK . Di sini kami mengelompokkan beberapa kategori energi terbarukan ke dalam satu kategori.
```
      "primary_fuel" IN ('Biomass', 'Geothermal', 'Hydro', 'Solar', 'Wind', 'Storage', 'Wave and Tidal')
```
   ![15](https://user-images.githubusercontent.com/114122090/197018104-23846d30-c56e-4694-941e-714d7223caae.png) 
     
15. Gulir ke bawah dan klik Pen sederhana . Pilih warna Isi yang sesuai . Setelah selesai, klik tombol Kembali .
![16](https://user-images.githubusercontent.com/114122090/197018355-87f0ca6b-2da0-490b-9fe5-393b4fcfb296.png)

16. Kita akan melihat satu aturan diterapkan pada lapisan untuk kategori bahan bakar terbarukan . Klik kanan baris dan pilih Salin . Klik kanan lagi dan pilih Tempel .
![17](https://user-images.githubusercontent.com/114122090/197018382-d9d2c228-b778-42c6-950d-1b62b3e51da7.png)

17. Salinan aturan yang ada akan ditambahkan. Pilih baris yang baru ditambahkan dan klik Edit aturan saat ini .
![18](https://user-images.githubusercontent.com/114122090/197018422-fb5d15b3-c3cb-473f-a05b-e7180b9c5dfe.png)

18. Masukkan sebagai Label . Klik tombol Ekspresi di sebelah Filter .Non-renewable fuel
![19](https://user-images.githubusercontent.com/114122090/197018442-249463d7-4a07-4a62-b205-93013dd93917.png)

19. Dalam dialog Pembuat String Ekspresi , masukkan ekspresi berikut dan klik OK .
```
      "primary_fuel" IN ('Coal', 'Gas', 'Nuclear', 'Oil', 'Petcoke')
```
   ![20](https://user-images.githubusercontent.com/114122090/197018574-230a52bc-d6f7-4d9f-865d-cea0b3933e67.png)

20. Gulir ke bawah dan klik Pen sederhana . Pilih warna Isi yang sesuai . Setelah selesai, klik tombol Kembali .
![21](https://user-images.githubusercontent.com/114122090/197018527-daa44eb9-ba71-4b34-b640-2fe6b1e93162.png)

21. Ulangi proses Copy/Paste untuk menambahkan aturan ketiga. Pilih dan klik Edit aturan saat ini .
![22](https://user-images.githubusercontent.com/114122090/197018603-bd6f584d-a48e-4f1c-92d4-463a6b2037ce.png)

22. Masukkan Othersebagai Label . Pilih Else - Catch all untuk fitur lain daripada Filter . Ini akan memastikan bahwa setiap kategori yang terlewatkan dalam 2 aturan sebelumnya, akan ditata oleh aturan ini. Gulir ke bawah dan klik Pen sederhana . Pilih warna Isi yang sesuai . Setelah selesai, klik tombol Kembali .
![23](https://user-images.githubusercontent.com/114122090/197018625-5e7fbfa4-9332-4a1a-a295-2ade91f4caa4.png)

23. Pengkategorian ulang selesai sekarang.  akan melihat tampilan yang jauh lebih bersih yang menunjukkan distribusi sumber bahan bakar terbarukan vs. tidak terbarukan yang digunakan oleh pembangkit listrik dan distribusinya di seluruh negara. Namun ini tidak memberikan gambaran yang lengkap. Kita bisa menambahkan variabel lain ke styling. Daripada menampilkan semua pen dengan ukuran seragam, kami dapat menunjukkan ukuran yang proporsional dengan kapasitas pembangkit listrik masing-masing pembangkit. Teknik kartografi ini disebut pemetaan Multivariat . Klik kanan aturan dan pilih Ubah Ukuran .Renewable fuel
![24](https://user-images.githubusercontent.com/114122090/197018631-4d6b438c-18f7-4952-b640-b35320a276cb.png)

24. Klik tombol Penggantian yang ditentukan data di sebelah Ukuran . Pilih Sunting .
![25](https://user-images.githubusercontent.com/114122090/197018654-3527f5c4-1e24-4dd1-865f-88b4eaa79917.png)

25. Karena kapasitas pembangkit listrik sangat bervariasi di antara kumpulan data kami, cara yang efektif untuk mendapatkan rentang ukuran yang kecil adalah dengan menggunakan log10fungsi.  dapat bereksperimen dengan ekspresi yang berbeda untuk sampai pada apa yang terbaik untuk visualisasi pilihan . Masukkan ekspresi berikut dan klik OK .
```
      log10("capacity_mw") + 1
```
   ![26](https://user-images.githubusercontent.com/114122090/197018705-ac999882-b594-4cb8-b4db-8c1c87832212.png)
    
26. Ulangi proses yang sama untuk aturan lainnya.
![27](https://user-images.githubusercontent.com/114122090/197018718-321ed12f-383f-408e-9f04-a23e315ead17.png)

27. Setelah puas,  dapat menutup panel Layer Styling .
![28](https://user-images.githubusercontent.com/114122090/197018742-fe6ec311-fa52-46dc-afbc-13c713f47460.png)

28. Melihat visualisasi akhir kami,  dapat langsung melihat pola di dataset. Sebagai contoh, di Eropa terdapat lebih banyak pembangkit listrik yang menggunakan sumber energi terbarukan, tetapi kapasitasnya lebih rendah daripada pembangkit yang menggunakan sumber energi tidak terbarukan.
![29](https://user-images.githubusercontent.com/114122090/197018766-4a9a6675-d40f-40e0-b8e5-774884b7ce51.png)
![30](https://user-images.githubusercontent.com/114122090/197018797-2d3e09d5-b5bb-43fa-a083-f248ab67bfb2.png)


## Modul 5
# `Menghitung Panjang Garis dan Statistik (QGIS3)`
file : [modul5.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/5b8d7345ab4eca9dc7ead2cc9c7f619bdaed1c73/Menghitung%20Panjang%20Garis%20dan%20Statistik%20(QGIS3)_siti%20nurhaliza%20yus_2101091013.qgz)

## Prosedure 
1. Temukan ne_10m_railroads_north_america.zipfile yang diunduh di panel Browser dan perluas. Seret ne_10m_railroads_north_america.shpfile ke kanvas.
![1](https://user-images.githubusercontent.com/114122090/201804982-083c3cf5-6619-400d-9aa3-3ed5aebac9d2.png)

2. Selanjutnya akan melihat layer baru ne_10m_railroads_north_americadimuat di panel Layers . Kita akan melihat bahwa layer tersebut memiliki garis yang mewakili rel kereta api untuk seluruh Amerika Utara. Sekarang, mari hitung panjang setiap fitur garis. Pergi ke Memproses ‣ Kotak Alat .
![3](https://user-images.githubusercontent.com/114122090/201804999-0f824be2-b631-46b1-be8b-e87212897daa.png)

3. Cari dan temukan geometri Vektor ‣ Tambahkan algoritme atribut geometri. Klik dua kali untuk meluncurkannya.
![4](https://user-images.githubusercontent.com/114122090/201805005-d775a27e-d358-4a96-a350-7d81536aa3d9.png)

4. Dalam dialog Add Geometry Attributesne_10m_railroads_north_america , pilih sebagai Input layer . Coordinate Reference System (CRS) layer input adalah EPSG:4326 WGS84 . Ini adalah CRS Geografis dengan Lintang dan Bujur sebagai koordinat, WGS84 sebagai ellipsoid dan derajat sebagai satuan. Karena lintang dan bujur tidak memiliki panjang standar, Anda tidak dapat mengukur jarak atau luas secara akurat menggunakan fungsi geometri planar. Untungnya, QGIS menyediakan cara yang lebih baik untuk menghitung jarak menggunakan geometri ellipsoidal, yang merupakan metode paling akurat untuk lapisan yang menjangkau area yang luas seperti ini. Pilih Ellipsoidalsebagai opsi Hitung menggunakan . Klik Jalankan . Setelah proses selesai, klik Tutup.
![5](https://user-images.githubusercontent.com/114122090/201805009-3dd6ab65-59f1-4f2e-ad54-6ab9d1e4aeff.png)
      >Catatan : 
      >Jika layer input Anda berada dalam Projected CRS , Anda dapat memilih opsi untuk perhitungan. Sistem koordinat lokal atau regional yang diproyeksikan dirancang       >untuk meminimalkan distorsi pada wilayah yang diminati, sehingga lebih akurat untuk perhitungan tersebut.Layer CRS

5. Kita akan melihat layer baru dimuat di panel Layers . Ini adalah salinan dari lapisan input dengan kolom baru yang ditambahkan untuk jarak. Klik kanan layer dan pilih Open Attribute Table .Added geom infoAdded geom info
![6](https://user-images.githubusercontent.com/114122090/201805015-f0d16929-3c91-4a4b-adad-ccf62372c86e.png)
      >Catatan : 
      >Alat Add Geometry Attribute menambahkan rangkaian atribut yang berbeda bergantung pada apakah lapisan masukan berupa titik, garis, atau poligon. Lihat                 >dokumentasi QGIS untuk detail lebih lanjut.

6. Di Tabel Atribut , Kita akan melihat kolom baru bernama distance . Ini berisi panjang setiap garis fitur dalam meter . Perhatikan juga atribut sov_a3 yang berisi kode negara untuk setiap fitur. Tutup jendela Tabel Atribut .
![7](https://user-images.githubusercontent.com/114122090/201805019-5706fd19-8ad1-4200-bf08-2b25fe0edf18.png)

7. Sekarang setelah kita memiliki panjang segmen jalur kereta api individual, kita dapat menjumlahkannya untuk menemukan panjang total rel kereta api. Tetapi karena pernyataan masalah menuntut kita membutuhkan total panjang rel kereta api di Amerika Serikat, kita harus menggunakan hanya segmen-segmen yang ada di AS. Kita dapat menggunakan nilai kode negara di kolom sov_a3 untuk memfilter layer. Klik kanan layer dan pilih Filter .Added geom info
![8](https://user-images.githubusercontent.com/114122090/201805022-8d6ed654-ef0d-44fb-880d-6cb9ae4493e7.png)

8. Dalam dialog Pembuat Kueri , masukkan ekspresi berikut dan klik OK .
```
"sov_a3" = 'USA'
```
![9](https://user-images.githubusercontent.com/114122090/201805032-b4211763-6cc5-4748-bcbf-c7887ec103f3.png)

9. Kita akan melihat ikon Filter muncul di sebelah layer di panel Layers yang menunjukkan bahwa filter diterapkan ke layer. Kita juga dapat mengonfirmasi secara visual bahwa lapisan tersebut sekarang berisi segmen garis hanya untuk Amerika Serikat. Sekarang kita siap menghitung jumlahnya. Klik tombol Tampilkan ringkasan statistik pada Bilah Alat Atribut .Added geom info
![10](https://user-images.githubusercontent.com/114122090/201805035-e8fc7e75-cf92-4d40-b8ad-e2ce1a449df7.png)

10. Panel Statistik baru akan terbuka. Pilih lapisan dan kolom.Added geom infolength
![11](https://user-images.githubusercontent.com/114122090/201805038-a044f3c5-2703-4485-9b5b-7718b24e3210.png)

11. Kita akan melihat berbagai statistik ditampilkan di panel. Satuan statistik sama dengan satuan lengthkolom- meter . Mari kita ubah perhitungan untuk menggunakan kilometer sebagai gantinya. Klik ikon Ekspresi di sebelah menu tarik-turun bidang di panel Statistik .
![12](https://user-images.githubusercontent.com/114122090/201805045-3b53a50b-8ae6-4df1-9c81-51c06f369cc5.png)

12. Masukkan ekspresi berikut dalam Dialog Ekspresi yang mengubah panjang menjadi kilometer.
```
length / 1000
```
![13](https://user-images.githubusercontent.com/114122090/201805053-67911cb1-b01f-4924-bdd9-d6e4798a9135.png)
![14](https://user-images.githubusercontent.com/114122090/201805059-4698ed87-9f1b-42fe-bcb1-e87a09c64c38.png)

13. Nilai Sum yang ditampilkan adalah total panjang rel di Amerika Serikat.
![15](https://user-images.githubusercontent.com/114122090/201805063-903d4146-d82e-438f-af48-78fb86bab623.png)

## Modul 6
# `Styling dan Analisis Raster Dasar (QGIS3)`
file : [modul6.qpt]()

## Procedure
1.	Buka QGIS dan temukan file yang diunduh di panel Browser . Perluas gpw-v4-population-count-rev11_2000_2pt5_min_tif.zipfile dan seret gpw-v4-population-count-rev11_2000_2pt5_min.tiffile ke kanvas.

2.	Layer baru gpw-v4-population-count-rev11_2000_2pt5_minakan ditambahkan ke panel Layers . Demikian pula, cari gpw-v4-population-count-rev11_2010_2pt5_min_tif.zipfile dan seret gpw-v4-population-count-rev11_2010_2pt5_min.tiffile ke kanvas.

3.	Mari jelajahi lapisan ini. Klik tombol Identifikasi pada Bilah Alat Atribut . Setelah alat dipilih, klik titik mana pun di kanvas.

4.	Nilai yang terkait dengan piksel tersebut akan ditampilkan di panel Identifikasi Hasil yang baru. Di panel Identifikasi Hasil , ubah Mode menjadi . Ini akan menampilkan nilai piksel dari semua raster, bukan hanya lapisan paling atas. Bandingkan nilai dari kedua layer. Karena resolusi raster kira-kira 5km x 5km, nilai piksel mewakili total populasi di area (25 km persegi) yang diwakili oleh piksel.Top down

5.	Tutup panel Identifikasi Hasil . Mari buat visualisasi layer yang lebih baik. Klik tombol Open the layer Styling panel di panel Layers .

6.	Di panel Layer Styling , klik dropdown Render type dan pilih renderer.Singleband pseudocolor

7.	Renderer ini akan memberi style pada layer menggunakan color ramp. Ramp warna default adalah putih-merah di mana nilai minimum akan diberi warna putih dan nilai maksimum di lapisan akan diberi warna merah. Nilai tengah akan diberi warna interpolasi linier merah. Perluas Pengaturan Nilai Min / Maks dan pilih opsi. Kita akan melihat bahwa visualisasi peta sekarang jauh lebih baik. Rentang data stKitar ditetapkan dari 2% hingga 98% dari nilai data, artinya outlier tidak akan digunakan untuk menetapkan nilai minimum dan maksimum, sehingga menghasilkan visualisasi yang jauh lebih representatif.Cumulative count cut

8.	Tutup panel Layer Styling . Kita bisa menerapkan gaya serupa ke lapisan lain juga. Namun ada cara yang lebih mudah untuk mentransfer gaya dari satu lapisan ke lapisan lainnya. Klik kanan gpw-v4-population-count-rev11_2010_2pt5_minlayer dan pilih Styles ‣ Copy Style .

9.	Sekarang klik kanan gpw-v4-population-count-rev11_2000_2pt5_minlayer tanpa gaya dan pilih Styles ‣ Paste Style .

10.	Parameter gaya yang sama akan diterapkan ke lapisan lainnya. Fitur ini sangat berguna ketika Kita ingin membandingkan lapisan yang berbeda menggunakan kategorisasi yang sama. Saat Kita mengaktifkan visibilitas lapisan atas, Kita dapat melihat perubahan populasi secara visual.

11.	Tugas kita adalah membuat peta tematik dari perubahan populasi. Mari hitung selisih antara 2 layer dan buat raster lain di mana setiap piksel mewakili perubahan dalam populasi. Pergi ke Raster ‣ Kalkulator raster .

12.	Di bagian Raster bands , Kita dapat memilih layer dengan mengklik dua kali pada layer tersebut. Band diberi nama setelah nama raster diikuti dengan @dan nomor band. Karena setiap raster kami hanya memiliki 1 band, Kita akan diberi nama dengan @1ditambahkan ke nama layer. Kalkulator raster dapat menerapkan operasi matematika pada piksel raster. Dalam hal ini kita ingin memasukkan rumus sederhana untuk mengurangkan populasi tahun 2010 dari tahun 2000. Masukkan ekspresi berikut. Selanjutnya, klik tombol ... di sebelah Output layer .
```
"gpw-v4-population-count-rev11_2010_2pt5_min@1" - "gpw-v4-population-count-rev11_2000_2pt5_min@1"
```

13.	Masukkan population_change_2010_2000.tifsebagai file Keluaran . Klik OK untuk memulai perhitungan.

14.	Setelah selesai, layer baru population_change_2010_2000akan ditambahkan ke panel Layers . Mari ubah gaya sehingga perubahan populasi negatif dan positif divisualisasikan dengan lebih baik. Klik tombol Open the layer Styling panel di panel Layers .

15.	Salah satu opsinya adalah menggunakan teknik penataan yang serupa seperti sebelumnya dan memilih jalan warna yang berbeda. Klik drop-down Color ramp dan pilih Spectralramp. Klik drop-down lagi dan pilih untuk menetapkan warna biru ke nilai rendah dan merah ke nilai tinggi.Invert Color Ramp

16.	Ini adalah visualisasi yang bagus, tetapi tidak mudah untuk ditafsirkan. Mari buat peta yang lebih baik dengan 4 kategori terpisah, Decline, Neutral, Growthdan . Gulir ke bawah ke tabel dengan kelas. Tahan tombol dan pilih semua baris. Klik tombol Hapus baris yang dipilih .High GrowthShift

17.	Ubah mode InterpolasiDiscrete ke . Kami sekarang akan membuat peta warna secara manual. Klik tombol Tambahkan nilai secara manual . Masukkan -100sebagai Nilai dan Declinesebagai Label . Tetapkan warna biru untuk kategori ini. Cara kerja peta warna adalah semua nilai yang lebih rendah dari nilai yang dimasukkan akan diberi warna entri tersebut. Kita akan melihat bahwa kanvas hanya akan menampilkan area dengan perubahan populasi negatif.

18.	Lengkapi peta warna dengan nilai yang sesuai. Saya memilih 100, 1000dan 100000sebagai batas atas untuk Neutral, Growthdan kategori masing-masing. Tetapkan warna untuk setiap kategori yang dibuat, misalnya krem, oranye, dan merah.High Growth

19.	Setelah Kita puas dengan visualisasinya, tutup panel Layer Styling . Kita sekarang memiliki peta tematik global tentang perubahan populasi.


## Modul 7
# `Mosaik dan Kliping Raster (QGIS3)`
file : [modul7.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/4711acc366f036e3185f1e0ad8baa80712fbac15/Raster%20Mosaicing%20and%20Clipping%20(QGIS3)_2101091013_siti%20nurhaliza%20yus.qgz)

## Prosedure
1. Buka QGIS dan temukan file yang diunduh di panel Browser . Perluas file zip individual untuk menampilkan .hgtfile. Tahan Ctrltombol dan pilih semua file individual. Setelah dipilih, seret ke kanvas.
![1](https://user-images.githubusercontent.com/114122090/201807284-e80d305f-947e-4b8e-b078-1bd87d362338.png)

2. Kita akan melihat 11 layer individual dimuat di panel Layers dan ditampilkan di kanvas. Kami akan menggabungkan ubin individual ini menjadi satu mozaik. Pergi ke Memproses ‣ Kotak Alat .
![3](https://user-images.githubusercontent.com/114122090/201807297-0e404ff5-e738-4be3-a15c-e44574298dd2.png)

3. Cari dan temukan GDAL Raster miscellaneous Merge tool. Klik dua kali untuk meluncurkannya.
![4](https://user-images.githubusercontent.com/114122090/201807301-98791fec-126a-44c0-a0c9-cc7a4a7d1b8f.png)

4. Dalam dialog Gabung , klik tombol … di sebelah Lapisan masukan . Klik Select All untuk memilih semua layer individual.
![5](https://user-images.githubusercontent.com/114122090/201807305-2c08cee3-0054-41c6-9ab1-5871f3bf8392.png)
![6](https://user-images.githubusercontent.com/114122090/201807309-e5730ca6-af64-4c2c-b666-4e664c2caa95.png)
Seperti yang disebutkan dalam detail lapisan dataset , tipe data input adalah integer bertanda 16-bit . Untuk menjaga integritas data, kita harus menjaga tipe data yang sama untuk lapisan gabungan. Pilih Int16sebagai tipe data Output . Juga format data keluaran default adalah GeoTiff. File GeoTiff bisa menjadi sangat besar jika tidak dikompresi. Pilih sebagai Profil . Klik Jalankan .High Compression
![7](https://user-images.githubusercontent.com/114122090/201807312-91e4c740-a9e3-4d8d-b23e-cb5f175a0fa0.png)
![8](https://user-images.githubusercontent.com/114122090/201807315-cc1a29b0-9049-429c-b81a-515abbe257e6.png)

5. Setelah pemrosesan selesai, layer baru marge akan ditambahkan ke panel Layers . Jika lapisan tidak berada di bagian atas tumpukan, pilih dan seret ke bagian atas panel Lapisan .
![9](https://user-images.githubusercontent.com/114122090/201807319-30814b4f-31d7-4cba-b3dc-970384864dda.png)

6. Kita akan melihat bahwa marge layer tersebut berisi data elevasi yang digabungkan dari masing-masing petak masukan. Visualisasi default hanya menampilkan nilai piksel dalam rentang 0-255. Tetapi data kami mengandung piksel dengan nilai -14 hingga 2371, menghasilkan rendering kontras rendah. Mari mengubahnya menjadi visualisasi yang lebih baik. Klik tombol Open the layer Styling panel di panel Layers .
![10](https://user-images.githubusercontent.com/114122090/201807324-461ecb38-9a8c-4686-9c0a-eeb449f9631a.png)

7. Di panel Layer Styling , klik dropdown Render type dan pilih Hillshaderenderer. Opsi rendering ini sangat cocok untuk data elevasi.
![11](https://user-images.githubusercontent.com/114122090/201807329-ba103282-eaf9-4a49-b3cb-7718bce8f63a.png)
![12](https://user-images.githubusercontent.com/114122090/201807332-0102bd6c-af8b-4255-819e-3d71f4bd55a1.png)

8. Operasi umum lainnya saat bekerja dengan raster adalah untuk memotong raster ke area yang Anda minati. Untuk tutorial ini, kami akan memotong layer gabungan ke batas negara untuk Sri Lanka. Temukan ne_10m_admin_0_countries.zipfile yang diunduh dan perluas. Seret ne_10m_admin_0_countries.shpfile ke kanvas.
![13](https://user-images.githubusercontent.com/114122090/201807341-3cae6880-43b5-424a-bb8c-7d1d6d4acf40.png)
![14](https://user-images.githubusercontent.com/114122090/201807350-be5d7f50-91e4-40d3-aaa3-4f2baeff320c.png)

9. ne_10m_admin_0_countriesPilih layer yang baru ditambahkan di panel Layers . Klik tombol Select Features by area atau satu klik pada Attributes Toolbar . Setelah dipilih, klik poligon untuk Sri Lanka untuk memilihnya.
![15](https://user-images.githubusercontent.com/114122090/201807524-dbf27a7b-9402-4f2f-ad5a-ccdcd071e616.png)

10. Pertahankan seleksi seperti apa adanya dan buka Processing Toolbox . Cari dan temukan GDAL Ekstraksi raster Klip raster dengan alat lapisan topeng. Klik dua kali untuk meluncurkannya.
![16](https://user-images.githubusercontent.com/114122090/201807360-78f06cd3-0eb0-42b7-b4aa-dc8743e49962.png)

11. Dalam dialog Clip Raster by Mask Layer , tetapkan marge sebagai Input Layer . Pilih ne_10m_admin_0_countriessebagai layer Mask , dan centang kotak Selected features only . Masukkan 0.0000 sebagai Menetapkan nilai nodata yang ditentukan ke band keluaran . Seperti sebelumnya, pilih sebagai Profile . Klik Jalankan .High compression
![17](https://user-images.githubusercontent.com/114122090/201807576-df217e22-c121-42e2-8dfc-1ba7f16a8c4e.png)
![18](https://user-images.githubusercontent.com/114122090/201807372-a054900c-2785-4804-abec-afb119dca2b7.png)
![19](https://user-images.githubusercontent.com/114122090/201807373-2e6fb9d2-cc50-4b6a-9b53-58952f43048c.png)
![20](https://user-images.githubusercontent.com/114122090/201807380-7524c574-5785-4d8d-a92f-05fe1d627636.png)

12. Sebuah layer baru marge akan ditambahkan ke panel Layers . Pada titik ini, mungkin sulit untuk melihat hasilnya karena kita memiliki terlalu banyak lapisan tumpang tindih yang terlihat. Klik tombol Kelola Tema Peta di panel Lapisan dan pilih .Hide All Layers
![21](https://user-images.githubusercontent.com/114122090/201885617-cf008fab-7753-4671-8743-ad1f2595abe2.png)

13. Nyalakan hanya marge layer terbaru dan beri gaya dengan Hilshadeperender seperti yang dilakukan sebelumnya
![22](https://user-images.githubusercontent.com/114122090/201885654-bbe09bfd-0e9c-4342-b220-2baaf365aece.png)

14.  Lapisan elevasi keluaran gabungan dan subset untuk Sri Lanka sudah siap.


## Modul 8
# `Bekerja dengan Data Medan (QGIS3)`
file : [modul8.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/4711acc366f036e3185f1e0ad8baa80712fbac15/Working%20with%20Terrain%20Data%20(QGIS3)_siti%20nurhaliza%20yus_2101091013.qgz)

Berikut adalah cara mencari dan mengunduh data revelant dari USGS Earthexplorer.

1. Pergi ke USGS Earthexplorer . Di tab Kriteria Pencarian , klik Fitur Dunia . Di Feature Name enter Everest, di Country enter NEPAL, klik Show . Ini akan menampilkan tabel dengan informasi lokasi. Pilih Everest di bawah Placename .
![1](https://user-images.githubusercontent.com/114122090/201886726-0bb2a64d-b1bc-4c04-b7e5-74013bb091af.png)

2. Sekarang kanvas akan pindah ke lokasi Gunung Everest . Klik Kumpulan Data .
![2](https://user-images.githubusercontent.com/114122090/201886789-f8569b15-62e1-458c-b8af-fe011da586fa.png)

3. Luaskan grup Digital Elevation , dan centang GMTED2010 . Klik Hasil .
![3](https://user-images.githubusercontent.com/114122090/201886852-45b68ee6-a279-460b-88a1-2ef3695ea561.png)

4. Klik tombol Opsi Unduhan .
![4](https://user-images.githubusercontent.com/114122090/201886927-52418f3c-6c37-44a0-9334-17d98564f5a8.png)
>Peringatan :
>Kita harus masuk ke situs saat ini. Anda dapat membuat akun gratis jika Anda tidak memilikinya.

5. Pilih opsi 30 ARC SEC dan klik Download .
![5](https://user-images.githubusercontent.com/114122090/201887030-b60ecdfe-5d31-4cc5-8aab-429a4e4caee8.png)

6. Kita sekarang akan memiliki file bernama GMTED2010N10E060_300.zip . Data elevasi didistribusikan dalam berbagai format raster seperti ASC, BIL, GeoTiff, dll. QGIS mendukung berbagai format raster melalui pustaka GDAL. Data GMTED datang sebagai file GeoTiff yang terkandung dalam arsip zip ini.
Untuk kenyamanan, Anda dapat mengunduh salinan data langsung dari bawah.

[GMTED2010N10E060_300.zip](https://www.qgistutorials.com/id/docs/3/working_with_terrain.html#get-the-data)

Sumber Data: [[GMTED2010]](https://www.qgistutorials.com/id/docs/credits.html#gmted2010)

## Procedure
1. Buka Lapisan Tambahkan Lapisan Tambahkan Lapisan Raster .
![6](https://user-images.githubusercontent.com/114122090/201887230-d6cb7e70-f59f-4150-a99d-e9e8fcd545e6.png)

2. Klik pada ... di bawah Sumber , cari dan pilih file bernama 10n060e_20101117_gmted_mea300.tif .
![7](https://user-images.githubusercontent.com/114122090/201887245-0673d89a-c1c6-4e9d-b2af-bfdf995919cf.png)

3. Kita akan melihat data medan yang ditampilkan di Kanvas QGIS. Setiap piksel dalam raster medan mewakili elevasi rata-rata dalam meter di lokasi tersebut. Piksel gelap mewakili area dengan ketinggian rendah dan piksel lebih terang mewakili area dengan ketinggian tinggi.
![8](https://user-images.githubusercontent.com/114122090/201887271-44d9f16b-c785-4c7c-be25-0536e446ac83.png)

4. Mari temukan bidang minat kita. Dari Wikipedia , kami menemukan bahwa koordinat untuk area yang kami minati - Gunung Everest - terletak pada koordinat 27.9881° LU, 86.9253° BT. Perhatikan bahwa QGIS menggunakan koordinat dalam format (X, Y), jadi Anda harus menggunakan koordinat sebagai (Bujur, Lintang). Tempelkan 86.9253,27.9881 ini di bagian bawah jendela QGIS di mana tertulis Koordinasi dan tekan Enter. Area pandang akan dipusatkan pada koordinat ini. Untuk memperbesar, Masukkan 1:1000000 di bidang Skala dan tekan Enter. Anda akan melihat viewport zoom ke area sekitar Himalaya.
![9](https://user-images.githubusercontent.com/114122090/201887308-6c053f62-ae33-42b3-8b53-213fca465281.png)

5. Kami sekarang akan memangkas raster ke area minat ini. Cari Klip di Kotak Alat Pemrosesan . Pilih di bawah algoritma GDAL.Clip Raster by extent
![10](https://user-images.githubusercontent.com/114122090/201887369-1781dcc9-6737-4d8d-b253-2c61ef5419e7.png)

6. Di jendela Clip Raster by Extent , pilih 10n060e_20101117_gmted_mea300sebagai Input Layer... , klik Clipping extent dan pilih , klik Clipped (extent) dan masukkan nama sebagai . Klik Jalankan .Use Map canvas extent...mt_everest.tif
![11](https://user-images.githubusercontent.com/114122090/201887411-5302b141-7ff5-4b4a-9e14-ca495f554e91.png)

7. Sebuah layer baru mt_everestakan muncul di kanvas. Cari Hill di Processing Toolbox . Pilih Hillshadealgoritma di bawah algoritma GDAL.
![12](https://user-images.githubusercontent.com/114122090/201887442-a9567638-83dc-4d33-a612-3dc5a3a60168.png)

8. Di jendela Hillshade , pilih mt_everestsebagai Elevation Layer , masukkan 315.000dalam Azimuth (sudut horizontal) , masukkan 45.000dalam sudut Vertikal . Klik ...di Hillshade dan masukkan namanya sebagai mt_everest_hillshade.tif. Klik Jalankan .
![13](https://user-images.githubusercontent.com/114122090/201887529-b24e151a-6b40-4fbb-89fb-aad8fa9c5ffa.png)

9. Sebuah layer baru mt_everest_hillshadeakan muncul di kanvas.
![14](https://user-images.githubusercontent.com/114122090/201887544-14398536-8dfe-4f69-a594-ed0f96ba7f47.png)

10. Cari Contour di Processing Toolbox . Pilih Contouralgoritma di bawah algoritma GDAL.
![15](https://user-images.githubusercontent.com/114122090/201887597-2d00d267-00e2-42e7-82c7-959de76e4240.png)

11. Di jendela Contour , pilih mt_everestsebagai Input Layer , masukkan Interval 250antara garis kontur . Klik ...di Kontur dan masukkan nama sebagai mt_everest_contour.gpkg. Klik Jalankan .
![16](https://user-images.githubusercontent.com/114122090/201887630-0252f6db-dc2c-4f52-8186-40d94a1c494e.png)

12. Sebuah layer baru mt_everest_contourakan muncul di kanvas. Klik kanan pada layer dan klik Open Attribute Table .
![17](https://user-images.githubusercontent.com/114122090/201887642-35ee392b-75ab-4fc6-8de4-b4332a3f26e0.png)

13. Kita akan melihat bahwa setiap fitur baris memiliki atribut bernama ELEV . Ini adalah ketinggian dalam meter yang diwakili oleh setiap garis. Klik pada tajuk kolom beberapa kali untuk mengurutkan nilai dalam urutan menurun. Di sini Anda akan menemukan garis yang mewakili elevasi tertinggi dalam data kami, yaitu Gunung Everest.
![18](https://user-images.githubusercontent.com/114122090/201887668-08ed9071-4ea0-479f-896c-f56361e501c6.png)

14. Pilih baris atas, dan klik tombol Zoom to selection .
![19](https://user-images.githubusercontent.com/114122090/201887678-26d07158-5260-409c-8f54-f9f6beecb0a3.png)

15. Beralih ke jendela utama QGIS. Anda akan melihat garis kontur yang dipilih disorot dengan warna kuning. Ini adalah area elevasi tertinggi dalam kumpulan data kami.
![20](https://user-images.githubusercontent.com/114122090/201887686-03436aba-41a6-4e6e-a51c-0c31bd4b5821.png)

16. Cari Smooth di Processing Toolbox . Pilih di Smoothbawah geometri Vektor.
![21](https://user-images.githubusercontent.com/114122090/201887696-b48ae4b6-3096-47b4-a3d4-1b9be5a988bd.png)

17. Di jendela Smooth , pilih mt_everest_contoursebagai Input Layer5 , masukkan Iterasi . Klik Jalankan .
![22](https://user-images.githubusercontent.com/114122090/201887702-4fe534a5-d14d-4202-bd30-308f2deaa45d.png)
>Peringatan : 
>Algoritma pemulusan bekerja dengan menambahkan simpul ekstra di sepanjang garis. Saat Anda menambah jumlah iterasi, jumlah simpul di garis kontur bertambah banyak. Jadi berhati-hatilah dalam menggunakan jumlah iterasi yang lebih tinggi. Anda dapat mengurangi ukuran berkas keluaran dengan mengekspornya sebagai berkas bentuk dan menyederhanakan hasilnya menggunakan Mapshaper .

18. Sebuah layer baru Smoothedakan muncul di kanvas. Lapisan ini akan memiliki tepi yang lebih halus dibandingkan dengan mt_everest_contourlapisan.
![23](https://user-images.githubusercontent.com/114122090/201887709-1249b05c-c801-4aee-91c8-9414e4107f5f.png)

19. Kita juga dapat memvisualisasikan lapisan kontur dan memverifikasi analisis Anda dengan mengekspor lapisan kontur sebagai KML dan melihatnya di Google Earth. Klik kanan pada layer yang telah dihaluskan, pilih Export ‣ Save Feature As... .
![24](https://user-images.githubusercontent.com/114122090/201887714-c531475b-52d3-4257-a250-8afe9023e4ef.png)

20. Pilih Keyhole Markup Language [KML] sebagai Format . Klik ...di Nama file dan masukkan nama sebagai contour_smoothed.kml. Klik Oke .
![25](https://user-images.githubusercontent.com/114122090/201887718-ff9dace8-c69f-445b-bc21-44b86b3a8a04.png)
![26](https://user-images.githubusercontent.com/114122090/201887727-8626024f-6d03-4c03-a01d-255b646756bf.png)

21. Jelajahi file keluaran di disk Kita dan klik dua kali untuk membuka Google Earth Pro.
![finish](https://user-images.githubusercontent.com/114122090/201891887-da7e5da8-9579-4e83-952b-f8a8672999b9.png)


## Modul 9
# `Bekerja dengan Data WMS (QGIS3) `
file : [modul9.qpt]()

## Procedure
1.	Buka QGIS dan klik Buka Pengelola Sumber Data .

2.	Di kotak dialog Pengelola Sumber Data beralih ke WMS/WMTS , klik Baru .

3.	Di kotak dialog Buat Koneksi WMS/WMTS Baru di bawah Detail Koneksi , masukkan Nama sebagai SEDAC, dan tempel URL yang disalin di kotak teks URL . Klik Oke . Jika Kita mendapatkan kesalahan dengan URL yang disalin, coba dengan URL alternatif https://sedac.ciesin.columbia.edu/geoserver/ows.

>Catatan :
>Kita membuat koneksi baru ke layanan WMS - bukan lapisan tertentu. Layanan tunggal biasanya >menawarkan beberapa lapisan yang dapat ditambahkan ke proyek Kita.

4.	Sekarang di kotak dialog Pengelola Sumber Data , klik Sambungkan . Semua lapisan yang tersedia akan dimuat. Kita akan melihat ID yang berbeda terdaftar di sebelah lapisan. ID 0berarti Kita mendapatkan peta semua lapisan. Jika Kita tidak menginginkan semua lapisan, Kita dapat memperluas daftar dengan mengklik ikon dan memilih lapisan yang diinginkan.

5.	Untuk tutorial ini, kami tertarik pada lapisan tertentu. Telusuri . Pilih versi default dari lapisan ekspansi perkotaan 2030.Probabilities of Urban Expansion to 2030

6.	Di bagian Pengkodean Gambar , Kita harus memilih format gambar. Format gambar itu penting, dan tergantung pada kasus penggunaan. Berdasarkan perspektif pengguna, berikut adalah beberapa petunjuk,

Kualitas : Kompresi file untuk PNG adalah lossless, untuk JPEG itu adalah kompresi lossy dan TIFF dapat berupa keduanya. Itu berarti kualitas PNG akan lebih baik dibandingkan dengan JPEG. Jika tujuan utama Kita adalah mencetak peta, gunakan PNG.

>Kecepatan : Karena gambar PNG tidak terkompresi dan dengan demikian ukurannya lebih besar, mereka akan membutuhkan waktu lebih lama untuk dimuat. Jika Kita menggunakan lapisan dalam proyek Kita sebagai lapisan referensi dan perlu banyak memperbesar/menggeser, gunakan JPEG.

>Dukungan Klien : QGIS mendukung sebagian besar format, tetapi jika Kita mengembangkan aplikasi web, browser biasanya tidak mendukung TIFF, jadi Kita harus memilih format lain.

>Jenis data : Jika lapisan Kita terutama vektor, PNG akan memberikan hasil yang lebih baik. Untuk lapisan citra, JPEG biasanya merupakan pilihan yang lebih baik.

Untuk tutorial ini, pilih PNG sebagai formatnya. Ubah nama Layer jika Kita mau dan klik Add .

7.	Sekarang lapisan Probabilitas Ekspansi Perkotaan hingga 2030 akan dimuat di kanvas. Gunakan alat Zoom/Pan untuk menjelajahi lapisan. Cara kerja layanan WMS adalah setiap kali Kita melakukan zoom/pan, ia mengirimkan koordinat area pKitang Kita ke server dan server membuat gambar untuk area pKitang tersebut dan mengembalikannya ke klien. Jadi, akan ada penundaan sebelum Kita melihat gambar untuk area tersebut setelah Kita memperbesar. Oleh karena itu, koneksi internet selalu diperlukan untuk mengakses lapisan ini.

8.	Sekarang, perbesar ke tempat yang diketahui dan klik ikon Identifikasi Fitur di bilah alat.

9.	Klik pada sembarang piksel di kanvas, itu akan muncul kotak dialog dengan nilai sel. Ini adalah nilai piksel dalam lapisan - yang menunjukkan kemungkinan bahwa piksel akan mengalami urbanisasi pada tahun 2030. Karena lapisan tidak disimpan secara lokal, nilai-nilai ini diambil dari penyedia layanan. Kita dapat melihat hasilnya lebih baik dengan memilih Format sebagai HTMLdan Lihat sebagai Tree.

>Catatan :
>Informasi diambil oleh GetFeatureInfo , ini adalah panggilan stKitar WMS yang memungkinkan kita >untuk mengambil informasi tentang fitur dan cakupan yang ditampilkan di peta. Jika peta terdiri >dari berbagai lapisan, dan GetFeatureInfo dapat diinstruksikan untuk mengembalikan beberapa >deskripsi fitur, HTML/GeoJSON adalah format file yang biasa digunakan untuk mengambil >informasi.

10.	Untuk melihat, informasi tambahan tentang layer klik kanan pada layer dan pilih Properties... .

11.	Di kotak dialog Properti Lapisan , alihkan ke tab Informasi di sini semua informasi seperti penyedia data , proyeksi , jangkauan dapat ditemukan. Klik OK untuk menutup kotak dialog setelah menjelajah.

12.	Di Peramban QGIS , cari Ubin XYZ dan klik dan seret OpenStreetMapke kanvas.

13.	Klik pada ikon panel Open the Layer Styling dan alihkan ke Transparency .

14.	Setel opasitas Global ke 50 %

15.	Sekarang di kanvas, lapisan Urban dapat dieksplorasi dengan referensi geografis.

16.	Untuk mendapatkan lebih banyak akses ke transparansi layer, klik kanan pada layer dan pilih Properties... .

17.	Di kotak dialog Properti Lapisan , alihkan ke tab Legenda , di bawah Widget yang tersedia pilih dan klik ikon Tambahkan widget yang dipilih . Klik Oke .Opacity slider

18.	Sekarang widget penggeser akan tersedia untuk mengontrol opacity layer.
![Working with WMS Data (QGIS3)_siti nurhaliza yus_2101091013](https://user-images.githubusercontent.com/114122090/202321773-92cd2e0d-6352-45f4-9f01-7937f166f6dd.PNG)


## Modul 10
# `Bekerja dengan Proyeksi (QGIS3)`
file : [modul10.qpt]()

## Procedure
1.	Buka QGIS. Pergi ke Layer ‣ Add Layer ‣ Add Vector Layer... .

2.	Klik ... di sebelah Sumber , Telusuri ke ne_10m_admin_0_countries.shpfile yang diunduh dan klik Tambah .

3.	Di bagian bawah jendela QGIS, Kita akan melihat label Coordinate . Saat Kita menggerakkan kursor di atas peta, koordinat X dan Y di lokasi tersebut akan ditampilkan. Di pojok kanan bawah Kita akan melihat EPSG:4326 . Ini adalah kode untuk CRS (Projection) saat ini untuk proyek - juga dikenal sebagai Project CRS .

4.	Untuk menentukan proyeksi layer, kita dapat melihat ke dalam metadata. Klik kanan pada ne_10m_admin_0_countrieslayer dan pilih Properties .

5.	Beralih ke tab Informasi di dialog Properti Lapisan . Luaskan bagian Informasi dari penyedia . Di bagian bawah, Kita akan melihat nama proyeksi di bawah CRS .

6.	Sekarang mari kita lihat bagaimana kita bisa mengubah proyeksi layer. Operasi ini disebut Re-Projection . Daripada memproyeksikan ulang seluruh lapisan, kita juga dapat memilih subset fitur dan memproyeksikannya kembali ke lapisan baru. Gunakan alat Select features by area or single click dan klik fitur United Kingdom untuk memilihnya.

7.	Cari dan temukan algoritma Vector General ‣ Proyeksi ulang layer di kotak alat Pemrosesan.

8.	Pilih ne_10m_admin_0_countriessebagai Input layer , centang Selected features only lalu klik ikon bola dunia di sebelah Target CRS , cari dan pilih . Di Diproyeksikan ulang , pilih dan klik Simpan ke file . Sekarang pilih direktori dan masukkan nama sebagai dan klik Run .EPSG:27700 - OSGB 1936 / British National Grid...united_kingdom.gkpg

9.	Sebuah layer baru united_kingdomakan muncul pada Layer Panel . Seperti yang Kita lihat, kedua layer masih sejajar satu sama lain - meskipun berada di CRS yang berbeda. Ini karena QGIS mendukung transformasi CRS On-The-Fly (OTF) . Artinya, setiap kali CRS sebuah layer tidak cocok dengan Project CRS, maka secara otomatis akan diubah menjadi Project CRS sehingga dapat ditampilkan dengan benar. Sekarang mari atur Project CRS agar cocok dengan CRS united_kingdomLayer yang baru dibuat. Hapus ne_10m_admin_0_countrieslayer dan, klik kanan pada united_kingdomlayer Layer CRS ‣ Set Project CRS from Layer .

10.	Kita akan melihat Proyek CRS diperbarui ke EPSG:27700.

11.	Sekarang mari tambahkan layer Raster. Pergi ke Layer ‣ Add Layer ‣ Add Raster Layer... .

12.	Klik di ...sebelah Sumber , pilih layer MiniScale_(stKitard)_R23.tif. Klik Tambahkan .

13.	Sekarang layer baru MiniScale_(stKitard)_R23ditambahkan ke kanvas.

14.	Untuk membuat kedua layer terlihat, ganti urutan layer dengan menyeret MiniScale_(stKitard)_R23ke bawah di panel Layers .

15.	Klik kanan pada MiniScale_(stKitard)_R23layer dan klik Properties .

16.	Di Layer Properties , pindah ke Information , CRS adalah . Ini menegaskan bahwa CRS layer raster sama dengan Project CRS.EPSG:27700 - OSBG 1935 / British National Grid - Projected
>Catatan
>Jika Kita ingin memproyeksikan ulang lapisan raster, Kita dapat menggunakan GDAL ‣ >Proyeksi raster ‣ Algoritma warp (proyeksi ulang) di kotak alat Pemrosesan.


## Modul 11
# `Lembar Topo Georeferensi dan Peta yang Dipindai (QGIS3)`
file : [modul11.qpt]()

## Procedure
1.	Buka QGIS dan klik Raster ‣ Georeferencer untuk membuka alat.
>Catatan
>Dari QGIS versi 3.26 dan seterusnya, Georeferencer dapat diluncurkan >dari Layer ‣ Georeferencer .

2.	Georeferensi dibagi menjadi 2 bagian. Bagian atas tempat gambar akan ditampilkan dan bagian bawah tempat tabel yang menunjukkan GCP Anda akan muncul.

3.	Sekarang kita akan membuka gambar JPG kita. Buka File ‣ Buka Raster . Telusuri ke gambar yang diunduh dari peta yang dipindai dan klik Buka .

4.	Anda akan melihat gambar akan dimuat di bagian atas. Anda dapat menggunakan kontrol zoom/pan pada bilah alat untuk mempelajari lebih lanjut tentang peta.

5.	Sekarang kita perlu menetapkan koordinat ke beberapa titik di peta ini. Jika Anda melihat lebih dekat, Anda akan melihat kotak koordinat dengan tanda. Ini adalah garis grid Lintang dan Bujur.

6.	Sebelum menambahkan Titik Kontrol Tanah (GCP), kita perlu menentukan Pengaturan Transformasi. Klik ikon roda gigi di jendela georeferensi untuk membuka dialog pengaturan Transformasi.

7.	Dalam dialog Pengaturan transformasi , pilih jenis Transformasi sebagai . Lihat Dokumentasi QGIS untuk mempelajari tentang berbagai jenis transformasi dan penggunaannya. Kemudian pilih metode Resampling sebagai . Klik tombol Select CRS di sebelah Target SRS .Polynomial 2Nearest neighbor

8.	Jika Anda melakukan geo-referensi peta yang dipindai seperti ini, Anda dapat memperoleh informasi CRS dari peta itu sendiri. Melihat gambar peta kita, koordinatnya ada di Lintang/Bujur. Tidak ada informasi datum yang diberikan, jadi kita harus mengasumsikan yang sesuai. Karena ini adalah India dan petanya cukup tua, kita bisa bertaruh bahwa data Everest 1830 akan memberi kita hasil yang baik. Cari everestdan pilih CRS dengan definisi terlama dari datum Everest (EPSG:4042). Klik Oke .

>Catatan :
>Survey of India Topo Sheets dibuat antara tahun 1960 dan 2000 menggunakan spheroid >Everest 1956 dan datum India_nepal. Jika Anda melakukan georeferensi SOI Topo Sheets, , >Anda dapat menentukan CRS Kustom di QGIS dengan parameter berikut dan >menggunakannya dalam langkah ini. Definisi ini mencakup parameter delta_x, delta_y dan >delta_z untuk mengubah datum ini menjadi WGS84. Lihat halaman ini untuk informasi lebih >lanjut tentang Sistem Grid India .
+proj=longlat +a=6377301.243 +b=6356100.2284 +towgs84=295,736,257,0,0,0,0 +no_defs
>Catatan :
>Sebagian besar peta dibuat menggunakan Proyeksi CRS. Jika peta yang Anda coba >georeferensi menggunakan proyeksi CRS yang Anda ketahui, tetapi label graticules berada >dalam CRS Geografis (lintang/bujur), Anda dapat menggunakan alur kerja alternatif untuk >meminimalkan distorsi. Alih-alih menggunakan CRS Geografis seperti yang kami gunakan di >sini, Anda dapat membuat kisi vektor di QGIS dan mengubahnya menjadi CRS yang >diproyeksikan untuk digunakan sebagai referensi pengambilan koordinat yang >akurat. Lihat halaman ini untuk detail lebih lanjut.
9.	Beri nama raster keluaran Anda sebagai 1870_southern_india_modified.tif. Pilih LZWsebagai Kompresi . Periksa Simpan poin GCP untuk menyimpan poin sebagai file terpisah untuk tujuan di masa mendatang. Pastikan opsi Muat di QGIS saat selesai dicentang. Klik Oke .

>Catatan :
>File GeoTIFF yang tidak terkompresi bisa berukuran sangat besar. Jadi mengompresi mereka >selalu merupakan ide yang bagus. Anda dapat mempelajari lebih lanjut tentang berbagai opsi >kompresi TIFF (LZW, PACKBITS, atau DEFLATE) di artikel ini .
10.	Sekarang kita dapat mulai menambahkan Ground Control Points (GCP). Klik pada tombol Tambah Titik .

11.	Sekarang tempatkan cross-hair di persimpangan garis grid dan klik kiri, ini akan berfungsi sebagai ground-truth dalam kasus kita. Saat garis kisi diberi label, kita dapat menentukan koordinat X dan Y dari titik-titik tersebut. Di jendela pop-up, masukkan koordinat. Ingat bahwa X = bujur dan Y = lintang. Klik Oke .

12.	Anda akan melihat tabel GCP sekarang memiliki baris dengan detail GCP pertama Anda.

13.	Demikian pula, tambahkan lebih banyak GCP yang mencakup seluruh gambar. Semakin banyak poin yang Anda miliki, semakin akurat gambar Anda didaftarkan ke koordinat target. Transformasi membutuhkan setidaknya 6 GCP. Setelah Anda menambahkan jumlah poin minimum yang diperlukan untuk transformasi, Anda akan melihat bahwa GCP sekarang memiliki nilai bukan nol dan kesalahan . Jika GCP tertentu memiliki nilai error yang luar biasa tinggi, hal itu biasanya berarti kesalahan manusia dalam memasukkan nilai koordinat. Jadi, Anda dapat menghapus GCP itu dan menangkapnya lagi. Anda juga dapat mengedit nilai koordinat di Tabel GCP dengan mengeklik sel di salah satu Tujuan. X atau Des. kolom Y.Polynomial 2dXdYResidual

14.	Setelah Anda puas dengan GCP, klik tombol Mulai Georeferensi . Ini akan memulai proses membengkokkan gambar menggunakan GCP dan membuat raster target.

15.	Setelah proses selesai, Anda akan melihat lapisan georeferensi dimuat di QGIS. Georeferensi sekarang selesai. Juga, Anda akan melihat Project CRS di kanan bawah diatur ke EPSG:4042 seperti yang dijelaskan di Pengaturan Transformasi.

16.	Seret dan lepas OpenStreetMapas Base Map dari dropdown XYZ Tiles di bagian bawah panel Browser untuk memverifikasi lapisan georeferensi. Untuk menyetel transparansi, klik ikon Open layer styling panel dan pilih tab Transparency . Atur transparansi menjadi . Sekarang gambar georeferensi harus dilapisi dengan garis peta dasar.40 %

17.	Jika georeferensi membutuhkan lebih banyak penyesuaian, kita dapat mulai dari poin GCP yang terkumpul. Telusuri 1870_southern_india_modified.tiflokasi file. Anda dapat menemukan file tambahan, 1870_southern_india_modified.tif.points. File ini akan berisi informasi poin GCP.

18.	Buka alat georeferensi di QGIS, klik File ‣ Load GCP Points , dan pilih 1870_southern_india_modified.tif.points. Ini akan memuat GCP yang dibuat sebelumnya. Kemudian muat 1870_southern_india_modified.tifuntuk menyempurnakan pekerjaan Anda.


## Modul 12
# `Citra Udara BasisGeo`
file : [modul12.qpt]()

Prosedur
1.	Kami akan menggunakan peta dasar dari OpenStreetMap untuk menangkap koordinat georeferensi. QGIS3 hadir dengan dukungan built-in untuk lapisan petak. Ini umumnya dikenal sebagai lapisan 'XYZ' karena dibuat menggunakan petak peta individual untuk setiap tingkat zoom (z) pada petak koordinat ax,y. Anda dapat menemukan OpenStreetMaplapisan di bawah Ubin XYZ di Panel Peramban . Seret layer ke kanvas utama. Setelah dimuat, catat Sistem Referensi Koordinat (CRS) untuk lapisan ini di corder kanan bawah. Ini diatur sebagai . Ini penting karena koordinat yang kami simpulkan dari lapisan ini selama georeferensi akan berada di CRS ini.EPSG 3857 Pseudo Mercator

>Catatan :
>Lihat halaman ini untuk detail lebih lanjut tentang lapisan XYZ dan cara menambahkan peta dasar lainnya di QGIS.
2.	Gambar yang kami georeferensi adalah untuk . Anda dapat memperbesar/menggeser untuk menemukan taman ini di peta. Tapi itu rumit dan tidak praktis. Dari QGIS versi 3.20 dan seterusnya, ada dukungan bawaan untuk Nominatim Geocoder berbasis OpenStreetMap. Klik bilah pencarian di kiri bawah jendela QGIS. Untuk menggunakan ini sebagai awalan geocoder, tempat pencarian dengan . Pencarian akan memunculkan daftar alamat yang dapat dipilih. Klik alamat pertama.Washington Square Park, New York>> Washington Square Park

3.	Kanvas peta akan dipusatkan ke Square Park. Sekarang mari kita mulai georeferensi. Luncurkan Georeferensi dari Raster ‣ Georeferensi .
Catatan
Dari QGIS versi 3.26 dan seterusnya, Georeferencer dapat diluncurkan dari Layer ‣ Georeferencer .

4.	Untuk melakukan georeferensi pada citra udara, kita harus memilih titik koordinat dari OpenStreetMap, jadi pertama-tama mari tempatkan alat Georeferensi ke jendela utama QGIS. Pilih Configure Georeference dari Settings ‣ Configure Georeferencer .

5.	Centang Show georeferencer window docked dan klik OK .

6.	Jendela Georeferencer akan diletakkan di bagian bawah jendela utama QGIS. Mari memuat file gambar dengan mengklik ikon Open Raster di jendela Georeferencer dan menavigasi ke file JPG yang diunduh. Klik Buka.

7.	Sebelum menambahkan Titik Kontrol Tanah (GCP), kita perlu menentukan Pengaturan Transformasi. Klik ikon Pengaturan Transformasi untuk membuka dialog Pengaturan Transformasi. Pilih jenis Transformasi sebagai . Lihat Dokumentasi QGIS untuk mempelajari tentang berbagai jenis transformasi dan penggunaannya. Seperti disebutkan sebelumnya, peta dasar kita ada di CRS, jadi tetapkan itu sebagai Target CRS . Anda dapat membiarkan nama raster Output ke default dan memilih sebagai Compression . Periksa Gunakan 0 untuk transparansi bila diperlukan . Periksa Simpan poin GCPPolynomial 2EPSG 3857 Pseudo MercatorLZWuntuk menyimpan poin sebagai file terpisah untuk tujuan masa depan. Pastikan opsi Muat di QGIS saat selesai dicentang. Klik Oke .

8.	Sekarang klik tombol Add Point pada toolbar dan pilih lokasi yang mudah dikenali pada gambar. Sudut, persimpangan, tiang dll, membuat titik kontrol yang baik. Setelah Anda mengklik gambar di lokasi titik kontrol, Anda akan melihat pop-up yang meminta Anda untuk memasukkan koordinat peta. Klik tombol Dari kanvas peta .

9.	Di OpenStreetMaplapisan, klik lokasi yang tepat di lapisan referensi. Koordinat akan diisi secara otomatis dari klik Anda pada kanvas peta. Klik Oke .

>Catatan :
>Tips: Saat memilih GCP pada gedung, selalu pilih bagian bawah gedung. Sebagian besar citra >udara dan satelit memiliki bangunan miring, jadi memilih titik di atap akan menimbulkan >kesalahan.
10.	Demikian pula, pilih setidaknya 6 titik pada gambar dan tambahkan koordinatnya dari lapisan referensi. Setelah Anda menambahkan jumlah poin minimum yang diperlukan untuk transformasi, Anda akan melihat bahwa GCP sekarang memiliki nilai bukan nol dX, dY, dan Residualerror. Jika GCP tertentu memiliki nilai error yang luar biasa tinggi, hal itu biasanya berarti kesalahan manusia dalam memasukkan nilai koordinat. Jadi, Anda dapat menghapus GCP itu dan menangkapnya lagi.

11.	Setelah Anda puas dengan GCP, klik Mulai georeferensi . Ini akan memulai proses membengkokkan gambar menggunakan GCP dan membuat raster target. Setelah proses selesai, Anda akan melihat layer dimuat di QGIS. Tutup jendela Georeferensi .

12.	Sekarang klik pada ikon panel penataan lapisan Terbuka dan Beralih ke tab Transparansi . Tambahkan 255sebagai nilai tambahan tanpa data . Ini akan menghapus batas putih di sekitar gambar. Sekarang Anda akan melihat gambar georeferensi Anda terhampar dengan baik di lapisan dasar.

>Catatan :
>Citra 8-bit memiliki nilai piksel dalam rentang 0-255. 0 berwarna hitam dan 255 berwarna >putih.
![image](https://user-images.githubusercontent.com/114122090/202321419-c856f175-f198-4dc9-ae23-1010c450a1e6.png)



## Modul 13
# `Digitalisasi Data Peta (QGIS3)`
file : [modul13.qpt]()

## Procedure
1.	Di QGIS, mari muat file gambar. Pergi ke Layer ‣ Add Layer ‣ Add Raster Layer .

2.	Dalam dialog Pengelola Sumber Data pilih Raster. Di bawah Sumber klik ...dan cari yang diunduh BX24_GeoTifv1-02.tifdan klik Buka . Kemudian klik Tambah diikuti dengan Tutup.

3.	Ini adalah file raster yang besar, dan Kita mungkin memperhatikan bahwa saat Kita memperbesar atau menggeser peta, peta memerlukan sedikit waktu untuk merender gambar. QGIS menawarkan solusi sederhana untuk membuat raster memuat lebih cepat dengan menggunakan Image Pyramids . QGIS membuat petak pra-render pada resolusi yang berbeda, dan ini disajikan kepada Kita alih-alih raster penuh. Ini membuat navigasi peta cepat dan responsif. Klik kanan BX24_GeoTifv1-02layer dan pilih Properties .

4.	Dalam dialog Properti Lapisan , Pilih tab Piramida . Tahan Ctrltombol dan pilih semua resolusi yang ditawarkan di panel Resolusi . Biarkan opsi lain ke default dan klik Bangun piramida .

5.	Setelah proses selesai, kotak dialog akan menampilkan piramida tanpa tKita silang. Ini menKitakan pembangunan Piramida Gambar sudah selesai. Klik Oke .

6.	Sebelum kita mulai, kita perlu mengatur Opsi Digitalisasi default . Buka Pengaturan ‣ Opsi... .

7.	Pilih tab Digitalisasi di dialog Opsi . Centang Enable snapping by default di bawah bagian Snapping . Dalam mode snap Default pilih Vertex . Ini akan memungkinkan Kita untuk menjepret ke simpul terdekat. Saya juga lebih suka menyetel toleransi gertakan default dan Radius pencarian untuk suntingan titik dalam piksel daripada unit peta. Ini akan memastikan bahwa jarak jepretan tetap konstan terlepas dari tingkat zoom. Tergantung pada resolusi layar komputer Kita, Kita dapat memilih nilai yang sesuai. Klik Oke .

8.	Sekarang kita siap untuk memulai digitalisasi. Pertama-tama kita akan membuat layer jalan dan mendigitalkan jalan di sekitar area taman. Klik ikon Layer ‣ Create Layer ‣ New GeoPackage Layer... dari Panel. GeoPackage adalah format data terbuka, non-proprietary, platform-independen, dan berbasis stKitar untuk sistem informasi geografis yang diimplementasikan sebagai wadah database SQLite. Ini membuatnya lebih mudah untuk memindahkannya daripada sekumpulan shapefile. Dalam tutorial ini, kami membuat beberapa lapisan poligon dan lapisan garis sehingga GeoPackage akan lebih cocok. Kita selalu dapat memuat GeoPackage dan mengekspor layer sebagai shapefile atau format lain yang Kita inginkan.

9.	Dalam dialog Lapisan GeoPackage Baru , klik tombol ... dan simpan database GeoPackage baru bernama digitizing.gpkg. Pilih nama Tabel sebagai Roadsdan pilih LineStringsebagai jenis Geometri . Peta topografi dasar adalah CRS.EPSG:2193 - NZGD 2000

10.	Saat membuat lapisan GIS, Kita harus memutuskan atribut setiap fitur. Karena ini adalah layer jalan, kita juga akan memiliki dua atribut utama - Nama dan Kelas. Di Bidang Baru Masukkan Namejenis data Teks, dengan panjang Maksimum50 dan klik Tambahkan ke daftar atribut. Sekarang buat atribut baru dengan tipe Text data , dengan sebagai Maximum length . Klik OkeClass50

11.	Setelah Roadslayer dimuat, klik tombol Toggle Editing untuk menempatkan layer dalam mode edit.

12.	Klik tombol Tambahkan Fitur Garis . Klik pada kanvas peta untuk menambahkan simpul baru. Tambahkan simpul baru bersama dengan fitur jalan. Setelah Kita mendigitalkan ruas jalan, klik kanan untuk mengakhiri fitur.

>Catatan
>Kita dapat menggunakan roda gulir mouse untuk memperbesar atau memperkecil saat melakukan digitasi. Kita juga dapat menahan tombol gulir dan menggerakkan mouse untuk >menjelajah.

13.	Setelah Kita mengklik kanan untuk mengakhiri fitur, Kita akan mendapatkan dialog pop-up yang disebut Road - Feature Attributes . Di sini Kita dapat memasukkan atribut dari fitur yang baru dibuat. Lewati memasukkan nilai apa pun untuk fid karena ini adalah id berurutan yang akan dibuat secara otomatis. Masukkan nama jalan seperti yang tertera di peta topo. Secara opsional, tetapkan juga nilai Kelas Jalan. Klik Oke .

14.	Gaya default dari layer garis baru adalah garis tipis. Mari kita ubah untuk lebih melihat fitur digital pada kanvas. Pilih Roadslayer dan klik Layer Styling Panel .

15.	Di Layer Styling Panel , cari gaya layer jalan yang berbeda. Pilih . Klik Oke .topo road

16.	Sekarang lapisan jalan akan terlihat jelas. Jika Kita puas dengan pekerjaannya, klik tombol Save Layer Edits untuk menyimpan perubahan.

17.	Sebelum mendigitalkan jalan yang tersisa, penting untuk memperbarui beberapa pengaturan snap penting lainnya untuk membuat lapisan bebas kesalahan. Klik kanan pada ruang mana pun di area toolbar dan aktifkan toolbar Snapping.

18.	Sekarang Enable Snapping (Magnet Icon) akan muncul di panel. Klik untuk mengaktifkannya dan pilih Semua Lapisan dan pilih .Open Snapping Options..

19.	Dalam dialog Snapping options , klik Snapping on Intersection , yang memungkinkan Kita menjepret perpotongan lapisan latar belakang.

20.	Sekarang Kita dapat mengklik tombol Tambahkan fitur dan mendigitalkan jalan lain di sekitar taman. Pastikan untuk mengklik Simpan Hasil Editan setelah menambahkan fitur baru untuk menyimpan pekerjaan Kita. Alat yang berguna untuk membantu Kita mendigitalkan adalah Vertex Tool . Klik tombol Vertex Tool dan pilih .Vertex Tool (Current Layer)
21.	Setelah alat simpul diaktifkan, klik fitur apa pun untuk menampilkan simpul. Klik pada simpul mana pun untuk memilihnya. Verteks akan mengubah warna setelah dipilih. Sekarang Kita dapat mengklik dan menyeret mouse Kita untuk memindahkan simpul. Ini berguna saat Kita ingin melakukan penyesuaian setelah fitur dibuat. Kita juga dapat menghapus simpul yang dipilih dengan mengklik Deletetombol. ( di mac)Option+Delete

22.	Setelah Kita selesai mendigitalkan semua jalan, klik tombol Toggle Editing . Klik Simpan .

23.	Sekarang kita akan membuat layer lain untuk mendigitalkan taman sebagai poligon. Klik ikon Layer ‣ Create Layer ‣ New GeoPackage Layer... dari Panel. Dalam dialog New GeoPackage Layer , klik tombol ... dan pilih database GeoPackage bernama digitizing.gpkg. Beri nama layer baru sebagai atribut yang disebut Parks. Pilih MultiPolygonsebagai Jenis . Peta topografi dasar adalah CRS. Klik Oke . Di New Field Enter , dan ketik sebagai Text data , dengan sebagai Maximum length dan klik :guilabel:` Add to Fields List.`. Klik Oke .EPSG:2193 - NZGD 2000Name50

>Catatan :
>Poligon vs Multi-Poligon
>Polygon - Planar Permukaan didefinisikan oleh 1 batas eksterior dan 0 atau lebih batas >interior. Setiap batas interior mendefinisikan sebuah lubang di Poligon.
>Multi-Polygon - Ini digunakan untuk mewakili area dengan lubang di dalamnya atau terdiri >dari beberapa area yang terpisah. Misalnya, 3 poligon terputus-putus dapat ditarik dan >dikelompokkan sebagai fitur tunggal.
24.	Dialog pop-up akan muncul. Pilih tombol Tambahkan Lapisan Baru .

25.	Sekarang pilih layer Parkslalu klikroad Toggle Editing dan klik tombol Add feature dan klik pada kanvas peta untuk menambahkan simpul poligon. Digitalkan poligon yang mewakili taman. Pastikan Kita menjepret simpul jalan sehingga tidak ada celah antara poligon taman dan garis jalan. Klik kanan untuk menyelesaikan poligon.

26.	Masukkan nama taman di jendela pop-up Taman - Atribut Fitur .

27.	Sekarang digitalkan bagian atas taman. Masukkan nama taman dan simpan perubahannya.

28.	Sekarang, sebelum mendigitalkan poligon dalam, mari atur pengaturan yang dapat memudahkan pekerjaan ini. Lapisan Multi-Poligon menawarkan pengaturan berguna lainnya yang disebut Hindari persimpangan poligon baru . Pilih Enable Snapping (Magnet Icon), klik untuk mengaktifkannya, dan klik All Layers dan pilih .Advanced Configuration

29.	Klik tombol di bilah alat gertakan.Avoid Overlap on Active layers

30.	Sekarang di Edit Konfigurasi Lanjutan , pilih Unit sebagai pixels.

31.	Centang kotak di kolom Hindari Tumpang Tindih pada baris untuk Parkslapisan tersebut.

32.	Klik Tambahkan fitur untuk menambahkan poligon. Dengan Avoid Overlap , Kita akan dapat dengan cepat mendigitalkan poligon baru tanpa khawatir akan menjepret tepat ke poligon tetangga.

33.	Klik kanan untuk menyelesaikan poligon dan masukkan atribut. Ajaibnya poligon baru menyusut dan tersentak tepat ke batas poligon tetangga! Ini sangat berguna saat mendigitalkan batas kompleks di mana Kita tidak perlu tepat dan masih memiliki poligon yang benar secara topologi. Klik Toggle Editing untuk menyelesaikan pengeditan Parkslayer.

34.	Sekarang saatnya mendigitalkan lapisan bangunan. Buat layer poligon baru bernama Buildingsdengan mengklik ikon Layer ‣ Create Layer ‣ New GeoPackage Layer... dari Panels. Atur Bangunan dan MuiltiPolygon . Pilih CRS sebagai . Klik Oke .EPSG:2193 - NZGD 2000

35.	Setelah Buildingslapisan ditambahkan, matikan lapisan Parksdan Roadsuntuk membuat peta topo dasar terlihat. Pilih Buildingslayer dan klik Toggle Editing .

36.	Mendigitalkan bangunan bisa menjadi tugas yang rumit, dan juga menantang untuk menambahkan simpul secara manual sehingga ujung-ujungnya tegak lurus dan membentuk persegi panjang. Kami akan menggunakan toolbar QGIS yang disebut Shape Digitizing untuk membantu tugas ini. Klik kanan pada ruang kosong mana pun di area bilah alat dan aktifkan file .Shape Digitizing Toolbar

37.	Aktifkan pengeditan dengan menekan ikon pensil Toggle Editing .

38.	Sekarang di bawah Add Rectangle dropdown pilih Add Rectangle from Extent tombol.

39.	Perbesar ke area dengan bangunan. Klik dan seret mouse untuk menggambar persegi panjang yang sempurna. Demikian pula, tambahkan bangunan yang tersisa.

40.	Kita akan melihat bahwa beberapa bangunan tidak vertikal, dan kita perlu menggambar persegi panjang pada sudut yang sesuai dengan tapak bangunan. Di bawah Add Rectangle dropdown pilih Add Rectangle from Center dan tombol Point .

41.	Perbesar ke area bangunan berbentuk wajik. Klik di tengah untuk menjatuhkan titik dan seret mouse untuk menggambar persegi panjang.

42.	Kita perlu memutar persegi panjang ini agar sesuai dengan gambar di peta topo. Alat putar tersedia di toolbar Advanced Digitizing . Klik kanan pada area kosong di bagian toolbar dan aktifkan toolbar Advanced Digitizing .

43.	Klik tombol Putar Fitur .

44.	Gunakan alat fitur Select Single untuk memilih poligon yang ingin Kita putar. Setelah alat Fitur Putar diaktifkan, Kita akan melihat garis bidik di tengah poligon. Klik tepat pada garis bidik itu dan seret mouse sambil menahan tombol klik kiri. Pratinjau fitur yang diputar akan muncul. Lepaskan tombol mouse saat poligon sejajar dengan tapak bangunan.

45.	Simpan hasil edit layer dan klik Toggle Editing setelah Kita selesai mendigitalkan semua bangunan. Kita dapat menyeret lapisan untuk mengubah urutan tampilannya. Tugas digitalisasi sekarang selesai. Kita dapat bermain dengan opsi gaya dan pelabelan di properti lapisan untuk membuat peta yang terlihat bagus dari data yang Kita buat.
![Digitizing Map Data (QGIS3)_siti nurhaliza yus_2101091013](https://user-images.githubusercontent.com/114122090/202320865-7d6ebc21-d5ea-4998-b9f7-e3a9b2f615a8.jpeg)



## Modul 14
# `Mencari dan Mengunduh Data OpenStreetMap (QGIS3)`
file : [modul14.qpt]()

## Procedure
1.	Cari dan pasang plugin QuickOSM dari QGIS Official Plugin Repository. Lihat Menggunakan Plugin untuk instruksi mengunduh plugin. Pastikan Kita telah memilih kotak centang. Klik Tutup .

2.	Setelah diinstal, luncurkan plugin dari Vector ‣ QuickOSM ‣ QuickOSM... .

3.	Di tab Kueri cepat , Kita dapat menyetel filter untuk memilih subkumpulan. Atribut fitur peta dalam database OSM disimpan sebagai Tag . Tag diwakili dengan kunci dan nilai. Kuncinya adalah topik dan nilai adalah bentuk spesifik. Lihat halaman wiki Fitur Peta OSM untuk daftar lengkap tag untuk berbagai jenis fitur. Bilah diwakili menggunakan tag amenity:bardan pub dengan tag amenity:pub. Kami pertama-tama akan mengekstrak bilah. Pilih amenitysebagai Kunci dari menu drop-down.

4.	Pilih bardari menu tarik-turun Nilai .

5.	Kami dapat merangkai banyak kueri di versi terbaru (v2.0.0 +) dari plugin QuickOSM. Klik tombol plus bilah pemilihan kueri berikutnya akan muncul. Klik pada kotak pilihan pertama dimana kita bisa mendapatkan opsi Anddan Or. Dan hanya akan memilih fitur yang benar untuk semua kueri. Atau akan memilih semua fitur yang benar untuk salah satu kueri. Klik Oruntuk memilih fitur bar dan pub.

6.	Pilih amenitysebagai Kunci dari menu drop-down. Kemudian pilih pubdari menu tarik-turun Nilai .

7.	Masukkan Londonsebagai Masuk untuk membatasi pencarian di dalam batas kota.

8.	Luaskan bagian Lanjutan . Dalam model data OSM, fitur direpresentasikan menggunakan node, cara, dan relasi . Karena kami tertarik dengan fitur poin, Kita hanya dapat memilih Nodedan Points. Klik Jalankan kueri .

9.	Setelah kueri selesai, alihkan ke jendela utama QGIS. Kita akan melihat layer baru bernama amenity_bar_amenity_pub_Londonditambahkan ke panel Layers . Kanvas akan menunjukkan lokasi bar dan pub yang diekstrak.

10.	Buka tabel Atribut layer. Ada 2091fitur. Fasilitas kolom berisi kategori apakah fitur tersebut adalah pubatau bar. Dengan menggunakan kolom kategorikal ini, mari beri gaya pada layer kita.

11.	Klik pada icon panel Open the Layer StylingCategorized , pilih kemudian pada Value pilih amenitykemudian klik Classify . Sekarang layer akan ditata dengan 2 warna yang menampilkan keduanya barsdan pubs.

12.	Sekarang klik kanan pada layer, Export ‣ Save Feature As... untuk mengekspor layer sebagai GeoPackage.

13.	Di kotak dialog Save Vector Layer as... , di Format pilih GeoPackage, di File name klik ...dan telusuri ke direktori tempat Kita ingin menyimpan data dan beri nama outputnya london.gpkg. Dalam Nama lapisan masukkan bar_and_pubs. Klik Oke .

14.	Sekarang lapisan GeoPackage london_bar_and_pubsakan ditambahkan ke kanvas.
![image](https://user-images.githubusercontent.com/114122090/202321345-3fb0642c-96fc-41cc-a660-2a037fd0babf.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## Modul 1
# `Performing Table Joins (QGIS3)`
file : [modul1.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/a88b54890b808b333ea320897242a8ddc5e6972d/performing%20table%20joins.qgz)
view : [modul1.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/a88b54890b808b333ea320897242a8ddc5e6972d/performing%20table%20joins.png)

## Procedure
1. Temukan tl_2019_06_tract.zipfile di Peramban QGIS dan kembangkan. Pilih tl_2019_06_tract.shpfile dan seret ke kanvas.
![image](https://user-images.githubusercontent.com/114122090/211183380-170909c0-1d6c-496f-a7ef-22181943e5eb.png)

2. Dialog Select Transformation akan meminta untuk mengkonversi dari EPSG:4269 ke EPSG:4326 . Dialog ini menyajikan beberapa transformasi untuk mengkonversi antara koordinat antara proyeksi tersebut. Tinggalkan pilihan ke pilihan default dan klik OK.

3. Kita akan melihat layer tl_2019_06_tractdimuat di panel Layers . Lapisan ini berisi batas-batas bidang sensus di California. Klik kanan pada tl_2019_06_tractlayer dan pilih Open Attribute Table .
![image](https://user-images.githubusercontent.com/114122090/211183478-568775a6-1c00-4bc7-b4c6-eee339df38d2.png)

4. Periksa atribut layer. Untuk menggabungkan tabel dengan lapisan ini, kita memerlukan atribut unik dan umum dari setiap fitur. Dalam hal ini, ada 8057 catatan traktat individu dengan GEOIDbidang tersebut. Kolom ini dapat menautkan lapisan ini dengan lapisan atau tabel lain yang berisi ID yang sama.
![image](https://user-images.githubusercontent.com/114122090/211183507-1f769123-b537-45e2-ac2f-2e688c0e4a5f.png)

5. Untuk memuat data tabular, klik Open Data Source Manager .
![image](https://user-images.githubusercontent.com/114122090/211183529-54740105-7554-4b2b-9106-043e92fd9630.png)

6. Dalam dialog Pengelola Sumber Data , pilih Teks yang Dibatasi . Kemudian di sebelah kanan, klik di ...sebelah Nama file dan ramban ke folder yang tidak di-zip dengan CSV populasi California.
![image](https://user-images.githubusercontent.com/114122090/211183539-59511121-76dc-4f14-a514-e15d9f19f8f3.png)

7. Sekarang di bawah Sample Data , kita dapat memeriksa data bahkan sebelum memuatnya sebagai layer. Representasi menunjukkan bahwa tabel data berisi 2 baris header.
![image](https://user-images.githubusercontent.com/114122090/211183552-fc545472-3443-4e6d-a438-50f6a70b5dff.png)

8. Untuk menghilangkan baris header tambahan, di bawah Opsi Rekam dan Bidang atur Jumlah baris header yang akan dibuang ke 1. Sekarang tabel akan berisi tajuk kolom yang tepat. Karena layer ini hanya berisi data tabular, pilih di bawah Geometry Definition . Klik Add untuk menambahkannya sebagai layer dan kemudian klik Close untuk menutup kotak dialog ini.No geometry (attribute only table).
![image](https://user-images.githubusercontent.com/114122090/211183569-9f51277b-a2d3-4f39-a284-1dfc490c1c77.png)

9. CSV sekarang akan diimpor sebagai tabel ke QGIS dan muncul seperti ACST5Y2019.S0101pada panel Lapisan . Sekarang klik kanan pada layer dan pilih Open Attribute Table .
![image](https://user-images.githubusercontent.com/114122090/211183858-e0c17796-e421-47b9-a813-eaabee5a9645.png)

10. Kolom ID tersebut berisi id unik untuk setiap record, yang dapat digunakan untuk menggabungkan tabel ini dengan tl_2019_06_tractlayer. Jika  membandingkan nilai IDdengan GEOIDkolom dari tl_2019_06_tract.  akan melihat bahwa itu diawali dengan 1400000US . Untuk menggabungkan kedua tabel ini dengan sukses, nilainya harus sama persis. Mari kita hapus awalan ini dan tambahkan kolom baru dengan 11 karakter terakhir yang berisi nilai yang sama persis.
![image](https://user-images.githubusercontent.com/114122090/211183864-a00fa7bb-efe7-4214-904e-6ddecceda4fc.png)

11. Untuk membuat kolom baru dengan 11 digit terakhir, buka Processing Toolbox dengan masuk ke Processing ‣ Toolbox , dan cari dan temukan tabel Vector ‣ Algoritma kalkulator lapangan.
![image](https://user-images.githubusercontent.com/114122090/211183869-f685515e-f82e-473e-9993-a4d59cf54def.png)

12. Dalam dialog Kalkulator bidang ACST5Y2019.S0101 , pilih sebagai Input layer , masukkan Nama bidang geoid , dan pilih Jenis Bidang Hasil . Sekarang cari dalam ekspresi. Kita dapat menggunakan fungsi ini untuk mengekstrak bagian yang diperlukan dari bidang id.stringsubstr
![image](https://user-images.githubusercontent.com/114122090/211183874-dde13e11-adc0-4e7e-9e6f-37fb08612a7a.png)

13. Masukkan ekspresi di bawah ini. Kami menggunakan fungsi substr dan mengekstrak nilai dari posisi -11 (nilai negatif dihitung dari akhir). Hasil akhir dapat dilihat di bagian Pratinjau . Klik Jalankan.

```
substr("id", -11)
```
![image](https://user-images.githubusercontent.com/114122090/211183880-04dfa7d1-dfe8-4591-a416-e2fd5e41e488.png)

14. Sekarang layer baru Calculated akan dimuat di kanvas, mari kita periksa tabel atribut. Kolom baru geoiddengan nilai yang dapat dicocokkan dengan risalah pencacahan akan hadir.
![image](https://user-images.githubusercontent.com/114122090/211183884-96c5db7a-3fc3-4e53-ad39-16b8df863e8b.png)

15. Untuk membuat gabungan tabel, buka Processing Toolbox dengan masuk ke Processing ‣ Toolbox , dan cari dan temukan atribut Vector general ‣ Join dengan algoritma nilai bidang.
![image](https://user-images.githubusercontent.com/114122090/211183888-9e09f934-2141-4327-90ff-8623e4fc34e7.png)

16. Dalam dialog Gabungkan atribut menurut nilai bidang tl_2019_06_tract , pilih sebagai lapisan Input dan GEOIDsebagai bidang Tabel . Pilih Calculatedsebagai Input layer 2 dan geoidsebagai Table field 2 . Di bawah bidang Layer2 untuk menyalin , klik pada ....
![image](https://user-images.githubusercontent.com/114122090/211183899-7c6e6e3f-d864-4672-9363-668dd726f690.png)

17. Periksa , dan . Klik Oke .Geographic Area NameEstimate!!Total!!Total population geoid
![image](https://user-images.githubusercontent.com/114122090/211183904-2b703299-0e28-4a1b-8a05-d113bd6c6fb0.png)

18. Centang catatan Buang yang tidak dapat digabungkan . Ini akan menghilangkan catatan tambahan apa pun di tabel populasi. Klik tombol ... di bawah layer gabungan untuk memilih lokasi file keluaran dan pilih .Save to File...
![image](https://user-images.githubusercontent.com/114122090/211183907-80886f40-e86b-4ea5-881d-02d7774f09e4.png)

19. Beri nama geopackage keluaran sebagai california_total_population.gpkg. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211183912-b156b8ad-40d1-4751-a183-afe76cec0631.png)

20. Setelah pemrosesan selesai, verifikasi bahwa algoritme berhasil jika semua fitur 8057 digabungkan. Klik Tutup .
![image](https://user-images.githubusercontent.com/114122090/211183917-bee8f0a0-f3ff-431d-9cc6-35715cb8f4e1.png)

21. Kita akan melihat layer baru california_total_populationdimuat di panel Layers . Pada titik ini, bidang dari file CSV digabungkan dengan lapisan saluran sensus. Sekarang setelah kita memiliki data kependudukan di lapisan sensus, kita dapat menatanya untuk membuat visualisasi distribusi kepadatan penduduk. Klik tombol Buka Panel Penataan Lapisan .
![image](https://user-images.githubusercontent.com/114122090/211183922-b5a9eefd-1f26-4dac-ab08-46040a42f8fa.png)

22. Di panel Layer Styling , pilih Graduateddari menu drop-down. Saat kami ingin membuat peta kepadatan populasi, kami ingin menetapkan warna berbeda untuk setiap fitur saluran sensus berdasarkan kepadatan populasi. Kami memiliki populasi di kolom Estimasi!!Total!!Total populasi , dan area area di ALAND . Klik tombol Ekspresi , untuk menghitung persentase jumlah penduduk pada setiap saluran pencacahan.

>Catatan
>Saat membuat peta tematik (choropleth) seperti ini, penting untuk menormalkan nilai yang petakan. Memetakan jumlah total per poligon tidak benar. Penting >untuk menormalkan nilai-nilai yang dibagi dengan luas. Jika  menampilkan total seperti kejahatan,  dapat menormalkannya dengan membaginya dengan total >populasi, sehingga memetakan tingkat kejahatan dan bukan >>kejahatan. Belajarlah lagi

![image](https://user-images.githubusercontent.com/114122090/211183929-4b298913-f20b-490f-9d4d-f157dd0e0d57.png)


23. Masukkan ekspresi berikut untuk menghitung kepadatan populasi. Area fitur diberikan dalam kilometer persegi. Kami kemudian mengubahnya menjadi meter persegi dengan mengalikan dengan 1000000dan menghitung kepadatan penduduk dengan rumus Penduduk/Luas . Pratinjau hasilnya dan klik OK .

```
1000000 * ("Estimate!!Total!!Total population"/"ALAND")
```

![image](https://user-images.githubusercontent.com/114122090/211183941-30c9c9b0-30b5-4336-8aa4-84dc3cba2c78.png)

24. Di Panel Penataan Lapisan , klik klasifikasikan dan masukkan kelas sebagai 10.
![image](https://user-images.githubusercontent.com/114122090/211183948-ab7b8ba8-3cf6-4926-9667-73e0f7c1d8d1.png)

25. Klik pada jalur warna untuk memilih jalur warna RdYlGn.
![image](https://user-images.githubusercontent.com/114122090/211183949-07d656ac-8182-4038-8e36-bc4b15ce22d8.png)

26. Kerapatan yang lebih tinggi lebih penting, mari kita tetapkan warna hijau untuk kerapatan rendah dan merah untuk area dengan kerapatan tinggi. Klik pada jalur warna dan pilih Balikkan Jalur Warna .
![image](https://user-images.githubusercontent.com/114122090/211183955-e3cb93e0-a34c-4bc0-bad6-429d562be222.png)

27. Sekarang kami memiliki visualisasi informasi kepadatan populasi yang sangat baik di California. Untuk membuatnya lebih baik, mari kita buat batas setiap saluran sensus transparan. Klik pada tab Simbol.
![image](https://user-images.githubusercontent.com/114122090/211183959-90d9f3b0-5a1c-4e62-862b-4d2bed67bfb5.png)

28. Klik pada warna Stroke dan klik .Transparent stroke
![image](https://user-images.githubusercontent.com/114122090/211183961-0838342f-df2d-450f-888f-5d7a8e5c3ffc.png)

29. Tempat sampah dapat disesuaikan, klik pada Nilai ini akan memunculkan dialog untuk memasukkan nilai batas atas dan bawah.
![image](https://user-images.githubusercontent.com/114122090/211183968-6e699ddc-ee5a-41ab-9cc5-b87a34e941b4.png)

30. Setelah  puas menutup panel styling Layer. Kami sekarang memiliki visualisasi informasi kepadatan populasi yang terlihat bagus di California.
![Screenshot (1243)](https://user-images.githubusercontent.com/114122090/211184021-be5ff3e2-642b-46af-a812-7208ec851653.png)



## Modul 2
# `Performing Spatial Joins (QGIS3)`
file : [modul2.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.qgz)
view : [modul2.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.png)

## Procedure
1. Temukan nybb_19a.zipfile di Peramban QGIS dan kembangkan. Pilih nybb_19a/nybb.shplayer dan seret ke kanvas. Ini adalah lapisan poligon yang mewakili batas wilayah di kota New York.
![image](https://user-images.githubusercontent.com/114122090/211190037-bf9b3303-6b54-4413-a9ef-6ace45036fcd.png)

2. Selanjutnya, cari V_SSS_SEGMENTRATING_1.zipfile dan perluas. Pilih dot_V_SSS_SEGMENTRATING_1_20190129.shplayer dan tambahkan ke kanvas. Ini adalah lapisan garis dari semua jalan di kota.
![image](https://user-images.githubusercontent.com/114122090/211190061-2e026e80-4fa1-4223-85e9-cd018422f136.png)

3. Mari kita periksa atribut yang tersedia untuk setiap fitur dot_V_SSS_SEGMENTRATING_1_20190129layer. Klik kanan dan pilih Open Attribute Table .
![image](https://user-images.githubusercontent.com/114122090/211190080-ae08f531-1241-422a-8364-ae5ac359db54.png)

4. Kita akan melihat atribut yang dipanggil Rating_Byang memiliki nilai dalam rentang 0-10 yang mewakili peringkat segmen jalan. Atribut RatingWordmemiliki peringkat deskriptif. Kita dapat menggunakan Rating_B bidang tersebut untuk menghitung peringkat rata-rata.
![image](https://user-images.githubusercontent.com/114122090/211192582-ba1486b1-a1f1-4df6-980d-35ce924a3b98.png)

5. Kita mungkin telah memperhatikan bahwa beberapa fitur memiliki peringkat NR. Ini adalah segmen yang tidak diberi peringkat. Memasukkan mereka ke dalam analisis kami tidak akan benar. Sebelum kita melakukan penggabungan spasial, mari siapkan Filter untuk mengecualikan rekaman ini. Klik kanan dot_V_SSS_SEGMENTRATING_1_20190129layer dan pilih Filter .
![image](https://user-images.githubusercontent.com/114122090/211192611-571da133-d151-4864-9a8d-68ef204bd849.png)

6. Di Pembuat Kueri , ketikkan ekspresi berikut untuk memilih semua rekaman yang tidak diberi peringkat NR. Anda juga dapat membuat ekspresi secara interaktif dengan mengklik Field , Operator dan memilih Value yang sesuai . Klik Oke .
```
"RatingWord" != 'NR'
```
![image](https://user-images.githubusercontent.com/114122090/211192637-81daddfa-e193-4b62-819f-1e695706b1b1.png)

7. Kita akan melihat dot_V_SSS_SEGMENTRATING_1_20190129layer sekarang memiliki ikon filter yang menunjukkan bahwa ada filter aktif yang diterapkan ke layer ini. Sekarang kita bisa melakukan penggabungan spasial menggunakan layer ini. Pergi ke Memproses ‣ Kotak Alat .
![image](https://user-images.githubusercontent.com/114122090/211192652-2944b0e1-7225-44fe-b4a8-aab10ec6727f.png)

8. Cari dan temukan Vector general ‣ Gabungkan atribut berdasarkan algoritma lokasi (ringkasan). Klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211192679-527d1dbc-f470-4ff7-9f8c-f4ef226d9b34.png)

9. Dalam dialog Gabungkan atribut berdasarkan lokasi (ringkasan)nybb , pilih sebagai Input layer . Lapisan jalan dot_V_SSS_SEGMENTRATING_1_20190129akan menjadi lapisan Gabung . Anda dapat membiarkan predikat Geometri pada default Intersects. Klik tombol … di sebelah Fields to sumarize .
![image](https://user-images.githubusercontent.com/114122090/211192736-47d066e5-a034-4aeb-bd44-9a7ab21ffd7f.png)

>Catatan :
>Kiat untuk membantu Anda memilih masukan yang benar dan menggabungkan lapisan: Lapisan masukan adalah >salah satu yang akan dimodifikasi dengan atribut baru dalam gabungan spasial. Karena kami ingin bidang >peringkat rata-rata ditambahkan ke lapisan wilayah, itu akan menjadi lapisan masukan.

10. Pilih Rating_Bdan klik OK .
![image](https://user-images.githubusercontent.com/114122090/211192952-e9880e8b-0aa7-439a-870c-114aef079f31.png)

11. Demikian pula, klik tombol … di sebelah Ringkasan untuk menghitung .
![image](https://user-images.githubusercontent.com/114122090/211193094-0870a4d2-cdae-447d-a7a1-eee2a4d086ec.png)

12. Pilih meansebagai operator ringkasan dan klik OK . Sekarang kita siap untuk memulai pemrosesan. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211193123-654b7dc4-ddff-46e1-92e5-51282b132574.png)

13.	Algoritme pemrosesan akan bekerja melalui fitur dan menerapkan gabungan spasial. Verifikasi bahwa pekerjaan pemrosesan berhasil dan klik Tutup .
![image](https://user-images.githubusercontent.com/114122090/211193203-f6871ba8-023c-43d0-ae40-72d237199a68.png)
 
14.	Kembali ke jendela utama QGIS, kita akan melihat layer baru ditambahkan ke kanvas. Buka tabel atribut untuk lapisan ini. Anda akan melihat kolom baru ditambahkan ke layer input borough dengan rating rata-rata semua jalan yang bersinggungan dengan fitur tersebut.Joined layerRating_B_mean
![image](https://user-images.githubusercontent.com/114122090/211193226-19089a9e-3144-4ed1-ba61-cf67ef0ee148.png)

15.	Sekarang kita dapat melakukan operasi terbalik. Terkadang analisis memerlukan atribut dari lapisan lain berdasarkan hubungan spasial tetapi tidak menyelesaikan penyelesaian apa pun. Kita dapat menggunakan algoritma untuk analisis tersebut. Tugasnya adalah menambahkan nama borough ke setiap fitur di layer jalan berdasarkan poligon borough mana yang bersinggungan dengannya. Sebelum kita menjalankan algoritme ini, mari hapus filter dari layer. Klik ikon filter dan tekan Clear di Query Builder . Klik Oke .Join atribut berdasarkan locationdot_V_SSS_SEGMENTRATING_1_20190129
 ![image](https://user-images.githubusercontent.com/114122090/211193366-4028c49d-932a-49e4-b044-3c0a78acc69c.png)

16.	Matikan di panel Lapisan . Temukan Vector general ‣ Gabungkan atribut berdasarkan lokasi algoritme di Processing Toolbox dan klik dua kali untuk meluncurkannya.Joined layer
 ![image](https://user-images.githubusercontent.com/114122090/211193395-fe032564-e8d4-4238-9e21-207fbe1a8f13.png)

17.	Pilih dot_V_SSS_SEGMENTRATING_1_20190129 sebagai layer Input dan nybbsebagai layer Join . Kita dapat membiarkan predikat Geometri pada default Intersects. Klik tombol … di sebelah bidang untuk ditambahkan dan dipilih BoroName. Klik Oke .
 ![image](https://user-images.githubusercontent.com/114122090/211193417-e238a5e8-84ab-40b5-a9ed-73ebf720a669.png)

18.	Ruas garis dapat menjembatani batas wilayah, jadi kami memilih tipe Gabungan sebagai . Klik Jalankan .Crate fitur terpisah untuk setiap fitur yang terletak (one-to-many)
 ![image](https://user-images.githubusercontent.com/114122090/211194064-8a5a1aa8-dad5-49a6-b928-09f28977e4b4.png)

 
19.	Setelah pemrosesan selesai, buka tabel atribut file . Anda akan melihat bahwa ada atribut baru yang ditambahkan ke setiap fitur jalan.Joined layerBoroName
 ![image](https://user-images.githubusercontent.com/114122090/211194091-daa5268c-2339-4da6-a214-3687a02bf0a1.png)
 
 ![Screenshot (1244)](https://user-images.githubusercontent.com/114122090/211194117-b8e47a90-099a-46c5-8a3e-aa730b40b8a5.png)


## Modul 3
# `Performing Spatial Joins (QGIS3)`
file : [modul3.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.qgz)
view : [modul3.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.png)

## Prosedure
1.	Temukan metro_stations_accessbility.zipfile di Peramban QGIS dan kembangkan. Pilih metro_stations_accessbility.shpfile dan seret ke kanvas. Lapisan baru metro_stations_accessbilityakan dimuat di panel Lapisan .
![image](https://user-images.githubusercontent.com/114122090/211194230-1f26c81c-daea-4b8e-87f1-6f767d443bb9.png)

2.	Lapisan data untuk bar dan pub dalam format CSV. Untuk memuatnya di QGIS, buka Layer ‣ Add Layer ‣ Add Delimited Text Layer… . ( Lihat Mengimpor File Spreadsheet atau CSV (QGIS3) untuk detail lebih lanjut tentang mengimpor file CSV)
![image](https://user-images.githubusercontent.com/114122090/211194242-60e55db5-ba9c-4117-bf77-a5741bb508ab.png)

3.	Di Manajer Sumber Data | Dialog Teks Dibatasi , telusuri dan pilih file yang diunduh Bars_and_pubs__with_patron_capacity.csvsebagai Nama file . Bidang X dan kolom bidang Y harus dipilih secara otomatis ke dan masing- masing. Klik Tambahkan .x coordinatey coordinate
![image](https://user-images.githubusercontent.com/114122090/211194246-0d5b7ef8-43d9-47da-bcf6-297bb27b27f7.png)

4.	Kita akan melihat Bars_and_pubs__with_patron_capacitylayer baru ditambahkan ke panel Layers . Kedua layer input berada di Geograhpic Coordinate Reference System (CRS) . Untuk melakukan analisis spasial, disarankan untuk menggunakan Projected Coordinate Reference System (CRS). Jadi sekarang kita akan memproyeksikan ulang kedua layer ke CRS regional yang sesuai yang meminimalkan distorsi dan memungkinkan kita bekerja dalam satuan jarak seperti meter, bukan derajat. Pergi ke Memproses ‣ Kotak Alat .EPSG:4326 WGS84
![image](https://user-images.githubusercontent.com/114122090/211194255-d282ac59-9a08-421f-a90a-40fdc0e7aab1.png)

5.	Cari dan temukan Vector general ‣ Alat lapisan proyeksi ulang . Klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211194261-f2e2f00a-6c34-4aef-ae97-e5360dda2d89.png)

6.	Pilih Bars_and_pubs__with_patron_capacitysebagai lapisan Input . Klik tombol Select CRS di sebelah Target CRS .
![image](https://user-images.githubusercontent.com/114122090/211194267-10d2fc08-f0d9-48a2-afce-840727bf785b.png)

7.	Saat memilih sistem koordinat yang diproyeksikan untuk analisis Anda, tempat pertama yang harus dicari adalah CRS regional untuk area yang diminati. Untuk Australia, Map Grid of Australia (MGA) 2020 adalah sistem grid berbasis UTM yang digunakan untuk pemetaan lokal dan regional. Melbourne termasuk dalam UTM Zone 55, jadi kita bisa memilih GDA 2020 / MGA zone 55 EPSG:7855 CRS.
![image](https://user-images.githubusercontent.com/114122090/211194292-ccc8c0eb-f6e1-4fb5-82b4-668cf9ce3e73.png)

>Catatan
>Jika Anda tidak yakin dengan CRS lokal untuk wilayah tempat kita bekerja, memilih CRS untuk zona UTM berdasarkan datum WGS84 adalah pilihan yang aman. Kita dapat >mengetahui nomor zona UTM wilayah Anda menggunakan UTM Grid Zones of the World .

8.	Selanjutnya, klik tombol … di sebelah Diproyeksikan ulang dan pilih . Geopackage adalah data spasial format data terbuka yang direkomendasikan dan merupakan format pertukaran data default untuk QGIS3. Satu file GeoPackage dapat berisi beberapa layer vektor dan raster.Save to GeoPackage.gpkg
 ![image](https://user-images.githubusercontent.com/114122090/211194344-6e612ed0-d6da-4240-8579-bffdb4e53b86.png)

9.	Beri nama geopackage sebagai spatialquerydan klik Save .
 
10.	Saat diminta nama lapisan, masukkan bars_and_pubsdan klik OK . Klik Jalankan untuk memproyeksikan ulang lapisan.
 ![image](https://user-images.githubusercontent.com/114122090/211194356-122b86c3-fc89-4244-8e70-8f03224f47d4.png)

11.	Jendela akan beralih ke tab Log dan Anda akan melihat algoritme dijalankan dan membuat lapisan keluaran baru bars_and_pubs.
![image](https://user-images.githubusercontent.com/114122090/211194361-2ed06269-621e-4da9-a037-f09e5eb5bcbe.png)

12.	Sekarang kita akan memproyeksikan ulang metro_stations_accessbilitylayer. Beralih kembali ke tab Parameter di jendela Reproject layer . Pilih metro_stations_accessbilitysebagai lapisan Input . Pertahankan Target CRS yang sama . Selanjutnya, klik tombol … di sebelah Diproyeksikan ulang dan pilih . Pilih file keluaran yang sama (Ingat bahwa satu file geopackage dapat berisi banyak lapisan, jadi kami akan menyimpan lapisan baru ke file geopackage yang sama). Masukkan sebagai nama Layer . Klik Jalankan .Save to GeoPackagespatialquerymetro_stations
![image](https://user-images.githubusercontent.com/114122090/211194367-019bea34-79c7-45ff-be18-841d9d0b3f36.png)

13.	Kembali ke jendela utama QGIS, Anda akan melihat 2 layer baru dimuat di panel Layers : bars_and_pubsdan metro_stations. Anda dapat mematikan visibilitas untuk lapisan asli. Sekarang, kami siap untuk melakukan kueri spasial. Karena kami tertarik untuk memilih bar dan pub dalam jarak 500m dari stasiun metro, langkah pertama adalah membuat buffer di sekitar stasiun metro yang mewakili area pencarian kami. Cari dan temukan Vector geometry ‣ Buffer tool di Processing Toolbox dan klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211194374-dc89703d-7ce4-410e-a9cb-1b9a7e7a2171.png)

14.	Dalam dialog Buffermetro_stations , pilih sebagai Input layer . Tetapkan 500meter sebagai Jarak . Simpan hasilnya ke spatialquerygeopackage yang sama dan masukkan metro_stations_bufferssebagai Layer name . Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211194377-852e2c6c-6edd-4dfd-8899-155a65cea802.png)

15.	Kita akan melihat metro_stations_bufferslayer baru dimuat di panel Layers . Sekarang kita bisa mengetahui titik mana dari bars_and_pubslayer yang termasuk dalam poligon dari metro_stations_bufferslayer. Cari Vector selection ‣ Extract by Location tool dari Processing Toolbox dan klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211194389-7b74ed96-ffd1-485f-ab63-ef8f3d32d032.png)

>Catatan
>Ekstrak berdasarkan lokasi akan membuat layer baru dengan fitur yang cocok dari kueri spasial. Jika Anda hanya ingin memilih fitur, gunakan alat Pilih berdasarkan >lokasi .

16.	Dalam dialog Ekstrak berdasarkan lokasibars_and_pubs , pilih sebagai Ekstrak fitur dari . Periksa Intersectsebagai predikat geometri . Tetapkan metro_stations_bufferssebagai Dengan membandingkan fitur dari . Simpan hasilnya ke spatialquerygeopackage sebagai layer selected. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211194393-82796529-5495-4c41-a835-4d6fe49c3407.png)
  
17.	Setelah pemrosesan selesai, Kita akan melihat selectedlayer ditambahkan ke panel Layers . Perhatikan bahwa lapisan ini hanya berisi titik-titik dari bars_and_pubsyang termasuk dalam poligon penyangga.
![image](https://user-images.githubusercontent.com/114122090/211194412-13d58c49-72c2-4714-9e14-a02cd674ba69.png)

18.	Analisis kami selesai. Kita mungkin memperhatikan bahwa poligon penyangga terlihat berbentuk oval. Ini karena Project CRS kita masih disetel ke EPSG:4326 WGS84 . Untuk memvisualisasikan hasil dengan lebih baik, Kita dapat pergi ke Proyek ‣ Properti ‣ CRS dan pilih mana yang kami gunakan untuk analisis. Setelah diatur ke CRS ini, buffer akan muncul dalam bentuk yang benar.GDA 2020 / MGA zone 55 EPSG:7855
![image](https://user-images.githubusercontent.com/114122090/211194423-a7cd75aa-296f-4b2b-bf5f-18b6aa2db5e1.png)


## Modul 4
# `Nearest Neighbor Analysis (QGIS3)`
file : [modul4.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Nearest%20Neighbor%20Analysis%20(QGIS3).qgz)
view : [modul4.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Nearest%20Neighbor%20Analysis%20(QGIS3).png)

## Prosedure
1.	Temukan ne_10m_populated_places_simple.zipfile yang diunduh di panel Browser dan perluas. Seret ne_10m_populated_places_simple.shpfile ke kanvas.
![image](https://user-images.githubusercontent.com/114122090/211198783-d0effc44-c7ba-4bcc-b5b3-b0bf16df261a.png)

2.	Kita akan melihat layer baru ne_10m_populated_places_simple dimuat di panel Layers . Lapisan ini berisi titik-titik yang mewakili tempat berpenduduk. Sekarang kita akan memuat lapisan gempa bumi. Lapisan ini hadir sebagai file teks Tab Serepated Values (TSV) . Untuk memuat file ini, klik tombol Open Data Source Manager di Data Source Toolbar . Anda juga dapat menggunakan pintasan keyboard.Ctrl + L
![image](https://user-images.githubusercontent.com/114122090/211198806-1dc611a7-94c0-475c-923a-876dbc56aa85.png)

3.	Di kotak dialog Pengelola Sumber Data , pilih Teks yang Dibatasi .
![image](https://user-images.githubusercontent.com/114122090/211198811-709045e8-dfa2-4f5d-ae98-cc7aedabb26d.png)

4.	Klik tombol … di sebelah Nama file dan ramban ke earthquakes-2021-11-25_13-39-30_+0530.tsvfile yang diunduh. Bergantung pada sistem operasi, Anda mungkin tidak melihat file di direktori yang diunduh. Jika demikian, alihkan ke Semua file (*; .) dalam dialog Pilih File Teks yang Dibatasi untuk Dibuka . Setelah dibuka, pilih Pembatas khusus di bagian Format file , dan centang Tab. Di bagian Definisi geometri , pilih Koordinat titik . Secara default nilai bidang X dan bidang Y akan diisi secara otomatis dengan bidang yang sesuai di input. Dalam kasus kami, mereka adalah LongitudedanLatitude. Anda dapat meninggalkan CRS Geometri ke CRS default . Jika file Anda berisi koordinat dalam CRS yang berbeda, Anda dapat memilih CRS yang sesuai di sini. Klik Tambah diikuti oleh Tutup .EPSG:4326 - WGS 84
![image](https://user-images.githubusercontent.com/114122090/211198820-9408de04-fc03-4c82-8cea-51c76504f7b8.png)

5.	Perbesar dan jelajahi kedua set data. Setiap titik merah mewakili lokasi kejadian gempa bumi, dan setiap titik hijau mewakili lokasi tempat berpenduduk. Tujuan kita adalah menemukan titik terdekat dari lapisan tempat berpenduduk untuk setiap titik di lapisan gempa. Mari periksa tabel Atribut lapisan gempa bumi. Pilih layer dan klik ikon Open Attribute Table di Toolbar .
![image](https://user-images.githubusercontent.com/114122090/211198831-98d3b90a-e5e2-4990-baba-8a5079f2dbaf.png)
 
6.	Ada 2586 fitur, tetapi data berisi sedikit entri tanpa informasi lintang atau bujur. Kami harus menghapusnya sebelum melanjutkan lebih jauh. Tutup Tabel Atribut.
![image](https://user-images.githubusercontent.com/114122090/211198840-abb375ab-d7fb-43e6-8762-61a4a1d0b437.png)

7.	Pergi ke Pemrosesan ‣ Kotak Alat ‣ Geometri vektor ‣ Hapus alat geometri nol. Klik dua kali untuk membukanya.
![image](https://user-images.githubusercontent.com/114122090/211198845-14b79194-f2a6-435f-ba08-cef18fa69dac.png)

8.	Di kotak dialog Hapus Geometri Nullearthquakes-2021-11-25_13-39-30_+0530 , pilih sebagai lapisan Input dan centang kotak Juga hapus geometri kosong . Klik Jalankan . Setelah pemrosesan selesai, klik Tutup .
![image](https://user-images.githubusercontent.com/114122090/211198855-fe88fd1d-f505-4767-b8dc-a83fd34260f1.png)
 
9.	Layer baru akan ditambahkan ke panel Layers . Untuk analisis kita akan menggunakan layer ini sebagai pengganti layer aslinya. Hapus centang pada layer di panel Layers untuk menyembunyikannya. Pilih layer dan klik tombol Open Attribute Table dari Attributes Toolbar .Non null geometriesearthquakes-2021-11-25_13-39-30_+0530Non null geometries
![image](https://user-images.githubusercontent.com/114122090/211198867-ae00c717-0ae6-411d-b7ce-e24a7cad5046.png)

10.	Kita akan melihat jumlah fitur total yang lebih rendah karena semua baris dengan nilai lintang dan bujur kosong telah dihapus. Tutup tabel atribut.
![image](https://user-images.githubusercontent.com/114122090/211198872-e9e26323-f872-4f6f-b7d5-c4f0b8a6a1a2.png)

11.	Sekarang saatnya untuk melakukan analisis tetangga terdekat. Cari dan temukan Pemrosesan ‣ Toolbox ‣ Analisis vektor ‣ Jarak ke alat hub (baris ke hub) terdekat . Klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211198892-db0704dc-b7cd-403f-9d22-52c99db2133e.png)

>Catatan
>Kita juga dapat menambahkan lapisan titik sebagai keluaran, gunakan alat Jarak ke hub (titik) terdekat untuk itu.

12.	Di kotak dialog Distance to Nearest Hub (Line to Hub) , pilih sebagai layer Source points . Pilih sebagai layer Destination hubs . Pilih sebagai atribut nama lapisan Hub . Alat ini juga akan menghitung jarak garis lurus antara tempat berpenduduk dan gempa terdekat. Tetapkan sebagai unit Pengukuran . Klik di Jarak Hub dan klik Simpan ke File… untuk menyimpan file sebagai . Klik Jalankan . Setelah pemrosesan selesai, klik Tutup .Non null geometriesne_10m_populated_places_simplenameKilometers...earthquakes_with_nearest_city.gpkg
![image](https://user-images.githubusercontent.com/114122090/211198928-917400ee-f6eb-4921-ad86-4ce983b6aca5.png)

13.	Kembali ke jendela utama QGIS, Anda akan melihat lapisan baris baru bernama earthquakes_with_nearest_citydimuat di panel Lapisan . Lapisan ini memiliki ciri-ciri garis yang menghubungkan setiap titik gempa dengan tempat berpenduduk terdekat. Pilih earthquakes_with_nearest_citylayer dan klik ikon Open Attribute Tabel di Toolbar .
![image](https://user-images.githubusercontent.com/114122090/211198943-b2d98e16-5ba6-441f-9b27-43e60a0033a9.png)

14.	Gulir ke kanan ke kolom terakhir, dan Anda akan melihat 2 atribut baru bernama HubName dan HubDist ditambahkan ke fitur gempa asli. Ini adalah nama jarak ke tetangga terdekat dari layer tempat berpenduduk.
![image](https://user-images.githubusercontent.com/114122090/211198946-7c6a06c7-cc94-4667-bb78-4d583d1392da.png)


## Modul 5
# `Sampling Raster Data using Points or Polygons (QGIS3)`
file : [modul5.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Sampling%20Raster%20Data%20using%20Points%20or%20Polygons%20(QGIS3).qgz)
view : [modul5.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Sampling%20Raster%20Data%20using%20Points%20or%20Polygons%20(QGIS3).png)

## Prosedure
1.	Buka zip dan ekstrak keduanya 2018_Gaz_ua_national.zipdan tl_2018_us_county.zipke folder di komputer Anda. Buka QGIS dan cari us.tmax_nohads_ll_20190501_float.tiffile di Peramban QGIS seret ke kanvas.
![image](https://user-images.githubusercontent.com/114122090/211199153-092743bd-30c7-42c6-8c8c-14b59114d90f.png)

2.	Kita akan melihat layer raster baru us.tmax_nohads_ll_20190501_floatdimuat di panel Layers . Lapisan raster ini berisi suhu maksimum yang tercatat pada setiap piksel dalam derajat Celcius. Selanjutnya kita akan memuat file titik area perkotaan. File ini hadir sebagai file teks dalam format Tab Separated Values (TSV). Klik tombol Buka Pengelola Sumber Data di Bilah Alat Sumber Data .
![image](https://user-images.githubusercontent.com/114122090/211199168-94abfc88-8254-4bb9-a41e-a3b95b0a8c67.png)

3.	Beralih ke tab Teks Dibatasi . Klik tombol … di sebelah Nama file dan tentukan jalur ke file teks yang Kita unduh. Di bagian File format , pilih Custom delimiters dan centang Tab . Pilih INTPTLONGsebagai bidang X dan INTPTLATsebagai bidang Y . Klik Tambah lalu Tutup .
![image](https://user-images.githubusercontent.com/114122090/211199174-b0440c76-059d-436b-8e44-e94043a4dbff.png)

4.	Lapisan titik baru 2018_Gaz_ua_nationalakan dimuat di panel Lapisan . Sekarang kita siap untuk mengekstrak nilai dari lapisan raster pada titik-titik ini. Pergi ke Memproses ‣ Kotak Alat .
![image](https://user-images.githubusercontent.com/114122090/211199178-78abd11b-b2b5-48d1-8f92-dd62d1035d64.png)

5.	Cari dan temukan analisis Raster ‣ Contoh algoritme nilai raster. Klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211199187-70ac4e9f-cf23-4639-a9e0-490d41bc7dae.png)

6.	Pilih 2018_Gaz_ua_nationalsebagai Layer Titik Input . Pilih us.tmax_nohads_ll_20190501_floatsebagai Lapisan Raster untuk sampel . Luaskan parameter Lanjutan dan masukkan tmaxsebagai awalan kolom Keluaran . Klik Jalankan . Setelah pemrosesan selesai, klik Tutup .
![image](https://user-images.githubusercontent.com/114122090/211199199-78edc734-97f5-4f71-bd52-0259f66b38b2.png)

7.	Lapisan baru akan dimuat di panel Lapisan . Pilih alat Identifikasi di Bilah Alat Atribut dan klik titik mana saja. Anda akan melihat atribut ditampilkan di panel Identifikasi Hasil . Kita akan melihat atribut baru bernama tmax_1 ditambahkan ke setiap fitur. Ini adalah nilai piksel dari lapisan raster yang diekstraksi di lokasi titik. Angka 1 mewakili nomor pita raster. Jika lapisan raster memiliki banyak pita, kita akan melihat banyak kolom baru di lapisan keluaran.Sampled Points
![image](https://user-images.githubusercontent.com/114122090/211199208-a46a52c8-7556-4b47-a194-8a21b606628d.png)

8.	Bagian pertama dari analisis kami selesai. Mari kita hapus lapisan yang tidak perlu. Tahan Shifttombol dan pilih dan lapisan. Klik kanan dan pilih Hapus untuk menghapusnya dari QGIS. Saat diminta untuk Hapus 2 entri legenda? , pilih Oke .Sampled Points2018_Gaz_ua_national
![image](https://user-images.githubusercontent.com/114122090/211199224-a5ece14c-f99a-4603-a838-aa3c641f64a2.png)

9.	Sekarang kita akan menggunakan lapisan kabupaten untuk mengambil sampel raster dan menghitung suhu rata-rata untuk setiap kabupaten. Temukan tl_2018_us_county.shpfile di Peramban QGIS seret ke kanvas.
![image](https://user-images.githubusercontent.com/114122090/211199227-6ff4cd5b-0b0c-4ec4-a5e2-ca8df3fa712e.png)

>Catatan
>Sebagian besar algoritme pemrosesan akan membaca lapisan masukan dan membuat lapisan baru. Tetapi algoritma Statistik Zona berbeda. Itu memodifikasi lapisan input >dan menambahkan atribut baru ke dalamnya. Itulah mengapa penting untuk meng-unzip file input terlebih dahulu. QGIS dapat memuat lapisan dari arsip zip secara >langsung, tetapi tidak dapat memodifikasi lapisan yang di-zip. Algoritme pemrosesan akan gagal jika tidak dapat memperbarui lapisan masukan.

10.	Lapisan baru tl_2018_us_countyakan dimuat ke panel Lapisan . Pergi ke Memproses ‣ Kotak Alat .
![image](https://user-images.githubusercontent.com/114122090/211199242-b03a32d3-aec1-4f07-841e-7f79c5d6a409.png)

11.	Cari dan temukan analisis Raster ‣ Algoritme statistik zona dan klik dua kali untuk meluncurkannya.
 ![image](https://user-images.githubusercontent.com/114122090/211199252-281f3df2-1094-46be-873f-1ac2a324bf2e.png)

12.	Pilih us.tmax_nohads_ll_20190501_floatsebagai layer Raster dan tl_2018_us_countysebagai layer Vector yang mengandung zones . Masukkan tmax_sebagai awalan kolom Keluaran . Klik … di sebelah Statistik untuk menghitung .
![image](https://user-images.githubusercontent.com/114122090/211199259-bf9946c5-903b-454d-96b0-300d552bb72b.png)

13.	Pilih hanya Meannilainya dan klik OK .
![image](https://user-images.githubusercontent.com/114122090/211199265-32750de3-f6fc-4edf-81ec-1d472facb59a.png)

14.	Klik Jalankan untuk memulai pemrosesan. Algoritme mungkin membutuhkan waktu beberapa menit untuk selesai. Klik Tutup .
![image](https://user-images.githubusercontent.com/114122090/211199270-c5b195b1-1974-4a18-8132-6949a5ff6baa.png)

15.	Seperti disebutkan sebelumnya, algoritma Zonal Statistics tidak membuat layer baru, tetapi memodifikasi layer zona. Klik kanan tl_2018_us_countylayer, dan pilih Open Attribute Table .
![image](https://user-images.githubusercontent.com/114122090/211199276-1bd5e552-0ce3-4fa8-85df-160f46a877e8.png)

16.	Kita akan melihat kolom baru bernama tmax_meanditambahkan ke tabel atribut. Ini berisi nilai suhu rata-rata yang diekstraksi di atas poligon untuk setiap fitur. Ada beberapa nilai nol karena kabupaten tersebut (milik Alaska, Hawaii, dan Puerto Riko) berada di luar jangkauan lapisan raster.
![image](https://user-images.githubusercontent.com/114122090/211199289-6cde49e4-ced0-4a1d-a423-780cee365999.png)


## Modul 6
# `Calculating Raster Area (QGIS3)`
file : [modul6.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Calculating%20Raster%20Area%20(QGIS3).qgz)
view : [modul6.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Calculating%20Raster%20Area%20(QGIS3).png)

## Prosedure
1.	Buka zip semua file yang diunduh. Di Browser , cari folder yang berisi file batas WDPA_WDOECM_Apr2022_Publicc_10744_shp-polygons.shpdan seret dan lepas ke kanvas QGIS.
![image](https://user-images.githubusercontent.com/114122090/211199422-0490f564-8ab8-41c5-a54b-a73600493753.png)

2.	Sekarang cari ubin raster penutup dunia ESA_WorldCover_10m_2020_v100_N24_E093_Map.tifdan jatuhkan ke kanvas QGIS.
![image](https://user-images.githubusercontent.com/114122090/211199428-22675d56-a301-4df3-aac4-f5582be8efd4.png)

3.	Kita sekarang akan memiliki layer vektor batas dan raster tutupan lahan dimuat di panel Layers . Mari potong raster tutupan lahan ke batas taman nasional. Pergi ke Processing ‣ Toolbox untuk membuka Processing toolbox. Cari dan temukan GDAL ‣ Ekstraksi raster ‣ Klip raster dengan algoritma lapisan topeng. Klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211199434-3c246efc-6903-4ae3-9e69-a2797969ab8b.png)

4.	Dalam dialog Clip Raster by Mask Layer , pilih ESA_WorldCover_10m_2020_v100_N24_E093_Maplayer sebagai Input layer dan WDPA_WDOECM_Apr2022_Publicc_10744_shp-polygonslayer sebagai Mask Layer . Masukkan -9999di Tetapkan nilai nodata yang ditentukan ke bagian pita keluaran.
![image](https://user-images.githubusercontent.com/114122090/211199441-5e7f9c2a-7e3c-4a44-ab51-e92a46cc4b84.png)

5.	Sekarang buka bagian Advanced Parameters dan pilih di Profile . Sekarang di bawah Clipped (mask) , klik dan pilih Save To File… . Masukkan nama file sebagai . Klik Jalankan .High Compression...worldcover_clipped.tif
![image](https://user-images.githubusercontent.com/114122090/211199450-587234c4-a93d-47c4-8a17-9b933c525980.png)

6.	Sekarang worldcover_clippedlayer akan dimuat di kanvas QGIS. Klik kanan ESA_WorldCover_10m_2020_v100_N24_E093_Maplayer dan pilih Hapus Lapisan…
![image](https://user-images.githubusercontent.com/114122090/211199463-8419e5fb-c0fe-468c-ac7d-4c70f130328d.png)

7.	Kedua layer kami masuk dalam CRS Geografis EPSG:4326. CRS ini memiliki satuan derajat dan tidak cocok untuk menghitung luas. Pertama-tama kita harus memproyeksikan ulang layer ke Projected CRS. untuk analisis regional seperti ini, UTM adalah pilihan yang baik untuk proyeksi CRS. Kami akan memproyeksikan ulang layer ke CRS untuk zona UTM lokal. Buka kotak alat Pemrosesan dan cari Vector general ‣ Algoritma lapisan proyeksi ulang . Klik dua kali untuk meluncurkannya.
![image](https://user-images.githubusercontent.com/114122090/211199471-57245391-2c45-475e-96ff-67b92d457e73.png)

8.	Dalam dialog Reproject Layer , pilih WDPA_WDOECM_Apr2022_Publicc_10744_shp-polygonslayer sebagai Input layer , klik tombol Select CRS di bawah Target CRS .
![image](https://user-images.githubusercontent.com/114122090/211199477-58674454-89ba-44f3-b36c-bddea02df66a.png)

9.	Area minat kami termasuk dalam Zona UTM 46N. Cari 46 N dan pilih CRS.WGS 84 / UTM zone 46N
 ![image](https://user-images.githubusercontent.com/114122090/211199486-a116a537-ac8d-4658-8faf-bdd4c4ef6db2.png)

>Catatan :
>Untuk mengetahui zona UTM mana untuk wilayah Anda, lihat situs web What UTM Zone am I.

10.	Di bagian Diproyeksikan ulang , klik ...dan pilih Simpan Ke File… . Masukkan nama sebagai nationalpark_reprojected.gpkg. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211199510-188d227b-0f4c-4e9e-a33f-76c2af16749c.png)

11.	Sekarang nationalpark_reprojectedlayer akan dimuat di kanvas. Klik kanan WDPA_WDOECM_Apr2022_Publicc_10744_shp-polygonslayer dan pilih Remove Layer… untuk menghapusnya. Sekarang kita akan memproyeksikan ulang layer raster. Di Kotak Alat Pemrosesan , cari dan temukan GDAL ‣ Proyeksi raster ‣ Warp (proyeksi ulang)
![image](https://user-images.githubusercontent.com/114122090/211199517-66947f16-cb45-429b-a8be-d32d89c39622.png)

12.	Dalam dialog Warp (Reproject) pilih worldcover_clippedsebagai Input layer , pilih CRS di Target CRS . Buka Advanced Parameters dan pilih di Profile .WGS 84 / UTM zone 46NHigh Compression
![image](https://user-images.githubusercontent.com/114122090/211199519-08e255d4-8702-4afd-93ef-7b5527fcddb4.png)

13.	Sekarang di bawah Diproyeksikan ulang , klik ...dan pilih Simpan Ke File… . Masukkan nama sebagai worldcover_reprojected.tif. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211199522-142d767b-3349-4dc6-b9f7-67e5e1d258c1.png)

14.	Sekarang worldcover_reprojectedlayer akan dimuat di kanvas, hapus worldcover_clippedlayer tersebut. Mari atur layer proyek ke zona UTM. Klik pada layer mana saja dan pilih Layer CRS ‣ Set Project CRS from Layer .
![image](https://user-images.githubusercontent.com/114122090/211199527-1a17bbe6-8c3a-4a1f-8eda-6dfccc2b56d0.png)

15.	Sekarang proyek CRS akan diperbarui. Mari atur simbologi lapisan raster sesuai nama kelas dan warna kumpulan data ESA WorldCover. Klik kanan pada worldcover_reprojectedlayer dan klik Properties…
![image](https://user-images.githubusercontent.com/114122090/211199535-e9aa6038-a09d-4513-8e61-f43755c8e3c2.png)

16.	Dalam dialog Layer Properties , pilih Symbology . Kita dapat melihat warna Layer divisualisasikan dalam nada putih-hitam. Untuk memperbaikinya, klik Style ‣ Load Style… . Telusuri dan pilih ESAWorldCover_ColorLegend.qmlfile.
![image](https://user-images.githubusercontent.com/114122090/211199541-7ff8e565-d20c-46ca-a20f-05d7e19ad0eb.png)

17.	Sekarang Kita dapat melihat warna simbol yang diperbarui dan deskripsi kelas. Klik Oke .
![image](https://user-images.githubusercontent.com/114122090/211199554-0cf27dbc-b651-4512-8720-7c7d687ae400.png)

18.	Perluas worldcover_reprojectedlayer di panel Layers untuk melihat legenda dengan deskripsi kelas yang benar.
![image](https://user-images.githubusercontent.com/114122090/211199567-570b171b-c6cd-435d-af7e-5a81905c4afc.png)

19.	Sekarang mari kita hitung luas untuk setiap kelas. Di kotak alat pemrosesan, cari dan temukan alat laporan nilai unik lapisan Raster . Klik dua kali untuk membukanya.
![image](https://user-images.githubusercontent.com/114122090/211199572-67a168ab-ec04-4983-9a3e-c937f872a454.png)

20.	Dalam dialog Raster Layer Unique Values Report , pilih Input layer sebagai worldcover_reprojected. Di bawah tabel Unique values klik ...dan pilih Save to File… . Masukkan nama sebagai class_areas.gpkg. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211199578-69ccc633-9916-4dc4-91eb-24a1fdc77516.png)

21.	Sekarang class_areaslayer akan ditambahkan ke panel Layers . Klik kanan pada layer dan klik Open Attribute Table . Kolom m2berisi luas untuk setiap kelas dalam meter persegi.
![image](https://user-images.githubusercontent.com/114122090/211199584-19248c7e-2e31-4252-ad30-44db9f1f8f44.png)

22.	Mari ubah luas menjadi kilometer persegi. Di Processing Toolbox , cari dan pilih Vector table ‣ Field Calculator .
![image](https://user-images.githubusercontent.com/114122090/211199586-b1a142f2-9538-495d-9c2f-d9dd3e78e2f1.png)

23.	Dalam dialog Kalkulator Bidangclass_areas , pilih lapisan di Lapisan Input . Masukkan nama Bidang sebagai area_sqkm. Di bidang Hasil, pilih Float. Di jendela Ekspresi , masukkan ekspresi di bawah ini. Ini akan mengubah sqmt menjadi sqkm dan membulatkan hasilnya menjadi 2 tempat desimal. Di bawah Terhitung klik ...dan pilih Simpan Ke File… . Masukkan nama sebagai class_area_sqkm.gpkg. Klik Jalankan .
```
round("m2"/ 1e6, 2)
```
![image](https://user-images.githubusercontent.com/114122090/211199603-4294917e-818a-4d8d-819c-a21ad5d3addc.png)

24.	Sekarang class_area_sqkmlayer akan dimuat di kanvas. Buka tabel Atribut dan periksa kolom area_sqkm yang baru ditambahkan . Anda akan melihat bahwa kolom Nilai berisi angka untuk setiap kelas. Agar hasilnya lebih mudah diinterpretasikan, Mari tambahkan juga deskripsi untuk setiap nomor kelas. Deskripsi kelas tersedia di Panduan Pengguna Produk ESA .
![image](https://user-images.githubusercontent.com/114122090/211199607-f65105a3-51fb-4e5c-a979-8f5552ceb5f0.png)

25.	Buka Field Calculator, dan pilih class_areas_sqkmlayer di Input Layer . Masukkan nama Bidang sebagai landcover, dalam jenis bidang Hasil , pilih String. Di jendela Expression masukkan ekspresi di bawah ini. Ekspresi ini menggunakan pernyataan CASE untuk menetapkan nilai berdasarkan beberapa kondisi. Di bawah Terhitung klik ...dan pilih Simpan Ke File… . Masukkan nama sebagai class_area_with_landcover.gpkg. Klik Jalankan .
```
CASE
WHEN "value" = 10 THEN 'Tree cover'
WHEN "value" = 20 THEN 'Shrubland'
WHEN "value" = 30 THEN 'Grassland'
WHEN "value" = 40 THEN 'Cropland'
WHEN "value" = 50 THEN 'Built-up'
WHEN "value" = 60 THEN 'Bare / sparse vegetation'
WHEN "value" = 70 THEN 'Snow and Ice'
WHEN "value" = 80 THEN 'Permanent water bodies'
WHEN "value" = 90 THEN 'Herbaceous wetland'
WHEN "value" = 95 THEN 'Moss and lichen'
WHEN "value" = 100 THEN 'Mangroves'
END
```
![image](https://user-images.githubusercontent.com/114122090/211199632-7e29173d-4cb9-40cb-a642-236eef45b9bb.png)

26.	Sekarang class_area_with_landcoverlayer akan dimuat di kanvas. Buka tabel Atribut. Kolom tutupan lahan akan berisi nama tutupan lahan terhadap setiap nilai tutupan lahan.
![image](https://user-images.githubusercontent.com/114122090/211199637-7703db11-e56d-4049-b1f5-13eb1744f330.png)

27.	Mari ekspor hasil ini sebagai file excel. Sebelum mengekspor, kami juga akan mengatur tabel dan menghapus kolom yang tidak diinginkan. Di Processing Toolbox , cari dan pilih Vector table ‣ Refactor fields .
![image](https://user-images.githubusercontent.com/114122090/211199659-f652a9cf-036f-4f34-a1b2-0cb5bda4375b.png)

28.	Dalam dialog Refactor Fieldsclass_area_with_landcover , pilih layer di Input Layer . Pilih semua kolom kecuali area_sqkm dan landcover , lalu klik Delete selected field .
![image](https://user-images.githubusercontent.com/114122090/211199666-99e79801-931c-489c-9414-398809e0fe3b.png)

29.	Kita juga dapat mengubah urutan bidang dalam tabel menggunakan tombol Pindahkan Bidang yang Dipilih . Setelah kita selesai mengedit, klik ...tombol di sebelah Refactored dan pilih Save To File… . Pilih sebagai format. Masukkan nama file sebagai dan klik Simpan . Dalam dialog Bidang Refaktor, klik Jalankan untuk menerapkan perubahan Anda.XLSX Files (*.xlsx)park_area_by_landcover.xlsx
![image](https://user-images.githubusercontent.com/114122090/211199727-0a6eba36-8a06-47a0-a157-4398e6686914.png)

30.	Hasilnya akan berupa spreadsheet dengan kolom landcover dan area_sqkm .


## Modul 7
# `Creating Heatmaps (QGIS3)`
file : [modul7.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Creating%20Heatmaps%20(QGIS3).qgz)
view : [modul7.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Creating%20Heatmaps%20(QGIS3).png)

## Prosedure
1.	Pertama-tama kita akan memuat layer peta dasar dari OpenStreetMap dan kemudian mengimpor data CSV. Di tab Browser , gulir ke bawah dan temukan bagian Ubin XYZ .
 ![image](https://user-images.githubusercontent.com/114122090/211199915-6bd38a0c-319b-4311-8726-c159232cd8f3.png)

2.	Bentangkan untuk melihat layer petak OpenStreetMap . Seret dan lepas ke kanvas utama. Selanjutnya kita akan memuat file CSV. Klik tombol Buka Pengelola Sumber Data .
![image](https://user-images.githubusercontent.com/114122090/211199941-87db68b2-2a4b-4070-a142-335ec0f228e4.png)

3.	Beralih ke tab Teks Dibatasi . Di sini kita akan mengimpor data kejahatan yang datang dalam file teks format CSV. Klik tombol … di sebelah Nama file dan ramban ke 2019-02-surrey-street.csvfile yang diunduh. Bidang X dan bidang Y di bagian Definisi Geometri akan diisi secara otomatis dengan kolom Longitudedan Latitude. Geometri CRS harus dibiarkan definisi default . Pastikan data terlihat benar di panel Sample data dan klik Add , diikuti oleh Close .EPSG:4326 - WGS 84
 ![image](https://user-images.githubusercontent.com/114122090/211199947-a983d4fe-e85e-4c77-9fa5-55619cbdd0d6.png)

4.	Kita akan melihat 2 lapisan - OpenStreetMapdan dimuat di panel Lapisan2019-02-surrey-street QGIS . Klik kanan layer dan pilih Zoom to Layer .2019-02-surrey-street
![image](https://user-images.githubusercontent.com/114122090/211199952-c8c0f4f8-9ff3-4ca9-84ad-460f63a765c0.png)

5.	Kita akan melihat layer poin insiden kejahatan dihamparkan pada peta dasar OpenStreetMap. Zoom dan Pan untuk menjelajahi data. Datanya cukup padat dan sulit untuk mengetahui di mana terdapat konsentrasi kejahatan yang tinggi. Di sinilah visualisasi peta panas akan berguna. Pilih 2019-02-surrey-streetlayer dan klik tombol panel Open the Layer Styling .
![image](https://user-images.githubusercontent.com/114122090/211199959-a1aae562-7ebe-493a-b87d-c65134a4b988.png)

6.	Pilih Heatmapsebagai penyaji di menu dropbox. Panel Layer Styling bersifat interaktif dan Anda dapat segera melihat efek perubahan Anda tercermin di kanvas. Lapisan sekarang akan ditampilkan di jalan warna skala abu-abu default.
![image](https://user-images.githubusercontent.com/114122090/211199968-c785e9e9-a500-4226-864d-765252761a4a.png)

7.	Peta panas biasanya dirender menggunakan jalur warna kuning ke merah atau putih ke merah di mana konsentrasi titik yang lebih tinggi menghasilkan lebih banyak panas . Klik menu dropdown Color ramp dan pilih Redscolor-ramp.
![image](https://user-images.githubusercontent.com/114122090/211199976-f007723a-8f51-44b5-9660-214badb4cc36.png)

8.	Selanjutnya kita harus memilih Radius . Parameter ini menentukan lingkungan melingkar di sekitar setiap titik di mana titik tersebut akan memiliki pengaruh. Nilai ini akan sangat bergantung pada jenis data masukan kita. Untuk data kami, anggap saja insiden kejahatan akan berdampak hingga 5 Kilometer dari lokasi. Perhatikan bahwa CRS proyek saat ini diatur ke sudut kanan bawah. CRS ini memiliki satuan meter, jadi kita harus menentukan meter sebagai radius. Parameter lain yang disembunyikan dari menu ini adalah bentuk Kernel . Ini adalah fungsi yang menentukan bagaimana pengaruh suatu titik harus tersebar pada radius yang diberikan. Perender Heatmap menggunakan fungsi untuk perhitungan ini. Ada jenis kernel lain seperti ,EPSG: 38575000QuarticTriangularUniform, Triweightdan Epanechnikovitu bisa ditentukan saat menggunakan metode pembuatan peta panas berbeda yang dijelaskan nanti di tutorial ini. Lihat posting ini untuk penjelasan dan panduan yang bagus untuk memilih radius dan bentuk kernel yang tepat.
![image](https://user-images.githubusercontent.com/114122090/211200002-7f41028d-24ab-49ae-8323-b1dd37d956bb.png)

9.	Visualisasi peta panas sudah siap. Kita bisa mengatur Opacity dari heatmap di bagian Layer Rendering di bagian bawah. Atur opacity agar Anda dapat melihat peta dasar beserta peta panasnya.60 %
![image](https://user-images.githubusercontent.com/114122090/211200012-97cb4893-2f06-47ec-8b07-80bad379f727.png)

10.	Untuk banyak jenis analisis, hanya mempertimbangkan kerapatan poin sudah cukup baik. Namun terkadang, Anda mungkin ingin memberikan kepentingan yang berbeda untuk setiap poin. Kejahatan yang lebih kejam seharusnya memiliki pengaruh lebih besar pada peta panas keluaran daripada perampokan. Demikian pula, kadang-kadang suatu titik dapat mewakili beberapa pengamatan di satu lokasi yang perlu diperhitungkan dalam analisis. Untuk melakukannya, Anda dapat menyediakan kolom bobot numerik opsional yang menentukan nilai untuk setiap titik. Mari tambahkan bidang bobot dan gunakan untuk menyempurnakan peta panas. Klik kanan 2019-02-surrey-streetlayer dan pilih Open Attribute Table .
![image](https://user-images.githubusercontent.com/114122090/211200020-b86d109f-4ee7-41ca-8c77-93d470d32f8b.png)

11.	Kita akan melihat bidang teks yang disebut dalam data masukan yang menjelaskan jenis kejahatan. Kita dapat menggunakan ini untuk mengkategorikan berbagai jenis kejahatan dan menetapkan bobot yang lebih tinggi untuk kejahatan yang lebih kejam.Crime type
![image](https://user-images.githubusercontent.com/114122090/211200029-45098367-9c36-4cb0-8888-b5b383769ce3.png)

12.	Klik Kalkulator lapangan terbuka .
![image](https://user-images.githubusercontent.com/114122090/211200036-3fa413e7-bfe2-4e33-8d50-499c73775360.png)

13.	Kami sekarang akan memasukkan rumus yang menggunakan dan menentukan nilai bobot. QGIS memiliki cara praktis untuk menambahkan bidang yang dihitung tersebut menggunakan Bidang Virtual . Bidang virtual disimpan dalam proyek QGIS dan tidak mengubah data sumber. Ini juga dihitung secara dinamis dan dapat digunakan di mana saja di QGIS seperti halnya nilai atribut lainnya. Masukkan sebagai nama bidang Keluaran dan setel jenis bidang Keluaran ke . Masukkan ekspresi berikut di editor Ekspresi . Di sini kita menggunakan pernyataan CASE untuk menetapkan nilai yang berbeda berdasarkan kondisi yang berbeda. Klik Oke .Crime typeweightWhole number (integer)
```
CASE
WHEN "Crime type" LIKE 'Violence%' THEN 10
WHEN "Crime type" LIKE 'Criminal%' THEN 5
ELSE 1
END
```
![image](https://user-images.githubusercontent.com/114122090/211200044-38637462-9d87-4ea6-b641-1711d1e0f2f3.png)

14.	Atribut baru akan ditambahkan untuk setiap fitur dengan nilai bobot yang sesuai.
![image](https://user-images.githubusercontent.com/114122090/211200058-cec1784a-8665-49b4-b6fb-ec7946be142a.png)

15.	Kembali ke panel Layer Styling , klik menu drop-down untuk Weight points by dan pilih bidang yang baru ditambahkan weight.
![image](https://user-images.githubusercontent.com/114122090/211200066-a0c2b363-8e2c-4b1b-b438-e6605ab6ec86.png)

16.	Kita akan melihat perubahan rendering peta panas untuk memperhitungkan parameter bobot. Tutup panel Layer Styling .
![image](https://user-images.githubusercontent.com/114122090/211200072-e6853b02-6800-4045-b93e-cb37e9da1778.png)

17.	Jika kita memerlukan visualisasi peta panas untuk disimpan sebagai lapisan raster permanen atau ingin menyesuaikan peta panas dengan opsi lanjutan seperti kernel yang berbeda atau radius dinamis, Anda dapat menggunakan Peta Panas (Estimasi Kepadatan Kernel) dari Kotak Alat Pemrosesan. Kami sekarang akan menggunakan algoritma ini. Pergi ke Memproses ‣ Kotak Alat .

18.	Sebelum kita dapat membuat peta panas, kita perlu memproyeksikan ulang data sumber ke CRS yang diproyeksikan. Karena jarak memainkan peran penting dalam perhitungan peta panas, tidak benar menggunakan CRS geografis. Cari dan temukan algoritma Vector general ‣ Proyeksi ulang layer .

19.	Pada dialog Reproject layer , klik tombol Select CRS untuk Target CRS . Cari dan pilih CRS. CRS yang diproyeksikan ini adalah pilihan yang baik untuk data di Inggris. Klik Jalankan .EPSG:27700 OSGB 1936 / British National Grid
![image](https://user-images.githubusercontent.com/114122090/211200105-7f85b848-c0e0-4ce2-9214-aede80a366eb.png)

20.	Layer baru bernama Reprojectedakan ditambahkan ke panel Layers . Hapus centang pada kotak di sebelah 2019-02-surrey-streetlapisan lama untuk menyembunyikannya.
![image](https://user-images.githubusercontent.com/114122090/211200117-8e1611af-8320-48b8-8d94-294ed9b2847b.png)

21.	Cari dan temukan algoritma Interpolation ‣ Heatmap (Kernel Density Estimation) .
![image](https://user-images.githubusercontent.com/114122090/211200124-64f09d5b-d5a4-4579-8482-a4debdb2f097.png)

22.	Pada dialog Heatmap (Kernel Density Estimation) , kita akan menggunakan parameter yang sama seperti sebelumnya. Pilih Radius sebagai 5000meter dan Berat dari bidang sebagai weight. Atur ukuran Piksel X dan Ukuran Piksel Y menjadi 50meter. Biarkan Kernel membentuk nilai default Quartic. Klik Jalankan .
![image](https://user-images.githubusercontent.com/114122090/211200136-13c7f2a9-b9eb-410e-b6d4-bbc06aee2b05.png)

>Catatan :
>Parameter Radius from field memungkinkan Anda menentukan radius pencarian dinamis untuk setiap titik. Ini dapat digunakan bersama dengan Bobot dari bidang untuk >memiliki kontrol yang lebih baik tentang bagaimana pengaruh setiap titik tersebar.

23.	Setelah pemrosesan selesai, lapisan raster baru bernama OUTPUTakan dimuat. Visualisasi default jelek karena menggunakan perender. Klik tombol panel Open the Layer Styling .Singleband gray
![image](https://user-images.githubusercontent.com/114122090/211200147-ff3a8ab7-117a-471a-886c-e9741a352632.png)

24.	Ubah render menjadi dan pilih ramp warna. Lapisan sekarang terlihat seperti visualisasi peta panas yang telah kita buat sebelumnya.Singleband PseudocolorReds
![image](https://user-images.githubusercontent.com/114122090/211200155-25856776-faf2-4090-92bd-df62582c3d8a.png)

>Catatan :
>Perhatikan bahwa OUTPUTlayer pada panel Layers memiliki legenda tetapi 2019-02-surrey-streetlayer tidak. Masalah umum saat menggunakan lapisan peta panas yang >dibuat dengan perender Peta Panas adalah kurangnya legenda. Katakanlah Anda ingin menggunakan peta panas di Tata Letak Cetak dan menambahkan legenda. Peta panas >raster yang dibuat dengan metode algoritme pemrosesan Peta Panas memungkinkan hal ini.


## Modul 8
# `Animating Time Series Data (QGIS3)`
file : [modul8.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Animating%20Time%20Series%20Data%20(QGIS3).qgz)
view : [modul8.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Animating%20Time%20Series%20Data%20(QGIS3).png)

## Prosedure
1.	Di Panel Peramban QGIS, temukan direktori tempat kita menyimpan data unduhan. Luaskan ne_10m_land.zipdan pilih ne_10m_land.shplayer. Seret layer ke kanvas. Selanjutnya, cari ASAM_shp.zipfile. Perluas dan pilih asam_data_download/ASAM_events.shplayer dan seret ke kanvas.
![image](https://user-images.githubusercontent.com/114122090/211200281-f3c34c6a-895f-472f-9967-c8d726472193.png)

2.	Setelah lapisan dimuat, kita dapat melihat masing-masing titik yang mewakili insiden lokasi pembajakan. Ada ribuan insiden dan sulit ditentukan dengan lebih banyak pembajakan. Daripada poin individual, cara yang lebih baik untuk memvisualisasikan data ini adalah melalui peta panas. Pilih ASAM_eventslayer dan klik tombol Open the layer Styling Panel di panel Layers . Klik tarik-turun.Single symbol
![image](https://user-images.githubusercontent.com/114122090/211200305-696be455-2e39-4fc3-b2bd-109216f80581.png)

3.	Di drop-down pemilihan penyaji, pilih Heatmappenyaji. Selanjutnya, pilih jalur Viridiswarna dari pemilih Jalur warna .

4.	Sesuaikan nilai Radius ke 5.0. Di bagian bawah, luaskan bagian Layer Rendering dan sesuaikan Opacity menjadi 75.0%. Ini memberikan efek visual yang bagus dari hotspot dengan lapisan tanah di bawahnya.
![image](https://user-images.githubusercontent.com/114122090/211200320-794da2c7-3cab-44a5-bfa7-75068e309aae.png)

5.	Sekarang mari kita animasikan data ini untuk menunjukkan peta insiden pembajakan tahunan. Klik kanan pada ASAM_eventlayer, dan pilih Properties.
![image](https://user-images.githubusercontent.com/114122090/211200330-b305a582-ae4a-49ad-ab43-bb0d03bb1859.png)

6.	Di kotak dialog Properti lapisan , pilih tab Temporal dan aktifkan dengan mengklik kotak centang..
![image](https://user-images.githubusercontent.com/114122090/211200336-c0e8cc17-467c-4c97-b38f-f34fde6269af.png)

7.	Data sumber berisi atribut dateofocc- yang mewakili tanggal terjadinya insiden. Ini adalah bidang yang akan digunakan untuk menentukan poin yang diberikan untuk setiap periode waktu. Pilih di menu Drop down Konfigurasi , sebagai Field .Single Field with Data/Timedateofocc
![image](https://user-images.githubusercontent.com/114122090/211200342-445d3ed2-8239-46bf-bd2c-e321d8deb4d0.png)

8.	Sekarang simbol jam akan muncul di sebelah nama layer. Klik pada (ikon Jam) dari Bilah Alat Navigasi Peta.Temporal Control Panel

9.	Klik pada (ikon putar) untuk mengaktifkan kontrol animasi. Klik Atur ke Rentang Penuh (ikon segarkan) di sebelah Rentang untuk secara otomatis mengatur rentang waktu agar cocok dengan kumpulan data.Animated Temporal Navigation
![image](https://user-images.githubusercontent.com/114122090/211200359-a68aedc9-d41a-4d4e-ae12-d0252c2cb653.png)

10.	Sekarang kita siap untuk melihat animasi. Atur Langkah lalu klik tombol Play untuk memulai animasi.1 Year
![image](https://user-images.githubusercontent.com/114122090/211200368-1ed904af-7888-4ea7-85ec-827e30d48b06.png)

>Catatan :
>Jika animasi terlalu cepat, kita dapat menyesuaikan frame rate dengan mengklik (ikon gerigi kuning) di pojok kanan atas panel Temporal Controller. Menurunkan frame >rate (frame per detik) akan memperlambat animasi.Temporal Settings 

11.	Akan sangat membantu juga untuk menampilkan label yang menunjukkan kerangka waktu saat ini di peta. Kita dapat melakukannya dengan menggunakan dekorasi Judul bawaan. Pergi ke Lihat ‣ Dekorasi ‣ Label Judul 
![image](https://user-images.githubusercontent.com/114122090/211200386-66db0c1b-01b9-4ceb-85f9-b680db6e8b42.png)

12.	Klik kotak centang untuk mengaktifkannya dan klik tombol dan masukkan ekspresi berikut untuk menampilkan tahun. Di sini variabel berisi stempel waktu irisan waktu saat ini yang ditampilkan. Jadi kita bisa menggunakan stempel waktu itu dan memformatnya untuk menampilkan tahun kejadian. Lihat Dokumentasi QGIS untuk detail tentang berbagai opsi pemformatan yang didukung untuk stempel waktu.Insert an Expression@map_start_time
```
format_date(@map_start_time, 'yyyy')
```
![image](https://user-images.githubusercontent.com/114122090/211200414-03dc7047-95ea-4ff0-94b2-7a35915f8d47.png)

13.	Pilih ukuran font sebagai 25, atur warna bilah latar belakang sebagai Whitedan atur transparansi menjadi 50%. Di Penempatan pilih . Sekarang klik Oke.Bottom Right
![image](https://user-images.githubusercontent.com/114122090/211200429-b1b58a78-252c-4718-a6b3-730a3a575e0e.png)

14.	Setelah parameter diatur sesuai, tahun akan ditampilkan seperti yang ditunjukkan. Untuk mengekspornya sebagai gambar dan mengonversinya sebagai GIF, pilih (ikon simpan) di jendela kontrol Temporal.Export Animation

15.	Klik pada ... direktori Output untuk memilih direktori tempat gambar akan disimpan.

16.	Pada Extent pilih Hitung dari Layer ‣ ne_10_land layer. Klik Simpan.

17.	Setelah ekspor selesai, Kita akan melihat gambar PNG untuk setiap tahun (total 18 gambar) di direktori keluaran.
 
18.	Sekarang mari buat GIF animasi dari gambar-gambar ini. Ada banyak opsi untuk membuat animasi dari masing-masing bingkai gambar. ezgif untuk alat yang mudah dan online. Kunjungi situs dan klik Pilih File dan pilih semua file .png. Setelah dipilih, klik Unggah dan buat GIF! tombol. Setelah dibuat, Kita dapat mengunduh GIF menggunakan tombol Simpan .

## Modul 9
# `Handling Invalid Geometries (QGIS3)`
file : [modul9.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Handling%20Invalid%20Geometries%20(QGIS3).qgz)
view : [modul9.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Handling%20Invalid%20Geometries%20(QGIS3).png)

## Prosedure
1.	Jelajahi India-States.zipfile yang diunduh di Peramban QGIS. Perluas dan seret India-States.shpfile ke kanvas peta.
 
2.	Kita akan melihat India-Stateslayer baru dimuat di panel Layers . Pergi ke Memproses ‣ Kotak Alat .
 
3.	Kami akan mencoba menjalankan algoritme pemrosesan pada lapisan input untuk mendemonstrasikan bagaimana geometri yang tidak valid dapat menyebabkan masalah selama operasi geoproses. Cari dan temukan Kartografi ‣ Algoritma pewarnaan topologi. Klik dua kali untuk meluncurkannya.
 
4.	Dalam dialog pewarnaan Topologi , pilih India-Statessebagai lapisan Input . Simpan semua parameter lain ke default dan klik Run .
 
>Catatan :
>Algoritma pewarnaan topologi mengimplementasikan algoritma untuk mewarnai peta sehingga tidak ada poligon yang berdekatan memiliki warna yang sama. Ini adalah >teknik kartografi yang berguna dan Teorema Empat Warna menyatakan bahwa 4 warna cukup untuk mencapai hasil ini. Ada versi teori graf dari torem ini yang disebut >teorema Lima warna . Implementasi algoritma QGIS didasarkan pada grafik sehingga dalam praktiknya Anda akan melihat bahwa lapisan poligon kompleks seperti ini akan >membutuhkan hingga 5 warna.

5.	Saat algoritme berjalan, kita akan melihat peringatan ditampilkan di tab Log . 1 fitur di lapisan input memiliki geometri yang tidak valid dan dilewati selama pemrosesan. Pengaturan default untuk menangani geometri yang tidak valid di Kotak Alat Pemrosesan terletak di Pengaturan ‣ Opsi ‣ Pemrosesan ‣ Umum ‣ Pemfilteran fitur tidak valid dan diatur ke . Ini adalah pengaturan default yang bagus, tetapi jika masukan Anda besar, Anda mungkin melewatkan peringatan ini dan mungkin tidak mengetahui bahwa fitur masukan telah dilewati. Anda mungkin ingin mengubah nilainya menjadi .Skip (ignore) features with invalid geometriesStop algorithm execution when a geometry is invalid
 
6.	Kembali ke jendela utama QGIS, kita akan melihat layer baru Coloredditambahkan ke panel Layers . Perhatikan bahwa layer baru tidak memiliki status yang geometrinya tidak valid. Kami sekarang tahu bahwa poligon keadaan tertentu ini memiliki geometri yang tidak valid tetapi kami tidak tahu apa penyebabnya. Kita dapat dengan mudah mengetahuinya. Cari dan temukan geometri Vektor ‣ Periksa algoritme validitas.
 
7.	Dalam dialog Check ValidityIndia-States , pilih sebagai Input layer . Pilih GEOSsebagai Metode . Klik Jalankan .
 
8.	Saat algoritme selesai diproses, Anda akan melihat 3 layer baru di panel Layers - , dan . Lapisan berisi lokasi dan deskripsi kesalahan geometri. Klik kanan dan pilih Open Attribute Table .Valid outputInvalid outputError outputError output
 
>Catatan :
>Dokumentasi QGIS memiliki artikel terperinci tentang Jenis pesan kesalahan dan artinya yang menjelaskan penyebab semua kesalahan.

9.	Kita akan melihat bahwa pesan kesalahannya adalah Ring self-intersection . Pilih baris dan klik tombol Zoom map to selected features . Saat memperbesar, Anda akan melihat akar penyebab galat geometri.
 
10.	QGIS hadir dengan algoritme bawaan untuk memperbaiki kesalahan geometri secara otomatis. Cari dan temukan geometri Vektor ‣ Perbaiki algoritma geometri . Klik dua kali untuk menjalankannya.
 
11.	Dalam dialog Fix GeometriesIndia-States , pilih sebagai Input layer dan klik Run .
 
12.	Layer baru akan ditambahkan ke panel Layers . Pada titik ini, kesalahan geometri telah diperbaiki dan Kita dapat menjalankan algoritme pemrosesan apa pun pada lapisan ini tanpa masalah. Tetapi kita dapat melihat bahwa masih ada celah antara poligon yang berdekatan yang tidak terduga dan dapat menyebabkan kesalahan topologi di kemudian hari. Kami juga dapat memperbaikinya dengan mengedit poligon. Klik tombol Toggle Editing pada Digitizing Toolbar . Pilih Vertex Tool dan dari drop-down pilih .Fixed GeometriesVertex Tool (Current Layer)
 
13.	Saat alat vertex aktif, klik pada vertex untuk memilihnya. Kita dapat menekan Deletetombol untuk menghapus simpul atau menyeretnya untuk memindahkannya. Kita dapat memindahkan simpul sehingga tepi poligon sekarang menyentuh poligon yang berdekatan.
 
14.	Setelah selesai, klik tombol Toggle Editing lagi dan klik Save .
 
15.	Mari jalankan lagi algoritma Kartografi ‣ Pewarnaan topologi .
 
16.	Dalam dialog Pewarnaan Topologi , pastikan Anda memilih sebagai lapisan Input . Klik Jalankan .Fixed Geometries
 
17.	Kita akan melihat algoritme berjalan tanpa kesalahan dan lapisan baru Coloredakan ditambahkan ke panel Lapisan . Perhatikan bahwa algoritme tidak mewarnai lapisan dengan sendirinya, tetapi bekerja dengan menambahkan kolom baru yang dipanggil color_idke setiap poligon yang dapat digunakan untuk menetapkan warna unik yang berbeda dari poligon yang berdekatan. Pilih Coloredlayer dan klik tombol Open the Layer Styling Panel .
 
18.	Pilih Categorizedpenyaji dan kolom color_id sebagai Value . Klik Klasifikasikan . Kita sekarang akan melihat peta berwarna sehingga poligon yang berdekatan memiliki warna yang berbeda.


