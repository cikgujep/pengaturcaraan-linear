# Brief Lengkap: Slaid HTML Interaktif Pengaturcaraan Linear (Matematik Tambahan)

Dokumen ini menggantikan fail `pengaturcaraan-linear-roh-pengajaran.md`. Ia merangkum semua keputusan perbincangan dan boleh diberikan terus kepada Claude Code sebagai brief projek.

Modul rasmi (Sekolah Menengah Sains Banting, Bab 7: Pengaturcaraan Linear) kini ada dalam folder ini: `F5B07 Pengaturcaraan Linear.pdf` (modul murid, graf kosong) dan `F5B07 Pengaturcaraan Linear ans.pdf` (modul guru, graf dan jawapan penuh). Apabila ada percanggahan, **modul ialah rujukan utama**. Penemuan daripada semakan modul ini sudah dimasukkan ke bahagian 5, 6.2, 8.5 dan 12 di bawah.

---

## 1. Tujuan

Menghasilkan slaid HTML interaktif untuk guru mengajar Pengaturcaraan Linear kepada murid Matematik Tambahan, dengan fokus pada:

- membina graf langkah demi langkah dengan seluruh graf sentiasa kelihatan jelas
- memahami mengapa optimum berada di bucu
- mengendalikan kes jawapan integer apabila bucu berupa perpuluhan
- pemodelan daripada ayat ke ketaksamaan

Bahasa: Bahasa Melayu, istilah mengikut DBP dan konteks KPM.

---

## 2. Roh Topik

Pengaturcaraan linear ialah **pemodelan keputusan**, bukan sekadar melukis graf. Graf ialah alat untuk menjawab model yang betul.

Empat idea teras:

1. **Terjemah situasi kepada model:** pemboleh ubah keputusan, kekangan, fungsi objektif.
2. **Rantau tersaur** (istilah rasmi modul; nilai yang memenuhinya dipanggil **nilai tersaur**) ialah semua pilihan yang sah serentak.
3. **Optimum di bucu** (untuk kes selanjar). Fungsi objektif k = ax + by ialah keluarga garis selari. Apabila garis digelongsor, titik terakhir yang menyentuh rantau ialah satu bucu.
4. **Tafsir jawapan dalam konteks,** termasuk keperluan integer.

---

## 3. Urutan Pengajaran

Graf dahulu (kemahiran asas yang boleh diperhatikan), pemodelan berjalan selari dan tidak ditinggalkan di hujung.

| Fasa | Fokus | Hasil |
|------|-------|-------|
| 1 | Lukis satu ketaksamaan dan lorek | Garis tepat, jenis garis betul, rantau betul |
| 2 | Dua atau lebih ketaksamaan | Rantau sepunya |
| 3 | Tiga atau lebih ketaksamaan | Rantau tersaur, bucu dikenal pasti |
| 4 | Garis fungsi objektif | Garis selari, penggelongsoran, bucu optimum |
| 5 | Kes integer | Titik integer sah paling optimum |
| 6 | Ayat ke ketaksamaan (pemodelan) | Pemboleh ubah ditakrif, ketaksamaan betul |
| 7 | Soalan penuh dengan tafsiran | Model, graf, optimum, konteks |

---

## 4. Kemahiran Graf: Kesilapan Lazim dan Penyelesaian

| Kesilapan | Penyelesaian |
|-----------|--------------|
| Skala paksi salah, murid melukis sebelum mengira pintasan | Kira semua pintasan dahulu, kemudian pilih skala |
| Garis tidak tepat, murid meneka kecerunan | Kaedah dua pintasan: x = 0 untuk pintasan-y, y = 0 untuk pintasan-x |
| Garis pepejal atau putus-putus tersalah | ≤ dan ≥ pepejal, < dan > putus-putus |
| Rantau tersalah lorek | Guna titik ujian, biasanya (0, 0). Jika garis melalui asalan, guna titik lain |
| Bucu dibaca anggaran daripada graf | Baca daripada graf, kemudian sahkan dengan persamaan serentak |
| Menggunakan titik bukan integer apabila konteks memerlukan integer | Semak konteks sebelum menjawab |

Murid menyemak sebelum melukis: "Adakah semua garis dan rantau muat dalam graf dengan skala ini?"

---

## 5. Memilih Nilai k untuk Garis Fungsi Objektif

**Prinsip utama:** k hanya untuk melukis arah garis. Ia bukan jawapan. Hanya cerun yang penting, maka k boleh dipilih sesuka hati.

**Kaedah modul rasmi (utamakan dalam slaid):** modul guru tidak guna k = a × b. Mereka pilih sahaja satu nilai k yang munasabah berbanding konteks (cth. "Katakan J = RM450" atau "Katakan k = 3"), tulis sebagai garis lurus (cth. 9x + 5y = 450), lukis garis itu **sebagai garis rujukan putus-putus**, kemudian gelongsor selari daripadanya ke bucu optimum. Slaid patut tunjuk langkah ini dahulu supaya sama dengan cara guru akan ajar dan cara jawapan ditulis dalam peperiksaan.

Kaedah pekali-jadi-pintasan di bawah (5.1–5.4) dikekalkan sebagai **teknik bantu tambahan** — berguna bila guru mahu garis rujukan yang "kemas" (pintasan integer kecil) tanpa meneka, tetapi bukan kaedah yang modul tunjukkan kepada murid secara eksplisit.

### 5.1 Kaedah pekali menjadi pintasan

Untuk ax + by, ambil **k = a × b**.

- Pintasan-x = b (pekali y)
- Pintasan-y = a (pekali x)

Peraturan hafalan: **pekali y jadi pintasan-x, pekali x jadi pintasan-y.**

Contoh: P = 3x + 5y, k = 15. Garis melalui (5, 0) dan (0, 3).

### 5.2 Pekali besar atau ada faktor sepunya

1. Ringkaskan dahulu. 20x + 30y menjadi 2x + 3y.
2. k = 2 × 3 = 6. Pintasan (3, 0) dan (0, 2).
3. Jika garis terlalu kecil, darabkan k dengan pengganda. k = 60 memberi pintasan (30, 0) dan (0, 20).

Pengganda tidak mengubah cerun.

### 5.3 Pekali perpuluhan

Darabkan dahulu supaya menjadi integer. 2.5x + 4y menjadi 5x + 8y, k = 40.

### 5.4 Amaran

k = a × b boleh menghasilkan garis terlalu kecil atau terlalu besar berbanding skala. Murid menyemak sama ada garis muat dalam graf dan menggunakan pengganda jika perlu.

---

## 6. Mencari Titik Optimum

