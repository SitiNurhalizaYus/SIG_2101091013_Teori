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

12. Kembali ke jendela utama QGIS. Sekarang Anda akan melihat subset yang lebih kecil dari poin yang dipilih. Ini adalah hasil dari kueri kedua dan menunjukkan semua tempat dari kumpulan data yang merupakan ibu kota negara serta memiliki populasi lebih dari 1 juta.
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

2. Dialog Select Transformation akan meminta untuk mengkonversi dari EPSG:4269 ke EPSG:4326 . Dialog ini menyajikan beberapa transformasi untuk mengkonversi antara koordinat antara proyeksi tersebut. Tinggalkan pilihan ke pilihan default dan klik OK .
![image](https://user-images.githubusercontent.com/114122090/211183408-c9275ab0-4f80-4b18-9d33-cf40fbaa1223.png)

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

10. Kolom ID tersebut berisi id unik untuk setiap record, yang dapat digunakan untuk menggabungkan tabel ini dengan tl_2019_06_tractlayer. Jika  membandingkan nilai IDdengan GEOIDkolom dari tl_2019_06_tract.  akan melihat bahwa itu diawali dengan 1400000US . Untuk menggabungkan kedua tabel ini dengan sukses, nilainya harus sama persis. Mari kita hapus awalan ini dan tambahkan kolom baru dengan 11 karakter terakhir yang berisi nilai yang sama persis.

11. Untuk membuat kolom baru dengan 11 digit terakhir, buka Processing Toolbox dengan masuk ke Processing ‣ Toolbox , dan cari dan temukan tabel Vector ‣ Algoritma kalkulator lapangan.

12. Dalam dialog Kalkulator bidang ACST5Y2019.S0101 , pilih sebagai Input layer , masukkan Nama bidang geoid , dan pilih Jenis Bidang Hasil . Sekarang cari dalam ekspresi. Kita dapat menggunakan fungsi ini untuk mengekstrak bagian yang diperlukan dari bidang id.stringsubstr

13. Masukkan ekspresi di bawah ini. Kami menggunakan fungsi substr dan mengekstrak nilai dari posisi -11 (nilai negatif dihitung dari akhir). Hasil akhir dapat dilihat di bagian Pratinjau . Klik Jalankan.

```
substr("id", -11)
```

14. Sekarang layer baru Calculated akan dimuat di kanvas, mari kita periksa tabel atribut. Kolom baru geoiddengan nilai yang dapat dicocokkan dengan risalah pencacahan akan hadir.

15. Untuk membuat gabungan tabel, buka Processing Toolbox dengan masuk ke Processing ‣ Toolbox , dan cari dan temukan atribut Vector general ‣ Join dengan algoritma nilai bidang.

16. Dalam dialog Gabungkan atribut menurut nilai bidang tl_2019_06_tract , pilih sebagai lapisan Input dan GEOIDsebagai bidang Tabel . Pilih Calculatedsebagai Input layer 2 dan geoidsebagai Table field 2 . Di bawah bidang Layer2 untuk menyalin , klik pada ....

17. Periksa , dan . Klik Oke .Geographic Area NameEstimate!!Total!!Total population geoid

18. Centang catatan Buang yang tidak dapat digabungkan . Ini akan menghilangkan catatan tambahan apa pun di tabel populasi. Klik tombol ... di bawah layer gabungan untuk memilih lokasi file keluaran dan pilih .Save to File...

19. Beri nama geopackage keluaran sebagai california_total_population.gpkg. Klik Jalankan .

20. Setelah pemrosesan selesai, verifikasi bahwa algoritme berhasil jika semua fitur 8057 digabungkan. Klik Tutup .

21. Kita akan melihat layer baru california_total_populationdimuat di panel Layers . Pada titik ini, bidang dari file CSV digabungkan dengan lapisan saluran sensus. Sekarang setelah kita memiliki data kependudukan di lapisan sensus, kita dapat menatanya untuk membuat visualisasi distribusi kepadatan penduduk. Klik tombol Buka Panel Penataan Lapisan .

22. Di panel Layer Styling , pilih Graduateddari menu drop-down. Saat kami ingin membuat peta kepadatan populasi, kami ingin menetapkan warna berbeda untuk setiap fitur saluran sensus berdasarkan kepadatan populasi. Kami memiliki populasi di kolom Estimasi!!Total!!Total populasi , dan area area di ALAND . Klik tombol Ekspresi , untuk menghitung persentase jumlah penduduk pada setiap saluran pencacahan.

>Catatan
>Saat membuat peta tematik (choropleth) seperti ini, penting untuk menormalkan nilai yang petakan. Memetakan jumlah total per poligon tidak benar. Penting >untuk menormalkan nilai-nilai yang dibagi dengan luas. Jika  menampilkan total seperti kejahatan,  dapat menormalkannya dengan membaginya dengan total >populasi, sehingga memetakan tingkat kejahatan dan bukan >>kejahatan. Belajarlah lagi


23. Masukkan ekspresi berikut untuk menghitung kepadatan populasi. Area fitur diberikan dalam kilometer persegi. Kami kemudian mengubahnya menjadi meter persegi dengan mengalikan dengan 1000000dan menghitung kepadatan penduduk dengan rumus Penduduk/Luas . Pratinjau hasilnya dan klik OK .

```
1000000 * ("Estimate!!Total!!Total population"/"ALAND")
```

24. Di Panel Penataan Lapisan , klik klasifikasikan dan masukkan kelas sebagai 10.

25. Klik pada jalur warna untuk memilih jalur warna RdYlGn.

26. Kerapatan yang lebih tinggi lebih penting, mari kita tetapkan warna hijau untuk kerapatan rendah dan merah untuk area dengan kerapatan tinggi. Klik pada jalur warna dan pilih Balikkan Jalur Warna .

27. Sekarang kami memiliki visualisasi informasi kepadatan populasi yang sangat baik di California. Untuk membuatnya lebih baik, mari kita buat batas setiap saluran sensus transparan. Klik pada tab Simbol.

28. Klik pada warna Stroke dan klik .Transparent stroke

29. Tempat sampah dapat disesuaikan, klik pada Nilai ini akan memunculkan dialog untuk memasukkan nilai batas atas dan bawah.

30. Setelah  puas menutup panel styling Layer. Kami sekarang memiliki visualisasi informasi kepadatan populasi yang terlihat bagus di California.

## Modul 2
# `Performing Spatial Joins (QGIS3)`
file : [modul2.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.qgz)
view : [modul2.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.png)



## Modul 3
# `Performing Spatial Joins (QGIS3)`
file : [modul3.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.qgz)
view : [modul3.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/perfomating%20spatial%20joins.png)


## Modul 4
# `Nearest Neighbor Analysis (QGIS3)`
file : [modul4.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Nearest%20Neighbor%20Analysis%20(QGIS3).qgz)
view : [modul4.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Nearest%20Neighbor%20Analysis%20(QGIS3).png)


## Modul 5
# `Sampling Raster Data using Points or Polygons (QGIS3)`
file : [modul5.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Sampling%20Raster%20Data%20using%20Points%20or%20Polygons%20(QGIS3).qgz)
view : [modul5.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Sampling%20Raster%20Data%20using%20Points%20or%20Polygons%20(QGIS3).png)


## Modul 6
# `Calculating Raster Area (QGIS3)`
file : [modul6.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Calculating%20Raster%20Area%20(QGIS3).qgz)
view : [modul6.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Calculating%20Raster%20Area%20(QGIS3).png)


## Modul 7
# `Creating Heatmaps (QGIS3)`
file : [modul7.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Creating%20Heatmaps%20(QGIS3).qgz)
view : [modul7.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Creating%20Heatmaps%20(QGIS3).png)


## Modul 8
# `Animating Time Series Data (QGIS3)`
file : [modul8.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Animating%20Time%20Series%20Data%20(QGIS3).qgz)
view : [modul8.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Animating%20Time%20Series%20Data%20(QGIS3).png)


## Modul 9
# `Handling Invalid Geometries (QGIS3)`
file : [modul9.qgz](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Handling%20Invalid%20Geometries%20(QGIS3).qgz)
view : [modul9.png](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/2ffd583730d50424557a3ef44fa0c97bae8a5554/Handling%20Invalid%20Geometries%20(QGIS3).png)
