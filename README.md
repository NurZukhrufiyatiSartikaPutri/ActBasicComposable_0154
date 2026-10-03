# Tugas Basic Composable - Jetpack Compose

## Identitas

| Keterangan | Data |
|---|---|
| Nama | Nur Zukhrufiyati Sartika Putri |
| NIM | 20240140154 |
| Mata Kuliah | Pemrograman Aplikasi Mobile |
| Materi | Basic Composable |
| Repository | ActBasicComposable_0154 |

---

## Deskripsi

Project ini dibuat untuk memenuhi tugas praktik Jetpack Compose pada materi **Basic Composable**.

Pada project ini diterapkan beberapa konsep dasar Jetpack Compose, seperti:

- `Composable`
- `Box`
- `Column`
- `Row`
- `Image`
- `Text`
- `Modifier`
- `Alignment`
- `Padding`
- `Spacer`
- `Arrangement`
- `Preview`

Project terdiri dari implementasi layout dasar menggunakan `Column`, `Row`, dan `Box`, kombinasi beberapa layout, serta halaman login sederhana yang menggunakan gambar sebagai background, logo, judul, dan informasi identitas mahasiswa.

---

## Screenshot Hasil Mengikuti Arahan Modul

Screenshot berikut merupakan dokumentasi implementasi materi dari modul yang diterapkan ke dalam Android Studio, khususnya pada file `TataLetak.kt` dan `MainActivity.kt`.

Struktur dan konsep implementasi mengikuti contoh yang diberikan pada modul, seperti penggunaan `Column`, `Row`, `Box`, serta kombinasi dari beberapa layout tersebut.

Karena beberapa contoh layout dari modul diterapkan dan dikembangkan dalam satu project, susunan kode pada editor menjadi lebih padat dibandingkan tampilan contoh yang ditampilkan secara terpisah pada modul. Perbedaan tersebut merupakan penyesuaian penyusunan kode dalam project dan tidak mengubah konsep maupun fungsi dasar dari contoh yang diberikan.

### Implementasi TataLetak.kt

Kode pada `TataLetak.kt` menerapkan beberapa contoh layout yang terdapat pada modul, yaitu:

- `TataletakColumn`
- `TataletakRow`
- `TataletakBox`
- `TataletakColumnRow`
- `TataletakRowColumn`
- `TataletakBoxColumnRow`

Pada implementasi terakhir, bagian `TataletakBoxColumnRow` juga dikembangkan dengan penambahan pengaturan jarak, ukuran komponen, warna, serta gambar agar hasil tampilan lebih mudah dibaca pada emulator.

### Implementasi MainActivity.kt

`MainActivity.kt` digunakan untuk memanggil composable dari `TataLetak.kt` sehingga hasil implementasi dapat dijalankan dan diuji melalui emulator Android Studio.

### Dokumentasi Kode

Screenshot berikut merupakan dokumentasi kode terbaru yang telah diterapkan pada project.

<img width="884" height="494" alt="TataLetak" src="https://github.com/user-attachments/assets/f8eee0f1-cc0d-42b0-b506-87a910499055" />

<img width="886" height="525" alt="TataLetak" src="https://github.com/user-attachments/assets/28607026-051c-486a-bf93-5cd1d03acf78" />

<img width="876" height="527" alt="TataLetak" src="https://github.com/user-attachments/assets/d79f90c5-04eb-4c81-bba1-c6c7109cc554" />

<img width="881" height="494" alt="TataLetak" src="https://github.com/user-attachments/assets/dd9beb72-47a9-4f08-b01c-c24666472e28" />

<img width="881" height="563" alt="TataLetak" src="https://github.com/user-attachments/assets/f7a21a50-0b85-4d29-b456-6c8a14cddea3" />

<img width="878" height="556" alt="TataLetak" src="https://github.com/user-attachments/assets/dc5ff4cd-c91f-4d6a-9239-b34eab22c6ea" />

<img width="885" height="527" alt="TataLetak" src="https://github.com/user-attachments/assets/44a6b348-41d7-478a-abf8-74b75cb3e296" />

<img width="887" height="512" alt="TataLetak" src="https://github.com/user-attachments/assets/8636bb90-77c3-4c62-9883-d092deab88cd" />

<img width="881" height="502" alt="TataLetak" src="https://github.com/user-attachments/assets/d65eeb45-a0e8-4fb0-89e0-c30cdfe4c622" />

<img width="884" height="520" alt="TataLetak" src="https://github.com/user-attachments/assets/cab4a8c2-9b16-4744-be20-7352bb4c664c" />

<img width="887" height="560" alt="TataLetak" src="https://github.com/user-attachments/assets/f9e2097d-c6f0-4376-9dc0-e2f63b9d6396" />

<img width="881" height="563" alt="TataLetak" src="https://github.com/user-attachments/assets/bf07800c-49d8-4d99-a26e-fe75a46eb7f6" />

> Screenshot di atas menunjukkan implementasi materi Basic Composable yang telah diterapkan ke dalam project Android Studio.

---

## Hasil Implementasi Basic Composable

Berikut merupakan hasil implementasi `TataletakBoxColumnRow` setelah dijalankan melalui emulator Android Studio.

<img width="200" height="426" alt="Hasil Basic Composable" src="https://github.com/user-attachments/assets/29bdc265-7b64-414b-9440-956da66e2619" />

Tampilan tersebut menerapkan kombinasi beberapa komponen layout, yaitu:

- `Box`
- `Column`
- `Row`
- `Image`
- `Text`
- `Spacer`

Selain mengikuti struktur layout dari materi, beberapa bagian tampilan disesuaikan melalui pengaturan ukuran, jarak, warna, dan posisi komponen agar hasil implementasi lebih rapi dan mudah dibaca pada emulator.

---

## Hasil Implementasi Halaman Login

Project juga memiliki halaman login sederhana yang dibuat menggunakan Jetpack Compose.

<img width="193" height="407" alt="Hasil Halaman Login" src="https://github.com/user-attachments/assets/66aad344-9aba-46ff-a262-a5f7b324c78f" />

Tampilan halaman login menampilkan:

- Background halaman login
- Judul **Login**
- Subjudul halaman login
- Logo UMY
- Nama mahasiswa
- NIM mahasiswa
- Foto profil
- Layout menggunakan `Box` dan `Column`

---

## Struktur Project

```text
app/
└── src/
    └── main/
        ├── java/
        │   └── com/
        │       └── example/
        │           └── pertemuan3/
        │               ├── MainActivity.kt
        │               ├── TataLetak.kt
        │               ├── Tugas.kt
        │               └── ui/
        │
        └── res/
            └── drawable/
                ├── gambar_utama.jpeg
                ├── music.png
                ├── notasbalok.webp
                └── profile_image.png
