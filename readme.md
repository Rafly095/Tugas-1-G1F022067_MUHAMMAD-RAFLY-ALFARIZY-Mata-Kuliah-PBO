# *Tugas 1 Pemrograman Perbasis Objek*
## Nama : Muhammad Rafly Alfarizy
## NPM  : G1F022067

## 1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:(https://github.com/randiijulian/randiijulian/assets/81604461/e32b6d92-7e3a-4323-a0e3-711009112c8e)
- **Source Code** :  
```
for i in range(1, 101):
    if i % 10 == 0:
        print("Muhammad Rafly Alfarizy\nMuhammad Rafly Alfarizy\nMuhammad Rafly Alfarizy")
    else:
        print(i)
```
 - **Output :** 
![alt text](/image/Loop100.png?raw=true)

 - **Penjelasan :** 

1. ```for i in range(1, 101):```: Ini adalah loop for yang akan melakukan for pada variabel i dari 1 hingga 100 .

2. ```if i % 10 == 0:```: Pernyataan if digunakan untuk memeriksa apakah nilai i habis dibagi oleh 10. Dengan kata lain, ini memeriksa apakah i adalah kelipatan 10.

3. Jika kondisi pada langkah 2 terpenuhi (nilai i adalah kelipatan 10), maka blok berikutnya akan dijalankan, yaitu ```print("Muhammad Rafly Alfarizy\nMuhammad Rafly Alfarizy\nMuhammad Rafly Alfarizy")```

4. Jika kondisi pada langkah 2 tidak terpenuhi (nilai i bukan kelipatan 10), maka blok else akan dijalankan: ```print(i)```

## 2 Buatlah program bebas, dengan menerapkan if else pada: a. For Loops b. While Loops
***a. For Loops***

 - **Source Code :** 
```
# Program menggunakan if-else pada for loop
for i in range(1, 6):
    if i % 2 == 0:
        print(f"{i} adalah angka genap")
    else:
        print(f"{i} adalah angka ganjil")
```

 - **Output :**
 ![alt text](/image/For.png?raw=true)

 - **Penjelasan :**
1. ```for i in range(1, 6):``` : Membuat Loop pada variable i dengan range atau jangkau 1 sampai 6 

2. ```if i % 2 == 0:``` : adalah perkondisian jika sisa pembagian variable i oleh 2 adalah 0 maka program ```print(f"{i} adalah angka genap")``` akan dijalankan yang ana akan mengeluarkan output {i} adalah angka genap

3. sedangkan jika sisa pembagian variable i oleh 2 adalah 0 maka program else untuk mengeluatkan output ```print(f"{i} adalah angka ganjil"``` akan dijalankan, yang mana akan menunjukkan bahwa angka tersebut adalah ganjil


***b. while Loops***

- **Source Code :**
```
# Program menggunakan if-else pada while loop

counter = 1 
while counter <= 5: 
    if counter % 2 == 0: 
        print(f"{counter} adalah angka genap")
    else:
        print(f"{counter} adalah angka ganjil")
    counter += 1
```

- **Output :** 
![alt text](/image/while.png?raw=true)

- **Penjelasan :**

1. ```counter = 1 ``` Membuat variable yang bernama counter dengan nilai awal yaitu 1, ```while counter <= 5:``` membuat perulangan pada variable counter dengan menggunakan perulangan while.

2. ``` if counter % 2 == 0: ``` Perkondisian untuk mengecek apakah sisa pembagian ```counter``` oleh 2 adalah 0, jika iya maka akan menjalankan ```print(f"{counter} adalah angka genap")```.

3. sedangkan jika tidak maka akan menjalankan program selanjutnya adalah ```else``` yaitu ```print(f"{counter} adalah angka ganjil"```

34. ```counter += 1:``` Pernyataan ini menambahkan nilai counter sebesar 1 setiap kali loop dijalankan.

## 3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for

- **Source Code :**
```
# Membuat variabel dengan tipe data array (list)
nilai_array = ["R", "a", "f", "l", "y"]

# Menampilkan semua nilai dalam variabel menggunakan perulangan for
for nilai in nilai_array:
    print(nilai)
```

- **Output :**

![alt text](/image/array.png?raw=true)

- **Penjelasan :**

1. nilai_array = ["R", "a", "f", "l", "y"]: Inisialisasi variabel nilai_array sebagai list yang berisi karakter-karakter "R", "a", "f", "l", dan "y". List adalah struktur data yang dapat menyimpan beberapa nilai dalam satu variabel.

2. for nilai in nilai_array:: Inisiasi perulangan for, dimana setiap elemen dalam list nilai_array diakses satu per satu dan ditempatkan dalam variabel nilai.

3. print(nilai): Pernyataan ini mencetak nilai yang sedang dievaluasi dalam setiap iterasi perulangan. Dalam hal ini, akan mencetak karakter "R", kemudian "a", "f", "l", dan "y" secara berurutan.