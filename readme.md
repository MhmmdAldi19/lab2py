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
2. buka lalu centang bagian *add python to PATH* lalu klik install now
3. Instalasi Selesai, klik close



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