### 6.1 Kes selanjar (bucu integer)

1. Letak pembaris pada garis fungsi objektif.
2. Gelongsor selari ke bucu paling jauh dari asalan (maksimum) atau paling dekat (minimum).
3. Baca koordinat bucu daripada graf.
4. Sahkan dengan persamaan serentak.
5. Masukkan ke fungsi objektif.
6. Tafsir dalam konteks.

### 6.2 Kes integer apabila bucu berupa perpuluhan

Skop ini **termasuk dalam kurikulum** (disahkan guru).

**Nota penting:** kesemua 11 soalan dalam modul rasmi (7.1 dan 7.2) mempunyai bucu **integer** — tiada satu contoh pun bucu perpuluhan/kes bundar dalam modul. Jadi contoh untuk sub-bahagian ini **perlu dikarang berasingan** (bukan diambil terus daripada modul), dan patut dilabel jelas sebagai "contoh tambahan di luar modul" supaya guru tahu ini bukan soalan modul.

1. Cari bucu dan nilai fungsi objektifnya. Ini memberi **had** kepada jawapan, bukan jawapan.
2. Gelongsor garis objektif sedikit ke dalam rantau dan cari **titik integer pertama yang disentuh**.
3. Jika ada beberapa calon berhampiran, senaraikan, kira nilai fungsi objektif, pilih yang terbaik.
4. **Sahkan** dengan menggantikan ke semua ketaksamaan.

Kesilapan lazim:

- Membundarkan bucu. (3.4, 5.7) dibundar kepada (3, 6) mungkin berada di luar rantau.
- Mengandaikan titik integer paling hampir dengan bucu pasti terbaik.
- Menerima titik integer pada garis putus-putus (ketaksamaan ketat).
- Hanya membaca daripada graf tanpa penggantian.

Perlu dua contoh berdampingan: satu bucu integer, satu bucu perpuluhan.

### 6.3 Kes khas (satu slaid ringkas)

- Tiada rantau tersaur
- Rantau tak terbatas
- Garis objektif selari dengan satu sempadan (banyak titik optimum)

---

## 7. Pemodelan: Ayat ke Ketaksamaan

Langkah wajib: **takrif pemboleh ubah** dahulu ("Biar x ialah bilangan ... dan y ialah bilangan ...").

| Frasa | Simbol |
|-------|--------|
| sekurang-kurangnya, tidak kurang daripada | ≥ |
| tidak melebihi, paling banyak | ≤ |
| lebih daripada | > |
| kurang daripada | < |
| nisbah x kepada y tidak melebihi 2 : 3 | 3x ≤ 2y |
| x tidak melebihi dua kali ganda y | x ≤ 2y |

Sekurang-kurangnya **dua contoh penuh** dari cerita hingga graf. Murid membina ketaksamaan sendiri sebelum graf muncul.

---

## 8. Reka Bentuk UI

### 8.1 Tema

Tema **terang, bersih,** dengan **latar kertas graf halus** pada slaid yang ada graf.

Sebab:
- Projektor bilik darjah pada siang hari melunturkan latar gelap dan garis nipis.
- Latar kertas graf mengaitkan slaid dengan buku latihan murid.
- Tema gelap penuh tidak disyorkan (lemah di projektor, sukar dicetak).

### 8.2 Kod warna objek graf (tetap sepanjang slaid)

Satu kod tetap untuk:
- garis sempadan pepejal
- garis sempadan putus-putus
- rantau tersaur
- garis fungsi objektif
- bucu optimum
- titik integer sah

Mesti boleh dibezakan oleh murid buta warna. Jangan bergantung pada merah dan hijau sahaja. Gabungkan dengan jenis garis, bentuk penanda atau label.

### 8.3 Reka letak

- Graf mengambil sekitar **dua pertiga skrin,** kekal di kiri.
- Panel teks dan kawalan di kanan, ringkas.
- **Skala paksi tetap** dari awal hingga langkah terakhir. Graf tidak berubah saiz atau berpindah apabila garis baharu ditambah. Murid nampak seluruh ruang kerja.
- Saiz tulisan besar (isi sekurang-kurangnya sekitar 28px), satu idea setiap slaid.
- Matematik dipaparkan dengan KaTeX.

### 8.4 Mod

**Versi pertama: mod demonstrasi sahaja** (skala tetap, guru menerangkan).

Mod latihan (murid memilih skala, amaran jika garis terkeluar graf) ditangguhkan ke versi kemudian. Catatan: mod demonstrasi tidak melatih pemilihan skala, yang ialah punca kesilapan murid. Ini perlu ditangani di luar slaid atau dalam versi seterusnya.

### 8.5 Mod lorek (butang togol, tiga pilihan)

**Konvensyen modul rasmi (disahkan daripada modul guru):** dua lapisan serentak, bukan satu sahaja.

1. Sisi **tidak dikehendaki** bagi setiap kekangan dilorek/diisi **kelabu** sebaik garis itu dilukis (ujian titik (0, 0) menentukan sisi mana).
2. Selepas semua kekangan ditambah, rantau sepunya **R** (yang tinggal putih/tidak kelabu) diisi **biru terang** sebagai lapisan akhir dan dilabel "R".

Mod lalai untuk slaid demonstrasi ialah gabungan ini ("tidak dikehendaki" + highlight R), kerana ia yang akan dilihat murid dalam modul guru. Dua mod tambahan berikut dikekalkan sebagai alat mengajar pilihan:

| Mod | Cara paparan | Kegunaan |
|-----|--------------|----------|
| **Tidak dikehendaki + R (lalai, ikut modul)** | Sisi ditolak dilorek kelabu semasa setiap langkah; apabila rantau sepunya terbentuk, ia diisi biru terang dan dilabel R | Sama persis dengan graf dalam modul guru — murid tidak tertukar kebiasaan |
| Dikehendaki (satu warna) | Sisi yang dikehendaki diisi kuning, rantau mengecil apabila kekangan ditambah | Alternatif ringkas jika guru mahu gaya "lorek apa yang dikehendaki" |
| Dikehendaki (warna kekangan) | Setiap kekangan mewarnakan sisi yang dikehendaki dengan **warna garisnya sendiri**, separa lutsinar. **Rantau tersaur ialah bahagian di mana semua warna bertindih**, dengan garis luar bertitik tebal dan label R | Alat mengajar sahaja, supaya murid nampak persilangan sebagai satu rantau yang sama |

Spesifikasi mod warna kekangan:

