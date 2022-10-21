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
![latihan1](https://github.com/MhmmdAldi19/lab2py/blob/bb9b16c5ca22fde6aa531c6fe7c9cf89182e6663/img/run%20latihan1.PNG)

```python
#menampilkan tulisan 'Hello' di layar
print("Hello")
#menampilkan tulisan 'Saya sedang belajar python' di layar
print("Saya sedang belajar python")
```
* klik tombol run



* maka akan muncul program yang dijalankan


```
Hello
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py



* tulis kode seperti contoh


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



```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* buat file latihan3.py



* tulis kode seperti contoh



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


```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```
