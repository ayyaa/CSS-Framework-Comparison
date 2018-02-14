# Perbandingan Framework CSS
---
## Framework CSS
**Framework CSS** adalah kumpulan fungsi/prosedur dan class yang sudah siap pakai. untuk memulai kita tidak perlu membuat  class atau fungsi dari awal, kita dapat hanya memanggil komponen yang sudah ada. 
Isi dari Framework CSS sendiri adalah kode `html`, `CSS` dan `Javascript` yang digunakan untuk membuat situs web.
Fungsi lain dengan Menggunakan Framework CSS adalah menghemat waktu dan tenaga tentunya. 
Framework CSS sangat banyak, disini akan membandingkan antara `Bootstrap 4`, `Foundation 6` dan `Tailwind CSS`. Booststrap 4 merupakan versi terakhir dari Bootstrap, Foundation 6 juga Versi terakhir dari Foundation.

## `Tailwind CSS` dan framework lain
**Tailwind CSS**  berbeda dari kerangka seperti Bootstrap, foundation, atau Bulma, tailwind bukanlah sebuah UI Kit.
tailwind tidak memiliki tema default, dan ada tidak ada built-in komponen UI.

Tailwind bukanlah kerangka kerja yang dilengkapi dengan menu pradesain widget untuk membangun sebuah web.Tapi jika ingin  memulai untuk menerapkan desain kustom dengan identitas sendiri, Tailwind cocok untuk itu.

Tailwind ditulis dalam PostCSS dan dikonfigurasi dalam JavaScript, tailwind lebih dari sebuah CSS framework, tailwind lebih ke mesin untuk membuat desain sistem.

## persamaan Framework CSS `Bootstrap 4` dan  `Foundation 6` 
- Keduanya merupakan Framework yang bersifat open source dan dirilis dibawah lisensi MIT
- Keduanya memiliki sistem grid 12 kolom
- Keduanya responsif dan mobile - fisrt Framework
- Keduanya memiliki komponen pra tulis
- Sass sebagai prepocessor CSS

## Perbandingan Framework CSS `Bootstrap 4` dan  `Foundation 6` 
ada beberapa aspek yang dapat menjadi perbandingan antara kedua jenis Framework CSS ini diantara adalah:

### 1. Popularitas
diantara ketiga jenis framework, ada jenis framework yang menjadi sangat populer digunakan oleh pengembang yang tercatat di GitHub dengan Bintang tertinggi.

|Bootstrap 4| Foundation 6| Tailwind CSS |
|------| --------------| ---------- |
| 121.837 bintang di GitHub | 26.975 bintang di GitHub |3890 bintang di GitHub |
 
 ### 2. Komunitas Pengguna
 Fungsi dari adanya Komunitas adalah, apabila kita menemui kendala apa pun saat menggunakan frammework, kita akan dengan mudah menemukan solusinya dengan bertanya di beberapa komunitas yang tersedia.
 
Bootstrap 4| Foundation 6| 
|------| --------------|
|Komunitas bootstrap sangat besar  | Tidak sebesar bootstrap tapi cukup berkembang |22.227 bintang di GitHub |
 
### 3. Dokumentasi
Dokumentasi adalah semacam pedoman penggunaan, Intruksi maupun penjelasan beberaoa fitur yanga ada.

|Bootstrap 4| Foundation 6| 
|------| --------------| 
|Sangat detil, jelas dan lengkap. Dokumentasi memuat baik dari instalasi, persiapan dan contoh template. Bootstrap memiliki dokumentasi yang lebih terorganisir |Foundatin juga memiliki dokuemtasi tapi kurang jelas dan kurang teroganisir  |
 
 ### 4. Primary CSS Units
Kedua kerangka kerja menggunakan em dan rem sebagai unit CSS utama. em dan rem adalah unit CSS relatif yang membantu mengukur ukuran elemen relatif terhadap ukuran font yang cukup membantu saat membuat desain responsif.

|Bootstrap 4| Foundation 6| 
|------| --------------| 
| Bootstrap menggunakan piksel sebagai unit CSS namun kemudian pada Bootstrap versi 4, ia menggantinya dengan satuan em dan rem.|   Foundation menggunakan rem sebagai unit CSS utama |

### 5. Kustomisasi
Untuk kemudahan kustomisasi dijelaskan pada tabel ini.

|Bootstrap 4| Foundation 6| 
|------| --------------| 
| Komponen di Bootstrap sudah dipoles dengan baik dan siap pakai. Tidak banyak hal yang dilakukan dalam styling| Foundation memberi kebebasan pengembang untuk melakukan kustomisasi/pengaturan. Pengaturan styling di foundation lebih mudah dibanding dengan Bootstrap. | 

### 6. Dukungan Browser
ada banyak brwser yang *support* terhadap framework ini, diantaranya.

|Bootstrap 4| Foundation 6| 
|------| --------------| 
|   **Mobile** --> Chrome - Android and iOS, Firefox - Android, Safari - iOS, Android Browser & WebView - Android | Chrome, Firefox, Safari, Opera, Mobile Safari, IE Mobile
|**Desktop** --> Chrome - Mac/Wi, Firefox - Mac/Win, IE9+ - Win (IE9 limitations), Opera - Mac/Win, Safari - Mac | IE 9+, Android Browser 2.3+ |

### 7. CSS Reboot

|Bootstrap 4| Foundation 6| 
|------| --------------| 
|   reboot.css (_reboot.scss)| normalize.css|  

### 8. Grid dan Responsif
untuk ketiga framework sudah responsif

||Bootstrap 4| Foundation 6| 
|----|------| --------------| 
|Gutter-free row syntax | Tidak Tersedia | Tersedia |
|Centered syntax | Tidak Tersedia | Tersedia.
|Based Width | Fluid (0, 34em, 48em, 62em, 75em | Fluid (max-width 75rem default)

**Gutter-free row syntax Foundation**
```sh
<div class="row large-collapse medium-uncollapse [custom]-collapse">
```
**Centered syntax Foundation**
```sh
<div class="row">
  <div class="small-3 small-centered columns">3 centered</div>
</div>
```
