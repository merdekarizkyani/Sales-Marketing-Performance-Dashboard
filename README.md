# Sales-Marketing-Performance-Dashboard
Dashboard Power BI interaktif 3 halaman untuk memantau performa penjualan, efektivitas kampanye pemasaran (ROAS), profitabilitas produk, performa pengiriman, dan kepuasan pelanggan (CSAT) beserta analisis kontribusi per kategori dan wilayah.

<img width="1432" height="807" alt="image" src="https://github.com/user-attachments/assets/7ff45577-bbe9-4da8-b8c0-17fd1aa9197b" />
<img width="1430" height="807" alt="image" src="https://github.com/user-attachments/assets/f282cdd1-1abc-42ce-a99d-add6df6cb009" />
<img width="1437" height="806" alt="image" src="https://github.com/user-attachments/assets/62d1f1ca-2d31-44dd-b551-11166aa90ade" />

### Tools
1. **Power BI Desktop:** Untuk pembersihan dan transformasi data (*Power Query*), pemodelan data dan pembuatan metrik bisnis (*DAX*), serta perancangan dashboard interaktif 3 halaman (*Summary*, *Marketing & Campaign Performance*, dan *Product & Portfolio Analytics*).
2. **GitHub:** Sebagai repositori file proyek (`.pbix`), dokumentasi teknis (`README.md`), dan portofolio data analisis.

---

### 1. Business Insights
* **a. Kinerja Finansial & Skalabilitas Bisnis:** Secara keseluruhan (*All-Time*), perusahaan mencatat **Total Revenue sebesar Rp40,54 Miliar** (`Rp40.541.700.000`) dan **Total Profit sebesar Rp7,28 Miliar** (`Rp7.284.852.768`) dari **9.000 pesanan** (*Total Orders*), dengan nilai rata-rata per transaksi (**AOV**) mencapai **Rp4,50 Juta** (`Rp4.504.633`) dan rasio **Profit Margin stabil di 17,96%**. Pada tahun 2023 saja, perusahaan menyumbang **Rp20,75 Miliar** pendapatan (lebih dari separuh total omzet) dari **4.494 pesanan**.
* **b. Efektivitas Pemasaran & Paradoks ROAS:** Dari total anggaran pemasaran (**Total Marketing Spend**) sebesar **Rp3,65 Miliar** (`Rp3.647.420.724`), seluruh pendapatan tercatat terhubung dengan kampanye (**Total Campaign Revenue = Rp40,54 Miliar**), menghasilkan **ROAS sangat tinggi di angka 11,12x**. Secara nominal, kampanye **Loyalty Rewards** menjadi penyumbang pendapatan tertinggi (*Top Performing Campaign*), diikuti oleh **Back to School** dan **Ramadan Sale**. Namun secara kritis, seluruh 8 kampanye memiliki efisiensi ROAS yang nyaris seragam (berkisar antara **11,09x hingga 11,15x**), menunjukkan bahwa pertumbuhan pendapatan berbanding lurus dengan besarnya anggaran yang digelontorkan.
* **c. Konsentrasi Risiko pada Kategori & Produk Utama:** Kategori **Electronics** mendominasi struktur bisnis dengan kontribusi pendapatan **Rp24,14 Miliar** (**59,55%** dari total omzet) dan profit **Rp4,34 Miliar** dari 3.814 pesanan. Produk **Laptop** menjadi kontributor tunggal terbesar (*Top Performing Product*), diikuti oleh *Camera* dan *Smartphone*. Di sisi lain, kategori **Apparel** hanya menyumbang **Rp1,61 Miliar** (**3,98%** dari total pendapatan).
* **d. Anomali Operasional (Ketepatan Pengiriman vs. Tingkat Retur):** Terdapat celah operasional yang signifikan: tingkat pengiriman tepat waktu (**% On-Time**) hanya mencapai **32,04%** (artinya hampir **68% pesanan mengalami keterlambatan**). Sejalan dengan hal tersebut, tingkat pengembalian barang (**% Returned**) mencapai **16,48%** secara keseluruhan, dengan tingkat retur tertinggi terjadi pada kategori penyumbang omzet terbesar, yakni **Electronics (17,45%)**, dan terendah pada **Furniture (14,61%)**.
* **e. Kepuasan Pelanggan (CSAT) & Persebaran Wilayah:** Rata-rata skor kepuasan pelanggan (**Avg CSAT**) berada di angka **3,64 dari 5,00**. Meskipun **67,09%** pelanggan memberikan rating positif (36,37% skor 5 dan 30,72% skor 4), masih terdapat **32,91%** pelanggan yang memberikan skor rendah (skor 1 hingga 3) yang berpotensi berkaitan langsung dengan tingginya keterlambatan pengiriman. Secara geografis, wilayah **Jakarta dan Jawa Barat** (seperti Bekasi, Tangerang, Karawang, dan Bogor) menjadi pusat konsentrasi pendapatan utama.

