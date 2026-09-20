# Misi Ukur Panjang – PPKI Matematik Tahun 6

Aplikasi game Android offline untuk latihan **ukuran panjang** bagi murid Pendidikan Khas Tahun 6.

## Kandungan pembelajaran
- Mengenal unit mm, cm, m dan km
- Memilih unit/ukuran yang munasabah
- Membandingkan ukuran panjang
- Membaca ukuran objek/pembaris
- Hubungan asas 10 mm = 1 cm, 100 cm = 1 m, 1000 m = 1 km
- Menyelesaikan situasi harian mudah

## Ciri mesra PPKI
- Butang besar dan arahan pendek
- Satu soalan pada satu masa
- Petunjuk apabila salah dan boleh cuba semula
- Ganjaran bintang dan maklum balas positif
- Fungsi `🔊 Baca` menggunakan Text-to-Speech peranti jika tersedia
- Fungsi A+ untuk teks lebih besar
- Ringkasan skor mengikut kemahiran
- Offline dan tiada akaun/log masuk

## Bina APK dengan Android Studio
1. Buka folder projek ini dalam Android Studio.
2. Tunggu Gradle Sync selesai.
3. Pilih **Build > Build APK(s)**.
4. APK debug akan berada di `app/build/outputs/apk/debug/app-debug.apk`.

## Bina APK dengan GitHub Actions
Fail `.github/workflows/build-apk.yml` telah disediakan. Push projek ke repository GitHub dan jalankan workflow **Build APK**. Artifact bernama `Misi-Ukur-Panjang-PPKI-APK` akan mengandungi APK.

## Nota kurikulum
Aplikasi memfokuskan topik ukuran panjang dalam Matematik Pendidikan Khas Tahun 6. Kandungan boleh disunting dalam `app/src/main/assets/index.html` mengikut Standard Kandungan/Standard Pembelajaran sekolah anda.
