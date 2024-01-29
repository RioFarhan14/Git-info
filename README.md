| Perintah Git                           | Fungsi                                                                                   |
|----------------------------------------|------------------------------------------------------------------------------------------|
| `git init`                             | Memulai repositori Git di direktori aktif.                                               |
| `git add <nama_file>`                  | Menambahkan perubahan pada file ke staging area.                                         |
| `git commit -m "pesan"`                | Merekam perubahan yang ada di staging area menjadi commit.                               |
| `git status`                           | Menampilkan status file dalam repositori (perubahan yang belum di-commit, dll.).         |
| `git log`                              | Menampilkan riwayat commit dalam repositori.                                             |
| `git remote add <nama_remote> <url_remote>` | Menambahkan repositori remote.                                          |
| `git push -u origin <branch>`          | Mengirim perubahan lokal ke repositori remote.                                           |
| `git pull origin <branch>`             | Mengambil perubahan dari repositori remote dan menggabungkannya dengan repositori lokal. |
| `git branch <nama_cabang>`             | Membuat cabang baru dalam repositori.                                                   |
| `git checkout <nama_cabang>`           | Beralih ke cabang tertentu di dalam repositori.                                         |
| `git merge <nama_cabang>`              | Menggabungkan perubahan dari suatu cabang ke dalam cabang utama.                         |
| `git branch -d <nama_cabang>`          | Menghapus cabang lokal yang telah selesai.                                               |
| `git push origin --delete <nama_cabang>` | Menghapus cabang di repositori remote.                                     |
| `git reset --hard <kode_commit>`       | Kembali ke commit tertentu, menghapus perubahan setelahnya.                              |
| `git revert <kode_commit>`             | Membuat revisi baru yang membatalkan perubahan dari commit tertentu.                    |
| `git reset <nama_file>`                | Membatalkan staging dari file sebelum dilakukan commit.                                 |
| `git reset HEAD~1`                     | Membatalkan commit terakhir tanpa menghapus perubahan dalam file.                        |
| `git branch -d <nama_cabang>`          | Menghapus cabang lokal yang telah selesai.                                               |
| `git push origin --delete <nama_cabang>` | Menghapus cabang di repositori remote.                                     |
| `.gitignore`                           | File `.gitignore` digunakan untuk mengabaikan file/folder tertentu dalam repositori.    |
