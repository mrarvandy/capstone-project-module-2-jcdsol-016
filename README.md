# Analisis Listing Airbnb Bangkok

## Pembuka

Disadur dari [Forbes](https://www.forbes.com/sites/morganbrennan/2011/09/16/the-most-amazing-and-absurd-places-for-rent/), Airbnb adalah jaringan pasar daring dan penginapan rumahan sejawat yang menjadi titik temu antara mitra Airbnb sebagai penyedia hunian sewa yang mendaftarkan propertinya untuk disewa dalam jangka pendek dan pengguna Airbnb sebagai penyewa dengan tarif sewa yang ditetapkan langsung oleh mitra Airbnb. Tentu, sebagai perusahaan yang telah mengukuhkan diri sebagai perusahaan terbesar di dunia dalam bidang ini, dengan menaungi 2.000.000 properti di 34.000 kota di 191 negara, Bangkok, kota dengan nama setengah lengkap Krung Thep Maha Nakhon ini, selain menjadi pusat mandala pemerintahan Kerajaan Ayutthaya sejak dahulu kala, juga menjadi pusat mandala pariwisata bahkan di tingkat regional. Airbnb pun tergugah untuk menganalisis lebih lanjut performa mitra mereka di Bangkok.

## Data dan *Library*

Proses pengerjaan analisis ini menggunakan data yang disematkan pada repositori ini, dengan data awal berupa *file* berekstensi CSV dengan nama `Airbnb Listings Bangkok.csv` dan dengan penyesuaian analisis dihasilkan set data dalam bentuk CSV lain yang bernama `airbnb-listings-bangkok-cleaned.csv`. Lalu, dengan menggunakan bahasa pemrograman Python sebagai penunjang analisis, pada kesempatan ini disokong juga dengan beberapa *library* terkait seperti Pandas, Numpy, Seaborn, Scipy, WordCloud, Warnings, dan Matplotlib.

## Tahapan Pengerjaan

Untuk pengerjaan analisis ini, secara garis besar proses pengerjaan bisa dibagi menjadi dua proses, yakni:

1. Pembersihan Data dengan identifikasi data pra-pembersihan, identifikasi data absah pada set data dan pembersihannya, dan identifikasi data pasca-pembersihan.
2. Pengolahan dan Penyajian Data menggunakan visualisasi dengan Seaborn dan Tableau.

## Penutup

Dengan analisis yang disematkan pada file berekstensi .ipynb yang bernama `data-analysis.ipynb`, didapatkan beberapa rekomendasi bagi Airbnb dan mitranya di Bangkok yang berakar dari kesimpulan yang didapatkan dari analisis, yakni sebagai berikut:

1. Penamaan *listing* bisa dipadu-padankan dengan letak geografis yang lebih spesifik agar semakin menarik, seperti halnya Jalan Sukhumvit.
2. Mitra Airbnb bisa mempertimbangkan untuk mengubah jenis hunian sewanya menjadi hunian yang eksklusif untuk penyewaan sepert rumah/apartemen utuh, agar lebih menarik pengguna Airbnb.
3. Pihak Airbnb bisa memfokuskan untuk menggaet mitra di tengah kota karena kecenderungan pengguna Airbnb yang lebih sering menggunakan jasa mitra Airbnb untuk menginap di dekat berbagai titik-titik pariwisata yang mayoritas terkumpul di pusat kota.
4. Mitra Airbnb bisa mempertimbangkan untuk menurunkan harga sewa huniannya agar bisa meningkatkan popularitas dan pemasukan.
5. Dengan menimbang bahwa *listing* dengan popularitas buruk sebenarnya cukup longgar dalam menentukan ketersediaan untuk penyewaan dan jumlah minimal malam untuk penginapan, pihak Airbnb bisa memprioritaskan untuk promosi *listing* dengan kategori ini.