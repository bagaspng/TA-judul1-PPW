## 3 - Menambahkan File Page Baru ke Repository

### 🔹 Langkah-langkah

#### 1. Tambahkan File ke Staging Area
Gunakan perintah berikut untuk menandai file baru yang akan disimpan ke dalam commit.

```
git add kritik_saran.html
```
Perintah di atas menambahkan file kritik_saran.html ke staging area agar siap dikomit.


####2. Buat Commit
Setelah file ditambahkan, simpan perubahan tersebut ke repository lokal dengan pesan commit.

```
git commit -m "kritik saran page"
```
Pesan commit "kritik saran page" berfungsi sebagai keterangan bahwa perubahan yang dilakukan adalah penambahan halaman Kritik & Saran.


####3. Kirim Perubahan ke GitHub
Gunakan perintah berikut untuk mengunggah commit dari repository lokal ke repository di GitHub.

```
git push -u origin main
```
Opsi -u digunakan untuk menghubungkan branch lokal dengan branch main di GitHub, sehingga pada push berikutnya cukup menggunakan perintah git push tanpa parameter tambahan.

####💡 Hasil Akhir
Setelah perintah di atas dijalankan, file kritik_saran.html berhasil tersinkronisasi ke repository GitHub pada branch main.



<img width="909" height="334" alt="Screenshot 2025-11-01 221858" src="https://github.com/user-attachments/assets/4c9b70c5-aa96-41cd-8814-52cdadde9673" />

