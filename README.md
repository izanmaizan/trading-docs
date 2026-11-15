# Sistem Paper Trading Otonom

Sistem simulasi trading otomatis: mesin keputusan, pemungutan suara beberapa model bahasa, model pembelajaran mesin, dan dashboard pemantauan.

## Kegunaan

- Menjalankan strategi trading pada uang simulasi (paper trading).
- Menggabungkan sinyal dari beberapa model bahasa dan model ML.
- Memantau keputusan dan hasil lewat dashboard.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Layanan | Backend, frontend, dan modul ML terpisah |
| Keputusan | Multi-LLM voting + model ML |
| Data | Basis data untuk riwayat keputusan dan posisi |
| Infrastruktur | Docker Compose |

## Alur singkat

1. Data pasar dikumpulkan.
2. Mesin keputusan menggabungkan sinyal dari beberapa model.
3. Order simulasi dicatat tanpa uang nyata.
4. Hasil dan evaluasi ditampilkan di dashboard.

## Ringkasan

| | |
|---|---|
| Mulai dikembangkan | Agustus 2026 |
| Status | Eksperimen, uang simulasi |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
