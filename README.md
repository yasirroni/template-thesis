Template Naskah Master Thesis LaTeX
=============================

Template Naskah Thesis dengan typesetting LaTeX untuk Departemen Teknik Elektro dan Teknologi Informasi (DTETI) Universitas Gadjah Mada. Template ini merupakan modifikasi fork dari [Template Naskah Skripsi oleh Mas Guntur](https://github.com/gtrdp/template-skripsi), yang mana beliau sebut adalah hasil modifikasi dari versi pak Pekik Nurwantoro (FMIPA UGM) dan mas Yohan (T Elektro UGM 2008). Karena merupakan fork, sebagian penamaan masih menggunakan nama `Skripsi` (masih dalam tahap refactor ke naskah thesis secara utuh).

Semoga bermanfaat. Anda sangat dibolehkan untuk turut berkontribusi dalam project ini dengan *Fork*, *Pull Request*, *Create New Issue*, atau turut menjadi kontributor repo ini.

Terimakasih.

Download
--------
Silakan download versi terakhir di [https://github.com/yasirroni/template-thesis/releases](https://github.com/yasirroni/template-thesis/releases) (fork dimulai sejak versi 1.1.2).

Quick Start
-----------
1. Siapkan LaTeX environment pada komputer anda, begitu pula LaTeX editornya. File yang diperlukan biasanya berukuran besar, jadi siapkan koneksi internet yang lancar jaya.
	- [*Windows*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)
	- [*Linux*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=linux+setup+latex)
	- [*Mac OS X*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=mac+setup+latex)
	- [Editor LaTeX di web](https://www.overleaf.com/) bisa dengan overleaf.com. Dengan ini kita tidak usah repot siapkan LaTeX environment.

2. *Clone* repository ini dengan [Git](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=setup+git) (cara ini memungkinkan anda untuk mendapatkan update dengan `git fetch upstream`). Atau [unduh](https://github.com/yasirroni/template-thesis/releases) repository ini (cara ini lebih mudah).
3. Mulai tulis naskah anda, keterangan dari masing-masing file dalam template ini ada di bawah.
4. Pertamakali pakai LaTeX? Butuh bantuan? Pergunakanlah Google dengan baik dan bijak. Saya bantu:
	- [Bahasa Indonesia](https://www.google.com/search?q=tutorial+menggunakan+latex&oq=tutorial+menggunakan+latex&aqs=chrome..69i57j0.3219j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)
	- [English](https://www.google.com/search?q=latex+tutorial&oq=latex+tutorial&aqs=chrome..69i57j69i65l3j69i60l2.1884j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)

Contents
--------
Berikut penjelasan dari file-file utama dalam template ini. File lain yang tidak tercantum hanya pelengkap dalam repository ini.

		template-thesis/
			└── main/
				├── bibtex/
				│	└── daftar-pustaka.bib
				├── images/
				│	├── logougm.png
				│	└── wsn.png
				├── sections/
				│	├── bab1.tex
				│	├── bab2.tex
				│	├── bab3.tex
				│	├── bab4.tex
				│	└── bab5.tex
				├── jtetiskripsi.cls
				└── template-skripsi.tex

### sections/bab1.tex - bab5.tex
Konten utama dari skripsi, mulai dari BAB I (pendahuluan) sampe BAB V (kesimpulan). Silakan disesuaikan dengan jumlah bab skripsi anda, hapus file yang tidak perlu atau tambahkan file baru untuk bab baru.

### bibtex/daftar-pustaka.bib
File yang berisi daftar referensi-referensi yang anda gunakan dalam skripsi. File ini penting guna menyusun daftar pustaka anda. Dengan file ini menyusun daftar pustaka menjadi sangat sangat sangat mudah.

File ini adalah hasil export dari aplikasi *reference management* seperti Mendeley, Zotero, EndNote, dll. Biasakan mengorganisir referensi skripsi anda menggunakan aplikasi *reference management*.

### template-skripsi.tex
File ini template-skripsi.tex adalah file utama (kepala) dari template. Berisi informasi-informasi dasar, seperti judul skripsi, nama penulis, nama pembimbing, dll.

### template-skripsi.pdf (muncul setelah template-skripsi.tex dicompile)
File ini adalah skripsi anda dalam bentuk matang. Sudah rapi dan dapat dicetak untuk dijilid. File ini di-*generate* secara otomatis menggunakan LaTeX.

### jtetiskripsi.cls
File yang berisi aturan-aturan format skripsi. Contoh, format cover, halaman pengesahan, daftar isi, daftar pustaka, dan konten skripsi.

Jika anda ingin memodifikasi template skripsi ini, ubahlah file *jtetiskripsi.cls*.

### images/
Masukkan gambar-gambar pada skripsi anda di folder ini. Gambar default: logougm.png (dipakai di cover) dan wsn.png (hanya dipakai di template awal, silakan dihapus jika tidak diperlukan).

Lisensi
-------
Template sripsi ini dilisensikan dengan menggunakan [lisensi MIT](https://github.com/yasirroni/template-thesis/blob/master/LICENSE), melanjutkan [lisensi sebelumnya](https://github.com/gtrdp/template-skripsi/master/LICENSE).

Silahkan buat sublisensi dengan [No License](https://choosealicense.com/no-permission/) jika dirasa orang lain tidak boleh menyalin, mendistribusikan, dan mengedit thesis anda yang ditulis menggunakan projek ini. Adapaun menghapus lisensi MIT pada dasarnya adalah tindakan ilegal, namun penambahan sublisensi pada lisensi MIT adalah legal, sebagaimana penjelasan di [sini](https://softwareengineering.stackexchange.com/a/386584). Adapun hasil compile dari program ini (file `.pdf`) tidak terikat dengan lisensi ini. Untuk mempelajari lebih lanjut tentang sublisensi, silahkan baca sumber [stackexchange](https://softwareengineering.stackexchange.com/questions/279171/can-the-author-of-an-mit-licensed-project-convert-it-to-a-commercial-licensed-on). Untuk memilih sublisensi lainnya, silahkan melihat [https://choosealicense.com/](https://choosealicense.com/)