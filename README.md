# WordCounter

`WordCounter` adalah proyek Java yang digunakan untuk menghitung jumlah kemunculan setiap kata dalam sebuah teks yang diberikan, mempertahankan kapitalisasi kata agar tampil secara gramatikal sesuai teks asli, serta menyediakan total jumlah kata secara keseluruhan.

## Fitur

- Menghitung jumlah kemunculan setiap kata dalam teks dan mempertahanakan kapitalisasi kata.
- Menampilkan jumlah setiap kata dalam teks secara teratur sesuai bentuk text yang dimasukkan.
- Menghitung dan menampilkan total jumlah kata dari teks yang diberikan.

## Struktur Kelas
- **MainPanel**
  Kelas utama berisi main metode yang memanggil metode-metode function yang ada pada kelas `WordCounter`.
    - `main` digunakan untuk menginisialisasi fungsi metode di kelas `WordCounter`
- **WordCounter**
  Kelas yang mengimplementasikan antarmuka `WordCounterInterface`. Berisi metode-metode untuk menghitung kata, menampilkan hasil, dan menghitung total jumlah kata.
    - `countWords` merupakan metode yang digunakan untuk menghitung text yang sudah diinputkan.
    - `splitTextIntoWords` merupakan metode yang digunakan untuk memecah text menjadi beberapa kata-kata.
    - `updateWordCount` merupakan metode yang digunakan untuk mengupdate jumlah kata.
    - `displayWordCount` merupakan metode yang digunakan untuk mendisplay tiap kata dari text.

- **WordCounterInterface**
  Antarmuka yang mendefinisikan metode yang perlu diimplementasikan dalam kelas `WordCounter`, berupa :
    - `countWords`
    - `splitTextIntoWords`
    - `updateWordCount`
    - `displayWordCount`

## Prasyarat

Pastikan Anda memiliki:
- **Java JDK** versi 8 atau lebih baru
- **Maven** (opsional, jika ingin mengelola dependensi atau membangun proyek)

## Petunjuk Penggunaan

### 1. Clone Repository

Jika Anda menggunakan Git untuk mengunduh proyek ini, gunakan perintah berikut:

```bash
git clone https://github.com/AlyxxHander/Testing.git
