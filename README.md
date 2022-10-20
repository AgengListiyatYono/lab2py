# tugas python pertemuan5

Repository ini digunakan untuk memenuhi Tugas Bahasa Pemrograman Pertemuan-5<br><br>
Nama :  Ageng Listiyat Yono <br>
NIM : 312210082<br>
Kelas : TI.22.B1<br>

### DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Install Python| [Click Here](#Install-Python)|
| 2 | latihan 1 | [Click Here](#Latihan-1) |
| 3 | latihan 2 | [Click Here](#Latihan-2) |
| 4 | latihan 3 | [Click Here](#Latihan-3) |

## Install Python
1. Download python pada web Remis python [di sini](https://python.org)

![download python](https://user-images.githubusercontent.com/47426095/196260682-ab4d3c1a-b0d9-47ea-8737-db2b81b58410.PNG)

2. Buka lalu centang bagian *add python to PATH* lalu klik install now
![install python](https://user-images.githubusercontent.com/47426095/196260923-3c52d21d-89d4-465d-b0d2-ae11e1906d6c.PNG)
![install python2](https://user-images.githubusercontent.com/47426095/196261110-f1242a77-73a2-46e8-91d4-c428e9bdfd7e.PNG)


3. Instalasi Selesai, klik close

![install success](https://user-images.githubusercontent.com/47426095/196261213-d2d12ebd-893a-4e82-9715-28422d4fcc7b.PNG)


## Latihan 1
* buat file latihan1.py

![buat file latihan1](https://user-images.githubusercontent.com/47426095/196225814-00e353e7-4bf8-49fa-a0bf-dab618a3f01d.PNG)

* tulis kode seperti contoh

![sc latihan1](https://user-images.githubusercontent.com/47426095/196225840-74027b54-1759-44aa-a97a-24e6491f8ed9.PNG)
```python
#Menampilkan tulisan 'Hello' di layar
print("Hello")
#Menampilkan tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196225970-24f8e914-92ba-4f2b-8094-e67844053d1c.PNG)

* Maka akan muncul program yang dijalankan

![output latihan1](https://user-images.githubusercontent.com/47426095/196226031-5cf0d83f-7851-4915-8e9a-ba29573e4149.PNG)
```
Hello
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py

![buat file latihan2](https://user-images.githubusercontent.com/47426095/196226746-77ab9834-d5d9-478e-95b9-84c2a5929079.PNG)

* Tulis kode seperti contoh

![sc latihan2](https://user-images.githubusercontent.com/47426095/196226836-40354e47-58b9-41e1-984f-976a927d2750.PNG)
``` python
# Menjumlahkan dua bilangan menggunakan variabel a & b
a = 8
b = 6

print("Variabel a =",a)
print("Variabel b =",b)
print("hasil penjumlahan a + b =", a+b)
```


* klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196226867-b202f7d9-79ae-4577-b93f-8279d92d42a5.PNG)

* Maka akan muncul program yang dijalankan

![output latihan2](https://user-images.githubusercontent.com/47426095/196226922-3323d8f6-6c99-496f-a256-6be4fa13e638.PNG)

```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* Buat file latihan3.py

![buat file latihan3](https://user-images.githubusercontent.com/47426095/196228787-1fa10f4d-ac73-4f1f-a4ba-4f214f2d713b.PNG)

* Tulis kode seperti contoh

![sc latihan3](https://user-images.githubusercontent.com/47426095/196258729-9f8bb060-8d79-4dc9-9371-ce84242b866a.PNG)

```python
#input nilai variabel
a = input("masukan nilai pertama: ")
b = input("masukan nilai kedua: ")

#cetak nilai variabel
print("variabel a = ", a)
print("variabel b = ", b)

#cetak hasil kedua operasi variabel dengan string format
print("Hasil Penggabungan {1} & {0} = ".format(a,b) + str(a)+str(b))

#konversi nilai variabel 
a = int(a);
b = int(b);

print("Hasil penjumlahan {1} + {0} = %d".format(a,b) %(a+b))
print("Hasil pembagian {1} / {0} = %d".format(a,b) %(a/b))
```
* Klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196228887-fddb8a47-afc5-4476-af01-e03a07e849ab.PNG)

* Maka akan muncul program yang dijalankan, jangan lupa masukan angka

![output latihan3](https://user-images.githubusercontent.com/47426095/196228930-50635265-af56-4313-98db-6b3e90d333e1.PNG)
```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```
