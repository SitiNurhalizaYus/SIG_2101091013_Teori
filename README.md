# SIG-TEORI-2101091013
Tutorial Latihan :
- [Modul 1](README.md#modul-1) Membuat Peta (QGIS3)
- [Modul 2](README.md#modul-2) Bekerja dengan Atribut (QGIS3)
- [Modul 3](README.md#modul-3) Mengimpor file Spreadsheet atau CSV (QGIS3)
- [Modul 4](README.md#modul-4) Vektor Dasar (QGIS3)
- [Modul 5](README.md#modul-5)

## Modul 1
# `Membuat Peta (QGIS3)`
file : [modul1.qpt](https://github.com/SitiNurhalizaYus/SIG_2101091013_Teori/blob/05819c8059b8f05da157974393e37be8fa84bc17/kota_padang_2101091013.qpt)
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
## Procedure
1. Buka zip kedua kumpulan data ke folder di komputer . Di Panel Browser QGIS, temukan direktori tempat  mengekstrak data. Perluas ne_10m_landfolder dan pilih ne_10m_land.shplayer. Seret layer ke kanvas.

2. Selanjutnya akan mendapatkan layer baru yang ne_10m_land ditambahkan ke panel Layers . Basis data pembangkit listrik global hadir sebagai file CSV, jadi kita perlu mengimpornya. Klik tombol Buka Pengelola Sumber Data pada Bilah Alat Sumber Data .  juga dapat menggunakan pintasan keyboard. Ctrl + L

3. Di jendela Pengelola Sumber Data , alihkan ke tab Teks Dibatasi . Klik tombol ... di sebelah Nama file dan telusuri direktori tempat  mengekstrak globalpowerplantdatabasev120.zipfile. Pilih global_power_plant_database.csv. QGIS akan otomatis mendeteksi bidang pembatas dan geometri. Biarkan Geometri CRS ke nilai default . Klik Tambah diikuti oleh Tutup .EPSG:4326 - WGS84

4. Sebuah layer baru global_power_plant_databaseakan ditambahkan ke panel Layers dan  akan melihat titik-titik yang mewakili pembangkit listrik di kanvas. Sekarang kita siap untuk menata kedua lapisan ini. Klik tombol Open the Layer Styling panel di bagian atas panel Layers .

5. Panel Layer Styling akan terbuka di sebelah kanan. Pilih ne_10m_landlapisannya terlebih dahulu. Ini akan menjadi lapisan dasar kami sehingga kami dapat menjaga gaya minimalis agar tidak mengganggu. Klik dan gulir ke bawah. Pilih warna Fill sesuai keinginan . Klik drop-down di sebelah Stroke color dan pilih . Ini akan mengatur garis besar poligon tanah menjadi transparan.  akan melihat hasil seleksi  diterapkan segera ke lapisan.Simple fillTransparent Stroke

6. Selanjutnya pilih global_power_plant_databaselapisan. Klik dan gulir ke bawah. Pilih pen segitiga.Simple marker

7. Gulir ke atas dan pilih warna Isi sesuai keinginan . Teknik kartografi yang berguna adalah memilih versi warna isian yang sedikit lebih gelap sebagai warna Stroke . Daripada mencoba memilihnya secara manual, QGIS menyediakan ekspresi untuk mengontrol ini dengan lebih tepat. Klik tombol Penimpaan yang ditentukan data dan pilih Edit .

8. Masukkan ekspresi berikut untuk mengatur warnanya menjadi 30% lebih gelap dari warna isian dan klik OK .
darker(@symbol_color, 130)

>Catatan
>Perhatikan bahwa ekspresi ini tidak tergantung pada warna isian yang  pilih.  akan melihat bahwa ini sangat berguna dalam langkah-langkah berikut di mana secara >otomatis mengatur warna batas berdasarkan warna isian yang disediakan.

9. Kita akan melihat bahwa tombol Override yang ditentukan Data di sebelah Warna Stroke telah berubah menjadi kuning - menunjukkan bahwa properti ini dikendalikan oleh override. Render simbol tunggal dari lapisan pembangkit listrik tidak terlalu berguna. Itu tidak menyampaikan banyak informasi kecuali lokasi pembangkit listrik. Mari kita gunakan penyaji yang berbeda untuk membuatnya lebih berguna. Klik drop-down Symbology dan pilih Categorizedrenderer.

10. Lapisan tersebut global_power_plant_databaseberisi atribut yang menunjukkan bahan bakar utama yang digunakan di setiap pembangkit listrik. Kita dapat membuat gaya di mana setiap jenis bahan bakar yang unik ditampilkan dalam warna yang berbeda. Pilih primary_fuelsebagai Kolom . Klik Klasifikasi .  akan melihat beberapa kategori dan rendering peta berubah sesuai.

11. Meskipun tampilan Terkategori berguna, lapisan ini berisi terlalu banyak kategori untuk dapat ditafsirkan peta secara bermakna. Pendekatan yang lebih baik adalah mengelompokkan jenis kategori bahan bakar tertentu dan mengurangi jumlah kelas. Mari kita coba buat 3 kategori - Bahan bakar terbarukan , Bahan bakar tidak terbarukan , dan Lainnya . Pilih Rule-basedpenyaji. Pilih semua kecuali satu aturan dengan menahan Ctrltombol dan mengklik setiap baris. Setelah dipilih, klik tombol Hapus aturan yang dipilih untuk menghapusnya.

12. Pilih aturan yang tersisa dan klik Edit aturan saat ini .

13. Masukkan sebagai Label . Klik tombol Ekspresi di sebelah Filter .Renewable fuel

14. Dalam dialog Pembuat String Ekspresi , masukkan ekspresi berikut dan klik OK . Di sini kami mengelompokkan beberapa kategori energi terbarukan ke dalam satu kategori.
      "primary_fuel" IN ('Biomass', 'Geothermal', 'Hydro', 'Solar', 'Wind', 'Storage', 'Wave and Tidal')
      
15. Gulir ke bawah dan klik Pen sederhana . Pilih warna Isi yang sesuai . Setelah selesai, klik tombol Kembali .

16. Kita akan melihat satu aturan diterapkan pada lapisan untuk kategori bahan bakar terbarukan . Klik kanan baris dan pilih Salin . Klik kanan lagi dan pilih Tempel .

17. Salinan aturan yang ada akan ditambahkan. Pilih baris yang baru ditambahkan dan klik Edit aturan saat ini .

18. Masukkan sebagai Label . Klik tombol Ekspresi di sebelah Filter .Non-renewable fuel

19. Dalam dialog Pembuat String Ekspresi , masukkan ekspresi berikut dan klik OK .
      "primary_fuel" IN ('Coal', 'Gas', 'Nuclear', 'Oil', 'Petcoke')

20. Gulir ke bawah dan klik Pen sederhana . Pilih warna Isi yang sesuai . Setelah selesai, klik tombol Kembali .

21. Ulangi proses Copy/Paste untuk menambahkan aturan ketiga. Pilih dan klik Edit aturan saat ini .

22. Masukkan Othersebagai Label . Pilih Else - Catch all untuk fitur lain daripada Filter . Ini akan memastikan bahwa setiap kategori yang terlewatkan dalam 2 aturan sebelumnya, akan ditata oleh aturan ini. Gulir ke bawah dan klik Pen sederhana . Pilih warna Isi yang sesuai . Setelah selesai, klik tombol Kembali .

23. Pengkategorian ulang selesai sekarang.  akan melihat tampilan yang jauh lebih bersih yang menunjukkan distribusi sumber bahan bakar terbarukan vs. tidak terbarukan yang digunakan oleh pembangkit listrik dan distribusinya di seluruh negara. Namun ini tidak memberikan gambaran yang lengkap. Kita bisa menambahkan variabel lain ke styling. Daripada menampilkan semua pen dengan ukuran seragam, kami dapat menunjukkan ukuran yang proporsional dengan kapasitas pembangkit listrik masing-masing pembangkit. Teknik kartografi ini disebut pemetaan Multivariat . Klik kanan aturan dan pilih Ubah Ukuran .Renewable fuel

24. Klik tombol Penggantian yang ditentukan data di sebelah Ukuran . Pilih Sunting .

25. Karena kapasitas pembangkit listrik sangat bervariasi di antara kumpulan data kami, cara yang efektif untuk mendapatkan rentang ukuran yang kecil adalah dengan menggunakan log10fungsi.  dapat bereksperimen dengan ekspresi yang berbeda untuk sampai pada apa yang terbaik untuk visualisasi pilihan . Masukkan ekspresi berikut dan klik OK .
      log10("capacity_mw") + 1
      
26. Ulangi proses yang sama untuk aturan lainnya.

27. Setelah puas,  dapat menutup panel Layer Styling .

28. Melihat visualisasi akhir kami,  dapat langsung melihat pola di dataset. Sebagai contoh, di Eropa terdapat lebih banyak pembangkit listrik yang menggunakan sumber energi terbarukan, tetapi kapasitasnya lebih rendah daripada pembangkit yang menggunakan sumber energi tidak terbarukan.


## Modul 5
#
