Dokumentasi Tugas 2: Membuat Website Restoran dengan ReactJS
 Nama Kelompok: \<www>
 Anggota Kelompok
 1. L200220076 Dhimas Hidayat
 2. L200220079 Juliandre Sukma Betananda
 3. L200220118 Afif Fadhil Mahmudi
 4. L200220112 Muhammad Syahid Cahya Kusuma
 5. L200220149 Muhammad Ghifari Zaki Khatami
 6. L200220103 Moh Iqbal Fajriyansyah

Alamat Website yang dibuat
- Frontend: \<(http://localhost:5173/react-restaurant-app)>
- Backend: \<Jika ada, tuliskan alamat website Anda\>

Silahkan anda tuliskan dokumentasi tugas anda di sini!

pembagian tugas dalam pengerjaan proyek ini:
1. L200220076 Dhimas Hidayat
    -pembuatan kategori page 
2. L200220079 Juliandre Sukma Betananda
    -pembuatan FAQs page
3. L200220118 Afif Fadhil Mahmudi
    -pembuatan home page 
4. L200220112 Muhammad Syahid Cahya Kusuma
    -pembuatan kategori page 
5. L200220149 Muhammad Ghifari Zaki Khatami
    -pembuatan menu page
6. L200220103 Moh Iqbal Fajriyansyah
    -pembuatan Open Hour page

Cara Menjalankan website berikut adalah langkah-langkah untuk menjalankan website:
1. Backend(django) buat dan aktifkan virtual enviroment pastikan berada di folder server dan buat virtual environment : cd server$ py -m venv .venv

Aktifkan Virtual environment
Untuk MacOs dan Linux (Bash atau Zsh Shell)
```bash
$ source .venv/bin/activate
```
Untuk Windows Command Shell
```bash
$ ./venv/Scripts/activate
```

2. install dependencies install django dan dependencies lainnya yang terdaftar di requirements.txt

```bash
(.venv) $ pip install -r requirements.txt
```

3.  jalankan backend server jalankan server backend dengan perintah:
```bash
(.venv) $ python manage.py runserver yang berjalan di `http://127.0.0.1:8000/swagger-ui/`
```
4. Frontend instalasi dependencies frontend pastikan anda berada difolder website dan jalankan perintah berikut untuk menginstal dependencies:
```bash
cd website$pnpm install 
```
5. Jalankan frontend server setelah semua dependencies terinstal, jalankan server frontend dengan perintah:
$pnpm run dev website akan berjalan di
http://localhost:5173/react-restaurant-app

referensi yang kita gunakan:
https://vite.dev/guide/why

Tampilan Halaman Home

![alt text](image.png)

Tampilan Halaman Menu

![alt text](image-6.png)

Tampilan Halaman kategori

![alt text](image-2.png)

Tampilan Open Hour

![alt text](image-3.png)

Tampilan Halaman FAQs

![alt text](image-4.png)

Tampilan Footer

![alt text](image-5.png)

