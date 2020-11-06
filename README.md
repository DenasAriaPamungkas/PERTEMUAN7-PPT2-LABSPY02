# PERTEMUAN 7
### NAMA: DIYAN ARUM M
### KELAS: TI. 20. A. 1
### NIM: 312010133
___________________________________________________________________________________

 Pada pertemuan 7 tugas PPT ke-2 ini, saya diberikan beberapa tugas oleh dosen saya yaitu 

![Tugas Praktikum 2](https://user-images.githubusercontent.com/72906579/98377632-a5376480-2077-11eb-914b-7edfddf5d866.png)

untuk mencari sebuah nilai maksimal dari 3 data yang sebelumnya telah diinput, dan setelah mendapat nilai maksimalnya, dirubah menjadi dalam sebuah bentuk flowchart.

## TUGAS PRAKTIKUM 2
Pertama-tama disini saya akan mencoba untuk menginput 3 data dengan menggunakan syntax berikut terlebih dahulu.
```python
a = int(input("Masukkan bilangan 1: "))
b = int(input("Masukkan bilangan 2: "))
c = int(input("Masukkan bilangan 3: "))
```
Masukan syntax tersebut dengan angka yang kalian inginkan. 

![Input](https://user-images.githubusercontent.com/72906579/98377627-a36da100-2077-11eb-92f9-eae34d6ae1e4.png)

Jika sudah mendapat tampilan seperti gambar diatas, maka kalian sudah berhasil menginput ketiga data tersebut. <br>

Langkah selanjutnya adalah mencari tahu nilai terbesar (max) dari ketiga data tersebut. Sebelum memulainya kalian harus memasukan terlebih dahulu berapa jumlah data yang akan kalian kerjakan dari ketiga data tersebut dengan syntax <br>
```python
N=int(input("banyaknya data = "))
```
Karena disini saya diberi tugas mencari nilai max dari ketiga data maka saya akan menggunkan semua data diatas.

Selanjutnya kalian bisa langsung  memasukan syntax ini untuk melengkapi syntax diatas supaya bisa berjalan dengan baik.
```python
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Maka jika digabungkan, cara untuk mencari nilai max dari ketiga data yang diinputkan adalah dengan menggunakan syntax
```python
N=int(input("banyaknya data = "))
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```

