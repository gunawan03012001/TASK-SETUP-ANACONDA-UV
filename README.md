# TASK-SETUP-ANACONDA-UV


Nama : GUNAWAN

Nomor Absen : 05.037.DB2025

Batch & Asal : 10 Kuala Tungkal / Jambi

## 👋 Halo Sahabat Eco Techno Leader & Sobat Semua!
Selamat datang di repo TASK-SETUP-ANACONDA-UV! 🎉
Repo ini khusus dibuat untuk task mingguan sekaligus jadi panduan buat sobat semua yang pengen belajar setup Anaconda UV di laptop masing-masing.
Jadi, sama kayak aku yang lagi belajar dan masih pemula dalam dunia coding. aku harap kita bisa lebih jago dan makin kece dalam dunia data dan coding, yuk ikuti step-by-step-nya!

# 🎯 Tujuan Repository Ini
# ✅ Ngebantu teman-teman dan ingatin aku tentang cara setup Anaconda UV di laptop
# 📚 Tempat ngumpulin task mingguan dari pak Arry
## Bagian 1 - Mengenal dan Instalasi Anaconda 🐍
sebelum masuk ke setup anaconda, conda dan uv, aku mau kasih tau dulu Apa sih sebenarnya mereka ?

Setelah aku baca- baca dan cari beberapa materi,aku akan jelasin singkat dan sederhana ya temen-temen. Biar mudah dipahami terutama bagi pemula kayak aku.

## 🐍 1. APA ITU ANACONDA? 
🎒 Anaconda itu kayak tas ransel all-in-one buat data science & machine learning. jadi bisa jalanin project AI, statistik, visualisasi data, sampe ngoding web juga bisa.

## 2. APA ITU CONDA? 
🛠️ Conda itu ibarat si “manajer” atau “asisten pribadi” dari Anaconda. Dia itu kayak Play Store-nya Anaconda, mau install atau mau ganti phyton bisa dilakukan sama si conda.

## 3. APA ITU UV? 
🌱 UV itu cuma nama environment doang, bro & sis ETL kuuu!. Isinya? Bisa kamu isi dengan Python, Jupyter, Numpy, dst… sesuai kebutuhan project kamu.

okeee, mungkin singkatnya begitu. Aku akan perbaiki kalau ada masukan dan perbaikan saat zoom minggu ini yaaa...

## 🛠️ Step-by-Step Setup Anaconda Conda dan UV
Bagaimana cara menginstall anaconda ????
# 1. Download Anaconda
Pertama yang harus kita lakukan adalah download anaconda dan buka website resmi Anaconda (pastikan wajib website resmi ya).

Buka situs resminya di sini guys : 👉 https://www.anaconda.com/products/distribution

Pilih sesuai OS (Windows/Mac/Linux) , kali ini aku pilih windows. Teman-teman bisa sesuaikan dengan OS masing-masing.

