# ============================================
# 💻 PRAKTIKUM 1 — MENJALANKAN SYNTAX DASAR PYTHON
# ============================================

# Menampilkan teks
print("Hello, Python!")

# Operasi aritmatika
a = 10
b = 5
print("Hasil penjumlahan:", a + b)

# Input sederhana
# (Jika dijalankan di Jupyter/Colab, input dapat menunggu masukan)
nama = input("Masukkan nama Anda: ")
print("Halo,", nama)



# ============================================
# 💻 PRAKTIKUM 2 — TIPE DATA PYTHON
# ============================================

# Tipe data dasar
nama_pengguna = "Rafi"      # string
umur = 20                   # integer
tinggi = 170.5              # float
mahasiswa = True            # boolean

print(type(nama_pengguna))
print(type(umur))
print(type(tinggi))
print(type(mahasiswa))

# Konversi tipe data
angka = "100"
angka_int = int(angka)
angka_float = float(angka)

print(angka_int)
print(angka_float)



# ============================================
# 💻 PRAKTIKUM 3 — OPERATOR, INPUT, DAN OUTPUT
# ============================================

# Operator aritmatika
x = 15
y = 4

print("Tambah:", x + y)
print("Kurang:", x - y)
print("Kali:", x * y)
print("Bagi:", x / y)
print("Modulus:", x % y)
print("Pangkat:", x ** y)

# Program sederhana menggunakan input
nama_siswa = input("Masukkan nama Anda: ")
nilai1 = int(input("Masukkan nilai pertama: "))
nilai2 = int(input("Masukkan nilai kedua: "))

rata_rata = (nilai1 + nilai2) / 2
print(f"Halo {nama_siswa}, nilai rata-rata kamu adalah {rata_rata}")
