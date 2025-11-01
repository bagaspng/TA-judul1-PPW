## 2 - Membuat File HTML

### 🔹 Langkah-langkah

#### 1. Tambahkan File ke Staging Area
Gunakan perintah berikut untuk menandai semua file yang ingin disimpan ke dalam commit.
```
git add .
```
Perintah git add . digunakan untuk menambahkan seluruh perubahan di direktori kerja ke staging area agar siap dikomit.


#### 2. Buat Commit
Setelah file ditambahkan, simpan perubahan tersebut ke repository lokal dengan pesan commit.
```
git commit -m "html"
```
Pesan commit "html" digunakan untuk memberi keterangan bahwa perubahan yang dilakukan berkaitan dengan penambahan atau pembaruan file HTML.


#### 3. Kirim Perubahan ke GitHub
Selanjutnya untuk mengunggah commit dari repository lokal ke repository di GitHub.
```
git push -u origin main
```
Opsi -u berfungsi untuk menghubungkan branch lokal dengan branch main di GitHub, sehingga pada push berikutnya cukup menggunakan perintah git push saja.


####💡 Hasil Akhir
Setelah perintah di atas dijalankan, semua file yang telah dikomit akan tersinkronisasi ke repository GitHub pada branch main.
<img width="1079" height="333" alt="Screenshot 2025-11-01 221354" src="https://github.com/user-attachments/assets/0b01c188-1a43-49a1-8d01-4bf39cfec7a6" />