1. ![22](https://github.com/user-attachments/assets/44cf4008-be84-4326-8d12-d8ff3d37c81d)


Do :

     - Wajib Download di website resmi

     - Di web resmi dijamin dapat versi asli dari Anaconda, yang udah diverifikasi.
Dont :

     - Kalau kamu download dari sumber yang gak jelas atau situs pihak ketiga, bisa jadi file-nya udah dimodifikasi dan disisipi malware, spyware, atau virus yang bahaya banget buat laptop kamu 😱. 

     - File dari luar bisa aja palsu, atau udah di-crack yang bikin sistem kamu gak stabil dan rawan error.
# 2. Install Anaconda
🐍 Kenapa Install ANACONDA? Sebagai pemula anaconda itu ibarat = Paket Komplit 📦 Udah langsung bawa Python + ratusan tools penting buat data science, machine learning, statistik, dll. Cocok banget untuk pemula karena install sekali, dapet semua.

Setelah sebelumnya kita berhasil download anaconda di website resmi
Maka bisa langsung download ➡️ Install ➡️ Klik Next terus sampe Finish
Berikut Tutorialnya :

2. ![Untitled4](https://github.com/user-attachments/assets/2b340326-0781-4597-b545-05bde21d4d08)


3. ![Untitled4](https://github.com/user-attachments/assets/18a87d15-fb7c-4a34-bb29-70dcb31fc9a0)


4. ![Untitled5](https://github.com/user-attachments/assets/f4b18b2c-341b-4b67-af45-471ebe4b1316)






eeittss, aku mau kasih tau sesuatu sebelum lanjut ke tutorial. Pas kamu Next ke tahap berikutnya saat install Anaconda, pasti nemu opsi: -✅ "Add Anaconda to my PATH environment variable" Nah, ini penting banget untuk dipahami:


Do's :

     - kalau kamu mau anaconda bisa diakses di terminal manapun kamu bisa menceklisnya, ya. Ini bisa dilakukan atau tidak dilakukan, tergantung kebutuhan kamu.
Don'ts:

     - jika kamu merasa tidak memerlukannya, maka tidak perlu di ceklis (opsional)
5. ![Untitled7](https://github.com/user-attachments/assets/28bcf7f1-76c2-434a-8201-3ce8e8a3742c)

Do's: Tetap di direktori yang otomatis dipilih system

Don'ts: Jangan ubah direktori

6. ![install6](https://github.com/user-attachments/assets/4ef28749-d9de-4ba7-924e-1db65bffd13b)


7. ![install7](https://github.com/user-attachments/assets/253053e4-ee28-4b67-b955-b7aa4244128d)


Berhasil dan Proses instalasi sudah selesai dilakukan 🎉

# 3. Verifikasi Anaconda Teristall
Teman-teman harus membuka CMD alias Command Prompt bisa dilakukan langsung dengan :

Windows + R

ketik : conda --version


8. ![Untitled 2](https://github.com/user-attachments/assets/055f436c-3379-4a5c-9847-ffe8880f2f25)


Kalau muncul conda 24.9.2 artinya Anaconda SUDAH TERINSTALL dengan benar dan PATH-nya aman.

Tapi kalau yang muncul seperti ini 'conda' is not recognized as an internal or external command... artinya Anaconda belum ditambahkan ke PATH.


9. ![cmd-gagal](https://github.com/user-attachments/assets/307941ba-8a98-4e04-8275-5feb6d1df1e8)


Ini karena kita gak centang "Add Anaconda to PATH" saat instalasi, Windows gak tau di mana lokasi file conda atau python dari Anaconda.

## APA ITU PATH?

# PATH itu kayak daftar jalan tol tempat Windows nyari file executable kayak python, conda, atau jupyter.

# Kalau kamu ngetik conda di CMD, Windows akan nyari conda.exe di semua folder yang ada di dalam daftar PATH.

# Jadi, kalau Anaconda belum ditambahkan ke PATH, CMD gak bakal tahu harus nyari conda ke mana ➡️ muncullah error.

# Tapi tenang! Bukan berarti belum terinstall — kamu masih bisa akses lewat Anaconda Prompt.

# Atau kamu bisa tambahkan manual, Kenapa?? Hal ini agar kita bisa manggil anaconda dari terminal mana saja. Nah caranya adalah :

     - Buka Start Menu → cari "Environment Variables" → klik Edit the system environment variables.

     - Klik Environment Variables...

     - Di bagian User variables → klik Path → klik Edit.

     - Klik New dan tambahin ini :

10. ![edit-enviromental](https://github.com/user-attachments/assets/30bbccea-6200-4de1-b86d-a86a189ab78f)


    - Klik OK semua sampe keluar.
Do's:

    - Restart CMD atau buka yang baru.
Don'ts:

    - Jangan menghapus PATH penting lainnya.

    - Hati-hati saat edit variabel lingkungan.

    - Jangan asal tambahin folder lain dari dalam Anaconda ke PATH
4. Membuat Lingkungan Conda Baru
Kalau di analogikan secara sederhana "Lingkungan Conda tuh kayak kosan terpisah buat tiap proyek. Jadi tiap proyek gak rebutan isi kulkas (library) dan gak tabrakan Python-nya". Sama kayak baju dalam lemari yang kita susun sesuai gayanya, misal celana bersama celana, baju bersama baju, jilbab bersama dengan jilbab lainnya, begitulah analoginya. Dan tujuan akhirnya adalah agar semua menjadi rapi, tersusun dan ga saling berantem.

Jadi step by step yang harus kalian lakukan saat ingin membuat lingkungan conda baru adalah :

    - Ketik di terminal: conda create -n nama_env python=3.9

11. ![Untitled 3](https://github.com/user-attachments/assets/c5c6363f-f632-41ed-b441-648091a6e6cc)


Do's:

    - kasih nama environment-nya (bebas) yang mudah diingat dan disukai

    - tentuin versi Python (bisa disesuaikan)
Don'ts:

    - jangan asal campur-campur library

    - jangan asal hapus environment sebelum benar-benar yakin
Bagian 2. UV Environment
1. Membuat UV Environment
Apa sih UV Environment itu ??? UV Environment adalah virtual environment Python yang dibuat dan dikelola pakai uv. Kita analogikan begini, setelah aku baca dan cari tau bahwa conda itu ibarat garasi super gede dan lengkap tapi buka garasinya masih lama, ribet pokoknya makan waktu.

- Nah, sedangkan si UV ini garasi kecil, minimalis tapi canggih dan super cepat.

- Kenapa kita pakai UV ya karena super cepat, praktik, ga ribet dan cocok buat aku dan temen-temen ETL yang suka praktis.

Caranya adalah sebagai berikut :

     - Buka CMD dan pastikan conda sedang tidak aktif

     - Ketik: pip install uv

12. ![pip](https://github.com/user-attachments/assets/618d7083-c533-415e-97c2-739da261f92c)


     - Jika berhasil maka akan keluar Output seperti Successfully installed uv-0.7.12
## 2. Menginisialisasi Proyek UV
Apa itu inisialisasi proyek uv ? Menginisialisasi proyek uv artinya nyiapin folder kerja + environment Python-nya + file dependensi supaya lo bisa langsung ngoding dengan sistem yang terstruktur dan modern.

Kenapa kira perlu menginisialisasi proyek uv? Karena kalau kita coding bikin proyek phyton tanpa environment maka semua akan menjadi berantakan dan akan menggangu proyek yang lain.

Adapun cara-caranya adalah :

1. Pastikan environment UV sudah aktif

2. Ketik: uv init ghost_intellixuv

3. Untuk mencari dic kembali maka ketik : Cd ghost intellixuv

4. Output menunjukkan proyek diinisialisasi di C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv.

13. ![1](https://github.com/user-attachments/assets/e0690205-9297-4b60-babd-571919be885a)


## 3. Install Paket yang dibutuhkan
Apa yang dimaksud dengan install paket yang dibutuhkan ? Artinya adalah Install library atau tools Python yang lo perlukan ke dalam environment uv (bukan ke sistem global). Misal lo bikin proyek analisis data. Kita pasti butuh library kayak:

      - numpy

      - pandas

      - matplotlib
Nah, semua itu kita install ke dalam .venv (environment lokal) yang udah dibuat pake uv, bukan ke Python utama di laptop.

Install paket di uv environment itu kayak masukin alat ke toolbox pribadi. Gak minjem alat tukang sebelah, gak ribet rebutan, semua aman di tempat sendiri. Kalo kita mau upgrade, hapus, atau backup, tinggal gas aja.

Kenapa harus install paket yang dibutuhkan ? karena setiap proyek kebutuhannya berbeda-beda dan hal ini agar proyek kita menjadi bersih dan rapi.

langkah-langkah yang harus kita lakukan adalah :

1.	Ketik: uv add pandas
    
2.	maka outputnya akan seperti ini :

14. ![Untitled](https://github.com/user-attachments/assets/1b9e85ce-6ae9-4dcd-bfe0-d1dfe90ea170)


## 4. Menonaktifkan Lingkungan UV
Apa maksud dari Menonaktifkan Lingkungan UV? Nah, sini aku jelasin ya jadi Menonaktifkan Lingkungan UV artinya kita keluar dari environment yang sudah kita buat sebelumnya. Kembali ke Phyton utama di laptop kita.

kenapa harus Menonaktifkan Lingkungan UV? karena ya biar jelas kapan kita selesai atau kapan kita sedang mengerjakan proyek tersebut. Dan agar ga bentrok sama proyek lainnya.

Langkah-langkah:

1.	Ketik: .venv\Scripts\deactivate

2.	Prompt kembali ke C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv>.

15. ![Untitled1](https://github.com/user-attachments/assets/fae91376-c071-4ae4-8d28-0e7a977d4833)


Do's :

    - Selalu nonaktifkan env setelah selesai kerja	Biar gak ketuker waktu pindah proyek

    - Nonaktifkan sebelum aktifin env lain	Biar gak bentrok
Don'ts :

    - Jangan install paket di terminal kalau lupa environment-nya aktif apa enggak

    - Jangan aktifin dua environment sekaligus 
## 5. 🧪 Perbandingan Conda vs UV Environment
Dalam pengembangan proyek Python, kita bisa menggunakan environment manager untuk memisahkan paket/dependensi antar proyek. Dua tools populer adalah conda dan uv.

## ⚖️ Apa Itu Conda dan UV?
Tool	Penjelasan Singkat
Conda	Manajer environment dan paket, cocok untuk proyek sains data, AI, dan yang memerlukan library non-Python seperti C/C++.
uv	Manajer environment dan paket super ringan dan cepat, dibuat dengan Rust. Cocok untuk proyek Python modern, backend, dan development cepat.
## 🤔 Mengapa Menggunakan Conda atau UV?
Alasan	Conda	UV
Manajemen library non-Python (misal: OpenCV, NumPy dari C)	✅ Sangat kuat	❌ Tidak direkomendasikan
Proyek data science dan machine learning	✅ Optimal	⚠️ Bisa, tapi terbatas
Proyek backend, CLI tools, web dev, dll	⚠️ Berat, overkill	✅ Sangat cocok
Kecepatan dan efisiensi	❌ Lebih lambat	✅ Super cepat
Ukuran tools dan environment	❌ Besar (>3GB dengan Anaconda)	✅ Ringan (<100MB total)
Manajemen dependensi Python murni	✅ Bisa	✅ Sangat baik
Format environment	environment.yml	requirements.txt
## 🎯 Rekomendasi Penggunaan
Kebutuhan	Rekomendasi
Proyek data science/AI/ML besar	Conda
Proyek web, backend, CLI tools	UV
Butuh kecepatan & ringan untuk development	UV
Butuh library luar Python (non-pip)	Conda
## 📌 Kesimpulan
Gunakan Conda jika kamu butuh fleksibilitas tinggi untuk proyek data science dan non-Python dependencies.
Gunakan UV jika kamu ingin kecepatan, kesederhanaan, dan proyek Python murni yang modern.

## Sekian dan Terimakasih 👋
