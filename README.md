# labpy03 (Algoritma/ Penjelasan)

## latihan1
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


## latihan2
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


## Program1