- Isian separa lutsinar (sekitar 25 peratus) supaya kawasan bertindih kelihatan lebih pekat. Lutsinar mesti dikira oleh pelayar, bukan dilukis tangan.
- Warna isian sama dengan warna garis kekangan (kod warna tetap dalam bahagian 8.2), supaya murid mengaitkan garis dengan sisinya.
- Kekangan tersirat (x ≥ 0, y ≥ 0) tidak diwarnakan, kerana ia sudah ditunjukkan oleh paksi.
- Pada langkah rantau tersaur, isian kuning tidak digunakan. Gantinya, garis luar bertitik tebal dan label **R** di tengah rantau, kerana kuning akan bercampur dengan warna lain dan menjadi keruh.
- Teks langkah ujian berubah: "Warnakan sisi titik ujian dengan warna garis ini". Teks langkah rantau berubah: "R ialah bahagian di mana semua warna bertindih".

Risiko dan had yang perlu diketahui:

1. **Murid tidak akan mempunyai banyak warna di dalam peperiksaan.** Mereka melukis dengan satu pensel. Mod ini menerangkan konsep persilangan, bukan teknik menjawab. Selepas demonstrasi, tukar kepada mod satu warna atau mod tidak dikehendaki supaya murid melihat gaya yang mereka akan gunakan di dewan peperiksaan.
2. **Percampuran tiga atau empat warna boleh menjadi keruh.** Hadkan kepada paling banyak tiga kekangan yang diwarnakan dalam contoh, dan semak kebolehbacaan pada projektor sebenar.
3. **Murid buta warna.** Jangan bergantung pada warna sahaja. Garis luar bertitik dan label R memastikan rantau tetap dapat dikenal pasti, dan setiap garis kekangan kekal berlabel dengan persamaannya.
4. **Pemilihan mod lalai.** Pilih mod lalai selepas konvensyen modul atau skema SPM disahkan. Sehingga itu, mod lalai ialah "tidak dikehendaki".

---

## 9. Interaksi

### 9.1 Pembinaan graf berperingkat (butang "Langkah seterusnya" dan "Langkah sebelumnya")

1. Paksi dan grid kosong
2. Pintasan ditandakan, kemudian garis dilukis (pepejal atau putus-putus)
3. Titik ujian (0, 0) ditunjukkan, kemudian rantau tidak dikehendaki dilorek
4. Ulang untuk garis seterusnya, rantau tersaur terbentuk
5. Bucu dilabel dan koordinat dipaparkan
6. Garis fungsi objektif muncul, boleh digelongsor

Butang undur wajib ada supaya guru boleh berundur apabila murid keliru.

### 9.2 Ciri interaktif

- **Slider k:** gelongsor garis fungsi objektif, nilai k dipaparkan, penanda menunjukkan sama ada garis masih menyentuh rantau.
- **Klik bucu:** koordinat dan nilai fungsi objektif.
- **Togol kekangan:** hidup atau matikan satu ketaksamaan untuk melihat rantau berubah.
- **Togol mod lorek:** tiga pilihan (tidak dikehendaki, dikehendaki satu warna, dikehendaki warna kekangan). Lihat bahagian 8.5.
- **Lapisan titik integer:** togol memaparkan semua titik integer dalam rantau sebagai titik bernombor.
- **Slider k yang berhenti pada titik integer:** penanda menunjukkan titik integer terakhir yang disentuh.
- **Klik titik integer:** semakan setiap ketaksamaan (✓ atau ✗) dan nilai fungsi objektif.
- **Ramalan sebelum pendedahan:** contohnya "Garis ini pepejal atau putus-putus?", "Adakah bucu ini integer?", "Bucu mana optimum?". Beri murid beberapa saat menjawab di kertas.

### 9.3 Slaid "cari kesilapan"

Graf yang sengaja salah (garis putus-putus sepatutnya pepejal, rantau tersalah lorek, bucu tersalah baca) supaya murid terbiasa dengan graf kertas yang tidak sempurna.

---

## 10. Keperluan Teknikal

- **Satu fail HTML yang berfungsi luar talian.** KaTeX dan skrip tertanam, bukan dimuat dari CDN (wifi sekolah tidak boleh diharap).
- **Kawalan:** anak panah, PageUp dan PageDown (penuding klik laser), dan sentuhan.
- **Nisbah paparan:** reka letak tidak boleh pecah pada 4:3 selain 16:9.
- **Aksesibiliti:** kontras tinggi, label selain warna.
- **Semua nilai dikira oleh kod, bukan ditaip tangan:**
  - bucu daripada persilangan pasangan garis
  - kesahan bucu terhadap semua ketaksamaan
  - titik integer dalam rantau (penghitungan kekisi)
  - nilai fungsi objektif dan titik optimum integer
  - Ini mengelakkan ralat jawapan pada slaid.

### 10.1 Model data masalah (cadangan)

Setiap contoh ditakrif sebagai data, dan graf serta jawapan dijana daripadanya:

```json
{
  "id": "contoh-1",
  "pembolehubah": {"x": "bilangan ...", "y": "bilangan ..."},
  "kekangan": [
    {"a": 1, "b": 1, "op": "<=", "c": 10, "ayat": "..."},
    {"a": 1, "b": 0, "op": ">=", "c": 2, "ayat": "..."}
  ],
  "objektif": {"a": 3, "b": 5, "jenis": "maksimum", "label": "P"},
  "integer": true,
  "skala": {"xMin": 0, "xMax": 12, "yMin": 0, "yMax": 12}
}
```

`op` ∈ {`<`, `<=`, `>`, `>=`}. Operator ketat (`<`, `>`) menghasilkan garis putus-putus dan titik pada garis itu tidak sah.

### 10.2 Algoritma yang diperlukan

- Bucu: untuk setiap pasangan garis sempadan, selesaikan persamaan serentak, kekalkan jika memenuhi semua ketaksamaan (dengan toleransi kecil untuk titik pada garis).
- Titik integer: lelar semua (x, y) integer dalam skala, kekalkan yang memenuhi semua ketaksamaan.
- Optimum selanjar: nilai terbaik di bucu.
- Optimum integer: nilai terbaik di titik integer sah.
- Kes khas: rantau kosong, rantau tak terbatas, banyak titik optimum.

---

## 11. Cadangan Struktur Slaid

