
<h1 align="center">Panduan GitHub</h1>

<hr>
Dokumen ini menyajikan panduan yang praktis untuk memulai kerja sama dalam proyek melalui Git dan GitHub. Tujuan dari dokumen ini adalah untuk memungkinkan tim berkolaborasi secara efisien tanpa khawatir untuk menghapus atau menimpa kode rekan-rekan mereka.

<br><br>
<hr>

### Langkah-langkah untuk menghubungkan kode ke repositori baru
1. Inisialisasi Git (jika belum pernah)
    ```text
    git init
    ```
    
2. Sambungkan folder laptop ke GitHub
    ```text
    git remote add origin [link-repository]
    ```
    
3. Ubah nama branch utama menjadi 'main' (standar baru GitHub)
    ```text
    git branch -M main
    ```
    
4. Masukkan semua file ke antrean upload
    ```text
    git add .
    ```
    
5. Simpan perubahan (Commit)
    ```text
    git commit -m "Message"
    ```
    
6. Push (Upload) ke GitHub
    ```text
    git push -u origin main
    ```
 Catatan: Jika muncul error "`remote origin already exists`", abaikan langkah nomor 2 dan lanjut ke langkah 3.


<br><br>
<hr>

### Langkah-langkah untuk repository yang sudah di-clone dan sudah terhubung.
1. Copy repository dari github:
    ```text
    git clone [link-repository]
    ```
    
2. Pastikan kodinganmu sinkron dengan teman tim (opsional tapi disarankan):
    ```text
    git pull origin main
    ```
    
3. Buat branch baru
    ```text
    git checkout -b [Nama-branch]
    ```

    ##### Berpindah ke branch yang lain:
    ```text
    git checkout [Nama-branch]
    ```

4. Masukkan semua file ke antrean upload
    ```text
    git add .
    ```
    
5. Simpan perubahan (Commit)
    ```text
    git commit -m "Message"
    ```
    
6. Push (Upload) ke branch baru
    ```text
    git push origin [Nama-branch]
    ```
 


<br><br>
<hr>

### Langkah-langkah Collaborators Setting di GitHub:
1. Buka repository proyek kamu di GitHub.
2. Klik tab **Settings** (di bagian atas kanan menu repository).
3. Di menu sidebar kiri, pilih **Collaborators**.
4. Klik tombol **Add people**.
5. Ketik `username` GitHub atau email temanmu, lalu pilih akunnya.
6. Klik **Add to repository**.

Penting: Temanmu akan menerima undangan via email atau notifikasi di GitHub (ikon lonceng). Mereka harus menerima (**accept**) undangan tersebut sebelum bisa mulai.
<br><br>
<hr>

