# Prak-PBO-Pert10
Tugas 10 - Studi Kasus ATM dengan java
<img width="500" alt="Screenshot 2024-11-14 152331" src="https://github.com/user-attachments/assets/9f313653-d97a-4ac5-a49f-3442cb0746ea">
Jawaban
1.	Tambahkan fitur Ubah PIN
a.
<img width="960" alt="Screenshot 2024-11-14 152809" src="https://github.com/user-attachments/assets/a3cebe1f-1263-42e8-a079-70ce145154c0">
Penjelasan:
pada code ATM.java di bagian showMenu ditambahkan menu baru pada no.5 yaitu ubah PIN

b.
<img width="960" alt="Screenshot 2024-11-14 154916" src="https://github.com/user-attachments/assets/5130ba18-bd81-499e-8f8e-7b162829edd9">
Penjelasan:
pada code tersebut dibuat method changePin(), untuk dipakai sebagai fitur pengubah pin.

c.
<img width="960" alt="Screenshot 2024-11-14 155152" src="https://github.com/user-attachments/assets/2d6a1227-2ec3-41a7-bedd-80ce40a29078">
Untuk hasil running pada gambar tersebut didapatkanlah hasil pada method changePin yang telah dibuat seperti:
1. Meminta user untuk memasukkan PIN lama dan memverifikasinya.
2. Meminta user untuk memasukkan PIN baru dan mengonfirmasinya.
3. Jika semua validasi berhasil, PIN baru disimpan dan pengguna diberi tahu bahwa PIN telah berhasil diubah. Jika ada kesalahan, pengguna akan diberi tahu tentang kesalahan tersebut.

2.	Validasi Saldo Minimal pada saat penarikan
   a. <img width="960" alt="Screenshot 2024-11-14 161537" src="https://github.com/user-attachments/assets/acf091bf-64e6-40ca-addc-c7ca880de438">
   b. <img width="960" alt="Screenshot 2024-11-14 161805" src="https://github.com/user-attachments/assets/f25b894a-b713-44c6-b33b-d5b1d34fee43">
   c. <img width="959" alt="Screenshot 2024-11-14 162328" src="https://github.com/user-attachments/assets/269f7752-0ba6-4fe5-8e96-86bf8392516c">

Penjelasan:
Pada bagian Account.java ditambahkan public static final double MINIMUM_BALANCE = 50000; 
fungsinya untuk membuat saldo minimum penarikan = 50000
Pada bagian Withdrawal.java memodifikasi method execute() untuk memeriksa apakah saldo penarikan tidak kurang dari saldo minimal yaitu 50000
pada bagian output pilih cek saldo untuk memastikan saldo lalu pilih opsi penarikan dan buat penarikan melebihi sisa hasil minimum nya semisal saya 470000.
lalu akan memunculkan teks saldo tidak mencukupi. Saldo minimal yang harus disisakan adalah: 50000
