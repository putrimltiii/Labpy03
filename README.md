# Labpy03
# Praktikum 03
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

![Bespem per 7 (2)](https://github.com/user-attachments/assets/5f1823df-601d-4681-a317-eebbf96273d8)

Penjelasan Alur algoritma pada program diatas:

1. Inisialisasi awal:

      *modal_awal = 10000000

      *laba_bulanan = [] (list kosong untuk menyimpan laba per bulan)

      *total_laba = 0

2. Perulangan untuk bulan 1-8:

      *Menggunakan for loop for bulan in range(1, 9)

      *Perhitungan laba berdasarkan kondisi:

         *Bulan 1-2: laba = 0 (belum ada laba)

         *Bulan 3-4: laba = 1% dari modal awal (0.01 × modal_awal)

         *Bulan 5-7: laba = 5% dari modal awal (0.05 × modal_awal)

         *Bulan 8: laba = 2% dari modal awal (0.02 × modal_awal)

      *Setiap laba bulanan ditambahkan ke list laba_bulanan

      *Total laba diakumulasi

3. Menampilkan hasil:

      *Menggunakan enumerate untuk menampilkan laba per bulan

      *Format output: "laba bulan ke-[nomor_bulan] sebesar: [jumlah_laba]"

      *Di akhir menampilkan total laba keseluruhan

Dari output yang terlihat:

      *Bulan 1-2: Rp 0

      *Bulan 3-4: Rp 1.000.000

      *Bulan 5-7: Rp 5.000.000

      *Bulan 8: Rp 2.000.000

Total laba: Rp 19.000.000

Program ini mensimulasikan perhitungan laba bulanan dari sebuah investasi dengan persentase keuntungan yang berbeda-beda tiap periodenya.

![Baspem per 7 (3)](https://github.com/user-attachments/assets/72d40e7b-0eab-4cae-aa3f-6e87ad3e9a76)

alur algoritma dari kode tersebut:

1. Inisialisasi:
   
      *Program dimulai dengan mendefinisikan fungsi bernama atm_simulator().
   
      *Fungsi ini akan menjalankan program ATM secara berulang.
   
      *Variabel saldo diinisialisasi (tidak ditampilkan dalam kode ini) sebagai saldo awal pengguna.
   
2. Loop Utama:
   
      Fungsi atm_simulator() menggunakan loop while True: untuk terus menampilkan menu ATM selama pengguna tidak memilih untuk keluar.
   
3. Menampilkan Menu:
   
      Di dalam loop, program menampilkan menu ATM yang berisi pilihan untuk "Tarik Uang" dan "Keluar".
   
4. Meminta Input:
   
      Program meminta input dari pengguna untuk memilih menu dengan menggunakan input("Pilih menu (1/2): ").

5. Memeriksa Pilihan:

      *Program memeriksa pilihan pengguna menggunakan if dan elif statement:
   
         *Jika pilihan 1 (Tarik Uang):
   
         *Program meminta input jumlah penarikan dari pengguna menggunakan int(input("Masukkan jumlah penarikan: ")).
   
         *Program memeriksa apakah jumlah penarikan valid:
   
            *Jika jumlah penarikan lebih besar dari saldo: Program menampilkan pesan "Maaf, saldo tidak mencukupi!".
   
            *Jika jumlah penarikan kurang dari atau sama dengan 0: Program menampilkan pesan "Jumlah penarikan tidak valid!".
   
            *Jika jumlah penarikan valid: Program mengurangi saldo dengan jumlah penarikan dan menampilkan pesan "Penarikan berhasil!".
   
            *Jika pilihan 2 (Keluar): Program menampilkan pesan "Terima kasih telah menggunakan ATM!" dan keluar dari loop menggunakan break.
   
            *Jika pilihan tidak valid: Program menampilkan pesan "Pilihan tidak valid!".
   
7. Mengulang Loop:
   
Setelah proses pilihan selesai, program kembali ke awal loop untuk menampilkan menu ATM kembali.