1. Tajuk dan hasil pembelajaran
2. Soalan pencetus: situasi sebenar yang memerlukan keputusan
3. Roh topik: empat idea teras
4. Fasa 1: satu ketaksamaan (langkah demi langkah)
5. Fasa 2 dan 3: beberapa ketaksamaan, rantau tersaur
6. Kesilapan lazim graf (termasuk slaid cari kesilapan)
7. Fungsi objektif dan garis selari (slider k)
8. Memilih k: peraturan pekali menjadi pintasan
9. Mencari optimum dan mengesahkan bucu
10. Kes integer: bucu integer berbanding bucu perpuluhan
11. Kes khas (tiada penyelesaian, tak terbatas, banyak optimum)
12. Pemodelan: ayat ke ketaksamaan
13. Contoh penuh daripada cerita hingga tafsiran (sekurang-kurangnya dua)
14. Latihan murid dan semakan

---

## 12. Perkara Terbuka

Modul rasmi (dua PDF dalam folder ini) sudah disemak. Status setiap perkara:

1. ~~Konvensyen lorek~~ — **Selesai.** Dua lapisan: tolak sisi tidak dikehendaki dengan kelabu per-kekangan, kemudian isi rantau sepunya R dengan biru terang sebagai lapisan akhir. Lihat bahagian 8.5.
2. **Format kertas graf dan skala dalam peperiksaan** — Belum disahkan sepenuhnya. Modul beri skala khusus setiap soalan (cth. "2 cm kepada 10 orang peserta" / "2 cm kepada 20 buah bekas"), tetapi tiada keperluan skala seragam SPM yang dinyatakan dalam modul ini. Guru perlu sahkan daripada skema SPM jika ada keperluan tambahan.
3. **Standard Pembelajaran rasmi dan susunan topik** — Disahkan daripada modul: 7.1 Model Pengaturcaraan Linear (pemodelan ayat→ketaksamaan sahaja, serta dua soalan yang perlu graf) kemudian 7.2 Aplikasi Pengaturcaraan Linear (kaedah graf 9 langkah penuh + 4 soalan aplikasi). Ini sepadan dengan urutan di bahagian 3.
4. ~~Istilah rasmi~~ — **Selesai.** Modul guna **"rantau tersaur"** dan **"nilai tersaur"** (bukan "rantau boleh laksana"). Sudah dikemaskini di seluruh dokumen ini. Istilah lain yang disahkan: "pemboleh ubah keputusan", "fungsi objektif", "kekangan", "garis padu" (≤/≥), "garis sempadan/putus-putus" (</>).
5. **Skop pengiraan kes khas** — Modul rasmi **tidak** ada contoh tiada rantau tersaur, rantau tak terbatas, atau banyak titik optimum dalam 11 soalannya. Kekal sebagai andaian ia termasuk dalam kurikulum umum SPM, tetapi contoh perlu dikarang berasingan (sama seperti kes integer, bahagian 6.2).
6. **Konteks soalan** — **Selesai.** Konteks sebenar dalam modul: pengeluaran kereta/kolej pelajar/telefon pintar/program kerjaya/gerai makanan/bacaan puisi/komponen elektronik (7.1), dan program motivasi/bekas plastik/arca pasu/kedai perkakasan (7.2). Semua konteks perniagaan/pengeluaran mudah dengan dua pemboleh ubah — boleh jadi rujukan gaya cerita untuk contoh tambahan (kes integer, kes khas) supaya selari dengan nada modul.

---

## 13. Kriteria Penerimaan

- [ ] Satu fail HTML berfungsi luar talian
- [ ] Graf besar, skala tetap, tidak berubah semasa langkah berperingkat
- [ ] Langkah seterusnya dan sebelumnya berfungsi
- [ ] Semua bucu, titik integer dan nilai optimum dikira oleh kod daripada data masalah
- [ ] Slider k dan penanda sentuhan rantau berfungsi
- [ ] Lapisan titik integer dan semakan ketaksamaan berfungsi
- [ ] Satu contoh bucu integer dan satu contoh bucu perpuluhan
- [ ] Slaid cari kesilapan dan slaid kes khas
- [ ] Sekurang-kurangnya dua contoh pemodelan penuh
- [ ] Berfungsi pada 16:9 dan 4:3
- [ ] Kawalan papan kekunci, penuding klik dan sentuhan
- [ ] Warna boleh dibezakan tanpa bergantung pada merah dan hijau
- [ ] Togol tiga mod lorek berfungsi pada semua slaid yang berlorek, termasuk slaid pepejal atau putus-putus
- [ ] Dalam mod warna kekangan, rantau tersaur jelas kelihatan sebagai kawasan semua warna bertindih, dengan label R dan garis luar bertitik
- [ ] Semua istilah dan konvensyen disemak dengan modul

---

## 14. Keputusan Penting: PdP Ikut Modul Sepenuhnya

Arahan guru (disahkan): slaid bukan sekadar alat demo dengan contoh rekaan — ia **PdP sebenar** yang mengikut modul sepenuhnya (modul murid untuk soalan, modul guru untuk graf dan jawapan). Contoh rekaan hanya dibenarkan di **peringkat awal untuk imbas kembali kemahiran asas** (garis pepejal/putus-putus, titik ujian, cara lukis graf) — bukan untuk mengajar kandungan 7.1/7.2 itu sendiri. Selepas imbas kembali, urutan dan kandungan slaid ikut terus 7.1 Soalan 1-7 dan 7.2 Soalan 1-4 daripada kedua-dua PDF, sejajar Standard Pembelajaran 7.1.1 dan 7.2.1 DSKP.

Struktur `lp-slaid.html` sekarang (27 slaid):

| Bahagian | Slaid | Kandungan |
|----------|-------|-----------|
| 1. Imbas kembali asas | Tajuk, Roh topik, pembahagi, lalu 8 slaid kemahiran (pepejal/putus-putus, lukis graf, kesilapan lazim, garis objektif &k, teknik k, semak bucu, kes integer, kes khas) | Contoh rekaan sengaja (bukan soalan modul) — khusus kemahiran asas |
| 2. Modul 7.1 | Pembahagi + Soalan 1-5 (model sahaja, reveal stepwise) + Soalan 6-7 (model + graf rantau R) | Nombor dan ayat terus daripada PDF modul murid |
| 3. Modul 7.2 | Pembahagi + infografik 9 langkah rasmi + Soalan 1 (Program Motivasi) + Soalan 2 (bekas plastik, julat jualan) + Soalan 3 (arca pasu) + Soalan 4 (kedai perkakasan) | Setiap soalan: model → graf R → sub-soalan → optimum/julat. Semua nombor disahkan padan 100% dengan `...ans.pdf` (bucu, nilai, jawapan akhir) |
| 4. Ringkasan | Ringkasan dan latihan | Kekal daripada versi asal |

## 14c. Pembetulan Besar: Scaffolding Perbincangan & Susunan Kemahiran

