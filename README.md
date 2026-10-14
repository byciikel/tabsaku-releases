# Tabsaku

Tabsaku adalah buku keuangan Android yang gratis dan menjaga privasimu. Tabsaku membaca email dan notifikasi transaksi yang sudah dikirim bank dan dompet digitalmu, mencatat pemasukan, pengeluaran, dan pindah dana sendiri, lalu menyimpan saldo tiap rekening. Semua data tetap di HP-mu: tanpa daftar akun, tanpa server, tanpa AI di cloud. Satu-satunya tempat yang dihubungi Tabsaku adalah server email milikmu sendiri.

Repositori ini berisi rilis APK yang sudah ditandatangani dan [kebijakan privasi](https://byciikel.github.io/tabsaku-releases/privacy.html).

## Fitur

- Mencatat transaksi otomatis dari email bank dan notifikasi aplikasi
- Saldo per rekening, lengkap dengan kalibrasi saldo
- Transfer antar rekeningmu sendiri tercatat sebagai Pindah dana, bukan pengeluaran
- Buku: pengeluaran dan pemasukan per kategori, perbandingan bulanan selama enam bulan, dan kategori buatanmu sendiri
- Belum terbaca: pesan yang belum bisa dibaca Tabsaku menunggu kamu catat, tidak ada yang hilang
- Kebun saku: kebun kecil yang tumbuh dari kebiasaan mingguanmu, bukan dari jumlah uang
- Kunci aplikasi (sidik jari atau PIN), widget beranda, ekspor CSV, hapus semua data

## Bank dan dompet digital yang didukung

| Bank / dompet digital | Email | Notifikasi aplikasi |
| --- | --- | --- |
| BCA | ✓ | ✓ (myBCA) |
| Bank Jago | ✓ | ✓ |
| blu by BCA Digital | ✓ | ✓ |
| BSI (BYOND) | ✓ | |
| BRI | ✓ (QRIS) | ✓ (BRImo, uang masuk) |
| Superbank | ✓ | ✓ |
| OVO | | ✓ |

Bank Mandiri dan BNI sudah bisa ditambahkan, tetapi pesannya belum terbaca otomatis; pesan itu menunggu di Belum terbaca untuk kamu catat. Segera hadir: CIMB Niaga, Permata, SeaBank, GoPay.

Bankmu belum ada, atau ada pesan yang tidak dikenali? Buka issue di repositori ini (hapus dulu nomor rekening dan nama di dalamnya).

## Cara memasang

Membutuhkan Android 8.0 atau yang lebih baru.

1. Unduh `tabsaku-<versi>.apk` dari [rilis terbaru](https://github.com/byciikel/tabsaku-releases/releases/latest).
2. Cocokkan SHA-256 file APK dengan file `.sha256` di rilis yang sama.
3. Buka file APK, lalu izinkan pemasangan dari browser atau pengelola file saat Android memintanya.

## Cara memperbarui

Di aplikasi, buka Pengaturan → Periksa pembaruan, atau pasang APK yang lebih baru langsung di atas versi lama. Datamu tetap ada.
