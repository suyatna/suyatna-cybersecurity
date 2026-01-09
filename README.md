# Botium Toys internal security audit

## 📑 Table of contents

1. [Introduction](#introduction)
2. [Audit scenario](#scenario)
3. [Scope, goals, and risk assessmen report](#botiumtoys)
4. [Control categories](#controlcategories)
5. [Control and compliance checklist](#controlandcompliance)
6. [Conclusion](#conclusion)

---

## 👋 Introduction <a name="introduction">

Studi kasus ini saya susun sebagai bagian dari portofolio cybersecurity, dengan fokus pada audit keamanan internal. Proyek ini menggunakan skenario Botium Toys, sebuah perusahaan retail mainan fiktif, untuk menggambarkan proses audit keamanan yang mendekati kondisi nyata di industri. Pembahasan ini juga lahir dari pembelajaran saya dalam program Google Cybersecurity Professional Certificate di Coursera, khususnya pada course Play It Safe: Manage Security Risks.

Audit dilakukan untuk menilai sejauh mana sistem keamanan siber Botium Toys sudah berjalan dengan baik dan selaras dengan standar industri. Perhatian utama diarahkan pada risiko-risiko yang memiliki dampak besar, lalu diterjemahkan menjadi rekomendasi yang bisa langsung ditindaklanjuti. Hasil audit disusun secara rapi dan mudah dipahami, lengkap dengan rencana perbaikan, agar dapat disampaikan dengan jelas kepada para pemangku kepentingan.

---

## 💭 Audit scenario <a name="scenario">

Botium Toys adalah perusahaan retail mainan yang sedang bertumbuh dan menjalankan penjualan lewat toko fisik serta platform online. Aktivitas transaksi digital yang semakin padat membuat perusahaan harus menangani lebih banyak data pelanggan, termasuk informasi pribadi dan pembayaran. Sistem TI memegang peran penting dalam keseharian operasional, mulai dari pengelolaan stok hingga proses transaksi.

Laju pertumbuhan bisnis belum sepenuhnya diiringi dengan penguatan keamanan internal. Berbagai sistem digunakan bersama oleh karyawan lintas divisi, namun pengaturan akses, pencatatan aset, dan perlindungan data masih berjalan tanpa kerangka yang jelas. Situasi ini menimbulkan risiko, seperti kebocoran data, gangguan layanan, hingga masalah kepatuhan terhadap aturan yang berlaku.

Kondisi tersebut mendorong manajemen untuk melakukan audit keamanan internal. Tujuannya sederhana, yaitu memahami kondisi keamanan yang ada saat ini. Audit difokuskan pada aset-aset penting, cara sistem dilindungi, serta risiko yang bisa berdampak langsung pada operasional dan bisnis.

Audit ini disusun untuk melihat apakah praktik keamanan yang berjalan sudah sejalan dengan standar industri. Setiap temuan dicatat secara rapi dan disertai saran perbaikan yang realistis. Hasilnya diharapkan menjadi langkah awal bagi perusahaan untuk membangun keamanan yang lebih kuat dan berkelanjutan.

---

## 🎯 Scope, goals, and risk assessmen report <a name="botiumtoys">

### Scope and goals of the audit

#### a. Scope

Audit ini saya jalankan dengan melihat gambaran besar keamanan di Botium Toys. Perhatian tidak diarahkan pada satu sistem atau alat tertentu, melainkan pada seluruh aset yang dikelola oleh tim IT. Cakupannya meliputi sistem yang digunakan sehari-hari, perangkat kerja karyawan, data perusahaan, serta proses internal yang berkaitan langsung dengan pengamanan dan kepatuhan terhadap standar yang berlaku.

Penilaian tidak berhenti pada teknologi yang digunakan. Cara aset dikelola, pengaturan akses, dan penerapan kontrol keamanan dalam aktivitas harian juga menjadi bagian penting dari evaluasi. Dari proses ini terlihat apakah keamanan sudah benar-benar dijalankan secara konsisten atau masih sebatas kebijakan tertulis.

#### b. Goals

Audit ini saya lakukan untuk memahami seberapa kuat kondisi keamanan Botium Toys saat ini. Penilaian dimulai dengan melihat praktik yang sudah berjalan dan membandingkannya dengan standar umum yang lazim digunakan di industri.

Setiap aset ditinjau satu per satu dan dicocokkan dengan kontrol serta aturan yang relevan. Proses ini memudahkan saya mengenali area yang sudah terlindungi dengan baik dan area yang masih memiliki celah. Hasil tersebut terbentuk gambaran langkah-langkah perbaikan yang dibutuhkan agar keamanan Botium Toys bisa lebih kuat.

### Current assets

Aset yang dikelola oleh tim IT di Botium Toys cukup beragam dan saling terhubung. Seluruh aset ini berperan penting dalam mendukung aktivitas bisnis sehari-hari.
- Perangkat di kantor yang digunakan untuk menunjang operasional harian
- Perangkat kerja karyawan, seperti desktop, laptop, smartphone, workstation untuk kerja jarak jauh, serta perangkat pendukung lainnya
- Produk ritel yang dijual melalui toko fisik dan platform online, termasuk sistem penyimpanan dan pengelolaan gudang
- Sistem dan layanan bisnis yang digunakan setiap hari, mencakup keuangan, komunikasi, pengelolaan data, keamanan, platform penjualan online, dan manajemen inventori
- Akses internet dan infrastruktur jaringan internal yang menjadi dasar seluruh aktivitas digital perusahaan

### Risk assessment

#### a. Risk description

Pengelolaan aset di Botium Toys masih belum berjalan dengan optimal. Beberapa kontrol keamanan sudah diterapkan, namun pelaksanaannya belum terstruktur dan belum mengacu pada standar yang jelas. Situasi ini membuat celah keamanan masih terbuka.

Data sensitif berpotensi diakses oleh pihak yang tidak berwenang. Aktivitas bisnis juga bisa terganggu ketika terjadi masalah keamanan, karena belum ada perlindungan yang benar-benar siap menghadapi risiko tersebut.

#### b. Control best practices

Pendekatan yang saya pilih dimulai dari fungsi Identify dalam NIST Cybersecurity Framework. Langkah pertama dimulai dengan mengenali seluruh aset yang dimiliki perusahaan. Setiap aset dicatat dan dikelompokkan agar lebih mudah dipahami.

Proses ini membantu melihat aset mana yang paling penting bagi bisnis. Prioritas perlindungan bisa ditentukan dengan lebih jelas. Dampak terhadap operasional juga lebih mudah diperkirakan jika suatu aset mengalami masalah atau hilang.

#### c. Risk score

Hasil penilaian menunjukkan skor 8 dari 10, yang menandakan tingkat risiko cukup tinggi. Perlindungan yang ada masih terbatas dan belum merata. Penerapan standar keamanan juga belum dijalankan secara konsisten.

#### d. Additional risk considerations

Dampak kehilangan aset berada di tingkat menengah. Aset yang paling penting belum dipetakan dengan jelas. Peluang terjadinya kebocoran masih cukup besar. Risiko pelanggaran aturan juga tinggi karena perlindungan data belum kuat.

Beberapa temuan penting yang saya catat selama audit:
- Seluruh karyawan memiliki akses yang terlalu luas ke data internal, termasuk informasi pembayaran dan data pribadi pelanggan
- Data kartu kredit belum dilindungi dengan baik saat diproses maupun disimpan
- Prinsip pembatasan akses dan pemisahan tanggung jawab belum diterapkan
- Firewall sudah terpasang dan dikonfigurasi dengan aturan yang memadai
- Antivirus aktif dan dipantau secara rutin
- Sistem pendeteksian serangan belum tersedia
- Rencana pemulihan saat terjadi gangguan serta mekanisme pencadangan data belum disiapkan
- Prosedur pemberitahuan kebocoran data kepada pelanggan Uni Eropa sudah mengikuti batas waktu 72 jam
- Aturan kata sandi sudah ada, namun belum sesuai dengan standar kekuatan terbaru
- Sistem pengelolaan kata sandi terpusat belum digunakan

Gambaran ini membantu menunjukkan area yang perlu diprioritaskan agar keamanan Botium Toys dapat ditingkatkan secara bertahap.

---

## 🚧 Control categories <a name="controlcategories">

Bagian ini menjadi titik awal saya menyusun gambaran menyeluruh tentang keamanan di Botium Toys. Kerangka tersebut saya bagi ke dalam tiga lapisan utama, yaitu kebijakan, teknis, dan fisik. Pembagian ini memudahkan saya melihat keamanan tidak hanya dari sisi sistem, tetapi juga dari kebiasaan kerja tim dan cara aset dilindungi secara langsung di lingkungan kerja.

### Administrative/managerial controls (kebijakan)

Bagian ini berfokus pada aturan dan kebijakan yang mengatur cara orang bekerja dan menggunakan akses.

|Nama kontrol|Tipe kontrol|Penjelasan singkat|
|---|---|---|
|Least privilege|Preventif|Setiap orang hanya memiliki akses sesuai kebutuhan kerjanya|
|Rencana pemulihan bencana|Korektif|Aktivitas bisnis tetap bisa berjalan setelah terjadi gangguan|
|Kebijakan kata sandi|Preventif|Akun tidak mudah diakses dengan cara yang sederhana|
|Kebijakan kontrol akses|Preventif|Hak melihat dan mengubah data menjadi lebih jelas|
|Kebijakan pengelolaan akun|Preventif|Akun lama dan akun bawaan tidak menjadi celah keamanan|
|Pemisahan tugas|Preventif|Tanggung jawab dibagi agar tidak ada kendali berlebihan|

### Technical controls (teknis)

Lapisan ini berkaitan langsung dengan sistem dan perlindungan digital yang digunakan sehari-hari.

|Nama kontrol|Tipe kontrol|Penjelasan singkat|
|---|---|---|
|Firewall|Preventif|Jaringan terlindungi dari lalu lintas yang mencurigakan|
|IDS/IPS|Detektif|Aktivitas tidak wajar bisa diketahui lebih cepat|
|Enkripsi|Pencegah|Data sensitif tetap aman saat disimpan dan digunakan|
|Cadangan data|Korektif|Data bisa dipulihkan saat sistem bermasalah|
|Manajemen kata sandi|Preventif|Penggunaan kata sandi lebih rapi dan konsisten|
|Antivirus|Korektif|Ancaman umum bisa langsung ditangani|
|Pemantauan dan perawatan manual|Preventif|Sistem tetap aman lewat pengawasan rutin|

### Physical/operational controls (fisik)

Lapisan ini melihat bagaimana aset dijaga secara langsung di lingkungan kerja.

|Nama kontrol|Tipe kontrol|Penjelasan singkat|
|---|---|---|
|Brankas dengan pengatur waktu|Pencegah|Akses ke aset penting dibatasi secara fisik|
|Penerangan yang memadai|Pencegah|Area rawan menjadi lebih terbuka dan aman|
|CCTV|Preventif/detektif|Mencegah kejadian dan membantu saat investigasi|
|Lemari terkunci untuk perangkat jaringan|Preventif|Perangkat penting tidak mudah diakses sembarang orang|
|Papan peringatan sistem alarm|Pencegah|Pihak luar berpikir ulang sebelum bertindak|
|Kunci|Preventif/pencegah|Akses fisik tetap terjaga|
|Sistem deteksi dan pencegahan kebakaran|Detektif/preventif|Server dan inventori terlindungi dari risiko kebakaran|

---

## 📋 Control and compliance checklist <a name="controlandcompliance">
 
Pada tahap ini, saya mulai membandingkan kontrol keamanan yang ideal dengan kondisi nyata di Botium Toys. Proses ini membantu melihat bagian yang sudah berjalan dengan baik dan bagian yang masih memiliki celah.

|Kontrol|Sudah|Belum|
|---|---|---|
|Least privilege| |x|
|Rencana pemulihan bencana| |x|
|Kebijakan kata sandi|x| |
|Kebijakan kontrol akses| |x|
|Kebijakan pengelolaan akun| |x|
|Pemisahan tugas| |x|
|Firewall|x| |
|IDS/IPS| |x|
|Enkripsi| |x|
|Cadangan data| |x|
|Manajemen kata sandi| |x|
|Antivirus|x| |
|Pemantauan dan perawatan manual|x| |
|Brankas dengan pengatur waktu| |x|
|Penerangan yang memadai|x| |
|CCTV|x| |
|Lemari terkunci untuk perangkat jaringan|x| |
|Papan peringatan sistem alarm|x| |
|Kunci|x| |
|Sistem deteksi dan pencegahan kebakaran|x| |

Sejumlah kontrol dasar sudah diterapkan dan berjalan cukup baik. Perlindungan jaringan dasar, antivirus, pemantauan sistem lama, serta keamanan fisik sudah memberi lapisan perlindungan awal.

Kendala mulai terlihat pada perlindungan data yang bersifat sensitif. Enkripsi belum diterapkan. Sistem pendeteksi serangan belum digunakan. Cadangan data belum disiapkan. Akses pengguna juga belum diatur berdasarkan peran. Kondisi ini membuat risiko kebocoran data dan gangguan operasional menjadi lebih besar.

### Compliance Checklist

Setelah meninjau kontrol internal, saya beralih ke aspek kepatuhan. Perhatian diarahkan pada standar yang paling sesuai dengan aktivitas dan kebutuhan Botium Toys.

#### PCI DSS

Penilaian ini dilakukan karena Botium Toys mengelola dan menyimpan data kartu pembayaran pelanggan di dalam sistem internal perusahaan.

|Praktik yang seharusnya diterapkan|Sudah|Belum|
|---|---|---|
|Akses data kartu dibatasi hanya untuk pihak berwenang| |x|
|Data kartu diproses dan disimpan di lingkungan yang aman| |x|
|Enkripsi untuk transaksi kartu kredit diterapkan| |x|
|Kebijakan pengelolaan kata sandi yang aman| |x|

Hasil penilaian menunjukkan kondisi yang cukup mengkhawatirkan. Sebagian besar praktik penting terkait PCI DSS belum dijalankan. Area pembayaran terlihat sebagai salah satu sumber risiko terbesar bagi perusahaan.

#### GDPR

Bagian ini menyoroti cara perusahaan melindungi data pribadi pelanggan dan kesiapan saat terjadi insiden.

|Praktik yang seharusnya diterapkan|Sudah|Belum|
|---|---|---|
|Data pelanggan Uni Eropa dijaga keamanannya| |x|
|Pemberitahuan kebocoran data dilakukan dalam 72 jam|x| |
|Data diklasifikasikan dan dicatat dengan jelas| |x|
|Kebijakan privasi diterapkan|x| |

Beberapa hal sudah mulai dijalankan, terutama terkait prosedur pemberitahuan dan aturan tertulis. Pengelolaan data di tingkat teknis masih perlu banyak pembenahan supaya lebih tertata.

#### SOC type 1 and type 2

SOC saya gunakan sebagai acuan untuk menilai bagaimana akses dikelola dan bagaimana data dijaga dari sisi kerahasiaan, keutuhan, dan ketersediaannya.

|Praktik yang seharusnya diterapkan|Sudah|Belum|
|---|---|---|
|Kebijakan pengaturan akses pengguna diterapkan| |x|
|Data sensitif terlindungi dengan baik| |x|
|Keutuhan data tetap terjaga|x| |
|Data tersedia bagi pengguna yang berwenang|x| |

Penilaian menunjukkan bahwa aspek keutuhan dan ketersediaan data sudah mulai diperhatikan. Perlindungan kerahasiaan data masih perlu menjadi fokus utama perbaikan.

### Recommendations

Dari seluruh hasil penilaian, area yang paling perlu segera dibenahi adalah perlindungan data sensitif dan kesiapan operasional. Enkripsi menjadi kebutuhan utama. Pengaturan akses berdasarkan peran perlu segera diterapkan. Sistem pendeteksi dini dibutuhkan supaya masalah bisa diketahui lebih cepat. Cadangan data rutin juga harus disiapkan. Pengelolaan kata sandi secara terpusat dapat membantu menutup banyak celah kecil yang berisiko.

Langkah-langkah ini menjadi dasar penting supaya Botium Toys bisa menekan risiko kebocoran data, lebih siap saat menghadapi audit kepatuhan, dan membangun kondisi keamanan yang lebih kuat ke depannya.

---

## 🏁 Conclusion <a name="conclusion">

Audit keamanan internal di Botium Toys menunjukkan adanya jarak antara cepatnya pertumbuhan bisnis dan kesiapan sistem keamanannya. Beberapa perlindungan dasar sudah tersedia, terutama di sisi teknis dan keamanan fisik. Pengelolaan akses, perlindungan data, pemantauan sistem, serta kesiapan menghadapi insiden masih belum berjalan dengan baik.

Hasil penilaian memperlihatkan bahwa risiko tidak muncul dari satu masalah saja. Beberapa kontrol penting belum diterapkan secara menyeluruh. Pembatasan akses belum jelas, data belum dilindungi dengan baik, sistem pendeteksi belum tersedia, dan cadangan data serta rencana pemulihan belum disiapkan. Kondisi ini meningkatkan peluang terjadinya kebocoran data dan gangguan operasional.

Temuan audit menekankan pentingnya pendekatan keamanan yang lebih terarah dan berbasis risiko. Penyesuaian kontrol keamanan dengan standar industri dan aturan yang berlaku akan membantu Botium Toys bergerak dari pola reaksi sesaat menuju keamanan yang lebih siap dan berkelanjutan.

Audit ini menjadi langkah awal dalam pengambilan keputusan strategis terkait keamanan informasi. Rekomendasi yang dihasilkan memberi panduan yang jelas untuk memperkuat perlindungan, menekan risiko, dan menjaga kelangsungan bisnis seiring pertumbuhan perusahaan.
