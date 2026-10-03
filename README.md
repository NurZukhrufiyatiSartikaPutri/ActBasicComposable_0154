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
- `Preview`

Project juga menampilkan halaman login sederhana menggunakan gambar sebagai background, logo, judul, dan informasi identitas mahasiswa.

---

## Screenshot Hasil Mengikuti Arahan Modul

Screenshot berikut merupakan dokumentasi implementasi materi dari modul yang diterapkan ke dalam Android Studio, khususnya pada file `TataLetak.kt` dan `MainActivity.kt`.

Struktur dan konsep kode yang digunakan mengikuti contoh pada modul. Terdapat perbedaan pada tampilan susunan baris kode antara screenshot modul dan Android Studio karena penyesuaian format penulisan serta lebar area editor. Perbedaan tersebut tidak mengubah struktur maupun fungsi dari kode yang diimplementasikan.

### Implementasi TataLetak.kt

Kode pada `TataLetak.kt` mengikuti contoh `TataletakColumn`, `TataletakRow`, `TataletakBox`, serta kombinasi layout lainnya yang terdapat pada modul.

### Implementasi MainActivity.kt

`MainActivity.kt` digunakan untuk memanggil composable dari `TataLetak.kt` sehingga hasil implementasi dapat dijalankan dan diuji melalui emulator Android Studio.

### Dokumentasi

<img width="909" height="492" alt="image" src="https://github.com/user-attachments/assets/f0e40a81-774a-45be-8cae-6699bf15b89d" />


<img width="905" height="512" alt="image" src="https://github.com/user-attachments/assets/c357469b-1392-467e-af64-23dba7ec5f54" />


<img width="907" height="523" alt="image" src="https://github.com/user-attachments/assets/4e2aa0da-3a93-4e24-8073-b01d21e5db61" />


<img width="915" height="523" alt="image" src="https://github.com/user-attachments/assets/e2655422-4697-4efe-8008-d9e34e071f6f" />


<img width="908" height="520" alt="image" src="https://github.com/user-attachments/assets/8eedb61f-5202-4f6a-bda8-0dfd5231a536" />


<img width="920" height="518" alt="image" src="https://github.com/user-attachments/assets/37d0ea24-a09a-4760-8eca-401e2a5c485c" />


<img width="912" height="519" alt="image" src="https://github.com/user-attachments/assets/7e5af831-0aed-4921-857c-d36a39933217" />


<img width="914" height="563" alt="image" src="https://github.com/user-attachments/assets/536058e3-dc04-40b5-98a7-fce7366da01a" />


<img width="912" height="563" alt="image" src="https://github.com/user-attachments/assets/4a9a5bcb-642f-487f-ba88-d9bbb2361f18" />


> Letakkan screenshot modul yang sesuai pada folder `screenshots`.

---

## Hasil Implementasi

Berikut adalah hasil implementasi project pada emulator Android Studio.

<img width="193" height="407" alt="Screenshot 2026-10-03 215422" src="https://github.com/user-attachments/assets/74f2d4e6-f702-4b18-ab1e-8514e159e565" />


Tampilan hasil implementasi menampilkan:

- Background halaman login
- Judul **Login**
- Subjudul halaman login
- Logo UMY
- Area identitas mahasiswa
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
        │               └── Tugas.kt
        │
        └── res/
            └── drawable/
                ├── gambar_utama
                ├── notasbalok
                └── profile_image
