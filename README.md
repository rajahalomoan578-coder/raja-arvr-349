# Ruang Perkenalan Diri (A-Frame)

- **Nama:** RAJA HALOMOAN HARAHAP
- **NIM:**2309020349
- **Link demo (GitHub Pages):** https://USERNAME.github.io/NAMA-REPO/

## Deskripsi
Scene A-Frame berisi lantai, langit, 5 objek primitif (box, sphere, cylinder, cone, torus), teks nama dan NIM, serta torus yang berputar terus-menerus.

## Struktur Folder
```
/
├── index.html
└── README.md
```
(Sesuaikan dengan struktur folder di Langkah 2 modul Anda.)

## Jawaban Refleksi

**1. Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?**
Di A-Frame (dan three.js), kamera secara default menghadap ke arah sumbu z negatif. Objek dengan z negatif berada di depan pengguna sehingga langsung terlihat, sedangkan z positif berada di belakang kamera dan tidak tampak.

**2. Mengapa WebXR hanya aktif pada HTTPS atau localhost?**
WebXR mengakses sensor dan perangkat sensitif seperti kamera, gerak kepala, dan posisi pengguna. Browser mewajibkan secure context (HTTPS atau localhost) agar data tersebut tidak bisa disadap atau dimanipulasi di koneksi yang tidak terenkripsi.

**3. Perbedaan peran WebXR Device API, three.js, dan A-Frame**
WebXR Device API adalah antarmuka bawaan browser untuk mengakses perangkat VR/AR (headset, pelacakan, sesi imersif). three.js adalah library grafis 3D berbasis WebGL yang menggambar objek, cahaya, dan kamera. A-Frame adalah framework di atas three.js yang memungkinkan kita membuat scene 3D hanya dengan tag HTML sehingga lebih mudah dan cepat.
