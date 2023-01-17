# Praktikum10

## Nama : Mohamad Irvan Zidni

## NIM : 312210308

## Kelas : TI.22.A.3

## Python String
Penjelasan mengenai python string :

• String adalah jenis yang paling populer di Python.

• Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.

• Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

• Membuat string semudah memberi nilai pada sebuah variabel.

### Mengakses nilai dalam string

• Python tidak mendukung tipe data karakter.

• Untuk mengakses substring, gunakan tanda kurung siku.

Contoh :

Input :

        # Mengakses Nilai dalam String
        var1 = "Hello word!"
        var2 = "Python Programming"
        print("var1[0] : ", var1[0]) # Mengambil Karakter Pertama
        print("var[1:5] : ", var2[1:5]) # Karakter 2 s/d ke-5

Output :

Output akan mengeluarkan karakter pertama dari var1 dan di var2 akan mengeluarkan karakter 2 s/d 5

![Foto](Picture/Contoh%201.png)

### mengupdate string

• Anda dapat “memperbarui” string yang ada dengan (kembali) menugaskan variabel ke string lain.

• Nilai baru dapat dikaitkan dengan nilai sebelumnya atau ke string yang sama sekali berbeda sama sekali.

Contoh :

Input :

        # Mengupdate String
        message = "Hello Wordl!"
        print("Update String : - ", message[:6] + "Python")

Output :

Output hanya akan mengambil karakter 1 s/d 6 dan ditambahkan dengan "Python"

![Foto](Picture/Contoh%202.png)

## Latihan 1

### Penjelasan

• Untuk menghitung jumlah karakter, gunakan fungsi len()

        txt = "Hello World"
        # Menghitung jumlah karakter
        print(len(txt))

• Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [ ] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. 

        txt = "Hello World"
        # Mengambil karakter terakhir
        print(txt[10])

• Untuk mengambil karakter terakhir, gunakan index [-1]. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan index [2:5]

        txt = "Hello World"
        # Mengambil karakter index ke-2 sampai index ke-4 (llo)
        print(txt[2:5])

• Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], ""))

        txt = "Hello World"
        # Menghilangkan spasi pada text tersebut (HelloWorld)
        print(txt.replace(" ", ""))

• Untuk mengubah huruf menjadi besar, gunakan method upper()

        txt = "Hello World"
        # Mengubah text menjadi huruf besar
        print(txt.upper())

• Untuk mengubah huruf menjadi kecil, gunakan method lower()

        txt = "Hello World"
        # Mengubah text menjadi huruf kecil
        print(txt.lower())

• Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace()

        txt = "Hello World"
        # Mengganti karakter H dengan karakter J
        print(txt.replace("H", "J"))

### Output

Output yang dihasilkan adalah

![Foto](Picture/Latihan%201.png)

## Latihan 2
