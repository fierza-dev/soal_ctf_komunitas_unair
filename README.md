
# Cara Mengunduh dan Mengakses Repositori GitHub

Repositori GitHub dapat diakses dengan berbagai cara, tergantung pada kebutuhan Anda. Berikut adalah tiga metode yang dapat Anda gunakan:

---

## **Metode 1: Mengunduh ZIP (tanpa Git)**

1. **Buka Repositori GitHub**  
   Akses halaman repositori di GitHub. Contoh: `https://github.com/username/repository-name`.

2. **Klik Tombol "Code"**  
   Di halaman utama repositori, cari tombol berlabel **Code** di bagian kanan atas daftar file.

3. **Pilih "Download ZIP"**  
   Klik **Download ZIP** dari menu dropdown yang muncul setelah menekan tombol **Code**.

4. **Ekstrak File ZIP**  
   Setelah unduhan selesai:  
   - Gunakan aplikasi seperti **WinRAR**, **7-Zip**, atau alat bawaan sistem operasi untuk membuka file ZIP.  
   - Ekstrak isi file ZIP ke folder pilihan Anda.

---

## **Metode 2: Clone Repositori dengan Git**

Menggunakan Git memungkinkan Anda untuk mengelola repositori secara dinamis.

### **1. Install Git (Jika Belum Terinstal)**  
   - **Windows**:  
     Unduh installer dari [Git-SCM](https://git-scm.com/) dan ikuti proses instalasi.  
   - **Linux**:  
     Jalankan perintah berikut di terminal:
     ```bash
     sudo apt install git  # Untuk Ubuntu
     sudo yum install git  # Untuk CentOS
     ```  
   - **macOS**:  
     Instal Git menggunakan Homebrew:  
     ```bash
     brew install git
     ```

### **2. Salin URL Repositori**  
   - Buka halaman repositori di GitHub.  
   - Klik tombol **Code**, lalu salin URL di bawah bagian **HTTPS** (contoh: `https://github.com/username/repository-name.git`).

### **3. Clone Repositori**  
   - Buka **terminal** atau **Command Prompt**.  
   - Navigasikan ke folder tujuan menggunakan perintah:  
     ```bash
     cd path/to/folder
     ```  
   - Jalankan perintah berikut untuk mengunduh repositori:  
     ```bash
     git clone https://github.com/username/repository-name.git
     ```  
   - Semua file repositori akan diunduh ke folder baru.

---

## **Metode 3: Mengunduh File Tunggal**

Jika Anda hanya membutuhkan satu file, ikuti langkah berikut:

1. **Pilih File**  
   Akses file yang diinginkan di repositori GitHub.

2. **Klik Tombol "Raw"**  
   Setelah file terbuka, klik tombol **Raw** di kanan atas.

3. **Simpan File**  
   File akan ditampilkan dalam format mentah di browser.  
   Klik kanan pada halaman, lalu pilih **Save As (Simpan Sebagai)** untuk menyimpannya ke komputer Anda.
