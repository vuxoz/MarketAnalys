# MarketAnalys
# 1. Inisialisasi direktori lokal sebagai repositori Git
git init

# 2. Tambahkan file README.md (pastikan Anda sudah membuat file README.md dengan teks bahasa Inggris sebelumnya)
# Atau buat langsung dari terminal:
echo "# Financial Technical Analysis Telegram Bot" > README.md

# 3. Buat file lisensi (MIT License) secara otomatis
cat << 'EOF' > LICENSE
MIT License

Copyright (c) 2026 arifrfza (@vuxoz)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
EOF

# 4. Tambahkan file skrip utama bot Anda (misalnya analisa.py) ke Git
git add analisa.py README.md LICENSE

# 5. Lakukan commit pertama
git commit -m "Initial commit: Institutional financial analysis Telegram bot with Binance API"

# 6. Hubungkan repositori lokal ke repositori remote di GitHub (Ganti URL di bawah sesuai link repo Anda)
git branch -M main
git remote add origin https://github.com/username/nama-repo-anda.git

# 7. Unggah (push) kode ke GitHub
git push -u origin main