---

### 2. Pertanyaan Bisnis
1. **Akar Masalah Logistik:** Mengapa tingkat ketepatan waktu pengiriman (*% On-Time*) hanya berada di angka **32,04%**, dan seberapa besar korelasi keterlambatan pengiriman tersebut terhadap tingginya tingkat pengembalian barang (**16,48%**) serta **32,91%** ulasan pelanggan dengan skor CSAT ?
2. **Mitigasi Retur pada Kategori *High-Value*:** Bagaimana strategi menekan angka retur pada kategori **Electronics** (**17,45%**) yang menyumbang hampir 60% pendapatan perusahaan agar kerugian biaya logistik balik (*reverse logistics*) dan penyusutan profit dapat diminimalkan?
3. **Efisiensi Anggaran & Diversifikasi Kategori:** Mengingat seluruh kampanye memiliki ROAS yang identik (~11,12x), apakah penambahan anggaran pada kampanye *Loyalty Rewards* dan *Back to School* masih menghasilkan kenaikan margin yang optimal, serta bagaimana strategi mendongkrak kontribusi kategori **Apparel** (3,98%) dan **Furniture** agar bisnis tidak terlalu bergantung pada produk *Electronics*?

---

### 3. Peluang & Rekomendasi Strategis
1. **Restrukturisasi SLA Logistik & Manajemen Gudang Regional:** Lakukan audit terhadap mitra ekspedisi dan alokasi stok gudang di area Jabodetabek serta Jawa Barat guna mengejar target peningkatan *% On-Time* dari **32,04%** menjadi minimal **>80%**. Perbaikan ketepatan waktu adalah langkah paling krusial untuk mendongkrak skor CSAT dari 3,64 menembus angka >4,20.
2. **Program *Pre-Shipment Quality Control* (QC) & Edukasi Produk Electronics:** Terapkan standar pengecekan fisik/fungsi wajib serta kemasan pelindung ekstra khusus untuk produk bernilai tinggi (*Laptop, Camera, Smartphone*), disertai panduan spesifikasi yang jelas di halaman produk untuk memangkas tingkat retur kategori *Electronics* di bawah 10%.
3. **Strategi *Cross-Selling Bundling* & Realokasi Anggaran Kampanye:** Manfaatkan tingginya trafik pembeli *Electronics* dengan membuat paket *bundling* lintas kategori (misalnya *Laptop + Office Chair/Bookshelf*) untuk mengangkat volume penjualan kategori *Furniture* dan *Apparel* tanpa harus membakar anggaran pemasaran tambahan secara terpisah.

---

