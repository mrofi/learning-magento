###Install Magento
1. Download Magento Files di sini https://www.magentocommerce.com/products/downloads/magento/. Piih yang full release.
2. Extract File (zip|tar|tar.gz) ke dalam sebuah folder **htdocs/www-root** Anda atau bisa juga masukkan ke dalam folder mana pun
jika Anda menggunakan Built-in PHP Development Server. (Saya juga pake itu :smile:)
3. Akses menggunakan web browser Anda setelah Anda menghidupkan web service Anda. **P.S.** Saya menggunakan PHP Buil-in Web Server, 
dengan host: localhost port: 9999 maka saya mengakses http://localhost:9999/ untuk memulai instalasi.
4. Proses Instalasi dimulai ketika web browser menampilkan gambar berikut : 
![Install Magento](https://blog.hiret.web.id/wp-content/uploads/2015/05/screencapture-localhost-9999-index-php-install-1432635127725.png)
Check pada **I agree to the above terms and conditions.** kemudian Klik Tombol **Continue**
5. Di halaman selanjutnya Anda diminta untuk mensetting locale (bahasa), Timezone (Zona waktu) dan Currency (Mata uang) sesuaikan dengan
lokasi toko Anda. ![Setting Locale](https://blog.hiret.web.id/wp-content/uploads/2015/05/screencapture-localhost-9999-index-php-install-wizard-locale-1432636463820.png)
Klik Continue
6. Selanjutnya adalah Database Configuration ![Configuration](https://blog.hiret.web.id/wp-content/uploads/2015/05/screencapture-localhost-9999-index-php-install-wizard-config-1432636664667.png)

Untuk Host, Username, Password disesuaikan dengan settingan Database Anda. 
Kemudian untuk centang di bawahnya :

- [x] Enable Chart jika Anda ingin ada chart di dalam dashboard,
- [x] Skip Base Validation jika ingin melewati pengecekan base url, 
- [x] Use Web Server Rewrite jika server anda mendukung fungsi rewrite. 
- [x] Use Secure SSL, Jika sercer Anda support SSL

Kemudian di bawahnya ada pilih untuk menyimpan Session, apakah di file atau simpan di database. Klik **Continue**



