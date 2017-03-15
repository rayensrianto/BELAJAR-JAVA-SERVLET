# Rangkuman Servlet


## What is Servlet ?

Servlet adalah teknologi pada java untuk membuat applikasi berbasis web yang berada di sisi server dan menghasil sebuah website yang dinamis.

Teknologi servlet itu kuat dan scalable, karena menggunakna bahasa Java. Sebelum servlet, CGI adalah bahasa scripting populer yang digunakan sebagai server side. Tapi katanya banyak kelemahan di bandingkan servlet.

Servlet dapat di artikan lebih dari satu, tergantung konteks nya, antara lain:
- Servlet adalah teknologi yang digunakan untuk membangun web application
- Servlet adalah API yang menyediakan banyak interface dan class termasuk dokumentasi.
- Servlet adalah sebuah interface yang harus di implementasikan saat membuat servlet apapun.
- Servlet adalah sebuah class yang memiliki kemampuan server dan me response semua request yang masuk.
- Servlet adalah komponen web yang digunakan pada server untuk membuat halaman web dinamis


## Web Terminologi

### What is HTTP ? 
Sebuah protokol yang menghubungkan antara client dengan server.

HTTP adalah TCP/IP yang berbasis protokol komunikasi, yang digunakan untuk mengirimkan data seperti gambar, hasil query, file dll di WWW menggunakan port standar TCP yaitu 80. 

WWW merupakan kumpulan peladen web dari seluruh dunia yang mempunyai kegunaan untuk menyediakan data dan informasi untuk dapat digunakan bersama.

![](https://github.com/rayensrianto/belajar-java-servlet/blob/master/servlet-http4.png)

Karakteristik HTTP
- Protokol yang mengijinkan webserver dan browser saling bertukar data melalui web.
- Protokol yang akan meresponse semua request.

![](https://github.com/rayensrianto/belajar-java-servlet/blob/master/servlet-http5.png)

HTTP adalah request/response protocol yang berbasis client/server. Dalam web browser, search engine dan yang lain nya berperilaku sebagai HTTP klien dan Web Server seperti servlet berperilaku sebagai server.

### HTTP Request
Request yang dikirim oleh komputer ke web server yang berisi segala macam informasi sering disebut HTTP Request.

HTTP client mengirimkan sebuah request ke server dengan form request message yang berisi informasi sbb:
- The Request-line
- The analysis of source IP address, proxy and port
- The analysis of destination IP address, protocol, port and host
- The Requested URI (Uniform Resource Identifier)
- The Request method and Content
- The User-Agent header
- The Connection control header
- The Cache control header

HTTP Request memiliki method yang menunjukan method apa yang akan di lakukan, method ini di indetifikasi oleh request URI(Uniform Resource Identifier).

HTTP Request method antara lain:
- GET 		: meminta resource pada URL yang di minta
- POST 		: meminta server untuk menerima info body yang dibawa, hampir mirip GET
- HEAD 		: meminta server untuk menampikan bagian HEAD
- TRACE 	: meminta ulang request message untuk testing troubleshooting
- PUT
- DELETE
- OPTIONS

### GET vs POST
Perbedaan mendasar antara GET dengan POST, antara lain:
- pada GET request, data yang dikirm terbatas karena menggunakan header, sedangkan POST request data yang dikirim lebih besar karna menggunakan body.
- GET request kurang aman karna terlihat di URL bar, sedangkan POST request lebih aman karna tidak terlihat di URL bar.
- GET request dapat di bookmark, sedangkan POST request tidak bisa.
- GET request adalah idempotent(request ke dua akan di proses jika request pertama sudah di layani/dikirm kembali ke client) sedang kan POST request itu non-idempotent
- 



























































