#tugas bahasa pemrograman pertemuan 5

<br>
Nama : Muhammad Aldiansyah <br>
NIM : 312210118<br>
Kelas : TI.22.B1<br>

### DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Install Python| [Click Here](#Install-Python)|
| 2 | latihan 1 | [Click Here](#Latihan-1) |
| 3 | latihan 2 | [Click Here](#Latihan-2) |
| 4 | latihan 3 | [Click Here](#Latihan-3) |

## Install Python
1. download python pada web Resmi python [di sini](https://python.org)
![download python](https://user-images.githubusercontent.com/115919203/197144332-2f65b3c3-be9c-4e9f-b923-afad3cece58b.PNG)

2. buka lalu centang bagian *add python to PATH* lalu klik install now
![install python](https://user-images.githubusercontent.com/115919203/197144433-632f1b7c-2849-455d-a0e5-6d59ae14247f.PNG)
![install python2](https://user-images.githubusercontent.com/115919203/197144497-575b1145-6545-44e1-9452-43c8edc745dc.PNG)

3. Instalasi Selesai, klik close
![install success](https://user-images.githubusercontent.com/115919203/197144532-57d919b7-a316-4a76-b64e-9fa47666d0b0.PNG)
## Latihan 1
* buat file latihan1.py
* tulis kode seperti contoh
![sc latihan 1](https://user-images.githubusercontent.com/115919203/197143512-44883ba0-65fb-4031-9f77-cb0a3f298e79.PNG)

```python
#menampilkan tulisan 'Hello' di layar
print("Hello")
#menampilkan tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* klik tombol run
* maka akan muncul program yang dijalankan
![run latihan1](https://user-images.githubusercontent.com/115919203/197142752-48615e51-fff0-4e22-9d75-5d6b8ef989c3.PNG)


```
Hello
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py
* tulis kode seperti contoh
![sc latihan 2](https://user-images.githubusercontent.com/115919203/197142882-432d148a-6e66-4856-ae17-a23e0f4848be.PNG)


``` python
# menjumlahkan dua bilangan menggunakan variabel a & b
a = 8
b = 6

print("Variabel a =",a)
print("Variabel b =",b)
print("hasil penjumlahan a + b =", a+b)
```


* klik tombol run
* maka akan muncul program yang dijalankan
![run latihan2PNG](https://user-images.githubusercontent.com/115919203/197143080-b9e6f539-e92e-4074-b74e-8597523b4d39.PNG)



```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* buat file latihan3.py
* tulis kode seperti contoh
![sc latihan 3](https://user-images.githubusercontent.com/115919203/197143120-c8bf92bd-d5fc-4959-91cf-6fd0fce3e340.PNG)



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
* klik tombol run
* maka akan muncul program yang dijalankan, jangan lupa masukan angka
![run latihan3](https://user-images.githubusercontent.com/115919203/197143160-b920e9ad-0d32-4b42-ac83-18b3a1ca351b.PNG)


```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```
