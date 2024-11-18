# Praktikum-4
## Latihan.py
```Buat list sebanyak 5 elemen dengan nilai bebas
1. Buat sebuah list sebanyak 5 elemen dengan nilai bebas
1.akses list:
A. tampilkan elemen ke 3
B. ambil nilai elemen ke 2 sampai elemen ke 4
C. ambil elemen terakhir
2. ubah elemen list:
A. ubah elemen ke 4 dengan nilai lainnya
B. ubah elemen ke 4 sampai dengan elemen terakhir
3. tambah elemen list:
A. ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
B. tambah list B dengan nilai string
C. tambah list B dengan 3 nilai
D. gabungkan list B dengan list A
```
## Penyelesaian
```
Python
# Buat list dengan 5 elemen
list_a= [10, 20, 30, 40, 50]
# Akses list
print("Elemen ke-3:", list_a[2])
# Akses dengan indeks dimulai dari
0
print("Elemen ke-2 sampai ke-4:",
list_a[1:4]) # Slicing: ambil
dari indeks 1 sampai sebelum
indeks 4
print("Elemen terakhir:",
list_a[-1]) # Akses elemen terakhir
# Ubah elemen list
list_a[3] = 60
list_a[3:] = [70, 80, 90] # Ubah
dari indeks 3 sampai akhir
# Tambah elemen list
list_b list_a[1:3] # Ambil
elemen ke-2 dan ke-3 dari list_a
list_b.append("hello") # Tambah
string list_b.extend([100, 110, 120]) #
Tambah beberapa nilai
list_a.extend(list_b) # Gabungkan list_b ke list_a
print("List A setelah perubahan:",
list_a)
```

## Penjelasan:
• Pembuatan List: Kita membuat list list_a dengan 5 elemen angka.

## Akses Elemen:

![image](https://github.com/user-attachments/assets/1b923889-2aa7-438e-a23a-810c114bae71)

## Ubah Elemen:

![image](https://github.com/user-attachments/assets/e0b10014-1720-4675-98ba-a36edcb78207)

## Tambah Elemen:

![image](https://github.com/user-attachments/assets/3124fa33-f346-4657-a798-73ece0a8f10a)

## Hasil:

![image](https://github.com/user-attachments/assets/69a87559-a7b9-4fc0-ab9a-3c2581aa5149)

## Catatan:
```• Indeks: Indeks dalam list Python dimulai dari 0.
• Slicing: Slicing digunakan untuk mengambil bagian dari list. Sintaksnya adalah list[start: end], di mana end tidak termasuk.

•Metode List:
• append(): Menambahkan elemen ke akhir list.
• extend(): Menambahkan beberapa elemen ke akhir list.

Penting untuk diingat:
• Mutable vs Immutable: List adalah objek yang mutable, artinya nilainya dapat diubah setelah dibuat.
•Operasi List: Python menyediakan banyak operasi lain yang dapat dilakukan pada list, seperti insert(), remove(), pop(), dan lain-lain.
```

# Tugas Praktikum

```Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:
• Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
• Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya.
• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
• Buat flowchart dan penjelasan programnya pada README.md.
• Commit dan push repository ke github.
```
## Tampilan Program

![image](https://github.com/user-attachments/assets/713c604c-34b1-46a3-8995-684619980d09)

## Hasil Data Program

![image](https://github.com/user-attachments/assets/17bcca79-710c-4f43-98c3-b9e815a3b62f)

## © Rhendy Zhaky Alvian
email: rhendyzhakyalvian@gmail.com
