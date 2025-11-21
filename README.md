# 📘 Rangkuman Modul Praktikum Basis Data — BAB 1 & 2

## 🔷 BAB 1 — Konversi ER Diagram ke Skema Relasi

### 🎯 Tujuan Pembelajaran
- Memahami proses konversi ERD → skema relasi (tabel).
- Mampu mentransformasi model konseptual ke implementasi database.

### 📌 Aturan Konversi Utama
**1️⃣ Entitas Kuat → Tabel**
- Setiap entitas kuat menghasilkan satu tabel.
- Atribut sederhana → kolom.
- Primary key tetap digunakan sebagai PK tabel.

**2️⃣ Atribut Komposit → Dipecah**
Contoh:  
alamat → alamat_jalan, alamat_kota, alamat_provinsi, alamat_kodepos

**3️⃣ Atribut Multinilai → Tabel Baru**
- Dibuat tabel khusus.
- PK = PK entitas induk + atribut multinilai.

**4️⃣ Relasi One-to-Many (1:N)**
- Foreign key ditempatkan pada sisi “many”.
- FK mereferensi PK sisi “one”.

**5️⃣ Relasi Many-to-Many (N:N)**
- Dibuat tabel penghubung (junction table).
- Isi tabel: FK dari kedua tabel utama.

**6️⃣ Entitas Lemah → Tabel + Foreign Key**
- PK = PK entitas kuat + partial key.
- Wajib memiliki FK ke entitas kuat.

### 📝 Evaluasi
- Tes awal: identifikasi komponen ERD + konversi sederhana.  
- Tes akhir: konversi ERD kompleks ke beberapa tabel relasi.

---

## 🔷 BAB 2 — Pengantar Basis Data & DDL

### 🎯 Tujuan Pembelajaran
- Mengenal MySQL & aplikasi pendukungnya.
- Memahami tipe data dasar MySQL.
- Menguasai perintah DDL (Data Definition Language).

### 💡 Pengenalan MySQL
MySQL adalah DBMS open-source yang cepat, stabil, dan mendukung berbagai sistem operasi.  
Biasanya diinstall melalui XAMPP/LAMPP untuk keperluan praktikum.

### 🔑 Akses MySQL
**Login ke MySQL**
```bash
mysql -u root -p