Arahan guru lanjut (disahkan): kemahiran asas (garis padu/putus-putus, lukis graf, garis objektif, teknik k, semak bucu) **tidak salah sebagai kandungan**, tetapi mesti ditempatkan **kontekstual** (just-in-time) di tempat ia benar-benar diperlukan — bukan dikumpul semua di hadapan sebelum modul bermula. Selain itu, setiap ketaksamaan dalam soalan 7.1/7.2 mesti **keluar satu-satu semasa perbincangan**, dengan ayat rasmi modul ditunjuk dan **frasa pencetus ditonjolkan** (cth. "tidak lebih daripada", "sekurang-kurangnya") sebelum simbol dan ketaksamaan didedahkan — ini scaffolding, bukan terus bagi jawapan. Guru juga minta jadual rasmi modul "Bila Nak Guna &gt;,&lt;,≥,≤,=?" (daripada muka 2 modul murid) dimasukkan terus ke dalam perbincangan.

Perubahan pada `lp-slaid.html` (kekal 27 slaid, susunan baharu):

- **`modelSlide()`/`modelGraphSlide()` ditulis semula**: setiap ayat kekangan rasmi dipaparkan penuh, frasa pencetus (`trigger`) ditonjolkan dalam `<mark>` kuning semasa aktif (state: pending → kelabu malap, active → kuning + soalan "Fikir", done → chip frasa→simbol + ketaksamaan). Semua 7 soalan 7.1 (dan model-intro untuk 7.2 akan datang) guna fungsi ini.
- **Kemahiran diagihkan semula ikut konteks:**
  - Infografik rasmi modul 7.1 (3 langkah bina model + nota padu/putus-putus) + jadual simbol interaktif (reveal satu-satu) kini slaid PERTAMA selepas pembahagi 7.1 — bukan slaid rekaan generik.
  - Demo garis padu/putus-putus (ringkas, 3 langkah) + "Kesilapan lazim melukis graf" dipindah ke **sebelum Soalan 6** (kali pertama 7.1 perlu graf), dengan rujukan terus kepada nota modul yang baru ditunjuk.
  - Garis fungsi objektif/nilai k, teknik bantu k, dan semak bucu dipindah ke **selepas infografik 9-langkah 7.2**, sebelum Soalan 1 (Program Motivasi) — kerana ini konsep langkah 5-8 modul 7.2, bukan kemahiran 7.1.
  - "Contoh integer" dan "Kes khas" (tiada dalam modul) dipindah ke **hujung Bahagian 3**, diberi pembahagi "Tambahan" dengan label jelas supaya guru tahu ia bukan soalan modul.
- Dua pepijat kecil dibetulkan semasa ujian: baris jadual simbol terpapar dua kali (logik `body` diperbaiki), dan `<b>` di dalam kotak "Fikir dahulu" tertukar jadi blok (CSS `.ask b{display:block}` terpakai pada sebarang `<b>` — ditukar kepada `<span>` untuk penekanan simbol).
- Disahkan: 27 slaid × semua langkah dijalankan tanpa ralat JavaScript selepas pembetulan.
- **Lanjutan:** scaffolding frasa→simbol yang sama kini turut dipakai pada model-intro **keempat-empat soalan 7.2** (Program Motivasi, bekas plastik, arca pasu, kedai perkakasan) — bukan hanya 7.1. Setiap soalan 7.2 kini ada 3 langkah tambahan (satu per kekangan I/II/III) sebelum sampai ke graf, menjadikan jumlah langkah setiap soalan 7.2 meningkat (cth. Program Motivasi 4→7 langkah) tetapi bilangan slaid kekal 27.

## 14d. Pembetulan Halus (Maklum Balas Semakan Visual)

Selepas guru semak slaid secara visual, beberapa pembetulan dibuat (kini 26 slaid — "Roh topik" digugurkan):

1. **Nota status dalam slaid tajuk dibuang** (ayat "Versi 2. Istilah..." — nota pembangunan, bukan untuk murid/guru).
2. **Slaid "Roh topik: empat idea teras" digugurkan.** Sebab: modul sendiri dah ada 2 infografik konkrit (3-langkah model 7.1, 9-langkah 7.2) yang buat kerja framing dengan bahasa modul sendiri; abstraksi generik di hadapan jadi berulang.
3. **"Info Tambahan" padu/putus-putus kini infografik visual** — dua rajah SVG kecil (garis pepejal dengan titik hitam padat vs garis putus-putus dengan bulatan kosong) di sebelah teks, bukan teks sahaja. Istilah "padu" disahkan tepat ikut modul (muka 2 modul murid: "garis padu (solid line)").
4. **Baris "bilangan tidak negatif" dalam Latihan Cerita→Model dibetulkan** — asalnya hanya tunjuk y ≥ 0 (x tertinggal), kini tunjuk "x ≥ 2, y ≥ 0" dengan nota x sudah ≥ 2 daripada ayat kedua.
5. **Konsep "titik ujian" diterangkan secara eksplisit** pada slaid padu/putus-putus (sebelum Soalan 6-7): pilih titik bukan pada garis, gantikan ke ketaksamaan asal, benar → lorek sisi itu, salah → lorek sisi sebelah.
6. **"Kesilapan Lazim Melukis Graf" ditukar nada** — ayat "Pernahkah ini berlaku di kelas anda? ... minta murid mengangkat tangan" (dirasakan gimik/tidak sesuai) digantikan dengan tajuk neutral "Semak sebelum serah: kesilapan yang kerap berlaku".
7. **Infografik 9-langkah kini reveal satu-satu** dengan ikon emoji ringkas setiap langkah dan anak panah penyambung antara kad yang didedahkan, langkah semasa diserlah dengan sempadan oren — bukan lagi grid statik 3×3 yang terus penuh.
8. **Pepijat CSS `.ask b{display:block}` dibetulkan di 2 tempat lagi** — mana-mana `<b>` kedua di dalam kotak kuning "Fikir dahulu"/Info Tambahan tertukar jadi blok (reka bentuk asal untuk label sahaja). Semua kejadian lain dalam fail disemak — hanya satu `<b>` label dibenarkan setiap kotak `.ask`; penekanan tambahan guna `<span style="font-weight:700">`.

Disahkan: 26 slaid × semua langkah dijalankan tanpa ralat JavaScript selepas semua pembetulan ini.

**Pembetulan lanjut:** istilah "pepejal" (tertinggal daripada versi awal sebelum istilah modul disahkan) masih muncul di 4 tempat (fungsi `legend()`, slaid padu/putus-putus, Kesilapan Lazim, Tiket Keluar). Semua ditukar kepada **"garis padu"** mengikut istilah rasmi modul (muka 2 modul murid). Disahkan tiada lagi sebutan "pepejal" dalam seluruh fail.

