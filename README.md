# Indonesian Film Data Scraping and Genre Analysis

## Deskripsi Project
Project ini bertujuan untuk melakukan web scraping data film Indonesia dari website Film Indonesia menggunakan Python dan BeautifulSoup. Data yang berhasil dikumpulkan kemudian dilakukan proses cleaning dan Exploratory Data Analysis (EDA) untuk melihat distribusi genre dan tren jumlah film dari tahun ke tahun.

---

## Tools & Library
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib

---

## Sumber Data
Data film diperoleh melalui proses web scraping dari website Film Indonesia:

[Film Indonesia](https://filmindonesia.or.id/film)

Website tersebut menyediakan informasi terkait film Indonesia seperti judul film, tahun rilis, dan genre yang kemudian dikumpulkan menggunakan Python dan BeautifulSoup.

---

## Data yang Diambil
Data yang discrape meliputi:
- Judul Film
- Tahun
- Genre

---

## Data Cleaning
Tahapan cleaning yang dilakukan:
- Menghapus data duplicate
- Mengecek missing values / null values
- Mengecek tipe data setiap fitur
- Mengecek jumlah total baris data

Hasil cleaning:
- Tidak ditemukan null values
- Ditemukan beberapa data genre berupa string kosong sebanyak 492 baris data

---

## Exploratory Data Analysis (EDA)

Analisis yang dilakukan:
- Distribusi genre film menggunakan diagram batang
- Distribusi jumlah film berdasarkan tahun
- Analisis genre film pada tahun 2025 sebagai tahun dengan jumlah film terbanyak

---

## Hasil Analisis
Beberapa insight yang diperoleh:
- Genre Drama menjadi salah satu genre yang paling dominan
- Jumlah film meningkat signifikan pada tahun 2025
- Pada tahun 2025 genre horror dan drama menjadi genre dengan jumlah film terbanyak

---

## Output Project
Project menghasilkan:
- Dataset film Indonesia dalam format CSV
- Visualisasi distribusi genre
- Visualisasi distribusi jumlah film per tahun
- Analisis genre khusus pada tahun 2025

---
## Author
Nadia Pavita Amelia
LinkedIn: [www.linkedin.com/in/nadiapavitaamelia](https://www.linkedin.com/in/nadiapavitaamelia/)
