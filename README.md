# FanzzTheme📖 Deskripsi

Fanzz Theme Installer adalah script bash otomatis untuk mengelola dan menginstal berbagai tema dan addon pada Panel Pterodactyl. Script ini menyediakan antarmuka yang user-friendly dengan fitur animasi teks dan manajemen konfigurasi yang mudah.

✨ Fitur Utama

🎨 Tema (Files)

· Elysium Theme - Tema premium dengan desain modern
· Preview: https://www.sourcexchange.net/products/elysium-theme

🔌 Tema (Plugins)

· Nebula Theme - Tema dengan desain futuristik
· Slate Admin Panel - Tema admin panel yang elegan
· Preview: https://builtbybit.com/resources/nebula.32442/
· Preview: https://builtbybit.com/resources/slate.36101/

➕ Addon (Files)

· Auto Suspend - Fitur penangguhan otomatis
· Google Analytics - Integrasi analytics untuk monitoring
· Preview: https://builtbybit.com/resources/pterodactyl-v1-addon-auto-suspension.20012/
· Preview: https://builtbybit.com/resources/google-analytics-addon-for-pterodactyl.38696/

🔄 Tema (Remake)

· Enigma Premium - Tema premium remake oleh RainstoreID

⚙️ Pterodactyl (Edit)

· Ubah Background - Custom background panel
· Hapus Background - Reset ke background default
· Hapus Theme/Addon - Uninstall semua tema dan addon

🔧 Addon (Plugins)

· Cookies - Manajemen cookies untuk Pterodactyl
· Preview: https://builtbybit.com/resources/cookies.38647/

🛠️ Persyaratan Sistem

· Panel Pterodactyl yang terinstal
· Akses root/sudo
· Koneksi internet
· Git, curl, wget, unzip

📥 Instalasi

1. Download script:

```bash
wget https://raw.githubusercontent.com/fanzzhost/installer/main/installer.sh
```

1. Beri permission executable:

```bash
chmod +x installer.sh
```

1. Jalankan installer:

```bash
./installer.sh
```

🚀 Cara Penggunaan

1. Jalankan script dengan perintah ./installer.sh
2. Pilih opsi yang diinginkan (1-16)
3. Ikuti instruksi yang muncul
4. Tunggu proses instalasi selesai

📋 Menu Opsi

```
1. Install Theme Elysium
2. Install Nebula Theme  
3. Install Admin Panel Theme (Slate)
4. Install Addon Auto Suspend
5. Install Google Analytics
6. Install Enigma Premium Theme
7. Ubah Background Pterodactyl
8. Hapus Background (Reset)
9. Hapus Semua Theme/Addon
10. Install Cookies Addon
11. Install Dependencies
12. Matikan Animasi
13. Keluar dari Installer
14. Delete Theme Nebula
15. Delete Theme Slate
16. Delete Theme Cookies
```

🔧 Konfigurasi

Script menyimpan konfigurasi di /var/www/pterodactyl/config/installer_config:

· DISABLE_ANIMATIONS - Untuk mematikan animasi teks

🎯 Fitur Khusus

🎨 Animasi Teks

· Teks typing animation yang menarik
· Dapat dimatikan melalui opsi 12

🔒 Manajemen Dependencies

· Auto-install Node.js, Yarn, dan dependencies lain
· Blueprint framework untuk plugin management

🗑️ Clean Removal

· Fitur uninstall yang bersih untuk setiap tema
· Reset ke default Pterodactyl

⚠️ Troubleshooting

Error Dependencies

Jika muncul error dependencies, jalankan opsi 11 terlebih dahulu:

```bash
# Pilih opsi 11 untuk install dependencies
```

Permission Issues

Pastikan script dijalankan dengan akses yang tepat:

```bash
sudo ./installer.sh
```

GitHub Token

Script menggunakan GitHub token untuk akses repository private. Pastikan token valid.

📞 Support

· YouTube: FanzzTY
· Telegram: @FanzzHost

🔒 Keamanan

· Script menggunakan GitHub token untuk autentikasi
· File konfigurasi disimpan secara lokal
· Tidak ada data yang dikirim ke server external

📝 Catatan

· Backup panel sebelum instalasi tema
· Pastikan panel dalam keadaan sehat sebelum instalasi
· Restart services jika diperlukan setelah instalasi

🏆 Credits

Developer: Fanzz Host
License: Private - Untuk penggunaan pribadi

---

⭐ Jika project ini membantu, jangan lupa beri star!
