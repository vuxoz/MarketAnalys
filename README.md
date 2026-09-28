# 📈 MarketAnalys Bot Telegram

Bot Telegram canggih untuk analisa teknikal institusional adaptif, grafik multi-timeframe, dan berita pasar secara *real-time* menggunakan data dari Binance Spot Market.

> **Dibuat oleh:** [arifrfza](https://github.com/vuxoz) (@vuxoz)

---

## 🚀 Fitur Utama
* **Multi-Timeframe Adaptif:** Mendukung timeframe `6h`, `12h`, dan `1d` dengan penyesuaian indikator otomatis.
* **Analisa Komprehensif:** Dilengkapi dengan EMA, Bollinger Bands, ATR, RSI, serta deteksi *Bullish/Bearish Divergence*.
* **Cakupan Luas:** Dapat menganalisa **semua** koin kripto, token, komoditas (seperti Emas/PAXG), hingga saham global & ETF (seperti Apple, Tesla, S&P 500) yang terdaftar di Binance.
* **Grafik Visual:** Menghasilkan grafik *candlestick* beserta level *Entry*, *Take Profit (TP1 & TP2)*, dan *Stop Loss (SL)* secara otomatis.
* **Berita Terkini:** Integrasi dengan Marketaux API untuk menampilkan berita finansial terbaru terkait aset yang dianalisa.

---

## 📋 Perintah Bot di Telegram
* `/start` — Menampilkan pesan sambutan dan panduan awal.
* `/list` — Menampilkan direktori instrumen populer dan panduan timeframe.
* `/p <simbol> [timeframe]` — Analisa kripto atau komoditas (Contoh: `/p btc 6h` atau `/p gold 1d`).
* `/stock <simbol> [timeframe]` — Analisa saham/ETF (Wajib menambahkan huruf **'b'** di akhir simbol Binance, contoh: `/stock aaplb 12h`).

---

## 🛠️ Langkah-Langkah Menjalankan di VPS (Linux)

Ikuti langkah-langkah berikut untuk mengonfigurasi dan menjalankan bot di server VPS Anda:

### 1. Clone Repositori
```bash
git clone [https://github.com/vuxoz/MarketAnalys.git](https://github.com/vuxoz/MarketAnalys.git)
cd MarketAnalys
