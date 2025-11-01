## 2 - Menambahkan dan Mengunggah File ke Repository

### 🔹 Langkah-langkah

#### 1. Tambahkan File ke Staging Area
Gunakan perintah berikut untuk menandai file yang ingin disimpan ke dalam commit.

```
git add html/custom.css 
```
Perintah di atas akan menambahkan file custom.css yang berada di dalam folder html ke staging area agar siap dikomit.


#### 2. Buat Commit

Setelah file ditambahkan, simpan perubahan tersebut ke repository lokal dengan pesan commit.

```
git commit -m "css"
```

Pesan commit digunakan untuk memberi keterangan singkat terhadap perubahan yang dilakukan.


#### 3. Kirim Perubahan ke GitHub

Gunakan perintah berikut untuk mengunggah commit dari repository lokal ke repository di GitHub.

```
git push -u origin main
```

Opsi -u berfungsi untuk menghubungkan branch lokal dengan branch main di GitHub, sehingga pada push berikutnya cukup menggunakan perintah git push saja.


#### 💡 Hasil Akhir

Setelah perintah di atas dijalankan, file custom.css akan tersinkronisasi ke repository GitHub pada branch main.
<img width="1065" height="363" alt="Screenshot 2025-11-01 221638" src="https://github.com/user-attachments/assets/70abf44b-f7f8-46b3-a5e9-b013f8227ff3" />
