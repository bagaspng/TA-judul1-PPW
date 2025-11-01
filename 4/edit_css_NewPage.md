## 2 - Menambahkan File CSS ke Repository

### 🔹 Langkah-langkah

#### 1. Tambahkan File ke Staging Area
Gunakan perintah berikut untuk menandai file CSS yang ingin disimpan ke dalam commit.

```
git add custom.css
```
Perintah di atas menambahkan file custom.css ke staging area agar siap dikomit dan disimpan ke repository.

#### 2. Buat Commit
Setelah file ditambahkan, simpan perubahan tersebut ke repository lokal dengan pesan commit.

```
git commit -m "css page kritik saran"
```
Pesan commit "css page kritik saran" digunakan untuk memberi keterangan bahwa perubahan yang dilakukan adalah penambahan atau pembaruan pada halaman Kritik & Saran melalui file CSS.


#### 3. Kirim Perubahan ke GitHub
Gunakan perintah berikut untuk mengunggah commit dari repository lokal ke repository di GitHub.
```
git push -u origin main
```
Opsi -u berfungsi untuk menghubungkan branch lokal dengan branch main di GitHub. Dengan begitu, pada push berikutnya kamu cukup menggunakan perintah git push tanpa harus menuliskan nama remote dan branch lagi.

💡 Hasil Akhir
Setelah perintah di atas dijalankan, file custom.css berhasil diunggah dan tersinkronisasi ke repository GitHub pada branch main.



<img width="803" height="315" alt="Screenshot 2025-11-01 222141" src="https://github.com/user-attachments/assets/ca3ea445-ae20-45fb-9008-f51f7e49d48d" />
