## 1. Gauge Car Dark
I.	Type : Gauge

II.	Option :
#### **Toolbox** ####
1.	toolbox : show (boolean) : memunculkan komponen toolbox (default=false).
2.	toolbox : orient (string) : untuk menentukan letak ikon toolbox (default=horizontal) (horizontal,vertical).
3.	toolbox : itemSize (number) : menentukn ukuran ikon toolbox (default=15).
4.	toolbox : itemGap (number) : jarak antara masing-masing legend, jarak horizontal dalam tata letak horizontal, dan jarak vertical dalam tata letak vertical (default=10).
5.	toolbox : showTitle (Boolean) : untuk menunjukkan judul setiap ikon saat mouse melayang di atas icon (default=true).
6.	toolbox : feature (object) : item konfigurasi untuk setiap tool.
7.	toolbox : iconStyle (object) : normal (object) : color (color) : untuk mengubah warna ikon.
8.	toolbox : iconStyle (object) : normal (object) : borderColor (color) : mengubah warna area pinggir pada objek.
9.	toolbox : iconStyle (object) : normal (object) : borderWidth (number) : menentukan ketebalan border pada ikon (default=1).
10.	toolbox : iconStyle (object) : normal (object) : borderType (string) : untuk menentukan jenis border pada ikon (default=solid) (dashed,dotted,solid).
11.	toolbox : iconStyle (object) : normal (object) : shadowBlur (number) : mengatur blur pada bayangan.
12.	toolbox : iconStyle (object) : normal (object) : shadowColor (color) : mengatur warna bayangan.
13.	toolbox : iconStyle (object) : normal (object) : shadowOffsetX (number) : mengatur posisi bayangan horizontal (default=0).
14.	toolbox : iconStyle (object) : normal (object) : shadowOffsetY (number) : mengatur posisi bayangan vertical (default=0).
15.	toolbox : iconStyle (object) : normal (object) : opacity (number) : mendukung nilai dari 0 sampai 1, dan komponen tidak akan ditarik saat diatur ke 0.
16.	toolbox : iconStyle (object) : normal (object) : textPosition (string) : mengatur posisi teks.
17.	toolbox : iconStyle (object) : normal (object) : textAlign (string) : mengatur align teks.
18.	toolbox : iconStyle (object) : emphasis (object) : color (color) : mengatur warna saat mouse melayang di atas ikon.
19.	toolbox : iconStyle (object) : emphasis (object) : borderColor (color) : mengubah warna area pinggir pada objek.
20.	toolbox : iconStyle (object) : emphasis (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
21.	toolbox : iconStyle (object) : emphasis (object) : shadowColor (color) : mengubah warna bayangan objek.
22.	toolbox : iconStyle (object) : emphasis (object) : shadowOffsetX (number) : jarak bayangan horizontal.
23.	toolbox : iconStyle (object) : emphasis (object) : shadowOffsetY (number) : jarak bayangan vertikal.

#### **Series** ####
1.	series : axisLine (object) : show (boolean) : memunculkan garis (true) atau tidak memunculkan garis (false).
2.	series : axisLine (object) : onZero (boolean) : menentukan sumbu X atau Y terletak pada posisi asal yang lain, dimana value 0 pada sumbu. Berlaku hanya jika yang lain adalah value type, dan mempunyai value 0 (default=true).
3.	series : axisLine (object) : lineStyle (color) : warna pada garis.
4.	series : axisLine (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
5.	series : axisLine (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
6.	series : axisLine (object) : shadowColor (color) : mengubah warna bayangan objek.
7.	series : axisLine (object) : shadowOffsetX (number) : jarak bayangan horizontal.
8.	series : axisLine (object) : shadowOffsetY (number) : jarak bayangan vertikal.
9.	series : axisTick (object) : show (boolean) : untuk menunjukkan tanda.
10.	series : axisTick (object) : alignWithLabel (boolean) : sejajarkan dengan label, yang tersedia hanya jika boundaryGap diset menjadi true dalam kategori.
11.	series : axisLabel (object) : rotate (number) : untuk merotasikan label pada axis.
12.	series : axisLabel (object) : margin (number) : margin antara axis label dan garis.
13.	series : axisLabel (object) : formatter (string,function) : Formatter dari label, yang mendukung template string dan fungsi callback. 
14.	series : axisLabel (object) : textStyle (object) : color(string) : untuk mengubah warna pada text.
15.	series : axisLabel (object) : textStyle (object) : fontSize(number) : untuk mengubah ukuran text (default=18).
16.	series : axisLabel (object) : textStyle (object) : fontStyle(string) : italic : mengubah huruf menjadi miring.
17.	series : axisLabel (object) : textStyle (object) : fontWeight (string) : bold : membuat text menjadi tebal.
18.	series : axisLabel (object) : textStyle (object) : fontWeight (string) : lighter : membuat text menjadi tipis.
19.	series : axisLabel (object) : textStyle (object) : fontFamily (string) : mengubah jenis font.
20.	series : align (string) : menentukan posisi huruf (left,center,right).
21.	series : axisLabel (object) : textStyle (object) : baseLine (string) : textStyle (object) : mengatur posisi text dalam vertical (middle,top,bottom).
22.	series : splitLine (object) : show (boolean)  :  nilai ditampilkan secara default, sedangkan kategori tidak.
23.	series : splitLine (object) : lineStyle (object) : interval (number,function) : garis pada chart.
24.	series : splitLine (object) : lineStyle (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
25.	series : splitLine (object) : lineStyle (object) : shadowColor (color) : mengubah warna bayangan objek.
26.	series : splitLine (object) : lineStyle (object) : shadowOffsetX (number) : jarak bayangan horizontal.
27.	series : splitLine (object) : lineStyle (object) : shadowOffsetY (number) : jarak bayangan vertikal.
28.	series : splitLine (object) : lineStyle (object) : color(string) : untuk mengubah warna pada text.
29.	series : splitLine (object) : lineStyle (object) : width (number) : lebar splitLine.
30.	series : splitLine (object) : lineStyle (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
31.	series : detail : backgroundColor (color) : mengubah warna belakang pada detail gauge.
32.	series : detail : show (Boolean) : untuk memunculkan efek detail pada gauge.
33.	series : detail : width (number,string) : lebar untuk blok pada teks.
34.	series : detail : height (number,string) : panjang untuk blok pada teks.
35.	series : detail : borderWidth (number) : border pada detail teks.
36.	series : detail : borderColor (string) : warna border pada detail teks.
37.	series : detail : color (color) : warna teks.
38.	series : detail : color(string) : untuk mengubah warna pada text.
39.	series : detail : fontSize(number) : untuk mengubah ukuran text (default=18).
40.	series : detail : fontStyle(string) : italic : mengubah huruf menjadi miring.
41.	series : detail : fontWeight (string) : bold : membuat text menjadi tebal.
42.	series : detail : fontWeight (string) : lighter : membuat text menjadi tipis.
43.	series : detail : fontFamily (string) : mengubah jenis font.
44.	series : detail : borderRadius (number) : radius border.
45.	series : detail : padding (number,Array) : jarang pada area teks fragment.
46.	series : detail : shadowBlur (number) : membuat bayangan objek menjadi blur.
47.	series : detail : shadowColor (color) : mengubah warna bayangan objek.
48.	series : detail : shadowOffsetX (number) : jarak bayangan horizontal.
49.	series : detail : shadowOffsetY (number) : jarak bayangan vertikal.
50.	series : detail : offsetCenter (array) : posisi relatif offset terhadap pusat chart gauge.
