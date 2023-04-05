# JAVASCRIPT DOM WITH TRAVERSY MEDIA

Repositori ini merupakan tugas mengerjakan kode dari https://youtu.be/0ik6X4DJKCc

---

Jadi tugas ini adalah tugas dimana saya diminta untuk mengerjakan kode berdasarkan video dari kanal Traversy Media tentang Javascript DOM Part 1.

Sebagai permulaan, saya membuat 2 buah file, index.html dan dom.js. Pada index.html saya mengikuti kode divideo yang saya ketik secara manual. Disini Brad selaku pemilik video menggunakan Bootstrap CDN. Setelah mengcopas kode di file index.html, Brad mulai menjelaskan apa itu DOM.

Setelah itu, Brad mulai menjelaskan DOM dengan console.log() & console.dir(). Brad menunjukkan pada apa yang terjadi jika kita menampilkan _document_ ke console. Brad lalu mulai menjelaskan satu persatu method dari _document_, mulai dari domain, URL, title, dan sebagainya.

Setelah itu mulai Brad mulai menjelaskan tentang _getElementById_. Brad mencontohkan cara mengambil id dan apa yang diambil dengan ditampilkan ke console. Brad juga mencontohkan cara mengubah konten dari tag dengan id yang sudah diambil sebelumnya. Brad juga memberikan penjelasan perbedaan _textContent_, _innerText_, dan _innerHTML_. Beliau juga mencontohkan cara memberikan style pada tag dengan id yang diambil.

Lalu masuk pada cara mengambil class dari sebuah tag dengan _getElementsByClassName_. Tag ini mengambil HTMLCollection yang artinya bisa berisi lebih dari satu tag karena class bisa diterapkan pada lebih dari satu tag. Sehingga cara untuk mengubah konten maupun memberikan style juga berbeda, yaitu dengan menggunakan indeks. Jika ingin memanipulasi semua tag, bisa menggunakan perulangan for.

Untuk selanjutnya, yaitu mengambil tag menggunakan _getElementsByTag_. Cara untuk memanipulasi konten mirip dengan _getElementsByClassName_ karena berupa HTMLCollection.

Masuk ke _querySelector_ dimana cara ini bisa untuk mengambil tag, class, maupun id dari sebuah tag. Jika mengambil sebuah class, maka perlu menambahkan "." sebelum nama class dan "#" sebelum nama id jika mengambil sebuah id.

_querySelectorAll_ memiliki kemiripan dengan _querySelector_ tetapi _querySelectorAll_ mengambil NodeList. Sehingga cara untuk memanipulasinya bisa menggunakan indeks dan perulangan for jika ingin mengubah lebih dari satu.
