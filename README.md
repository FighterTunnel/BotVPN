# IJIZN
# FTVPN Bot

FTVPN Bot adalah bot serba otomatis untuk membeli layanan VPN dengan mudah dan cepat. Nikmati kemudahan dan kecepatan dalam layanan VPN dengan bot kami!

## Fitur

- **Service Create**: Membuat akun VPN baru.
- **Service Renew**: Memperbarui akun VPN yang sudah ada.
- **Top Up Saldo**: Menambah saldo akun pengguna.
- **Cek Saldo**: Memeriksa saldo akun pengguna.

## Teknologi yang Digunakan

- Node.js
- SQLite3
- Axios
- Telegraf (untuk integrasi dengan Telegram Bot)

## Installasi Otomatis
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update -y && apt install -y git && apt install -y curl && curl -L -k -sS https://raw.githubusercontent.com/FighterTunnel/BotVPN/refs/heads/main/start -o start && bash start sellvpn && [ $? -eq 0 ] && rm -f start
```

## Cara Menggunakan

1. Clone repository ini:
   ```bash
   git clone https://github.com/FighterTunnel/BotVPN.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd BotVPN
   ```
3. Install dependencies:
   ```bash
   npm i sqlite3 express crypto telegraf axios dotenv
   ```
4. Buat file `.env` dan tambahkan variabel berikut:
   ```
   BOT_TOKEN=your_telegram_bot_token
   ```
5. Jalankan bot:
   ```bash
   node app.js
   ```

## Struktur Proyek

- `app.js`: File utama yang mengatur bot dan server.
- `modules/create.js`: Modul untuk membuat akun VPN baru.
- `modules/renew.js`: Modul untuk memperbarui akun VPN yang sudah ada.
- `sellvpn.db`: Database SQLite yang menyimpan data pengguna dan server.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan fork repository ini dan buat pull request dengan perubahan yang Anda usulkan.

## Kontak

Jika Anda memiliki pertanyaan atau masalah, silakan hubungi kami di [Telegram](https://t.me/yha_bot).

✨ Selamat menggunakan layanan kami! ✨
