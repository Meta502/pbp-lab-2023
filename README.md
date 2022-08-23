# Repositori Tugas dan Tutorial Lab PBP Ganjil 2022/2023

Pemrograman Berbasis Platform (CSGE602022) - diselenggarakan oleh Fakultas Ilmu Komputer Universitas Indonesia, Semester Ganjil 2022/2023

## Daftar Konten

1. Tutorial Mingguan
2. [Pendahuluan](#pendahuluan)
3. [Aturan dan Skema Penilaian](#aturan-dan-skema-penilaian)
4. [Tutorial: Permulaan](#tutorial-permulaan)
5. [Tutorial: Cara Mengerjakan](#tutorial-cara-mengerjakan)
6. [Tutorial: Melakukan pull dari upstream](#tutorial-melakukan-pull-dari-upstream)
7. [Tutorial: Menjalankan Aplikasi Django](#tutorial-menjalankan-aplikasi-django)
8. [Tutorial: Menampilkan Badge Coverage](#tutorial-menampilkan-badge-coverage)
9. [Tutorial: Mendeploy Aplikasi](#tutorial-mendeploy-aplikasi)
10. [Sumber Bacaan](#sumber-bacaan)
11. [Credit](#credit)


## Pendahuluan

Selamat datang di repositori tugas dan tutorial lab PBP Ganjil 2022/2023. Repositori serta dokumen ini dimaksudkan sebagai wadah dari tutorial, instruksi, penjelasan serta _source code_ yang berhubungan dengan pembelajaran mata kuliah Pemrograman Berbasis Platform. 

Terdapat beberapa pekerjaan yang perlu Anda selesaikan selama pelaksanaan perkuliahan PBP Ganjil 2022/2023 ini, yaitu Esai Refleksi, Tutorial dan Tugas Lab. 

Setiap minggunya, Anda akan diberikan tutorial untuk mempelajari konsep-konsep serta praktisi dari pemrograman berbasis platform. 

Anda juga akan diminta untuk mengerjakan tugas lab sebagai bentuk implementasi dari pembelajaran yang Anda pelajari selama kelas dan sesi tutorial. 

Selain itu, Anda juga perlu menuliskan esai refleksi atas apa yang telah Anda pelajari dan implementasikan pada tugas lab yang telah Anda kerjakan. 

## Aturan dan Skema Penilaian

Tutorial, Esai dan Tugas Lab PBP Ganjil 2022/2023 berkontribusi kepada nilai akhir PBP dengan total **18%**. Untuk setiap pekerjaan yang dikerjakan, Anda bisa mendapatkan nilai dengan rentang **A** (4) sampai **E** (0). Beberapa aspek beserta bobotnya yang perlu Anda perhatikan dalam mengerjakan lab dan tugas adalah sebagai berikut.

1. Fungsionalitas program (45 poin)
2. Program dijalankan tanpa error (10 poin)
3. Kenyamanan penggunaan program (5 poin)
4. Validasi input (5 poin)
5. Standar penulisan kode (10 poin)
6. Dokumentasi (10 poin)
7. Efisiensi (10 poin)
8. Persyaratan submisi (5 poin)

Anda juga perlu menuliskan esai refleksi atas pekerjaan yang telah anda kumpulkan. Beberapa aspek beserta bobotnya yang perlu Anda perhatikan dalam pengerjaan esai refleksi adalah sebagai berikut.
1. Orisinalitas karya dan keatraktifan judul atau topik yang diangkat (10 poin)
2. Format penulisan (10 poin)
3. Penggunaan bahasa (15 poin)
4. Ketajaman analisis permasalahan (30 poin)
5. Manfaat dan urgensi permasalahan yang diangkat (15 poin)
6. Simpulan dan saran (15 poin)
7. Referensi (5 poin)

Setiap pekerjaan yang telah diselesaikan oleh mahasiswa harus didemonstrasikan kepada asisten dosen. Berikut merupakan ketentuan dari demo yang perlu diperhatikan:
1. Demonstrasi pekerjaan tutorial/tugas perlu dilakukan **paling lambat seminggu setelah deadline pengumpulan**. Waktu yang dialokasikan beserta jam akan disesuaikan dengan asisten dosen Anda masing-masing.
2. Apabila terdapat halangan sehingga Anda tidak dapat mendemonstrasikan pekerjaan Anda kepada asisten dosen dalam rentang waktu yang ditentukan, Anda perlu mengontak asisten dosen Anda serta mengirimkan email kepada dosen untuk susulan demonstrasi pekerjaan.

## Tutorial: Permulaan

Jika Anda sebelumnya belum pernah mengerjakan Tutorial Lab 1,

1. `fork` repositori ini ke akun GitLab milik Anda yang mana nantinya repositori ini akan secara otomatis di-copy ke akun GitLab Anda.
2. Bukalah halaman repositori anda di URL `https://gitlab.com/<YOURNAME>/pbp-lab` dengan keterangan `<YOURNAME>` sebagai GitLab username Anda.
3. Atur URL untuk Clone ke HTTPS dan copy URL tersebut ke clipboard.
4. Clone repositori tersebut ke komputer Anda dengan menggunakan command `git clone https://gitlab.com/<YOURNAME>/pbp-lab.git <PATH>` dengan keterangan `PATH` sebagai direktori tujuan.
5. Masuk ke dalam repositori yang telah di-clone pada komputer Anda dan jalankan `git remote add upstream https://gitlab.com/pbp-2022/pbp-lab` untuk menambahkan remote upstream.
6. Pastikan bahwa repository Anda memiliki visibiltas `Public`. Anda dapat mengaturnya pada halaman **Edit Project**.
7. Beritahukan kepada asisten dosen Anda bahwa URL dari repositori milik Anda untuk keperluan evaluasi dan penilaian.

Jika Anda pernah mengerjakan Tutorial Lab 1,

1. Masuk ke dalam repositori yang telah di-clone pada komputer Anda dan jalankan `git remote add upstream https://gitlab.com/pbp-2022/pbp-lab` untuk menambahkan remote upstream.
2. Pastikan bahwa repository Anda memiliki visibiltas `Public`. Anda dapat mengaturnya pada halaman **Edit Project**.
3. Beritahukan kepada asisten dosen Anda bahwa URL dari repositori milik Anda untuk keperluan evaluasi dan penilaian.


## Tutorial: Cara Mengerjakan
1. Misalkan Anda hendak mengerjakan tutorial lab 2. Pergilah ke dalam direktori yang berisikan README.md dari tutorial lab 2.
2. Untuk memastikan tutorial lab 2 tidak terganggu dengan tutorial lain, buatlah sebuah Django App yang spesifik untuk pengerjaan tutorial lab 2 dengan menggunakan perintah `python manage.py startapp lab_2` pada console.
3. Baca dan pahamilah dengan teliti berkas README. Berkas ini memuat tugas serta instruksi yang perlu Anda selesaikan.
4. Kerjakan tutorial tersebut.
5. Gunakan `git add <FILES/DIRECTORIES>` atau `git rm <FILES/DIRECTORIES>` untuk stage/unstage berkas yang nantinya akan Anda simpan ke Git.
6. Apabila Anda ingin menyimpan progres Anda secara lokal, Anda dapat melakukan **commit** ke Git. Gunakan perintah `git commit -m "<MESSAGE>"` dengan keterangan `<MESSAGE>` sebagai deskripsi pekerjaan yang akan Anda simpan.
7. Ulangi langkah 4-6 hingga Anda selesai mengerjakan tugas Anda.
8. Setelah Anda siap untuk mengumpulkan pekerjaan Anda atau Anda ingin menyimpannya pada repositori GitLab Anda, lakukan sebuah **push**. Anda dapat menggunakan perintah `git push origin <NAMA_BRANCH>` dengan keterangan `<NAMA_BRANCH>` sebagai _branch_ yang Anda tuju untuk penyimpanan di GitLab.


## Tutorial: Melakukan pull dari upstream

Apabila terdapat _update_ dari `upstream`, Anda dapat memperoleh _update commit_ tersebut dan mengintegrasikannya ke dalam repositori Anda secara lokal dengan menggunakan perintah `git pull upstream master`.

Ketika Anda melakukan pull dari upstream, Merge Conflicts dapat terjadi pada komputer lokal Anda maupun GitLab karena repositori berubah-ubah setiap minggunya dan mungkin terdapat perubahan yang bersinggungan dengan branch `master` yang ada pada repositori Anda.

Jika terdapat Merge Conflicts, gunakan commits terbaru yang berasal dari repositori `upstream`. Setelah Anda menyelesaikan segala konflik yang terjadi dan sukses menggabungkannya ke `branch` Anda, jangan lupa untuk melakukan `push` lagi ke repositori GitLab Anda dengan perintah `git push origin <NAMA_BRANCH>`.

## Tutorial: Menjalankan Aplikasi Django

Sebelumnya Anda perlu mendapatkan _copy_ dari repositori yang hendak Anda jalankan menggunakan perintah `git clone <URL_REPOSITORY>`.

1. Pada direktori yang telah Anda salin ke mesin Anda, bukalah _console_ di direktori tersebut dan mulailah dengan membuat sebuah _virtual environment_ terlebih dahulu dengan perintah:
```
python -m venv env
```
>Mohon pastikan Anda menjalankan perintah tersebut pada _root_ dari repositori di mesin Anda.

2. Setelah perintah tersebut selesai dieksekusi, Anda dapat melihat bahwa terdapat folder env pada repositori Anda. Folder env atau _virtual environment_ ini berfungsi untuk mengenkapsulasi segala _dependencies_ dari aplikasi sehingga tidak tercampur atau bertabrakan dengan versi yang tidak seharusnya.

3. Aktifkan _virtual environment_ tersebut dengan menggunakan perintah berikut. Perhatikan bahwa menjalankan perintah pengaktifan _virtual environment_ berbeda untuk Windows dengan sistem operasi berbasis UNIX:
```
Windows:
env\Scripts\activate.bat
pip install -r requirements.txt
```
```
Linux & Mac OS:
source env/bin/activate
pip install -r requirements.txt
```
4. Apabila _virtual environment_ berhasil diaktifkan, Anda akan melihat `(env)` di _console_ Anda. Jalankan perintah `python manage.py runserver` untuk menjalankan aplikasi Django di mesin Anda.
>Mohon pastikan terdapat file manage.py pada direktori aktif di console Anda sebelum menjalankan perintah tersebut.

5. Bukalah web server lokal dari aplikasi Django tersebut menggunakan browser di `http://localhost:8000`.

6. Apabila muncul sebuah halaman, selamat; Anda berhasil menjalankan aplikasi Django pada mesin Anda.

7. Apabila Anda sudah selesai mengerjakan tutorial atau ingin mengubah ke proyek Python lain, jangan lupa untuk mematikan _virtual environment_ yang telah diaktifkan sebelumnya dengan perintah:
```bash
deactivate
```

## Tutorial: Menampilkan Badge Coverage

1. Masuk ke Halaman CI/CD Settings (`Settings -> CI/CD`)
2. Masuk ke bagian General pipelines dan cari bagian test coverage parsing (`General pipelines -> Test coverage parsing`)
3. Masukkan _regex_ berikut pada _textbox_ Test Coverage Parsing
```
TOTAL\s+\d+\s+\d+\s+(\d+)%
```
4. Simpan perubahannya.
5. Untuk menambahkan badge coverage pada proyek GitLab seperti ini [![Pipeline](https://gitlab.com/pbp-2023/pbp-lab/badges/master/pipeline.svg)](https://gitlab.com/pbp-2023/pbp-lab/pipelines) [![Coverage](https://gitlab.com/pbp-2023/pbp-lab/badges/master/coverage.svg)](https://gitlab.com/pbp-2023/pbp-lab/pipelines) :
    - Pada header repositori dari proyek:
        1. Masuk ke Halaman CI/CD Settings (`Settings -> General`)
        2. Pergi ke bagian badges.
        3. Buatlah sebuah badge baru untuk pipeline dengan konfigurasi URL:
        ```
        https://gitlab.com/%{project_path}/badges/%{default_branch}/pipeline.svg
        ```
        4. dan untuk coverage badge:
        ```
        https://gitlab.com/%{project_path}/badges/%{default_branch}/coverage.svg
        ```
    - Pada berkas README.md
        1. Tambahkan 2 baris berikut pada README.md Anda:
        ```
        [![Pipeline](https://gitlab.com/YOUR_GITLAB_USERNAME/YOUR_REPOSITORY_NAME/badges/master/pipeline.svg)](https://gitlab.com/YOUR_GITLAB_USERNAME/YOUR_REPOSITORY_NAME/pipelines)
        [![Coverage](https://gitlab.com/YOUR_GITLAB_USERNAME/YOUR_REPOSITORY_NAME/badges/master/coverage.svg)](https://gitlab.com/YOUR_GITLAB_USERNAME/YOUR_REPOSITORY_NAME/pipelines)
        ```
        2. Ubah `YOUR_GITLAB_USERNAME` dan `YOUR_REPOSITORY_NAME` sesuai dengan repositori Anda. Berikut adalah contoh untuk repositori ini:
        ```
        [![Pipeline](https://gitlab.com/pbp-2023/pbp-lab/badges/master/pipeline.svg)](https://gitlab.com/pbp-2023/pbp-lab/pipelines)
        [![Coverage](https://gitlab.com/pbp-2023/pbp-lab/badges/master/coverage.svg)](https://gitlab.com/pbp-2023/pbp-lab/pipelines)
        ```
6. Jalankan ulang pipeline untuk memperbarui status dari pipeline dan coverage. Anda dapat melakukan commit dan push ulang atau mengulang kembali pipeline yang sebelumnya pernah dijalankan.

## Tutorial: Men-deploy Aplikasi

Apabila sebelumnya Anda belum memiliki akun Heroku dan/atau sebuah aplikasi Heroku aktif,
1. Buatlah akun Heroku. Anda dapat mulai membuat akun pada halaman Login Heroku yang dapat diakses pada link [berikut](https://id.heroku.com/login).
2. Setelah Anda masuk ke halaman dashboard Heroku, buatlah sebuah aplikasi Heroku.

Setelah Anda memiliki aplikasi Heroku,

1. Copy API Key dari akun anda. API Key dapat Anda temukan di `Account Settings -> API Key`. Simpanlah API Key beserta informasi tentang aplikasi Anda pada notepad/file lain dengan format berikut:
```
HEROKU_API_KEY: <VALUE_API_KEY_ANDA>
HEROKU_APP_NAME: <NAMA_APLIKASI_HEROKU_ANDA>
HEROKU_APP_HOST: <URL_APLIKASI_HEROKU_ANDA>
```
2. Bukalah konfigurasi repositori GitLab Anda bagian CI/CD (`Settings -> CI/CD`).
3. Tambahkan variabel baru untuk melakukan deployment. Pasangan Key-Value dari variabel yang akan Anda buat dapat Anda ambil dari informasi yang Anda catat pada notepad sebelumnya. Sebagai contoh:
```
(KEY)HEROKU_APP_NAME
(VALUE)APLIKASI-SAYA
```
4. Simpan variabel-variabel tersebut.
5. Pada mesin lokal Anda, buatlah sebuah berkas baru yang bernama `Procfile` di _root_ dari repositori Anda. Berkas ini akan digunakan oleh Heroku untuk membaca aktivitas log aplikasi ke sistem monitoring internal Heroku. Isi dari berkas tersebut adalah sebagai berikut:
```
web: gunicorn aplikasi_django.wsgi --log-file -
```
>Ubah `aplikasi_django` sesuai dengan aplikasi yang hendak Anda deploy.

6. Buatlah sebuah berkas baru bernama `gitlab-ci.yml` di _root_ dari repositori Anda. Berkas ini digunakan untuk mengeksekusi deployment oleh runner dari GitLab. Isi dari berkas tersebut adalah sebagai berikut:
```
Deployment:
  image: ruby:2.4
  stage: deploy
  before_script:
    - gem install dpl
    - wget -qO- https://cli-assets.heroku.com/install-ubuntu.sh | sh
  script:
    - dpl --provider=heroku --app=$HEROKU_APP_NAME --api-key=$HEROKU_API_KEY
    - export HEROKU_API_KEY=$HEROKU_API_KEY
    - heroku run --app $HEROKU_APP_NAME python manage.py migrate
  environment:
    name: production
    url: $HEROKU_APP_HOST
```

7. **Add**, **Commit** dan **Push** berkas-berkas tersebut ke repositori GitLab Anda dengan perintah `git push origin <NAMA_BRANCH>`.
8. Jalankan/jalankan kembali pipeline dari aplikasi Anda di GitLab. Anda dapat menemukan pipeline tersebut di sidebar kiri (`CI/CD -> Pipelines`).
> Perhatian! Proses pipeline mungkin saja terjadi **kegagalan** dikarenakan berbagai sebab. Kegagalan dari pipeline dapat Anda lihat di repositori GitLab Anda dengan adanya simbol silang merah atau di badge Pipeline dengan adanya status `pipeline: failed`.
>
> Apabila pipeline Anda gagal karena _dependencies_ atau konfigurasi dari aplikasi, periksa ulang konfigurasi aplikasi Django serta versi dari _dependencies_ yang digunakan. Pastikan semuanya berjalan dengan lancar di lokal Anda sebelum Anda melakukan proses _deployment_.
>
> Apabila pipeline Anda gagal karena permasalahan GitLab atau runner, cukup jalankan kembali pipelines. Permasalahan ini terkadang muncul ketika runner dari GitLab sedang sibuk atau mengalami kegagalan dari server GitLab.
>
> Apabila status pipeline pending, Anda hanya perlu menunggu giliran pipeline yang Anda sedang jalankan untuk dieksekusi oleh runner GitLab.

9. Jika seluruh proses dari pipeline berhasil dieksekusi, Anda dapat melihat terdapat sebuah tanda centang hijau yang menandakan bahwa proses pipeline telah berhasil. Apabila Anda menambahkan badges Pipelines pada repositori Anda, status dari badges ini akan secara otomatis diperbarui berdasarkan pipeline yang baru saja dijalankan.

10. Anda dapat mengakses aplikasi Anda yang sudah ter-deploy pada URL aplikasi Heroku yang Anda gunakan.
## Sumber Bacaan

Berikut adalah beberapa bacaan yang sekiranya dapat membantu selama proses pembelajaran PBP Ganjil 2022/2023.

- [Menulis Pesan Commit yang Baik](https://cbea.ms/git-commit/)

## Credit

Dokumen ini dibuat berdasarkan [Exercise 0: Introduction to Git](https://gitlab.com/CSUI-AdvProg-2017/lab-exercises) yang ditulis oleh Tim Pengajar Pemrograman Lanjut 2017 ([@addianto](https://gitlab.com/addianto), [@muhammad.ardhan](https://gitlab.com/muhammad.ardhan), [@fbenarto](https://gitlab.com/fbenarto), et al.) dan [PBP Ganjil 2021](https://gitlab.com/PBP-2021/pbp-lab) yang ditulis oleh Tim Pengajar Pemrograman Berbasis Platform 2021 ([@prakashdivyy](https://gitlab.com/prakashdivyy)). Segala tutorial serta instruksi yang dicantumkan pada repositori ini dirancang sedemikian rupa sehingga mahasiswa yang sedang mengambil mata kuliah Pemrograman Berbasis Platform dapat menyelesaikan tutorial saat sesi lab berlangsung.