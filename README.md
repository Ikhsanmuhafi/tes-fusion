# EVAN &amp; IKHSAN

#### Project Individu Gabungan Back End &amp; Front End
#### Praxis Academy Batch Desember 2020

#### << BACK END (Java, Maven, Spring Boot, Postgresql) >>
##### 1. [Spring Boot Initializr](https://start.spring.io/)
##### 2. Mendesain relasi tabel dan implementasi (products, keranjang, pesanan)
Tabel products :
```java
    private Long id;

    private String kode;

    private String nama;

    private Integer harga;

    private Boolean is_ready;

    private String gambar;
```
    
Tabel keranjang :
```java
    private Long id;

    private Integer jumlahPesanan;

    private String keterangan;

    private Long product;
```

Tabel pesanan :
```java
    private Long id;

    private String nama;

    private Integer noMeja;

    private Long keranjang;
```
Menggunakan @ManyToOne untuk relasinya

ID generate IDENTITY

Saat ini belum membuat fitur register &amp; login
