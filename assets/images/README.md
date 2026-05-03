# Menambahkan Foto Profil

Untuk menambahkan foto profil Anda pada halaman "Tentang Saya", ikuti langkah berikut:

## Langkah 1: Menyiapkan Foto
1. Ambil atau pilih foto profil Anda (selfie atau foto formal)
2. Format yang didukung: JPG, PNG
3. Ukuran rekomendasi: 500x500 piksel atau lebih

## Langkah 2: Menambahkan Foto
1. Letakkan foto Anda di folder ini: `assets/images/`
2. Rename foto menjadi: `profile.jpg` (jika JPG) atau `profile.png` (jika PNG)

## Langkah 3: Update Kode (Jika Perlu)
Jika Anda menggunakan format PNG, edit file `lib/main.dart` dan cari baris:
```dart
Image.asset(
  'assets/images/profile.jpg',
```

Ubah menjadi:
```dart
Image.asset(
  'assets/images/profile.png',
```

## Langkah 4: Jalankan Aplikasi
Setelah menambahkan foto, jalankan aplikasi dengan perintah:
```bash
flutter pub get
flutter run
```

## Catatan
- Jika foto belum ditambahkan, aplikasi akan menampilkan icon person placeholder
- Foto akan ditampilkan dalam bentuk circular (bulat) pada halaman Tentang Saya
- Pastikan file foto sudah disimpan di folder yang benar sebelum menjalankan aplikasi
