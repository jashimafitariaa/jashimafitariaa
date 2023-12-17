## 1.1 Latar Belakang

   Shalat adalah ibadah yang diwajibkan kepada tiap-tiap muslim.Bgitu juga dengan Al-quran. Al-quran adalah kalam allah yang diturunkan kepada Rasulullah SAW . Setiap Muslim mempunyai kewajiban untuk membaca,mempelajari dan mengamalkannya. Namun banyak sekali beberapa muslim tidak mengerjakan kewajiban tersebut dengan alasan sedaang berada di jalan sehingga tidak tahu jam sholat di daerah tersebut,lupa membawa Al-quran, ribet jika harus membawa Al-quran dan tidak mendapat Al-quran, dan lain sebagainya. Oleh sebab itu, saya berniat untuk membuat aplikasi Al-quran digital untuk mempermudah para muslim melaksanakan kewajiban tersebut dimana pun dan kapan pun. 
    
## 1.2 Deskripsi Teknologi Informasi  

   AestQuran adalah sebuah aplikasi yang berisikan ayat-ayat suci Al-quran dan jadwal sholat untuk setiap daerah di indonesia,dengan desain yang kekinian sehingga pengguna dapat menggunakan aplikasi dengan nyaman dan tidak ketinggalan jaman. Ketika pengguna membuka aplikasi ini, terdapat dua tombol yaitu membaca Al-quran dan jadwal sholat, kemudian pilihlah salah satu tombol yang pengguna butuhkan,lalu search surah yang ingin dibacakan, kemudian pengguna dapat membaca ayat, latin, arti dan audio perayat dari surah yang dicari, atau jika memilih tombol jadwal sholat maka search daerah yang ingin diketahui jadwal sholatnya. Setelah itu, pengguna akan melihat hasil yang dicarinya, kemudian pengguna dapat membuat alarm sholat sesuai waktu daerah yang dipilih.

## 1.3 Branding

  Merk : AestQuran
  Tagline : There is no reason to not worship
  Campaign : membuat aplikasi yang berisikan ayat-ayat suci al-quran dan jadwal sholat bagi tiap daerah
  Target User : 
      - Usia 7+
      - Penghafal al-quran yang ingin mengulang hafalannya dengan mudah dimana pun
      - Orang yang ingin mengaji kapan pun dengan mudah
      - Para traveller yang sering keluar daerah

   User experince theme:
      - Mudah
      - Sederhana
      - Menarik
      - Warna : Earth Tone / tortilla colour / peanut colour

## 2. User Story

  Sebagai | Saya ingin | Sehingga | Level Prioritas 
  ---|---|---|---
  Pengguna | melihat jadwal sholat | dapat mengetahui jadwal sholat daerah tersebut |⭐⭐⭐⭐⭐
  Pengguna | membuat alarm sholat | mengurangi ketidaktepatan waktu dalam melaksanakan sholat|⭐⭐⭐⭐⭐
  Pengguna | membaca al-quran | dapat membaca membaca al-quran dimanapun | ⭐⭐⭐⭐⭐
  Pengguna | membaca bahasa latinnya | dapat membaca Al-quran dengan benar bagi pemula| ⭐⭐⭐⭐⭐
  Pengguna | membaca artinya | dapat memahami arti ayat-ayat Al-quran |⭐⭐⭐⭐⭐
  Owner | menuliskan bahasan latin | anak- anak atau pemula bisa membacanya dengan mudah | ⭐⭐⭐⭐
  Owner | menampilkan audio per ayat | memudahkan anak-anak atau pemula untuk memahami baacaannya | ⭐⭐⭐⭐⭐
  Owner | audio yang diberikan dari berbagai qori | pengguna bisa memilih yang menurutnya lebih dia sukai | ⭐⭐⭐⭐⭐
  Owner | mencinptakan alarm sholat | memudahkan para muslim untuk mengikuti sholat berjamaah di masjid | ⭐⭐⭐⭐⭐
  Owner | membuat alarm sholat | meminimalisir keterlambatan dalam melakukan sholat |⭐⭐⭐⭐⭐
  owner | mempermudah pengguna | pengguna senang untuk mengaji dan sholat | ⭐⭐⭐⭐⭐
  Owner | mempermudah pengguna | pengguna tidak merasa bahwa ibadah itu ribet | ⭐⭐⭐⭐⭐
  
   
  
  
  

## 3. Struktur Data

[![](https://mermaid.ink/img/pako:eNqNkstOwzAQRX_F8rr-gSwRK8QC1G02t7Ebm_oRObaqKu2_M46j0hQKZJFIc8_ceWQm3gWpeMNVfDboI1zrGT31PSjf99njfBYiTOw19Mazhu3yARWokUV-QgfxniMK0_I3Y41u-Q_gC-QRVmx1sEjEDjM5czceC-yUK7IYKagJHo2FPsBXfq2WlPPEJPYJ8ZpxY79SvgrsSlWc5mZGpPw3TI3Pq5AZ_3COyRCbTP87nEsQWZogBhWXfpQbkGraem_LsGRGrBb1cz_urbTejofDg6Rv-pL5UeuPGlRfWEPAEYeUWeMU4eRx_S8P0eu0vqdF07gW0REX7i3Zzoy0rmrHN9yp6GAknepUYi1PWjnV8nJqUu2RbSrHdiEUOYXtyXe8STGrDc-DRFLLffNmDzuqyydy2gQL?type=png)](https://mermaid.live/edit#pako:eNqNkstOwzAQRX_F8rr-gSwRK8QC1G02t7Ebm_oRObaqKu2_M46j0hQKZJFIc8_ceWQm3gWpeMNVfDboI1zrGT31PSjf99njfBYiTOw19Mazhu3yARWokUV-QgfxniMK0_I3Y41u-Q_gC-QRVmx1sEjEDjM5czceC-yUK7IYKagJHo2FPsBXfq2WlPPEJPYJ8ZpxY79SvgrsSlWc5mZGpPw3TI3Pq5AZ_3COyRCbTP87nEsQWZogBhWXfpQbkGraem_LsGRGrBb1cz_urbTejofDg6Rv-pL5UeuPGlRfWEPAEYeUWeMU4eRx_S8P0eu0vqdF07gW0REX7i3Zzoy0rmrHN9yp6GAknepUYi1PWjnV8nJqUu2RbSrHdiEUOYXtyXe8STGrDc-DRFLLffNmDzuqyydy2gQL)
## 4. Arsitektur Sistem

    Database - SQL --> Aplikasi - Java

## 5. Teknologi, Library, dan Framework

    Teknologi : - React Native
                - SQL

    Library : -

    Framework : -

## 6. Desain User Experience dan User Interface
 Halaman Login : https://ibb.co/k87BDK8
 Halaman pertama : https://ibb.co/rcwfByP
 Halaman kedua : https://ibb.co/Myzryqr
 Halaman ketiga : https://ibb.co/dpQXdZB
 Halaman keempat : https://ibb.co/g7pWJNH


## 7. Demonstrasi Video

  Video YouTube (belum)

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

  Video YouTube (belum)

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrogramman berperan dalam produk teknologi informasimu?

   Video YouTube (belum)

## 10. Bagaimana metode pengembangan perangkat lunak/software development life cycle berperan dalam produk teknologi informasimu?

   Video YouTube (belum)

## 11. Bagaimana database/sistem basis data berperan dalam produk teknologi informasimu?

   Video YouTube (belum)


  

 
 


    
 
  


  
