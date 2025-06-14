# Proyek Peratma: Permasalahan Atrition Rate Perusahaan

## Business Understanding

Sumber daya manusia merupakan salah satu hal krusial yang harus dikelola dengan baik oleh perusahaan. Baik dan buruknya kinerja karyawan sangat berdampak pada performa perusahaan. Selain itu proses rekrutmen membutuhkan waktu dan dana yang tidak sedikit. Oleh karena itu departement Human Resource and Development (HRD) memiliki peran krusial dalam menjaga stabilitas performa perusahaan.

Salah satu permasalahan besar yang dihadapi perusahaan adalah tingginya attrition rate yang sangat berdampak pada performa perusahaan. Banyak hal yang menjadi pertimbangan karyawan untuk resign diantaranya rate gaji, work life balance, job satisfactory, kejelasan jenjang karir, dan berbagai hal pendukung lainnya. Tentunya berbagai faktor ini harus diperhatikan oleh perusahaan agar dapat menurunkan atrition rate.

Project ini akan mengolah data karyawan dari departemen HR menggunakan pendekatan data science. Harapannya dapat menghasilkan feedback yang dapat dipergunakan oleh manager HR dalam membuat kebijakan perusahaan dalam hal penurunan atrition rate.
### Permasalahan Bisnis

Tuliskan seluruh permasalahan bisnis yang akan diselesaikan.
- Perbandingan resign pria dan wanita
- Departement manakah paling banyak resign
- Apakah job satisfaction berpenagruh terhadap tingkat resign
- Apakah ada pengaruh marital status terhadap data resign karyawan
- Karyawan dengan performa rating bagaimana yang cendrung resign
- Bagaimana pengaruh work life balance terhadap kecendrungan resign
- Umur berapakah paling banyak karyawan resign
- Bagaimana pengaruh monthly income terhadap kecendrungan resign
- Kebanyakan pegawai resign adalah yang sudah pindah kerja berapa kali
- Pengaruh total lama bekerja di perusahaan ini terhadap kecendrungan resign
- Pengaruh kenaikan gaji terhadap kecendrungan resign

### Cakupan Proyek

Proyek ini mencakup pembuatan dashboard interaktf yang dapat digunakan user dalam memahami faktor-faktor atrition rate. Selain itu menggunakan pendekatan machine learning dibuat sebuah model yang dapat menghitung posibilitas resign karyawan.
### Persiapan

Sumber data: https://www.ibm.com/communities/analytics/watson-analytics-blog/watson-analytics-use-case-for-hr-retaining-valuable-employees/

Setup environment:

- Proses machine learning dilakukan mengunakan jupyter notebook. Setep environment dilampirkan pada file requirements.txt
- Business Dashboard dibuat menggunakan Tableau

## Business Dashboard


Dashboard dapat di akses menggunakan link berikut: https://public.tableau.com/shared/JKY5YX92R?:display_count=n&:origin=viz_share_link&:device=desktop

## Conclusion

- Pria lebih banyak melakukan resign yitu sebanyak 370, sedangkan wanita hanya 221.
- Department paling banyak resign adalah Research & Development lalu diikuti Sales dan Human Resource dengan jumlah 367, 193, dan 31 secara berurutan.
- Pada job Satisfaction resign terbanyak justru terjadi pada kelompok high sebanyak 186 dan paling sedikit pada medium sebanyak 117 orang. Kelompok very high dan low berada ditengah. Hal inimenunjukkan job satisfaction tidak berpengaruh terhadap kecendrungan resign.
- Pada marital status kategori married berada pada urutan pertama diikuti single dan divorce dengan jumlah 271, 212, dan 108 orang secara berurutan.
- Performa rating excelen terdapat kasus resign sebanyak 496 orang sedangkan outstanding hanya 95 orang.
- Kategori excelent pada work life balance terdapat 349 kasus resign, diikuti good dengan 138 orang, outstanding 62 orang, dan pada urutan terakhir low sebanyak 42 orang.
- Umur 29 merupakan usia paling banyak karyawan resign yaitu sebanyak 36 orang. Usia 60 menjadi yang paling sedikit kasus resign yaitu hanya satu orang.
- Pendapatan bulanan $2.000 merupakan paling banyak yaitu 170 orang resign, paling sedikit pada pendapatan $14.000 yaitu satu orang.
- Paling banyak  kasus resign pada orang yang baru pindah kerja satu kali yaitu sebanyak 224 orang dan paling sedikit 18 orang yang telah pindah kerja sembilan kali.
- Resign paling banyak pada orang yang baru bekerja satu tahun yaitu 87 orang dan paling sedikit adalah yang telah bekerja selama36, 33, 31, 30, 26, dan 24 tauhn yaitu masing-masing satu orang.
- Resign paling banyak pada orang yang mengalami kenaikan gaji setahun terakhir sebesar 13% adalah 87 orang sedangkan paling sedikit 9 orang pada kenaikan 24%

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- User bisa menggunakan model machine learning untuk mmprediksi kemungkinan resign karyawan lalu mengadakan pertemuan dengan kelompok karyawan tersebut. User bersama HR bisa melakukan diskusi yang dapat menyerap aspirasi mereka sehingga kecendrungan resign mereka dapat terjawab setelah pertemuan tersebut.
- Department HR dapat menganalisa dashboard dan menyelidiki kelompok kategori apa saja yang rentan resign, sehingga untuk rekrutmen kedepannya hal tersebut dapat menjadi pertimbangan.
