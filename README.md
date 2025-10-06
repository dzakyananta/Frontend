# 🎓 Website Pendaftaran Mahasiswa Baru - Universitas Indonesia

Sistem pendaftaran online untuk calon mahasiswa baru Universitas Indonesia dengan interface yang modern dan user-friendly.

## 📋 Deskripsi

Website ini adalah sistem pendaftaran mahasiswa baru yang memungkinkan calon mahasiswa untuk:
- Mendaftar akun baru
- Login ke sistem
- Melengkapi profil dan data akademik
- Upload dokumen pendukung
- Memantau status pendaftaran
- Melihat jadwal tes dan pengumuman

## 🚀 Fitur Utama

### 1. **Halaman Login** (`index.html`)
- Form login dengan email dan password
- Validasi input
- Responsive design
- Redirect ke dashboard setelah login berhasil

### 2. **Halaman Pendaftaran** (`register.html`)
- Form pendaftaran lengkap dengan validasi
- Input data pribadi dan akademik
- Pilihan program studi
- Password confirmation
- Layout responsive untuk semua device

### 3. **Dashboard/Beranda** (`beranda.html`)
- Overview status pendaftaran
- Menu navigasi utama
- Card-based interface
- Statistik pendaftaran
- Pengumuman terbaru
- Quick access ke fitur-fitur penting

### 4. **Halaman Profil** (`profil.html`)
- **4 Section Utama:**
  - 📝 Data Pribadi (dapat diedit)
  - 🎓 Data Akademik (dapat diedit)
  - 📄 Manajemen Dokumen
  - 🔒 Pengaturan Keamanan
- Upload foto profil
- Edit mode dengan visual feedback
- Status verifikasi dokumen
- Change password functionality

### 5. **Status Pendaftaran** (`status.html`)
- Timeline progress pendaftaran (6 tahap)
- Status dokumen dengan color coding
- Informasi pembayaran
- Jadwal tes masuk
- Download bukti pembayaran
- Print status functionality

## 🎨 Design Features

- **Modern UI/UX**: Gradient backgrounds, card layouts, hover effects
- **Fully Responsive**: Optimized untuk desktop, tablet, dan mobile
- **Color Coded Status**: Visual indicators untuk berbagai status
- **Interactive Elements**: Smooth transitions dan animations
- **Consistent Branding**: Tema Universitas Indonesia
- **Accessibility**: User-friendly navigation dan clear typography

## 📁 Struktur File

```
Frontend/
├── 📄 index.html          # Halaman Login
├── 📄 register.html       # Halaman Pendaftaran
├── 📄 beranda.html        # Dashboard/Beranda
├── 📄 profil.html         # Halaman Profil Mahasiswa
├── 📄 status.html         # Status Pendaftaran
├── 📄 style.css           # Complete CSS Styling
└── 📄 README.md           # Dokumentasi (file ini)
```

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur website
- **CSS3**: Styling dengan Flexbox, Grid, dan CSS Variables
- **JavaScript (Vanilla)**: Interactivity dan form handling
- **SVG Icons**: Icon system yang scalable
- **Responsive Design**: Mobile-first approach

## 🚀 Cara Menjalankan

1. **Clone atau Download** repository ini
2. **Buka file `index.html`** di web browser
3. **Atau gunakan Live Server** untuk development:
   ```bash
   # Jika menggunakan VS Code dengan Live Server extension
   # Klik kanan pada index.html → "Open with Live Server"
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🎯 User Journey

1. **Pendaftaran Akun** → Register dengan data lengkap
2. **Login** → Masuk dengan credentials
3. **Dashboard** → Overview dan navigasi utama
4. **Lengkapi Profil** → Edit data pribadi dan akademik
5. **Upload Dokumen** → Upload berkas pendukung
6. **Monitor Status** → Pantau progress pendaftaran
7. **Tes Masuk** → Ikuti jadwal yang diberikan
8. **Pengumuman** → Lihat hasil seleksi

## 🔧 Fitur Interaktif

### Halaman Profil:
- ✅ **Toggle Edit Mode**: Klik "Edit" untuk mengubah data
- ✅ **Visual Feedback**: Input berubah warna saat mode edit
- ✅ **Auto Focus**: Cursor otomatis ke input pertama
- ✅ **Save/Cancel**: Simpan atau batalkan perubahan
- ✅ **Section Navigation**: 4 tab untuk berbagai data

### Halaman Status:
- ✅ **Progress Timeline**: 6 tahap dengan visual indicator
- ✅ **Status Colors**: Hijau (selesai), Kuning (progress), Abu (pending)
- ✅ **Document Status**: Real-time status verifikasi dokumen
- ✅ **Print Function**: Cetak status pendaftaran

## 🎨 Color Scheme

- **Primary**: `#667eea` (Blue gradient)
- **Secondary**: `#764ba2` (Purple gradient)
- **Success**: `#28a745` (Green)
- **Warning**: `#ffc107` (Yellow)
- **Danger**: `#e74c3c` (Red)
- **Info**: `#17a2b8` (Teal)
- **Background**: `#f8f9fa` (Light gray)

## 📊 Sample Data

Website ini menggunakan data sample untuk demonstrasi:
- **Nama**: Ahmad Rizki Pratama
- **Email**: ahmad.rizki@ui.ac.id
- **Program Studi**: Teknik Informatika
- **Status**: Sedang Ditinjau

## 🔮 Future Enhancements

- [ ] Backend integration dengan database
- [ ] Real-time notifications
- [ ] File upload functionality
- [ ] Payment gateway integration
- [ ] Email verification system
- [ ] Admin dashboard
- [ ] Multi-language support
- [ ] Dark mode theme

## 🤝 Kontribusi

Untuk berkontribusi pada project ini:
1. Fork repository
2. Buat feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 Lisensi

Project ini dibuat untuk keperluan akademik - Etika Profesi, Semester 5.

## 👨‍💻 Developer

**Ahmad Rizki Pratama**
- GitHub: [@dzakyananta](https://github.com/dzakyananta)
- Project: Frontend Website Pendaftaran Mahasiswa Baru

## 📞 Support

Jika mengalami masalah atau memiliki pertanyaan:
1. Buka issue di GitHub repository
2. Periksa dokumentasi di README ini
3. Contact developer melalui GitHub

---

**© 2025 politeknik Negeri Lampung - Sistem Pendaftaran Mahasiswa Baru**

*Dibuat dengan ❤️ untuk kemudahan calon mahasiswa UI*
