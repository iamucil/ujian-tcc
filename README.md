# Teknik Cloud Computing

> Overview praktikum Mata Kuliah Teknik Cloud Computing. Link Repository Praktikum ada di reposity: [iamucil/tcc](https://github.com/iamucil/tcc)

1. [Materi Praktikum 1: Instalasi Git pada Sistem Operasi Windows dan Konfigurasi GIT](https://github.com/iamucil/tcc/blob/master/minggu-01/README.md)

    Pada praktikum Pertemuan pertama (minggu-01) terdapat beberapa bagian praktikum, berdasarkan sumber dari repository [stmik-akakom/rtfm](https://github.com/stmik-akakom/rtfm).

    Pada praktikum ini difokuskan pada pengenalan git. Sebelum melakukan instalasi `git` pada windows, pastikan terdapat teks editor (notepad++, visual studio code, sublime, vim, etc) sudah terinstall. Keberadaan teks editor ini akan mempengaruhi keberhasilan dari proses instalasi git di komputer nantinya.

2. [Materi Praktikum 2: Mengelola Repo](https://github.com/iamucil/tcc/blob/master/minggu-02/README.md)

    Git adalah _version control system_ yang digunakan para developer untuk mengembangkan software secara bersama-bersama. Fungsi utama git yaitu mengatur versi dari source code program dengan memberi tanda baris dan code mana yang ditambah atau diganti. Tempat untuk menyimpan _source code_ di dalam git di sebut sebagai _repository_ yang selanjutnya sering di sebut _repo_ saja.

    Dalam [github.com](https://github.com) setiap akun yang terdaftar dapat memanfaatkan 2 metode untuk mengatur repository, yaitu: *Personal Account* dan *Organization Account*.

3. [Materi Praktikum 3: SaaS](https://github.com/iamucil/tcc/blob/master/minggu-03/README.md)

    SaaS adalah suatu model aplikasi perangkat lunak berbasis cloud yang memungkinkan datanya bisa diakses dari perangkat apapun selama perangkat tersebut terkoneksi dengan internet. Aplikasi yang perlu tersedia di dalam perangkat hanyalah web browser. Pada layanan SaaS pengguna layanan tidak harus mengerti dan tidak perlu mengurus bagaimana data disimpan atau bagaimana aplikasi tersebut di maintenance, karena hal tersebut merupakan service yang disediakan penyedia layanan. Selengkapnya ada di laporan [praktikum minggu-03](https://github.com/iamucil/tcc/blob/master/minggu-03/README.md).

4. [Materi Praktikum 4: BPaaS](https://github.com/iamucil/tcc/blob/master/minggu-04/README.md)

    Melanjutkan tentang cloud services yaitu Business Process as a Service (BPaaS), merupakan jenis proses bisnis horizontal atau vertikal yang disampaikan berdasarkan model layanan cloud. Layanan ini mencakup Platform as a Service (PaaS), Software as a Service (SaaS) dan Insfrastructure as a Service (IaaS). Salah satu contoh software yang menerapkan BPaaS adalah ERP (Enterprise Resource Planning).

5. [Materi Praktikum 5: CockroachDB](https://github.com/iamucil/tcc/blob/master/minggu-05/README.md)

    CockroachDB adalah database SQL terdistribusi. Tujuan desain utama adaah scalability, consistency dan survivability yang kuat (oleh karena itu dinamakan Cockroach). Praktikum-5 (Minggu ke 5) mencoba instalasi cockroachdb dan menjalankan cockroachdb menggunakan beberapa environment mulai dari binary, kubernetes dan docker.

6. [Materi Praktikum 6: Docker](https://github.com/iamucil/tcc/blob/master/minggu-06/README.md)

    Docker container berjalan berdasarkan Docker Image. Docker Image ini berisi tentang semua kebutuhan untuk menjalankan sebuah proses. Ada beberapa docker image yang sudah tersedia di [Docker Registry](https://registry.hub.docker.com/) atau jalankan perintah `docker search nama-docker-image`. Praktikum 6 (Minggu ke-6) mencoba menjalankan docker dari [katacode](https://www.katacoda.com/courses/docker/deploying-first-container), mencoba eksekusi docker menggunakan emulator web yang tersedia, kasus nya adalah image redis bagaimana menjalankan mengakses docker container. Selain itu juga mencoba membuat image dengan membuat `Dockerfile` sendiri yang berisi html statis.

7. [Materi Praktikum 7: PaaS Provider - Google App Engine](https://github.com/iamucil/tcc/blob/master/minggu-07/README.md)

    Platform as a service (PaaS) adalah kategori layanan komputasi awan yang menyediakan platform yang memungkinkan pelanggan untuk mengembangkan, menjalankan, dan mengelola aplikasi tanpa kompleksitas membangun dan memelihara infrastruktur yang biasanya terkait dengan pengembangan dan peluncuran aplikasi. Pada praktikum ini saya memilih menjelaskan tentang Google App Engine yaitu salah satu layanan Paas dari google, selain menjalankan salah satu provider task lain adalah mencoba Gigalixir yaitu PaaS yang khusus digunakan untuk menjalankan aplikasi menggunakan bahasa pemrograman elixir.

8. [Materi Praktikum 8: Docker image](https://github.com/iamucil/tcc/blob/master/minggu-08/README.md)

    Praktikum pra UTS, praktikum ini mengerjakan UTS studi kasus. Ketentuan: Minimal menggunakan python+flask.\
TODO: Membuat image docker menggunakan elixir+phoenix untuk membuat webview. Dalam praktikum ini saya mencoba membuat sebuah docker image yang berisi web yang berbasis elixir yaitu menggunakan framework phoenix. Langkah-langkah dari pembuatan aplikasi menggunakan docker container sampai jadi sebuah docker image ada di dalam laporan praktikum ini.

9. [Materi Praktikum 9: Docker image - Lanjut](https://github.com/iamucil/tcc/blob/master/minggu-09/README.md)

    Tidak ada materi khusus pada praktikum 9, masih meneruskan dari praktikum 8 yaitu membuat sebuah docker image.

10. [Materi Praktikum 10: Kolaborasi dengan GIT](https://github.com/iamucil/tcc/blob/master/minggu-10/README.md)

    Selain untuk mengelola aset digital milik diri sendiri, kita bisa menggunakan Git untuk berkolaborasi dalam suatu repo di GitHub yang bisa diakses bersama. Dalam kolaborasi terdapat 2 peran yaitu pemilik repo yang disebut author (upstream) dan kontributor.

    Kontributor untuk bisa berkontribusi ke repo author menggunakan skenario forking. Langkah-langkah kolaborasi ada di laporan praktikum 10: Kolabosari dengan GIT.

11. [Materi Praktikum 11: IaaS](https://github.com/iamucil/tcc/blob/master/minggu-11/README.md)

    Tugas kelompok yang terdiri maksimal 5 orang, menjelaskan tentang IaaS (Infrastructure as a Service) yang mencakup tentang: Konsep IaaS, Berbagai software IaaS, Getting Started Software IaaS yang dipilih, dan arsitektur dan konsep deployment pada software IaaS yang dipilih. Pada praktikum ini masih kosong.

12. [Materi Praktikum 12: Docker compose](https://github.com/iamucil/tcc/blob/master/minggu-12/README.md)

    Compose adalah tool untuk mendefinisikan dan menjalan beberapa container secara bersamaan. Untuk bisa menjalankan drupal di perlukan beberapa service antara lain, nginx untuk web server, PHPFpm karena drupal basisnya ada php, MariaDB untuk database. Service-service ini di bungkus dalam satu file `docker-compose.yaml` dan untuk menjalankannya cukup dengan perintah `docker-compose up --build`. Langkah-langkah menjalankan drupal menggunakan `docker-compose` terdapat di dalam laporan [praktikum 12: Docker Compose](https://github.com/iamucil/tcc/blob/master/minggu-12/README.md)

13. [Materi Praktikum 13: Docker swarm mode](https://github.com/iamucil/tcc/blob/master/minggu-13/README.md)

    Docker memperkenalkan swarm mode pada versi 1.12. Mode ini memungkinkan pengguna untuk me-deploy container pada multiple hosts atau node, menggunakan overlay network. Swarm mode merupakan bagian dari command line interface Docker yang memudahkan pengguna untuk memanage komponen container apabila sudah familiar dengan command-command yang ada di Docker. Docker swarm merupakan salah satu metode untuk orkestrasi docker. Detail tentang docker swarm bisa di lihat pada laporan [Praktikum-13: Docker swarm mode](https://github.com/iamucil/tcc/blob/master/minggu-13/README.md)
