UAS WEB PEMOGRAMAN
RIFKI ARIF RAHMAN
I.2210002


1. {
  "universitas": "Djuanda",
  "prodi": "Ilmu Komputer",
  "iat": 1674270000
}

 
2. Aspek Struktur Aplikasi
Arsitektur Monolitik Struktur Aplikasi	Satu aplikasi besar terdiri dari modul atau komponen yang terkait erat.	
Arsitektur Mikroservis Aplikasi terdiri dari sejumlah kecil layanan independen.

Aspek Skalabilitas	
Arsitektur Monolitik Keseluruhan aplikasi ditingkatkan (vertikal atau horizontal).	
Arsitektur Mikroservis Skalabilitas dapat dicapai secara independen untuk setiap layanan.

Aspek Pengembangan dan Pemeliharaan
Arsitektur Monolitik  Memiliki kode yang lebih besar, proses pengembangan dan pemeliharaan mungkin lebih kompleks.	
Arsitektur Mikroservis Dapat memisahkan tim untuk mengembangkan dan memelihara setiap layanan secara independen.

Aspek Ketergantungan Antar Komponen
Arsitektur Monolitik Komponen-komponen saling tergantung dan berbagi basis kode.	
Arsitektur Mikroservis Setiap layanan berdiri sendiri dan dapat berkembang secara independen.

3. Middleware adalah perangkat lunak yang berada di antara dua atau lebih aplikasi atau komponen perangkat lunak untuk memfasilitasi komunikasi atau integrasi di antara mereka.
- Interoperabilitas: Middleware memungkinkan berbagai aplikasi atau sistem yang berbeda untuk bekerja bersama dengan cara yang lebih lancar.
- Dukungan untuk Komunikasi Antar Aplikasi: Middleware memungkinkan komunikasi dan pertukaran data antara aplikasi atau komponen yang berbeda, bahkan jika mereka ditulis dalam bahasa pemrograman atau memiliki arsitektur yang berbeda.
- Penanganan Transaksi: Middleware dapat memberikan dukungan untuk penanganan transaksi, memastikan konsistensi dan integritas data selama proses transaksi yang melibatkan beberapa aplikasi atau sistem.
- Keamanan: Middleware dapat menyediakan mekanisme keamanan untuk melindungi data yang ditransmisikan atau diakses oleh aplikasi atau sistem yang berpartisipasi. Ini termasuk enkripsi data dan autentikasi pengguna.
- Skalabilitas: Middleware dapat membantu dalam mencapai skalabilitas sistem dengan mengelola distribusi beban, mengoptimalkan kinerja, dan memastikan ketersediaan layanan.

4. Unit Testing adalah jenis pengujian perangkat lunak yang fokus pada pengujian setiap unit individual dalam kode program. Unit dapat berupa fungsi, metode, atau blok kode yang dapat diuji secara terpisah. Tujuan dari unit testing adalah untuk memastikan bahwa setiap unit dalam kode bekerja sebagaimana mestinya, sesuai dengan spesifikasi yang diinginkan.
jenis-jenis:
- Test Case: Test case adalah kasus uji yang mencakup input yang diberikan dan hasil yang diharapkan. Setiap unit diuji dengan beberapa test case untuk memastikan berbagai kondisi telah diambil seiring pengembangan.
- Setup dan Teardown: Setup adalah langkah awal yang menyiapkan kondisi awal untuk eksekusi test, sedangkan teardown adalah langkah terakhir yang membersihkan kondisi setelah eksekusi test selesai. Ini membantu dalam mengisolasi setiap test case dan menghindari ketergantungan antar test.
- Assertion: Assertion adalah pernyataan yang menyatakan kondisi yang diharapkan dari hasil test. Jika kondisi tersebut tidak terpenuhi, test dianggap gagal.
- Mocking: Mocking adalah teknik yang digunakan untuk menggantikan bagian-bagian tertentu dari sistem dengan objek palsu atau "mock". Ini membantu dalam mengisolasi unit yang diuji dan menjaga independensinya.
- White Box Testing: White box testing atau testing struktural melibatkan pengetahuan tentang struktur internal kode dan pengujian berdasarkan pengetahuan tersebut. Ini mencakup pengujian jalur kode, pengujian kondisi, dan pengujian batas.
- Black Box Testing: Black box testing atau testing fungsional dilakukan tanpa pengetahuan tentang struktur internal kode. Pengujian ini hanya berfokus pada input dan output yang dihasilkan oleh unit yang diuji.
- Test Runner: Test runner adalah alat atau kerangka kerja yang mengotomatisasi eksekusi test. Ini dapat menjalankan sejumlah besar test case dan memberikan laporan hasil.
- Continuous Integration (CI): CI adalah praktik pengembangan perangkat lunak di mana perubahan kode diperiksa secara otomatis dengan menjalankan serangkaian test setiap kali ada perubahan dalam repositori kode. CI memastikan bahwa setiap perubahan tidak mempengaruhi integritas keseluruhan sistem.

5. - Kontraintainerisasi (containerization) adalah pendekatan pengembangan dan penyebaran perangkat lunak yang mengemas aplikasi dan semua dependensinya ke dalam wadah (container).
- Docker adalah platform open-source yang memfasilitasi kontraintainerisasi. Docker memungkinkan para pengembang untuk membuat, mendistribusikan, dan menjalankan aplikasi di dalam kontainer.
- Kubernetes adalah sistem orkestrasi kontainer yang dirancang untuk otomatisasi penyebaran, penskalaan, dan pengelolaan aplikasi yang dikontainerisasi.

6. - Continuous Integration (CI): cara mengembangkan perangkat lunak dengan diintegrasikan cara otomatis ke dalam repository.
   - Continuous Delivery (CD): adalah perluasan dari Continuous Integration yang memastikan perubahan kode secara otomatis dikirim ke lingkungan uji atau produksi setelah melewati fase integrasi dan pengujian.
  Berikut adalah beberapa alat CI/CD yang umum digunakan:
- Jenkins
- GitLab CI/CD
- Travis CI
- GitHub Actions

7. https://github.com/rifki227/my-app.git
   https://rifki227.github.io/my-app/

 
