# Bedah Mie Ayam Pakai Data, Bukan Sumpit

Menghitung biaya bahan semangkuk mie ayam dari data harga pangan Indonesia (PIHPS, 2021 sampai sekarang), dibagi jadi beberapa notebook. Yang dihitung adalah biaya bahan baku dengan resep asumsi, bukan harga jual di warung.

## Notebook

Semua notebook ada di folder [`notebooks/`](notebooks/).

1. [`01_isi_mangkuk`](notebooks/01_isi_mangkuk.ipynb) ([Kaggle](https://www.kaggle.com/code/samuelgeraldo/1-isi-mangkuk-bedah-mie-ayam-pakai-data)): Mengenal isi mangkuk, resep asumsi, dan data harga PIHPS, termasuk bulan yang kosong.
2. [`02_modal_semangkuk`](notebooks/02_modal_semangkuk.ipynb) ([Kaggle](https://www.kaggle.com/code/samuelgeraldo/2-modal-semangkuk-berapa-biaya-bahan-mie-ayam)): Mengubah harga per kg menjadi biaya bahan per porsi dan melihat trennya sejak 2021.
3. [`03_biang_kerok`](notebooks/03_biang_kerok.ipynb): Mencari bahan mana yang paling besar porsinya di modal dan mana yang paling menyumbang kenaikan.
4. [`04_beda_kota`](notebooks/04_beda_kota.ipynb): Membandingkan biaya bahan per porsi antarprovinsi memakai rata-rata harga hari kerja September 2026.
5. [`05_Efek_Lebaran`](notebooks/05_Efek_Lebaran.ipynb): Mengecek apakah biaya bahan naik di sekitar Lebaran, lewat perubahan % bulanan menurut jarak dari bulan Lebaran.
   - [`05b_Uji_Terigu`](notebooks/05b_Uji_Terigu.ipynb): Uji sensitivitas, yaitu apakah kesimpulan notebook 2 sampai 5 berubah kalau terigu (data Badan Pangan Nasional) ikut dihitung.
6. [`06_Siapa_Untung`](notebooks/06_Siapa_Untung.ipynb): Mengecek lewat korelasi apakah perubahan biaya bahan bergerak bersama saham CPIN, JPFA, INDF, ICBP, dan AALI.
7. [`07_Indeks_Mie_Ayam_Bagian1`](notebooks/07_Indeks_Mie_Ayam_Bagian1.ipynb): Bagian 1 dari pembuatan indeks biaya mie ayam (Jan 2021 = 100); baru mengenal struktur dan kekosongan data, belum ada chart atau kesimpulan.

## Dataset

[bedah mie ayam pakai data bukan sumpit](https://www.kaggle.com/datasets/samuelgeraldo/bedah-mie-ayam-pakai-data-bukan-sumpit)

File lokal: [`data/harga_pangan_bersih.csv`](data/harga_pangan_bersih.csv)
