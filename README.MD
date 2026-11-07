# JatmiCAD Releases

Installer aplikasi desktop JatmiCAD, aplikasi CAD kelistrikan untuk merancang skema kontrol dan otomasi.
Repo ini hanya berisi rilis, bukan kode sumber.

> Status: **pre-alpha**.

## Unduh

Ambil installer dari **[rilis terbaru](https://github.com/gamanlab/jatmicad-releases/releases/latest)**:

| Sistem | Berkas | Pembaruan |
|--------|--------|-----------|
| Windows x64 | `JatmiCAD-Setup-<versi>-win-x64.exe` | otomatis |
| Linux x64 (AppImage) | `JatmiCAD-<versi>-linux-x86_64.AppImage` | otomatis |
| Linux x64 (deb) | `jatmicad_<versi>_amd64.deb` | pasang versi baru secara manual |

macOS belum tersedia.

## Pasang

**Windows:** jalankan installer. Installer belum ditandatangani, jadi SmartScreen bisa menampilkan
"Windows protected your PC" saat instalasi pertama. Pilih **More info > Run anyway**.

**Linux (AppImage):**

```bash
chmod +x JatmiCAD-*-linux-x86_64.AppImage
./JatmiCAD-*-linux-x86_64.AppImage
```

**Linux (deb):**

```bash
sudo apt install ./jatmicad_*_amd64.deb
```

## Mulai memakai

Aplikasi memuat JatmiCAD dari server, jadi saat pertama dibuka Anda diminta mengisi alamat server JatmiCAD.
Alamatnya bisa diganti lewat **Berkas > Ganti server…**.

Berkas proyek berekstensi `.hjatmi`. Berkas lama `.elektra` tetap bisa dibuka.

## Usulan fitur dan laporan bug

Sampaikan lewat [Issues](https://github.com/gamanlab/jatmicad-releases/issues/new/choose) dan pilih templatenya:

- **[Laporan bug](https://github.com/gamanlab/jatmicad-releases/issues/new?template=bug_report.yml)**: ada yang tidak berjalan sebagaimana mestinya.
- **[Usulan fitur](https://github.com/gamanlab/jatmicad-releases/issues/new?template=feature_request.yml)**: fitur baru atau perbaikan pada fitur yang ada.

Cek dulu [issue yang sudah ada](https://github.com/gamanlab/jatmicad-releases/issues) agar tidak dobel. Issue bersifat publik,
jadi jangan menyertakan kata sandi, token, atau data dan gambar proyek yang rahasia.