## 14e. Lorekan Kini Scaffolding (Soalan 6 & 7)

Maklum balas guru: fasa graf dalam `modelGraphSlide()` (Soalan 6 dan 7) dahulu terus memaparkan rantau R siap, tanpa murid nampak proses membina. Dibetulkan:

- `modelGraphSlide()` ditulis semula supaya fasa graf kini **satu langkah per garis** (bukan satu langkah untuk semua): bagi setiap kekangan — (a) garis dilukis sendirian dengan label jenis garis (padu/putus-putus) dan sebab, (b) titik ujian diuji dan sisi tidak dikehendaki dilorek kelabu. Selepas semua kekangan selesai, satu langkah akhir memaparkan rantau tersaur R (biru) dengan bucu.
- Soalan 6 kini 11 langkah (3 model + 7 graf berperingkat + info), Soalan 7 sama. Titik ujian ditambah pada data `PS6`/`PS7` (termasuk titik ujian alternatif untuk garis yang melalui asalan).
- Pembetulan lain dalam pusingan ini: ruang kosong pada slaid "Langkah bina model" diisi (kad dan rajah diperbesarkan, ikon ditambah); baris "Biar x = ..., y = ..." dalam Latihan Cerita→Model kini dipisah baris supaya tidak bertindih.
- Disahkan: 26 slaid × semua langkah dijalankan tanpa ralat JavaScript selepas pembetulan ini; graf Soalan 6 dan 7 disahkan visual sepadan dengan pengiraan bucu yang disahkan sebelum ini.

## 14n. Langkah "Pilih k dan Lukis Garis Rujukan" Ditambah + Buang Rujukan "Modul Guru"

Dua pembetulan lanjut:

1. **"Padan dengan jawapan rasmi modul guru"** dan frasa serupa dibuang — janggal untuk guru sebut "modul guru" semasa mengajar sendiri. Hanya satu komen kod dalaman (tidak dipaparkan) yang kekal guna istilah ini.
2. **Langkah "Pilih k dan lukis garis rujukan" ditambah** sebelum langkah gelongsor interaktif, untuk **keempat-empat soalan pengoptimuman 7.2** — mengajar murid proses PENUH: pilih nilai k munasabah (bukan jawapan) → lukis sebagai garis putus-putus (sokongan `kDashed` baharu dalam enjin graf) → *kemudian* baru gelongsor (slaid interaktif sedia ada). Nilai rujukan dipilih hampir dengan apa yang digunakan modul guru:
   - Soalan 1: J = RM4 800 (120x+60y=4800)
   - Soalan 2: J = RM450 (9x+5y=450)
   - Soalan 3: K = RM15 000 (300x+250y=15000)
   - Soalan 4: k = 30 (x+y=30)

Disahkan: 26 slaid tanpa ralat; setiap soalan kini ada 3 langkah akhir (sub-soalan/min → pilih-k-rujukan → gelongsor interaktif) berbanding 2 sebelum ini.

## 14m. Garis Objektif Interaktif untuk Semua Soalan Pengoptimuman

Atas permintaan guru ("setiap soalan yg ada nilai optimum kita buat garis tu interaktif"): langkah akhir (penentuan nilai optimum) bagi **keempat-empat soalan 7.2** (Program Motivasi, bekas plastik, arca pasu, kedai perkakasan) kini ada **slaid interaktif k** (bukan graf statik sahaja) — murid boleh gelongsor sendiri dan nampak:
- Garis bergerak secara langsung mengikut nilai k/J/K yang ditetapkan.
- Status masa-nyata (hijau = garis masih bertemu rantau R, "ada pilihan sah"; merah = garis dah keluar rantau, "tiada pilihan sah").
- Bucu digelang emas secara automatik apabila k tepat sama dengan nilai optimum.

Slaid bermula pada nilai optimum (padan jawapan rasmi), murid boleh gelongsor ke kedua-dua arah untuk terokai sendiri kenapa itu titik optimum. Saiz julat slaid disesuaikan ikut skala setiap soalan (0-12000 untuk Program Motivasi, 0-1200 untuk bekas plastik, 0-30000 untuk arca pasu, 0-100 untuk kedai perkakasan).

Disahkan: 26 slaid tanpa ralat; diuji gerakkan slider pada Soalan 1 — status bertukar masa-nyata daripada "nilai maksimum" kepada "ada pilihan sah, gelongsor lagi" apabila k dikurangkan.

## 14l. PEPIJAT PENTING Dibetulkan: Soalan 2 Tak Padan Modul Guru + Saiz Graf Konsisten

**Pepijat nyata ditemui oleh guru:** slaid "Julat jumlah jualan" (7.2 Soalan 2) memaparkan **RM880**, tetapi jawapan rasmi modul guru ialah **RM877**. Punca: modul baca bucu maksimum daripada graf sebagai **(53, 80)** (anggaran graf, nombor bulat — juga munasabah kerana bilangan bekas mesti integer), bukan persilangan algebra tepat (53⅓, 80) yang kod kira secara automatik. 9(53)+5(80)=877, bukan 9(53⅓)+5(80)=880.

Pembetulan:

1. **Slaid ditulis semula** — langkah "Julat jumlah jualan" tunggal (jadual 4 bucu) dipecah kepada **dua langkah berasingan**: (c) Jualan minimum (bucu (0, 50), terbuka, RM250) dan (c) Jualan maksimum (gelongsor garis objektif, baca graf ≈(53, 80), RM877) — **bukan lagi jadual bucu**, sebaliknya kaedah gelongsor garis objektif/baca-graf, konsisten dengan cara semua soalan 7.2 lain diajar (Program Motivasi, arca pasu, kedai perkakasan).
2. **Jadual bucu (teknik senarai semua bucu) tidak lagi diajar sebagai kaedah utama** di mana-mana slaid 7.2 — guru jelas minta ia hanya jadi alternatif jika perlu, bukan kaedah pengajaran. Nota jelas ditambah: "Bucu sebenar ialah (53⅓, 80) — tetapi bilangan bekas mesti integer, jadi dibundarkan ke bawah supaya kekal dalam R, sejajar modul guru."
3. **Amaran untuk soalan akan datang:** mana-mana bucu algebra yang bukan integer perlu disemak dan dibundarkan mengikut cara modul baca graf (bukan terus guna nilai algebra tepat) sebelum dipaparkan sebagai jawapan akhir — ini kesilapan yang perlu dielak pada sebarang kerja lanjut.

## 14k1. Saiz Graf Diselaraskan

