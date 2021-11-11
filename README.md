# labpy03 (Algoritma/ Penjelasan)

# latihan1
## Program untuk menampilkan n bilangan acak yanng lebih kecil dari 0.5

### penjelasan alur program:
Masukan program untuk menampilkan bilangan acak yanng lebiih kecil dari 0.5 seperti berikut

1. print("Tampilkan n bilangan acak yang lebih kecil dari 0.5") - adalah perintah untuk menampilkan judulnya.

2. jumlah = int(input("Masukkan jumlah n: ")) - adalah perintah untuk menginput nilai n tersebut

3. import random - adalah perintah untuk mengimport built-in random yang telah tersedia di python

4. for i in range(jumlah): - adalah perintah untuk i sebagai integer dalam baris jumlah

5.    print("data ke", i+1,"=",(random.uniform(0.1,0.5))) - adalah perintah untuk menampilkan hasil yang telah di input dengan ketentuan random uniform mulai dari nilai 0.1 sampai 0.5

### Berikut contoh gambar programnya:

![Gambar 1](screenshot/ss1.png)

setelah membuat program, kemudian "RUN" program dan masukan nilai N (Berapa banyak  data yg di  inginkan). lalu program akan menampilkan hasil data bilangan acak yanng lebih  kecil dari 0.5 sebanyak yang anda inginkan.

### Berikut contoh hasil dari prrogram saat dijalankan:

![Gambar 2](screenshot/ss2.png)

SELESAI


# latihan2
## Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan

### Penjelasan alur program:
Masukan program untuk menampilkan bilangann terbesar dari sebuah data yang di input seperti berikut

1. print("Menampilkan bilangan terbesar dari n buah data yang diinput") - adalah perintah untuk menampilkan judul program

2. max = 0 - adalah perintah untuk menampilkan nilai max yang adalah 0

3. while True: - adalah perintah untuk pengulangan hingga waktu yang tidak ditentukan

4.      a = int(input("Masukkan Bilangan: ")) - adalah perintah untuk menginput nilai integer

5.   if max < a: - adalah perintah untuk tipe data if atau jika, maksimal nilai lebih kecil dari a atau integer

6.      max = a - perintah untuk nilai maximal sama dengan a atau integer

7.    if a ==0: - perintah untuk tipe data if atau jika a sama dengan 0 maka

8.      break - perintah untuk mengakhiri pengulangan, jadi jika menginput nilai 0 maka pengulangan berakhir atau selesai

9. print("Bilangan Terbesar Adalah: ", max) - adalah perintah untuk menampilkan hasil bilangan yang terbesar dari angka-angka yang telah terinput

### Berikut contoh gambar programnya:

![Gambar 3](scrreenshot/ss3.png)

Setelah membuat program, kemudian "RUN" program dan masukan  nilai yang di  inginkan satu persatu. Data akan langsung terhenti dan akan menampilkan hasil jika telah menginput nilai 0 (nol).

### Berikut contoh dari hasil program setelah dijalankan:

![Gambar 4](screenshot/ss4.png)

SELESAI


# Program1
## Program untuk meenghitung laba investasi

### Penjelasan alur program:
Masukan program untuk menghitung laba investasi seperti berikut

print("Laba Investasi") - adalah untuk menampilkan judul

x = int(input("Uang Modal Awal: ")) - adalah untuk menginput nilai x sebagai modal awal

a = 0*x - a adalah bulan pertama, karena bulan pertama belum memiliki laba, jadi masih 0 dikali dengan x nilai uang modal awal

b = 0*x - b adalah bulan kedua, karena bulan kedua belum memiliki laba, jadi nilai x dari uang modal dikali dengan 0

c = 0.01*x - c adalah bulan ketiga, dan sudah memiliki laba 1%, jadi ditulis 0.01 bentuk sederhana dari 1% dikali dengan modal atau uang awal dengan nilai x

d = 0.01*x - d adalah bulan keempat, dan labanya 1%, jadi ditulis 0.01 dikalikan dengan nilai x yang adalah uang awal atau modal

e = 0.05*x - e adalah bulan kelima, dan laba pada bulan kelima sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

f = 0.05*x - f adalah bulan keenam, dan laba pada bulan keenam sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

g = 0.05*x - g adalah bulan ketujuh, dan laba pada bulan ketujuh sebesar 5%, maka ditulis 0.05 dikalikan dengan nilai x untuk nilai uang awal atau modal

h = 0.02*x - h adalah bulan kedelapan, dan laba pada bulan kedelapan sebesar 2%, maka ditulis 0.02 dikalikan dengan nilai x untuk nilai uang awal atau modal

y=[a,b,c,d,e,f,g,h] - adalah untuk menentukan syarat y yang berisi a,b,c,d,e,f,g,h

for i in range(len(y)): - adalah untuk perulangan data dengan isi data y, dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke urutan yang diinputkan dari data y

    print("Laba Bulan Ke",i+1 ,"sebesar: ",y[i]) - untuk menampilkan hasil laba dari bulan ke 1 sampai terakhir

z=(a+b+c+d+e+f+g+h) - Z untuk data yang berisi hasil penjumlahan laba dari bulan pertama sampai bulan ke delapan

print("Jumlah Laba Selama 8 Bulan: ",z) - menampilkan hasil dari jumlah laba

### Berikut contoh gambar perogramnya:

![Gambar 5](screenshot/ss5.png)

Setelah membuat program, kemudian "RUN" program dan masukan  jumlah uang modal awal yanng telah di tentukan. setelah memasukan jumlah uang modal maka data akan menghitung hasil persentasi sesuai dengan program.

### Berikut contoh hasil dari program setelah di jalankan:

![Gambar 6](screenshot/ss6.png)