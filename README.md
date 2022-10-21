# Tugas Python Pertemuan5

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
* ![kode latihan 1](https://user-images.githubusercontent.com/115475428/197215998-21414cd7-95f2-4eb4-98d0-43668ea69d85.png)

```python
#Menampilkan tulisan 'Hello World' di layar
print("Hello World")
#Menampilkan tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* klik tombol run

![run python](https://user-images.githubusercontent.com/47426095/196225970-24f8e914-92ba-4f2b-8094-e67844053d1c.PNG)

* Maka akan muncul program yang dijalankan

![hasil latihan 1](https://user-images.githubusercontent.com/115475428/197217978-fb789aeb-d2b5-4382-b882-27909ae805b6.png)
```
Hello World
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py

![buat file latihan2](https://user-images.githubusercontent.com/47426095/196226746-77ab9834-d5d9-478e-95b9-84c2a5929079.PNG)

* Tulis kode seperti contoh

![kodelatihan2](https://user-images.githubusercontent.com/115475428/197220151-2b8dd36f-a8e1-43c4-9cc0-b8bee8bf3d52.png)
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
![hasillatihan2](https://user-images.githubusercontent.com/115475428/197220430-d4797f59-df86-47c5-9688-ec9d64199680.png)

```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* Buat file latihan3.py

![buat file latihan3](https://user-images.githubusercontent.com/47426095/196228787-1fa10f4d-ac73-4f1f-a4ba-4f214f2d713b.PNG)

* Tulis kode seperti contoh
![kodelatihan3](https://user-images.githubusercontent.com/115475428/197234062-f7a6a8e8-2e53-4565-a1ab-38aea3bf9a67.png)
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
![hasillatihan3](https://user-images.githubusercontent.com/115475428/197234343-cb5dfdde-edc9-404d-a1fd-e103eb149742.png)


```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```