Atas permintaan guru ("besarkan sedikit dan tekal, mudah nak tgok" — pancaran projektor): semua graf satu-panel diselaraskan kepada **700×620** (daripada pelbagai saiz 640-760 sebelum ini), panel dua-sisi (demo padu/putus-putus) 420×470, panel tiga-sisi (kes khas) 410×390. Disahkan 26 slaid tanpa ralat selepas perubahan.

## 14k. Titik Satu-satu dengan Kaedah x=0/y=0 Dijelaskan + Saiz Fon Projektor

Maklum balas guru: (1) titik patut keluar satu-satu, dan kaedah memilih x=0 atau y=0 penting diajar sendiri; (2) slaid dipancar di hadapan kelas — pastikan saiz fon maksimum ruang supaya murid di belakang nampak.

**Titik satu-satu:** `graphStepInfo()` kini kenal pasti **tiga jenis kekangan**: `simple` (garis menegak/mendatar, 4 fasa, tiada titik diajar), `origin` (garis melalui asalan, 6 fasa, satu titik rujukan sahaja kerana asalan sendiri sudah jelas), dan `standard` (garis dua-pintasan biasa, **7 fasa**) — untuk `standard`, fasa "cari titik" kini dipecah kepada dua:
- **Gantikan x = 0 dahulu** — kira dan plot HANYA titik pertama, dengan sebab "pilih x=0 dahulu (senang kira)".
- **Gantikan y = 0 kemudian** — kira dan plot titik kedua, titik pertama kekal kelihatan, jadual koordinat lengkap dua lajur.

Ini mengajar explicit kaedah pemilihan nilai (bukan terus bagi dua titik sekali gus).

**Saiz fon projektor:** beberapa saiz fon dibesarkan untuk kelihatan jelas dari jauh — bungkusan teks utama model-intro 19px→22px (6 tempat), baris ketaksamaan belum didedah 17px→19px, label simbol 19px→21px, jadual koordinat 18px→22px, kad infografik 9-langkah (nombor, emoji, teks) dibesarkan ~10-15%.

Disahkan: 26 slaid × semua langkah tanpa ralat; Soalan 6 disahkan — garis 1 (simple) terus ke padu/putus-putus, garis 2 (standard) tunjuk x=0 dan y=0 berasingan dengan titik bertambah satu-satu, garis 3 (origin) kekal satu langkah titik, bucu akhir tetap (1,1), (2,0), (6,0), (6,6).

## 14j. Pembetulan Lanjut (Kredit, Istilah, Jadual, Garis Mudah)

Empat pembetulan daripada maklum balas guru:

1. **Garis mudah (x=c atau y=c) langkau fasa "cari titik".** Guru betul: tiada perlu ajar cari titik untuk garis menegak/mendatar ringkas seperti x≤6 — ia terus nampak. `graphStepInfo()` kini kira **bilangan fasa berlainan setiap kekangan** (4 fasa untuk garis mudah [a=0 atau b=0], 6 fasa untuk garis dua pemboleh ubah), guna array `offsets` untuk pemetaan dinamik `gt`→(kekangan, fasa). Antara 11 soalan, hanya Soalan 6 ada satu garis mudah (x≤6); semua yang lain kekal 6 fasa.
2. **Kredit "Panitia Matematik Tambahan, SM Sains Banting"** ditambah pada slaid tajuk, bawah "Matematik Tambahan".
3. **"Diserlah/serlah" ditukar balik kepada "dilorek/lorek"** di semua tempat (termasuk slaid imbas kembali padu/putus-putus) — istilah modul dan skema SPM konsisten guna "lorek", walau dalam mod "rantau dikehendaki".
4. **Jadual koordinat** menggantikan ayat panjang "Gantikan x=0...Gantikan y=0..." — fungsi `ptsTable()` baharu bina jadual 3-baris (Titik / x / y) secara automatik daripada `c.pts`, dipaparkan di bawah ayat arahan ringkas. Lebih jelas berbanding teks berterusan.

Disahkan: 26 slaid × semua langkah tanpa ralat; Soalan 6 disahkan — garis 1 (x≤6) terus ke soalan padu/putus-putus tanpa titik dipaparkan awal, garis 2 tunjuk jadual koordinat dengan jelas, bucu akhir kekal (1,1), (2,0), (6,0), (6,6).

## 14i. Fasa "Cari Titik" (Kemahiran Paling Asas)

Maklum balas guru: ramai murid bermasalah pada langkah paling asas — menentukan titik untuk lukis garis lurus. Dibetulkan: `renderGraphStep()` kini **6 fasa setiap kekangan** (bukan 4), fasa baharu disisip di hadapan:

1. **Tanya titik** — tunjuk kekangan dan persamaan garis, tanya "macam mana nak cari titik untuk lukis garis ini?" (petunjuk: gantikan x=0, kemudian y=0). Graf masih kosong untuk garis ini.
2. **Dedah titik** — tunjuk pengiraan (`c.how`, teks eksplisit setiap kekangan) dan plot dua titik (`c.pts`) di atas graf — garis masih BELUM dilukis, hanya dua titik.
3. **Tanya padu/putus-putus** (titik kekal kelihatan)
4. **Dedah garis** — garis dilukis menyambung dua titik tadi
5. **Tanya titik ujian/lorek**
6. **Dedah lorek**

Setiap kekangan dalam semua 11 soalan (PS6, PS7, P3, P4, P5, P6) kini ada medan `pts` (dua titik rujukan) dan `how` (ayat penjelasan gantian) tersendiri — termasuk kes khas garis menegak (x=6: "tidak kira nilai y, x kekal 6") dan garis melalui asalan (x=3y: "pilih satu titik lain, cth y=30, x=90"). `gSteps` bertukar daripada `gm*4+1` kepada `gm*6+1` (cth. Soalan 6: 17→23 langkah), automatik untuk semua slaid kerana guna `graphStepInfo()` dinamik.

Disahkan: 26 slaid × semua langkah dijalankan tanpa ralat; graf Soalan 6 disahkan visual langkah demi langkah (titik keluar dahulu tanpa garis, garis sebelumnya kekal lengkap dengan labelnya), bucu akhir kekal (1,1), (2,0), (6,0), (6,6).

## 14h. Fikir Dahulu Sebelum Dedah (Scaffolding Ditambah Baik)

Maklum balas guru: soalan "Fikir Dahulu" mesti keluar SEBELUM jawapan (garis/lorekan) ditunjuk, bukan selepas atau serentak. Dibetulkan:

