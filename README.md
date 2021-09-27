# Project at DQLab Machine Learning for Retail with R Product Packaging

**Create Next Best Offering to Drive Revenue and Loyalty**

DQLab.id Fashion adalah sebuah toko fashion yang menjual berbagai produk seperti jeans, kemeja, kosmetik, dan lain-lain. Walaupun cukup berkembang, namun dengan semakin banyaknya kompetitor dan banyak produk yang stoknya masih banyak tentunya membuat kuatir Pak Agus, manajer DQLab.id Fashion. 

Salah satu solusi adalah membuat paket yang inovatif. Dimana produk yang sebelumnya tidak terlalu laku tapi punya pangsa pasar malah bisa dipaketkan dan laku.

Anda sebagai seorang data scientist, akan ditugaskan membantu Pak Agus untuk mengidentifikasi paket produk yang menarik untuk dipaketkan sehingga akhirnya bisa meningkatkan keuntungan dan loyalitas para pelanggan DQLab.id Fashion. Dan untuk wewujudkan ini, Anda akan menggunakan R dan algoritma aproriari dari paket arules di sepanjang project ini.

**Dataset Transaksi Penjualan DQLab.id Fashion**

Untuk memulai project ini, Pak Agus meminta Pak Charlie, data engineer dari DQLab.id Fashion memberikan data transaksi 3 bulan kepada Anda dalam bentuk format TSV (Tab Separated Value) dengan nama transaksi_dqlab_retail.tsv dengan jumlah baris 33,669 baris data (3,450 kode transaksi).

Data transaksi ini telah dirapikan untuk Anda dengan hanya mengandung dua variable, yaitu:

Kode Transaksi
Nama Produk
Variable lain seperti harga, tanggal, jumlah pembelian, dan lain-lain – tidak dimasukkan sesuai permintaan pihak DQLab.id Academy kepada DQLab.id Fashion dengan alasan dua variable tersebut sudah cukup.

**Petunjuk Penyelesaian Project**

Untuk menyelesaikan project, maka kita akan mengetikkan code yang perlu disubmit untuk dicek jawabannya benar atau salah. Berbeda dengan course, setiap code yang disubmit akan otomatis disimpan dan dimunculkan kondisi code terakhir setiap kali Anda buka soal terkait.

Project ini terdiri dari 3 soal, yaitu:

-Mendapatkan insight top 10 dan bottom 10 dari produk yang terjual.

-Mendapatkan daftar seluruh kombinasi paket produk dengan korelasi yang kuat.

-Mendapatkan daftar seluruh kombinasi paket produk dengan item tertentu.

Tiap soal memerlukan input dataset yang telah dijelaskan pada subbab sebelumnya. Setelah diproses maka Anda perlu menuliskan dalam nama file sesuai petunjuk.

**Output Awal: Statistik Top 10**

Tahap pertama sebenarnya yang diinginkan oleh Pak Agus adalah melihat apakah Anda mampu memberikan info top 10 dari dataset transaksi yang diberikan.

Buatlah script R untuk menghasilkan daftar tersebut, dan hasilnya disimpan ke dalam file top10_item_retail.txt.

Gunakan dataset transaksi_dqlab_retail.tsv pada saat membaca data.

**Output Awal: Statistik Bottom 10**

Tahap berikutnya adalah Anda harus bisa memberikan informasi bottom 10 dari dataset transaksi yang diberikan.

Tahap pertama sebenarnya yang diinginkan oleh Pak Agus adalah melihat apakah Anda mampu memberikan info top 10 dari dataset transaksi yang diberikan.

Buatlah script R untuk menghasilkan daftar tersebut, dan hasilnya disimpan ke dalam file bottom10_item_retail.txt.

Gunakan dataset transaksi_dqlab_retail.tsv pada saat membaca data.

**Mendapatkan Kombinasi Produk yang menarik**

Setelah yakin Anda dapat melakukannya Pak Agus ingin Anda mengirimkan file yang berisi daftar 10 paket kombinasi produk yang paling "menarik".

Anda pertamanya bingung, apa sih definisi menarik versi Pak Agus ini. Setelah wawancara intensif, ternyata pengertiannya adalah sebagai berikut:

-Memiliki asosiasi atau hubungan erat.

-Kombinasi produk minimal 2 item, dan maksimum 3 item.

-Kombinasi produk itu muncul setidaknya 10 dari dari seluruh transaksi.

-Memiliki tingkat confidence minimal 50 persen.

Buatlah script R untuk menghasilkan daftar tersebut dan hasilnya disimpan ke dalam file kombinasi_retail.txt. Namun untuk menulis hasil dari rules yang akan tampak seperti di bawah ini, Anda tidak perlu melakukan konversi rules menjadi data.frame.

**Mencari Paket Produk yang bisa dipasangkan dengan Item Slow-Moving**

Slow-moving item adalah produk yang pergerakan penjualannya lambat atau kurang cepat. Ini akan bermasalah apabila item produk tersebut masih menumpuk.

Kadang kala item ini belum tentu tidak laku, hanya saja mungkin harganya tidak bagus dan jarang dibutuhkan jika dijual satuan.  Nah, jika tidak dijual satuan kita perlu cari asosiasi kuat dari item produk ini dengan produk lain sehingga jika dipaketkan akan menjadi lebih menarik.

Pak Agus juga meyakini hal ini, dan ingin agar Anda membantu mengidentifikasi dua item produk yang menurut dia stoknya masih banyak dan perlu dicari pasangan item untuk pemaketannya.

Dua item produk tersebut adalah "Tas Makeup" dan "Baju Renang Pria Anak-anak". Pak Agus ingin meminta kombinasi yang bisa dipaketkan dengan kedua produk tersebut.

Masing-masing produk tersebut dikeluarkan 3 rules yang asosiasinya paling kuat, sehingga total ada 6 rules. Persyaratan-persyaratan asosiasi kuat ini masih sama dengan yang telah disebutkan Pak Agus sebelumnya, kecuali tingkat confidence dicoba pada tingkat minimal 0.1.

Buatlah script R untuk menghasilkan daftar tersebut dan hasilnya disimpan ke dalam file kombinasi_retail_slow_moving.txt.


referensi:

https://academy.dqlab.id/main/projectcode/16/109/514?pr=0

https://academy.dqlab.id/main/projectcode/16/109/515

https://academy.dqlab.id/main/projectcode/16/109/516

https://academy.dqlab.id/main/projectcode/16/109/517

https://academy.dqlab.id/main/projectcode/16/109/518

https://academy.dqlab.id/main/projectcode/16/109/519

https://academy.dqlab.id/main/projectcode/16/109/520
