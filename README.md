# Otomasi_API

* Membuat Kerangka Otomasi API dengan Java dan otomatiskan beberapa kasus.

* Menggunakan framework testing TestNG.

* Dengan struktur :

- src
  - main
    - java
      - api
        - APIClient.java (untuk memvalidasi kode status response)
      - utilities
        - TestUtilities.java (untuk membaca data pengujian dari file dan untuk menyiapkan lingkungan pengujian)
  - test
    - java
      - tests
        - APITestCases.java
      - TestRunner.java (untuk melaksanakan tes dan menghasilkan laporan pengujian)
    - resources
      - testng.xml
     


* Pada APITestCases.java yang berisikan beberapa test cases terdiri dari :

  -Tes positif: uji API untuk respons yang benar dengan input yang benar.

  -Tes negatif: uji API untuk respons yang salah dengan input yang salah, seperti mengirim tipe data yang salah atau kolom 
  wajib diisi tidak ada.

  -Tes batas: uji API untuk edge cases yang berbeda, seperti nilai maksimum atau minimum untuk parameter masukan.

* Cara melakukan testing adalah :
 Running code pada TestRunner.java