- `renderGraphStep()` (dipakai semua 11 soalan) kini **4 fasa setiap kekangan** (bukan 2): (1) tanya padu/putus-putus — garis belum dilukis; (2) dedah garis dengan sebab; (3) tanya titik ujian/sisi mana diserlah — lorekan belum ditunjuk; (4) dedah pengiraan dan lorekan. `gSteps` bertukar daripada `gm*2+1` kepada `gm*4+1`, automatik meningkatkan bilangan langkah setiap soalan (cth. Soalan 6: 11→17 langkah) tanpa perlu ubah mana-mana slaid panggilan (semuanya guna `graphStepInfo()` secara dinamik).
- Slaid imbas kembali padu/putus-putus (sebelum Soalan 6-7) turut disusun semula kepada 4 langkah dengan susunan sama: tanya → dedah substitusi → tanya klasifikasi+konsep titik ujian → dedah lorekan.
- Pepijat `<b>` di dalam kotak "Fikir Dahulu" (CSS `.ask b{display:block}`) muncul lagi pada teks baharu ini — dibetulkan dengan `<span style="font-weight:700">` di semua tempat baharu.

Disahkan: 26 slaid × semua langkah dijalankan tanpa ralat JavaScript; graf Soalan 6 disahkan visual langkah demi langkah — graf kosong semasa soalan, garis/lorekan hanya muncul selepas klik seterusnya, bucu akhir kekal (1,1), (2,0), (6,0), (6,6).

## 14g. Mod Lorek Lalai Ditukar

Atas arahan guru, mod lorek lalai ditukar daripada "tidak dikehendaki" kepada **"rantau dikehendaki"** (`mode='required'`). Kesan:

- Setiap langkah "titik ujian dan lorek" dalam `renderGraphStep()` kini serlah **sisi dikehendaki** (biru) secara progresif, bukan lorek kelabu sisi ditolak. Teks penerangan dibuat responsif kepada mod (`reqMode` check) supaya ayat sentiasa padan dengan visual, dalam kedua-dua mod jika guru tukar guna butang "Lorek" atau kekunci.
- Slaid imbas kembali padu/putus-putus (sebelum Soalan 6-7) turut ikut mod global ini secara automatik.
- Togol mod (butang "Lorek: ...") masih berfungsi untuk guru tukar semula ke "tidak dikehendaki" jika perlu semasa kelas.

Disahkan: 26 slaid dijalankan tanpa ralat selepas pertukaran; graf Soalan 6 disahkan visual — bucu kekal sama (1,1), (2,0), (6,0), (6,6).

## 14f. Menu Navigasi

Ditambah atas permintaan guru: butang **"☰ Menu"** (atau kekunci **M**) pada bar bawah membuka overlay penuh skrin yang menyenaraikan semua slaid, dikumpulkan ikut bahagian (tajuk pembahagi jadi header hijau). Klik mana-mana item terus lompat ke slaid itu (langkah 1) dan menu tertutup automatik. Tutup dengan butang ✕, klik luar panel, atau kekunci Escape. Ini membolehkan guru lompat terus ke mana-mana soalan semasa kelas tanpa kena tekan "Seterusnya" berulang kali.

**Kemas kini:** scaffolding lorekan-per-garis kini dipakai juga pada **keempat-empat soalan 7.2** (Program Motivasi, bekas plastik, arca pasu, kedai perkakasan), bukan hanya Soalan 6-7. Logik dikongsi melalui fungsi generik baharu `graphStepInfo()` dan `renderGraphStep()` (diekstrak daripada `modelGraphSlide`), supaya tiada pertindihan kod antara fasa 7.1 dan 7.2. Titik ujian ditambah pada data P3-P6 (termasuk titik ujian alternatif untuk garis yang melalui asalan). Semua 11 soalan kini konsisten sepenuhnya: model (frasa→simbol) → graf (garis→titik ujian→lorek, satu-satu) → rantau R → (untuk 7.2) sub-soalan dan optimum. Disahkan semua nilai optimum kekal padan modul rasmi (RM8 400, RM21 000, 75 buah, julat RM250–RM880) selepas refactor.

## 14b. Status Versi

`lp-slaid.html` kini **Versi 3** — PdP penuh ikut modul (lihat bahagian 14). Sejarah ringkas:

- **Versi 2:** istilah "rantau tersaur"/"nilai tersaur", warna R biru terang (bukan kuning), kaedah garis rujukan k sebagai kaedah utama.
- **Versi 3 (semasa):** struktur disusun semula ikut modul sepenuhnya — 27 slaid:
  - Semua 7 soalan 7.1 (model; Soalan 6-7 tambah graf rantau R) dibina sebagai slaid reveal-stepwise guna fungsi generik `modelSlide()` / `modelGraphSlide()`.
  - Semua 4 soalan aplikasi 7.2 dibina penuh (model → graf R → sub-soalan → optimum/julat), setiap satu disahkan padan 100% dengan jawapan rasmi `...ans.pdf`:
    - Soalan 1 (Program Motivasi): bucu (60, 20), min guru 10, maks guru 50, yuran maks RM8 400.
    - Soalan 2 (bekas plastik): julat jualan RM250 < J ≤ RM880 (bucu (0,50) terbuka, (160/3,80) tertutup).
    - Soalan 3 (arca pasu): bucu optimum (20, 60), untung maks RM21 000; (c)(i) min pasu B = 15 unit.
    - Soalan 4 (kedai perkakasan): bucu optimum (15, 60), jumlah maks 75 buah; (d)(i) maks penyembur = 20 buah.
  - Slaid pembahagi ("Bahagian 1/2/3") dan satu slaid infografik 9-langkah rasmi (teks sahaja, daripada modul) menandakan peralihan antara imbas kembali asas dan kandungan modul sebenar.
  - Pembetulan kecil: jarak gridline paksi kini automatik elak label bertindih pada domain besar (cth. skala 0-170).
- Disahkan: semua 27 slaid × setiap langkah dijalankan dalam pelayar tanpa ralat JavaScript; graf utama disahkan visual sepadan dengan rajah dalam `...ans.pdf`.

Belum ada dalam versi ini:

- Mod lorek warna kekangan (bahagian 8.5)
- Mod latihan (murid memilih skala)
- Slaid "cari kesilapan" interaktif
- Pengesahan format skala seragam peperiksaan (perkara terbuka #2 di bahagian 12)
- Kemas kini kecil: label bucu pada beberapa graf besar (Soalan 3, Soalan 2) sedikit rapat antara satu sama lain pada skrin kecil — tidak menjejaskan ketepatan, hanya kekemasan visual

Claude Code boleh sambung daripada fail ini untuk tambah item di atas.
