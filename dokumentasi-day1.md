# Dokumentasi Day 1: Building with AI, Managing Change with GitHub

Pemateri: Nugi Farhan (Senior Product Designer)

## Rangkuman Materi

### 1. Prompt Engineering
Prompt itu instruksi yang kita kasih ke AI. Prompt engineering adalah cara
menulis instruksi supaya jawaban AI lebih tepat dan bisa dipakai.

Prompt yang bagus punya 4 bagian:
- **Role**: AI diminta berperan sebagai apa.
- **Task**: tugas yang mau dikerjakan.
- **Context**: kebutuhan dan batasan, misalnya pakai HTML, CSS, dan JavaScript.
- **Format**: bentuk hasil yang diinginkan.

Di materi ada contoh perbandingannya. Prompt "Create student task planner"
hasilnya kurang jelas, sedangkan prompt yang detail hasilnya jauh lebih
sesuai dengan yang kita mau.

### 2. Git dan GitHub
- **Git** adalah aplikasi di komputer untuk mencatat perubahan file (siapa yang
  ubah, kapan, dan apa yang diubah). Dibuat oleh Linus Torvalds tahun 2005.
- **GitHub** adalah website untuk menyimpan repository Git secara online dan
  untuk kerja bareng orang lain.

Singkatnya, Git itu alatnya, GitHub itu tempat penyimpanan online-nya.

### 3. Alur kerja Git
Ada 3 tempat yang dilewati file kita:
1. **Working directory**: folder tempat kita ngoding atau edit file.
2. **Staging area**: tempat "antrean" untuk perubahan yang mau disimpan.
3. **Repository (.git)**: tempat Git menyimpan semua riwayat perubahan.

### 4. Perintah dasar yang dipelajari
| Perintah | Fungsinya |
|---|---|
| `git init` | Membuat repo baru di komputer |
| `git clone "url"` | Mengambil repo dari GitHub ke komputer |
| `git add .` | Memasukkan semua perubahan ke staging area |
| `git commit -m "pesan"` | Menyimpan perubahan ke repository |
| `git push` | Mengirim hasil commit ke GitHub |
| `git pull` | Mengambil perubahan terbaru dari GitHub |

### 5. Setup yang dilakukan
- Install VS Code, lalu cek dengan `code --version`.
- Install Git, lalu cek dengan `git --version`.
- Atur nama dan email Git pakai `git config --global`.
- Buat repo di GitHub, lalu clone ke komputer.

### 6. Praktik
Membuat proyek sederhana bernama **Student Task Planner**, yaitu aplikasi
pencatat tugas dan deadline kuliah. Prosesnya: bikin pakai bantuan AI, simpan
ke Git, push ke GitHub, ubah lagi, lalu push lagi.

## Poin Penting / Pengetahuan Baru
- Prompt yang jelas dan lengkap bikin hasil AI jauh lebih bagus.
- Git dan GitHub itu beda, jangan disamakan.
- Urutan dasarnya: edit file, `git add`, `git commit`, lalu `git push`.
- `git clone` otomatis membuat folder repo di komputer.
- Ketik `code .` di terminal untuk membuka folder langsung di VS Code.
- Kalau mengetik URL tanpa `git clone` di depannya, terminal akan error.

## Pendapat Pribadi tentang Day 1 Proyek Workshop
Menurut saya Day 1 ini seru dan berguna karena langsung praktik, bukan cuma
dengerin teori. Awalnya saya bingung sama terminal dan sempat error karena
lupa mengetik `git clone`, tapi dari situ saya jadi ngerti fungsi tiap
perintah. Saya juga baru sadar kalau cara nulis prompt itu berpengaruh besar
ke hasil AI. Ke depannya saya mau lebih lancar pakai Git, terutama soal branch
dan pull request.