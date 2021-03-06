# Tugas Besar Mata Kuliah Etika dan Hukum TIK Kelas TI-3B

Membuat buku tentang cybercrime

## Materi :
**1. Pengertian cybercrime**
   - Fadli
   - Aditya

**2. pengaturan cybercrime**
   - Idris
   - Imron
   - Andre

**3. jenis dan metode kejahatan**
   - Frans
   - Nadhifa
   - Eko

**4. teori cybercrime**
   - Berlian
   - Gandha
   - Tholib

**5. kasus cybercrime di Indonesia dan negara lain**
   - Atina
   - Andy
   - Iqbal

**6. penegakan hukum cybercrime di Indonesia**
   - Dika
   - Angel
   - Clara

**7. perbandingan cybercrime Indonesia dgn negara lain (disertai tabel)**
   - Dirga
   - Devan
   - Ananta
   - Eri

**8. perlindungan hukum cybercrime**
   - Tri
   - Bagus
   - Beby
   - Ryan

## Lampiran :
1. UU yg mengatur
2. Ada daftar isi, cover, daftar pustaka, footnote, ringkasan buku

## Deadline :
1. Buku dikumpulkan minggu 12
2. Deadline materi minggu 11

>**Catatan:**  
>- Tidak mengumpulkan sesuai deadline = *auto-skip*.  
>
>- Pengumpulan Materi menggunakan format `.md` / [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) agar penulisan materi lebih mudah.

## Tutorial

### 1. Branching

Branch biasanya digunakan untuk menambahkan fitur diluar master, sehingga master aman dari kesalahan, dan apabila sudah selesai branch tersebut dapat digabungkan kembali ke master

```bash
# membuat branch
git branch [nama-branch]

# pindah ke branch yang sudah dibuat
git checkout [nama-branch]

# menambah commit pada branch yang sudah dibuat
git add .
git commit -m "pesan"

# kembali ke branch master
git checkout master

# menggabungkan commit pada branch yang dibuat ke master
git merge [nama-branch]

# menyimpan perubahan master ke remote repository
git push origin master
```

### 2. Pull Request

Pull request merupakan cara untuk menggabungkan branch lain ke master namun penggabungannya dilakukan pada remote repository

```bash
# membuat branch
git branch [nama-branch]

# pindah ke branch yang sudah dibuat
git checkout [nama-branch]

# menambah commit pada branch yang sudah dibuat
git add .
git commit -m "pesan"

# menyimpan perubahan branch baru ke remote repository
git push origin [nama-branch]

# menghapus branch baru apabila sudah di merge di remote repository
git branch -d [nama-branch]
```

### 3. Rangkuman

Berikut rangkuman beberapa perintah yang digunakan pada tutorial - tutorial diatas

```bash
# membuat branch baru
git branch [nama-branch]

# pindah ke branch baru
git checkout [nama-branch]

# menghapus branch
git branch -d [nama-branch]

# menggabungkan commit pada branch yang dibuat ke master
git checkout master
git merge [nama-branch]
```
