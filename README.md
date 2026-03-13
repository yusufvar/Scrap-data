# Scrap-data

Code serbaguna yang dirancang untuk mengekstrak email, nomor telepon, dan akun media sosial dari situs web. Anda dapat menggunakan informasi yang terkumpul untuk berbagai tujuan, seperti penelitian lebih lanjut atau menghubungi pemilik situs web.

## Instalasi dan setup

1. Clone repositori:

```bash
https://github.com/yusufvar/Scrap-data.git
```

2. Ubah directori:

```bash
cd Scrap-data
```

3. Instal semua requirement:

```bash
pip3 install -r requirements.txt
```

## Penggunaan

- Scan sederhana:

```bash
python3 Scrapdata.py --url URL
```

- Scan dan jelajahi URL yang ditemukan:

```bash
python3 Scrapdata.py --url URL --crawl
```

- Scan untuk mencari media sosial:

```bash
python3 Scrapdata.py --url URL -s
```

Untuk melihat menu bantuan:

```bash
python3 TheScrapper.py -h
```
## Masalah
Code ini tidak selalu mampu menampilkan hasil yang diperlukan secara konsisten, karena dalam beberapa kondisi tertentu proses yang dijalankan dapat mengalami kendala, kesalahan pemrosesan, atau keterbatasan pada data yang digunakan sehingga output yang diharapkan tidak selalu muncul sesuai dengan kebutuhan.