### 4. Ringkasan Visualisasi Dashboard
1. **KPI Cards (Multi-Page):** Menampilkan metrik inti secara dinamis di setiap halaman: *Total Revenue, Total Profit, Total Orders, Profit Margin, Total Marketing Spend, ROAS, Total Campaign Revenue, AOV, Top Performing Campaign,* dan *Top Performing Product*.
2. **Trend Line & Area Charts:** Memvisualisasikan pergerakan *Total Revenue* dan *Total Profit* berdasarkan bulan dan kuartal (Halaman 1), korelasi tren *Revenue vs. Marketing Spend* bulanan (Halaman 2), serta fluktuasi *Total Orders* dan *Total Profit* bulanan (Halaman 3).
3. **Donut & Pie Charts:** Menganalisis proporsi *Total Revenue* berdasarkan *Customer Segment, Region,* dan *Sales Channel* (Halaman 1), serta distribusi *Total Marketing Spend* per kanal pemasaran dan proporsi *Total Orders* berdasarkan kelompok skor *CSAT* (Halaman 2).
4. **Bar, Column & Scatter Charts:** Membandingkan performa produk (*Revenue & Profit by Product Name*), efisiensi *ROAS by Marketing Campaign*, serta *Scatter Plot* hubungan antara *Marketing Spend, Revenue,* dan *ROAS*.
5. **Treemap, Filled Map & Gauge Charts:** Menampilkan hierarki kontribusi pendapatan per produk (*Treemap*), persebaran geografis penjualan per kota (*Map*), serta indikator kesehatan operasional berupa **% On-Time (32,04%)** dan **% Returned (16,48%)** (*Gauge Charts*).

---

### 5. Pemrosesan Data & DAX Measures

#### A. Pembersihan & Transformasi Data (*Power Query & DAX*)
* **Validasi & Integritas Data:** Memastikan keunikan setiap transaksi menggunakan `Order_ID` untuk mencegah perhitungan ganda pada agregasi pendapatan maupun jumlah pesanan, serta menangani nilai kosong (*null/blank*) pada atribut kampanye pemasaran.
* **Standardisasi Tipe Data:** Mengonversi kolom tanggal transaksi ke tipe *Date*, atribut finansial (`Revenue`, `Profit`, `Marketing_Spend`) ke format *Currency (IDR)*, serta kolom status biner (`Is_On_Time`, `Is_Returned`) ke tipe numerik agar dapat dihitung rasio persentasenya.
* **Kategorisasi Produk (*Calculated Column*):** Membuat kolom `Category` menggunakan logika kondisional `SWITCH` untuk mengelompokkan 15 SKU produk ke dalam 4 kategori bisnis utama (*Electronics, Home Appliances, Furniture, Apparel*):

```dax
Category = 
SWITCH(
    TRUE(),
    sales_marketing_indonesia[Product_Name] IN {"Headphones", "Camera", "Smart Watch", "Smartphone", "Laptop"}, "Electronics",
    sales_marketing_indonesia[Product_Name] IN {"Air Fryer", "Rice Cooker", "Microwave", "Blender", "Vacuum Cleaner"}, "Home Appliances",
    sales_marketing_indonesia[Product_Name] IN {"Office Chair", "Sofa", "Bookshelf"}, "Furniture",
    "Apparel"
)

B. Summary DAX Measures Utama
No	Nama Measure	              Rumus DAX
1.	Total Revenue	              SUM(sales_marketing_indonesia[Revenue])
2.	Total Profit	              SUM(sales_marketing_indonesia[Profit])
3.	Total Orders	              DISTINCTCOUNT(sales_marketing_indonesia[Order_ID])
4.	Total Marketing Spend	      SUM(sales_marketing_indonesia[Marketing_Spend])
5.	Total Campaign Revenue	      CALCULATE([Total Revenue], NOT(ISBLANK(sales_marketing_indonesia[Marketing_Campaign])))
6.	AOV	                      DIVIDE([Total Revenue], [Total Orders], 0)
7.	Profit Margin	              DIVIDE([Total Profit], [Total Revenue], 0)
8.	ROAS	                      DIVIDE([Total Revenue], [Total Marketing Spend], 0)
9.	% On-Time	              AVERAGE(sales_marketing_indonesia[Is_On_Time])
10.	% Returned	              AVERAGE(sales_marketing_indonesia[Is_Returned])
11.	Avg CSAT	              AVERAGE(sales_marketing_indonesia[CSAT_Score])
12.	Top Performing Campaign	      CALCULATE(SELECTEDVALUE(sales_marketing_indonesia[Marketing_Campaign]), TOPN(1, ALL(sales_marketing_indonesia[Marketing_Campaign]), [Total Revenue], DESC))
13.	Top Performing Product	      CALCULATE(SELECTEDVALUE(sales_marketing_indonesia[Product_Name]), TOPN(1, ALL(sales_marketing_indonesia[Product_Name]), [Total Revenue], DESC))
