# Weather App

Weather App adalah aplikasi website sederhana yang menampilkan informasi cuaca berdasarkan lokasi yang dicari pengguna. Aplikasi ini menggunakan API dari OpenWeatherMap untuk mendapatkan data cuaca secara real-time.

# Screenshot
1. Tampilan awal
   ![weather app 1](https://github.com/user-attachments/assets/c88aa109-6ebe-4a0f-aedc-b69311cdaf4d)

3. Tampilan setelah mengisi kota
   ![weather app 2](https://github.com/user-attachments/assets/b5ec073c-ab29-4da4-9155-5b1d3ac626d0)

5. Tampilan alert jika pencarian kosong
   ![weather app 3](https://github.com/user-attachments/assets/06e6fe6d-d8d1-437e-b884-fd1693286514)

7. Tampilan alert jika kota tidak ditemukan atau input tidak valid
   ![weather app 4 1](https://github.com/user-attachments/assets/44b09da5-5a56-44ee-9050-e1974c8e7a21)
   ![weather app 4 2](https://github.com/user-attachments/assets/bfc66fe7-c836-4c23-a95b-3a1ac2f50651)



# Fitur
🔍 Pencarian kota untuk melihat cuaca saat ini

🌡️ Menampilkan suhu, kelembaban, dan kecepatan angin

🎨 Antarmuka sederhana dengan desain modern


# Teknologi yang Digunakan
- React.js
- CSS
- API (OpenWeatherMap)


# Konfigurasi API Key
Untuk menggunakan aplikasi ini, Anda memerlukan API key dari OpenWeatherMap.
1. Daftar di OpenWeatherMap (https://openweathermap.org/)
2. Pilih API pada navbar
3. Cari “Current Weather Data” dan buka dokumentasi API-nya (API doc)
4. Temukan API Keys di akun Anda
5. Salin API Key yang diberikan
6. Cari file .env pada root proyek dan tempel API Key nya pada VITE_APP_ID
7. Simpan file dan restart aplikasi


# Cara Install & Menjalankan
1. Clone repositori
git clone https://github.com/hotraa/weather-app.git
2. pindah direktori dengan "cd weather-app"
3. Install dependencies
"npm install"
4. Jalankan proyek
"npm run dev"
