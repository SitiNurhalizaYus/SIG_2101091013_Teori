# SIG-TEORI-2101091013
Tutorial Latihan :
- [Modul 1](README.md#modul-1) Membuat Peta (QGIS3)
- [Modul 2](README.md#modul-2) Bekerja dengan Atribut (QGIS3)
- [Modul 3](README.md#modul-3) Mengimpor file Spreadsheet atau CSV (QGIS3)
- [Modul 4](README.md#modul-4) Vektor Dasar (QGIS3)
- [Modul 5](README.md#modul-5) Menghitung Panjang Garis dan Statistik (QGIS3)
- [Modul 7](README.md#modul-7) Mosaik dan Kliping Raster (QGIS3)

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

28. Setelah Anda puas dengan peta, Anda dapat mengekspornya sebagai Gambar, PDF, atau SVG. Untuk tutorial ini, mari kita ekspor sebagai gambar. Klik Tata Letak Ekspor sebagai Gambar .

29. Simpan gambar dalam format yang Anda sukai. Di bawah ini adalah gambar PNG yang diekspor.
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


## Modul 7
# `Mosaik dan Kliping Raster (QGIS3)`
file : [modul7.qgz]()

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

11. Dalam dialog Clip Raster by Mask Layer , tetapkan OUTPUTsebagai Input Layer . Pilih ne_10m_admin_0_countriessebagai layer Mask , dan centang kotak Selected features only . Masukkan 0.0000sebagai Menetapkan nilai nodata yang ditentukan ke band keluaran . Seperti sebelumnya, pilih sebagai Profile . Klik Jalankan .High compression
![17](https://user-images.githubusercontent.com/114122090/201807576-df217e22-c121-42e2-8dfc-1ba7f16a8c4e.png)
![18](https://user-images.githubusercontent.com/114122090/201807372-a054900c-2785-4804-abec-afb119dca2b7.png)
![19](https://user-images.githubusercontent.com/114122090/201807373-2e6fb9d2-cc50-4b6a-9b53-58952f43048c.png)
![20](https://user-images.githubusercontent.com/114122090/201807380-7524c574-5785-4d8d-a92f-05fe1d627636.png)

12. Sebuah layer baru OUTPUTakan ditambahkan ke panel Layers . Pada titik ini, mungkin sulit untuk melihat hasilnya karena kita memiliki terlalu banyak lapisan tumpang tindih yang terlihat. Klik tombol Kelola Tema Peta di panel Lapisan dan pilih .Hide All Layers

13. Nyalakan hanya OUTPUTlayer terbaru dan beri gaya dengan Hilshadeperender seperti yang dilakukan sebelumnya

14.  Lapisan elevasi keluaran gabungan dan subset untuk Sri Lanka sudah siap.
