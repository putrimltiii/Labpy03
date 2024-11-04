# Labpy3
# Praktikum 3
# Putri Melati Ramadhaniati (312410194)

Latihan 1

![BASPEM PER 7 (1)](https://github.com/user-attachments/assets/1222e34e-fa92-4154-a300-f70ab808191c)

Penjelasan Alur algoritma pada program diatas:

1. Program dimulai dengan mengimpor fungsi random dari modul random Python
   
2. Didefinisikan sebuah fungsi bernama generate_random_numbers()
   
3. Alur dalam fungsi:
   
   *Meminta input nilai N dari user
   
   *Menginisialisasi variabel count = 1
   
   *Melakukan perulangan while selama count <= N:

   *Generate angka random antara 0-1 menggunakan random()
   
     *Jika angka random < 0.5:
   
        *Cetak data ke-count beserta nilai randomnya
   
        *Increment count
   
   *Setelah perulangan selesai, cetak "Selesai"
   
4. Program utama memanggil fungsi generate_random_numbers()

   Dari output yang terlihat, ketika dijalankan:

     *User memasukkan N = 5

     *Program menghasilkan 5 angka random yang nilainya < 0.5

     *Setiap angka dicetak dengan format "data ke: [urutan] => [nilai random]"

     *Program berakhir dengan mencetak "Selesai"
   
Program ini pada dasarnya membangkitkan N buah angka random antara 0-1, namun hanya mencetak angka-angka yang nilainya kurang dari 0.5.

