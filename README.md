# PKM-KC – Smart Cane IoT untuk Tunanetra

## Deskripsi Singkat
Proyek ini mengembangkan **tongkat pintar berbasis IoT** untuk membantu penyandang tunanetra dalam mendeteksi rintangan dan meningkatkan keselamatan mobilitas, khususnya saat berjalan di lingkungan ramai dan menyeberang jalan. Sistem menggunakan **sensor ultrasonik**, **sensor inframerah (IR)**, dan **ESP32** dengan **adaptive threshold** serta **sensor fusion** untuk meminimalkan noise dan false alarm.

---

## Latar Belakang
Tongkat konvensional hanya mendeteksi rintangan setelah terjadi kontak fisik. Di lingkungan perkotaan Indonesia (trotoar tidak rata, kendaraan parkir sembarangan), pendekatan ini berisiko. Oleh karena itu, diperlukan solusi preventif yang:
- Memberi peringatan **sebelum** terjadi tabrakan
- Tetap **ergonomis** dan mudah digunakan
- **Terjangkau** dan dapat diproduksi lokal

---

## Tujuan
- Mendeteksi rintangan jarak dekat dan menengah secara real-time
- Mengurangi noise sensor dengan **filtering** dan **adaptive threshold**
- Memberikan umpan balik intuitif (getaran & suara)
- Menyediakan fondasi pengembangan IoT (monitoring/telemetri)

---

## Fitur Utama
- **Sensor Fusion**: Ultrasonik + IR
- **Adaptive Threshold**: Ambang jarak dinamis sesuai kondisi
- **Anti-Noise**: Median/sliding window filter
- **Haptic Feedback**: Getaran bertingkat (PWM)
- **Audio Alert**: Buzzer (opsional)
- **IoT-Ready**: Wi-Fi ESP32 (opsional)

---

## Arsitektur Sistem
