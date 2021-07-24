# FORENSIC
**Forensik** adalah seni memulihkan jejak digital yang tertinggal di komputer.

# TABLE OF CONTENT
- [Forensic dalam CTF](#forensic-dalam-ctf)
- [File Format Identification & Magic Bytes](#file-format-identification-magic-bytes)
- [File Carving](#file-carving)
- [Initial Analysis File](#initial-analysis-file)
- [Encoding & Decoding](#encoding-decoding)
- [Archive, Cracking Use Wordlist](#archive-cracking-use-wordlist)
- [Steganography](#steganography)
	
## Forensic dalam CTF
**Forensic** dalam dunia CTF atau Capture The Flag secara umum memiliki tujuan untuk menyembunyikan pesan yang disembunyikan (flag) pada berbagai media digital seperti gambar, audio, video, dll. dan tugas kita adalah mencari flag pada media digital yang telah di sisipkan sebuah pesan rahasia dengan berbagai metode forensic yang ada.
	
## File Format Identification & Magic Bytes
Pada forensic terdapat istilah yaitu file format identification & magic bytes atau biasa di kenal juga dengan file signature. Adalah Teknik untuk mengidentifikasi informasi (metadata) dari sebuah file.  untuk melihat jenis apakah sebuah file biasanya kita akan memperhatikan tentang header nya atau biasa disebut juga file signature. lalu untuk jenis jenis file signature bisa dilihat pada link dibawah :
	[Link File Signature](https://en.wikipedia.org/wiki/List_of_file_signatures)
	
## File Carving
File Carving adalah sebuah teknik untuk mencari data yang telah hilang atau tersembunyi dalam suatu file. Pada linux tools yang bisa digunakan untuk melakukan file carving adalah seperti' binwalk & foremost.
	
## Initial Analysis File
Langkah langkah untuk menganalisa sebuah soal forensic :
- Baca deskripsi soal dan juga judul soal
- Tentukan jenis forensic soal dari hint yang ada
- Cek type file nya ( bisa menggunakan "file", binwalk ,atau "xxd" dengan mengcek header file nya)
- Cek file apa saja yang ada dalam file tersebut ( pada umumnya menggunakan binwalk )
- Lalu untuk mengcek isi dari file bisa menggunakan "cat", "xxd", "strings", dll.
- Lalu gunakan tools tools dasar seperti grep untuk memudahkan menganalisa file nya.
- Selesaikan soal dengan hasil analysis

## Encoding & Decoding
- Encoding merupakan proses membuat pesan yang sesuai dengan kode tertentu
- Decoding merupakan proses menggunakan kode untuk memaknai pesan


## Archive, Cracking Use Wordlist
Inti dari topik ini adalah kita diharuskan mengcrack file zip atau archive lainnya menggunakan file  wordlist yang sudah umum digunakan. contoh wordlist yang biasa digunakan adalah rokyou, ransom, crackdown dll. lalu tools yang digunakan pada linux biasanya adalah fcrackzip
	
## Steganography
Adalah ilmu dan seni menulis sebuah pesan rahasia atau menyembunyikan pesan dengan suatu cara. Tujuan steganography adalah untuk menyembunyikan keberadaan sebuah pesan rahasia atau kalau dalam dunia ctf menyembunyikan keberadaan dari flag. Tools yang bisa digunakan untuk steganography ini cukup banyak seperti stegsolves, steghide, stegsnow dll.
	
	