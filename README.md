# Hands-on Multimedia

Repositori ini berisi kumpulan tugas praktikum mata kuliah **Multimedia** yang mencakup beberapa topik pemrosesan data multimedia seperti pengolahan gambar, audio, dan video.

---

## 🧾 Informasi Umum

* **Nama:** Bagas Andreanto
* **NIM:** 122140017
* **Mata Kuliah:** Multimedia
* **Dosen Pengampu:** Martin Clinton Tosima Manullang, Ph.D.

---

## 📁 Struktur Repository

```
Hands-on_Multimedia/
│
├── Worksheets 1/                                               
│   └── data/         
│
├── Worksheets 2/               
│   └── data/
│
└── Hands-on Pemrosesan Audio/   
    ├── data/
    └── output/
```

---

## ⚙️ Cara Menjalankan Kode

### 1. Clone atau Download Repository

Kamu bisa mendownload repository ini dengan dua cara:

**a. Melalui Git (disarankan):**

```bash
git clone https://github.com/username/Hands-on_Multimedia.git
```

**b. Melalui ZIP:**

1. Klik tombol **Code** di bagian atas repository GitHub.
2. Pilih **Download ZIP**.
3. Ekstrak file ZIP ke lokasi yang kamu inginkan.
   Misalnya:

   ```
   C:\Users\<user>\Documents\Hands-on_Multimedia\
   ```

---

### 2. Masuk ke Direktori Proyek

Gunakan terminal atau command prompt:

```bash
cd Hands-on_Multimedia
```

---

### 3. Buat dan Aktifkan Virtual Environment (Python)

Pastikan sudah menginstal **Python 3.8+**.
Kemudian jalankan perintah berikut:

#### Windows:

```bash
python -m venv env
env\Scripts\activate
```

#### macOS/Linux:

```bash
python3 -m venv env
source env/bin/activate
```

---

### 4. Install Dependencies

Setiap folder tugas memiliki file `requirements.txt` yang berisi daftar pustaka yang dibutuhkan.
Masuk ke folder tugas yang ingin dijalankan, lalu jalankan:

```bash
pip install -r requirements.txt
```

---

## ▶️ Menjalankan Setiap Tugas

### 🧩 Worksheets 1

Masuk ke direktori:

```bash
cd "Worksheets 1/src"
```

Jalankan kode:

```bash
python main.py
```

Output hasil akan disimpan di folder `../hasil_output/`.

---

### 🖼️ Worksheets 2

Masuk ke direktori:

```bash
cd "Worksheets 2/src"
```

Jalankan kode:

```bash
python process_video.py
```

Pastikan folder `data/` sudah berisi file input (gambar atau video).
Hasil akan tersimpan di `../hasil_output/`.

---

### 🎵 Hands-on Pemrosesan Audio

Masuk ke direktori:

```bash
cd "Hands-on Pemrosesan Audio/src"
```

Jalankan:

```bash
python audio_processing.py
```

Hasil pemrosesan (misalnya spektrum, grafik, atau file audio hasil filter) akan disimpan di `../hasil_output/`.

---

## 🧩 Catatan Tambahan

* Pastikan semua library sudah terinstal sebelum menjalankan script.
* Disarankan menjalankan setiap tugas di dalam environment yang sama.
* Beberapa tugas mungkin membutuhkan file tambahan (dataset, contoh media). Jika tidak tersedia, gunakan file dummy dengan nama dan format yang sama.

---

## 📚 Lisensi

Dokumen dan kode dalam repository ini digunakan untuk keperluan akademik mata kuliah **Multimedia** dan tidak diperuntukkan untuk distribusi komersial.
