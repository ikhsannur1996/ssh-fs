### Tutorial Menggunakan Plugin SSH FS di VS Code

#### Langkah 1: Menginstal Plugin SSH FS

1. **Buka VS Code**: Buka aplikasi Visual Studio Code Anda.
2. **Pergi ke Menu Extensions**: Pergi ke menu **Extensions** di VS Code.
3. **Cari Plugin SSH FS**: Pada kolom pencarian, ketikkan `ssh fs` dan cari plugin **SSH FS**.
4. **Klik Install**: Klik tombol **Install** untuk menginstal plugin SSH FS.

#### Langkah 2: Membuat Konfigurasi SSH

1. **Buka SSH FS Tab**: Setelah plugin SSH FS terinstal, buka tab **SSH FS** di sisi kiri toolbar VS Code.
2. **Buat Konfigurasi Baru**: Klik tombol **Create** untuk membuat konfigurasi baru.
3. **Masukkan Nama Konfigurasi**: Beri nama konfigurasi Anda, misalnya `cse`.
4. **Simpan Konfigurasi**: Klik tombol **Save** untuk menyimpan konfigurasi.

#### Langkah 3: Mengisi Detail Konfigurasi

1. **Masukkan Detail Konfigurasi**:
   - **Username**: Masukkan username Anda.
   - **Root**: Masukkan `/` untuk root directory.
   - **Host**: Masukkan alamat host server, misalnya `loginX.cse.unsw.edu.au`, di mana `X` adalah digit terakhir dari zID Anda.

Contoh:
```
Host cse
  Username z1234567
  Root /
  Host login7.cse.unsw.edu.au
```

2. **Simpan Konfigurasi**: Klik tombol **Save** untuk menyimpan konfigurasi.

#### Langkah 4: Menghubungkan ke Server

1. **Buka Konfigurasi**: Buka list konfigurasi SSH FS di tab SSH FS.
2. **Tambahkan sebagai Folder Kerja**: Klik tombol **Add as workspace folder**.
3. **Masukkan Password**: Masukkan password SSH Anda.
4. **Buka Folder**: Pilih folder yang ingin dibuka dan klik **Open Folder**.

#### Langkah 5: Menggunakan Terminal

1. **Buka Terminal**: Klik tombol terminal di tab SSH FS.
2. **Buka Terminal di Server**: Sebuah terminal akan terbuka di server Anda, dengan direktori awal sebagai home directory.

#### Langkah 6: Mengubah Direktori Awal (Opsional)

1. **Edit Konfigurasi**: Klik tombol **Edit Configuration** di list konfigurasi SSH FS.
2. **Ubah Root Path**: Ubah path root ke direktori yang diinginkan, misalnya `/tmp` untuk melihat file sementara.
3. **Simpan Perubahan**: Klik tombol **Save** untuk menyimpan perubahan.

### Tips Tambahan

- **Membuat Konfigurasi Baru**: Anda dapat membuat konfigurasi baru untuk mengakses direktori lain di server.
- **Menggunakan Multiple Konfigurasi**: Anda dapat membuat konfigurasi lain untuk mengakses direktori yang berbeda, seperti `/tmp` untuk melihat file sementara.

Dengan mengikuti langkah-langkah di atas, Anda dapat menggunakan plugin SSH FS di VS Code untuk mengakses dan mengedit file di server dengan lebih mudah dan efisien.

Citations:
[1] https://www.rumahweb.com/journal/cara-remote-ssh-melalui-visual-studio-code/
[2] https://www.ayongoding.com/remote-server-visual-studio-code/
[3] https://www.cse.unsw.edu.au/~learn/homecomputing/sshfs-remote/
[4] https://code.visualstudio.com/docs/remote/ssh
[5] https://www.nusa.id/knowledge-base/remote-ssh-cpanel-dengan-visual-studio-code/
