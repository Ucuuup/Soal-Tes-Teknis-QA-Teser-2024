# Soal-Tes-Teknis-QA-Teser-2024

# User Stories dan Acceptance Criteria

## EPIC 1: Sub Sistem Perangkat IoT

### User Story 1
**Sebagai pengguna**, saya ingin sistem memiliki sensor-sensor lingkungan (suhu, kelembaban, intensitas cahaya, dan pengambilan gambar) sehingga saya dapat memantau kondisi lingkungan secara real-time.

#### Acceptance Criteria
- Sistem harus memiliki sensor untuk:
  - Suhu lingkungan
  - Kelembaban lingkungan
  - Intensitas cahaya lingkungan
  - Pengambilan gambar lingkungan

### User Story 2
**Sebagai pengguna**, saya ingin sistem dapat mendeteksi suhu lingkungan sehingga saya dapat mengetahui kondisi suhu saat ini.

#### Acceptance Criteria
- Sistem harus mampu mendeteksi suhu lingkungan dan menampilkan hasilnya.

### User Story 3
**Sebagai pengguna**, saya ingin sistem dapat mendeteksi kelembaban udara sehingga saya bisa memantau kelembaban lingkungan.

#### Acceptance Criteria
- Sistem harus mampu mendeteksi kelembaban dan menampilkan hasilnya.

### User Story 4
**Sebagai pengguna**, saya ingin sistem dapat mendeteksi intensitas cahaya sehingga saya dapat mengetahui seberapa terang lingkungan.

#### Acceptance Criteria
- Sistem harus mampu mendeteksi intensitas cahaya dan menampilkan hasilnya.

### User Story 5
**Sebagai pengguna**, saya ingin sistem dapat mengambil gambar kondisi perangkat serangga sehingga saya dapat memantau keberadaan serangga.

#### Acceptance Criteria
- Sistem harus dapat mengambil gambar dan menyimpannya dengan benar.

### User Story 6
**Sebagai pengguna**, saya ingin sistem dapat mengisi daya dari solar panel sehingga perangkat bisa beroperasi secara mandiri.

#### Acceptance Criteria
- Sistem harus mampu mengisi daya dari solar panel dan menampilkan status pengisian.

---

## EPIC 2: Sub Sistem Komunikasi

### User Story 7
**Sebagai pengguna**, saya ingin sistem memiliki modem 4G untuk mengirim data dari sensor-sensor sehingga data dapat dipantau secara remote.

#### Acceptance Criteria
- Sistem harus dilengkapi dengan modem 4G untuk mengirim data sensor.

### User Story 8
**Sebagai pengguna**, saya ingin sistem dapat mengirim data dari sensor suhu, kelembaban, dan intensitas cahaya agar data dapat diproses di Sub Sistem Back End.

#### Acceptance Criteria
- Sistem harus dapat mengirim data dari semua sensor yang disebutkan.

### User Story 9
**Sebagai pengguna**, saya ingin sistem dapat mengirim data status aktif perangkat IoT untuk memantau keberlangsungan kerja perangkat.

#### Acceptance Criteria
- Sistem harus dapat mengirim data status aktif atau tidaknya perangkat IoT.

### User Story 10
**Sebagai pengguna**, saya ingin sistem dapat menerima perintah dari Sub Sistem Back End untuk mengaktifkan sensor lingkungan.

#### Acceptance Criteria
- Sistem harus mampu menerima dan mengeksekusi perintah untuk mengaktifkan sensor.

### User Story 11
**Sebagai pengguna**, saya ingin sistem dapat menggunakan protokol MQTT atau HTTP untuk mengirim data sehingga komunikasi berlangsung dengan efisien.

#### Acceptance Criteria
- Sistem harus dapat beroperasi dengan protokol MQTT atau HTTP.

---

## EPIC 3: Sub Sistem Back End

### User Story 12
**Sebagai pengguna**, saya ingin sistem dapat menerima dan menyimpan data dari sensor-sensor perangkat IoT untuk analisis lebih lanjut.

#### Acceptance Criteria
- Sistem harus mampu menerima dan menyimpan data dari semua sensor.

### User Story 13
**Sebagai pengguna**, saya ingin sistem dapat mengolah data dari sensor untuk ditampilkan di Sub Sistem Aplikasi Front End.

#### Acceptance Criteria
- Sistem harus dapat mengolah dan mengirim data ke Sub Sistem Aplikasi Front End.

### User Story 14
**Sebagai pengguna**, saya ingin sistem dapat menyimpan gambar yang diambil oleh sensor ke Object Storage agar dapat diakses kapan saja.

#### Acceptance Criteria
- Sistem harus dapat menyimpan gambar ke Object Storage.

### User Story 15
**Sebagai pengguna**, saya ingin sistem dapat menyimpan data ke Database Postgres untuk keperluan pengolahan data lebih lanjut.

#### Acceptance Criteria
- Sistem harus dapat menyimpan semua data ke Database Postgres.

---

## EPIC 4: Sub Sistem Front End

### User Story 16
**Sebagai pengguna**, saya ingin sistem dapat menampilkan data dari sensor suhu dan kelembaban sehingga saya dapat memantau kondisi lingkungan.

#### Acceptance Criteria
- Sistem harus dapat menampilkan data dari sensor suhu dan kelembaban.

### User Story 17
**Sebagai pengguna**, saya ingin sistem dapat menampilkan grafik hasil sensor berdasarkan waktu dan lokasi untuk analisis yang lebih baik.

#### Acceptance Criteria
- Sistem harus dapat menampilkan grafik berdasarkan filter jangka waktu dan lokasi.

### User Story 18
**Sebagai pengguna**, saya ingin sistem dapat memberikan notifikasi mengenai status perangkat IoT agar saya bisa segera merespons.

#### Acceptance Criteria
- Sistem harus dapat menampilkan notifikasi tentang status aktif/non-aktif perangkat.

### User Story 19
**Sebagai pengguna**, saya ingin sistem dapat mengatur jadwal pengiriman data ke Sub Sistem Back End untuk mengoptimalkan penggunaan sumber daya.

#### Acceptance Criteria
- Sistem harus memungkinkan pengaturan jadwal pengiriman data (jam, harian, mingguan).

### User Story 20
**Sebagai pengguna**, saya ingin sistem dapat mengatur hak akses berdasarkan Role Based Access Control untuk keamanan data.

#### Acceptance Criteria
- Sistem harus dapat mengelola hak akses berdasarkan peran pengguna.
