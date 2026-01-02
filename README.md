# Botium toys: Internal security audit

## 📑 Table of contents

1. [Introduction](#introduction)
2. [Audit scenario](#scenario)
3. [Scope, goals, and risk assessmen report](#botiumtoys)
4. [Control categories](#controlcategories)
5. [Control and compliance checklist](#controlandcompliance)
6. [Conclusion](#conclusion)

---

## 👋 Introduction <a name="introduction">

The audit evaluates Botium toys cybersecurity program and examines how existing business practices align with industry standards and best practices. The assessment focuses on identifying high-risk vulnerabilities, providing mitigation recommendations, and defining an overall strategy to improve the organization’s security posture. Audit findings are documented clearly, supported by remediation plans, and structured to enable effective communication with stakeholders.

---

## 💭 Audit scenario <a name="scenario">

The audit evaluates Botium Toys’ cybersecurity program and examines how existing business practices align with industry standards and best practices. The assessment focuses on identifying high-risk vulnerabilities, providing mitigation recommendations, and defining an overall strategy to improve the organization’s security posture. Audit findings are documented clearly, supported by remediation plans, and structured to enable effective communication with stakeholders.

---

## ✅ Scope, goals, and risk assessmen report <a name="botiumtoys">

### Scope and goals of the audit

#### a. Scope

Audit ini saya lakukan dengan melihat keseluruhan program keamanan di Botium Toys. Fokusnya bukan hanya pada satu sistem atau alat tertentu, tapi ke semua aset yang dikelola tim IT. Mulai dari sistem yang dipakai sehari hari, perangkat kerja, data perusahaan, sampai proses internal yang berkaitan langsung dengan penerapan kontrol keamanan dan kepatuhan terhadap standar yang berlaku.

Dalam prosesnya, saya tidak hanya menilai teknologi yang digunakan. Saya juga melihat bagaimana aset dikelola, siapa saja yang punya akses, dan bagaimana kontrol keamanan benar benar diterapkan dalam aktivitas harian. Dari sini terlihat apakah praktik keamanan sudah berjalan konsisten atau masih sebatas aturan di atas kertas.

#### b. Goals

Tujuan utama audit ini sederhana, saya ingin tahu sekuat apa kondisi keamanan Botium Toys saat ini. Dari sana saya mulai membandingkan praktik yang sudah berjalan dengan standar dan best practice yang biasa dipakai di industri.

Saya menelusuri aset yang ada satu per satu sambil mencocokkannya dengan daftar kontrol dan kepatuhan. Proses ini membantu saya melihat bagian mana yang sudah aman dan bagian mana yang masih punya celah. Dari hasil itulah muncul gambaran langkah keamanan apa saja yang perlu diterapkan supaya posisi keamanan Botium Toys bisa jadi lebih kuat.

### Current assets

Aset yang dikelola tim IT di Botium Toys cukup luas dan saling terhubung.
- Perangkat on premises di kantor yang menunjang aktivitas operasional harian
- Perangkat kerja karyawan seperti desktop, laptop, smartphone, workstation untuk kerja jarak jauh, serta perangkat pendukung lainnya
- Produk ritel yang dijual melalui toko fisik dan platform online, termasuk sistem penyimpanan di gudang
- Sistem dan layanan bisnis yang digunakan setiap hari, seperti akuntansi, telekomunikasi, database, sistem keamanan, platform e commerce, dan sistem manajemen inventori
- Akses internet serta infrastruktur jaringan internal yang menjadi fondasi seluruh aktivitas digital

### Risk assessment

#### a. Risk description

Pengelolaan aset di Botium Toys masih terasa setengah jalan. Kontrol keamanan sudah ada, tapi belum tertata rapi dan belum mengikuti standar keamanan yang berlaku. Kondisi ini membuka banyak celah. Data sensitif rawan tersentuh pihak yang tidak seharusnya. Operasional bisnis juga berisiko terganggu saat terjadi insiden keamanan.

#### b. Control best practices

Pendekatan yang paling masuk akal mengacu ke fungsi Identify dari NIST Cybersecurity Framework. Langkah awalnya jelas, mengenali semua aset yang dimiliki. Setiap aset dicatat lalu diklasifikasikan. Dari sini terlihat mana yang paling krusial. Tim bisa menentukan prioritas perlindungan. Dampak bisnis saat aset hilang juga lebih mudah dipetakan.

#### c. Risk score

Hasil penilaian menunjukkan skor 8 dari 10. Angka ini menggambarkan tingkat risiko yang tinggi. Kontrol keamanan masih terbatas. Kepatuhan terhadap standar keamanan juga belum konsisten.

#### d. Additional risk considerations

Dampak kehilangan aset berada di level menengah. Aset penting belum terpetakan dengan jelas. Peluang terjadinya kebocoran cukup besar. Risiko sanksi regulasi juga tinggi. Perlindungan data masih lemah.

Temuan spesifik yang saya catat:
- Seluruh karyawan memiliki akses data internal yang terlalu luas, termasuk data pembayaran dan data pribadi pelanggan
- Data kartu kredit belum dilindungi dengan enkripsi saat diproses maupun disimpan
- Prinsip least privilege dan pemisahan tugas belum diterapkan
- Firewall sudah terpasang dan dikonfigurasi dengan aturan keamanan yang sesuai
- Antivirus aktif dan rutin dipantau
- Sistem intrusion detection belum tersedia
- Rencana pemulihan bencana dan mekanisme backup data belum ada
- Prosedur notifikasi kebocoran data untuk pelanggan sudah memenuhi batas waktu 72 jam
- Kebijakan kata sandi sudah ada, tapi belum mengikuti standar kompleksitas saat ini
- Sistem manajemen kata sandi terpusat belum digunakan

Bagian ini menjadi titik penting dalam cerita audit saya. Dari sini terlihat jelas area mana yang perlu dibenahi lebih dulu supaya keamanan Botium Toys bisa meningkat.

---

## 🚧 Control categories <a name="controlcategories">

Bagian ini jadi titik di mana saya mulai menyusun gambaran besar soal keamanan di Botium Toys.

### Administrative/managerial controls

|Nama kontrol|Tipe kontrol|Alasan|
|---|---|---|
|Least privilege|Preventative|Setiap orang hanya pegang akses yang benar benar dibutuhkan|
|Disaster recovery plans|Corrective|Aktivitas bisnis tetap bisa lanjut setelah insiden|
|Password policies|Preventative|Akses akun tidak mudah ditembus dengan cara sederhana|
|Access control policies|Preventative|Hak lihat dan ubah data jadi lebih jelas|
|Account management policies|Preventative|Akun lama dan akun default tidak jadi pintu masuk ancaman|
|Separation of duties|Preventative|Tanggung jawab dibagi supaya tidak ada kendali berlebih|

### Technical controls

|Nama kontrol|Tipe kontrol|Alasan|
|---|---|---|
|Firewall|Preventative|Jaringan terlindungi dari lalu lintas yang mencurigakan|
|IDS/IPS|Detective|Aktivitas aneh bisa terdeteksi lebih cepat|
|Encryption|Deterrent|Data sensitif tetap aman saat disimpan dan diproses|
|Backups|Corrective|Data bisa dipulihkan saat sistem bermasalah|
|Password management|Preventative|Penggunaan password jadi lebih rapi dan konsisten|
|Antivirus (AV) software|Corrective|Ancaman umum bisa langsung ditangani|
|Manual monitoring, maintenance, and intervention|Preventative|Sistem lama tetap aman lewat pengawasan rutin|

### Physical/operational controls

|Nama kontrol|Tipe kontrol|Alasan|
|---|---|---|
|Time-controlled safe|Deterrent|Akses aset penting dibatasi secara fisik|
|Adequate lighting|Deterrent|Area rawan jadi lebih terbuka dan aman|
|Closed-circuit television (CCTV)|Preventative/detective  |Mencegah kejadian dan jadi bukti saat insiden|
|Locking cabinets (network equipment)|Preventative|Perangkat jaringan tidak mudah disentuh sembarang orang|
|Alarm service provider signage|Deterrent|Ancaman berpikir dua kali sebelum bertindak|
|Locks|Preventative/deterrent|Akses fisik tetap terjaga|
|Fire detection and prevention systems|Detective/preventative|Inventori dan server terlindungi dari risiko kebakaran|

---

## 📋 Control and compliance checklist <a name="controlandcompliance">
 
Di sini, saya mulai mencocokkan kontrol keamanan yang seharusnya ada dengan kondisi nyata di Botium Toys.

|Kontrol|Yes|No|
|---|---|---|
|Least privilege| |x|
|Disaster recovery plans| |x|
|Password policies|x| |
|Access control policies| |x|
|Account management policies| |x|
|Separation of duties| |x|
|Firewall|x| |
|IDS/IPS| |x|
|Encryption| |x|
|Backups| |x|
|Password management| |x|
|Antivirus (AV) software|x| |
|Manual monitoring, maintenance, and intervention|x| |
|Time-controlled safe|x| |
|Adequate lighting|x| |
|Closed-circuit television (CCTV)|x| |
|Locking cabinets (network equipment)|x| |
|Alarm service provider signage|x| |
|Locks|x| |
|Fire detection and prevention systems|x| |

