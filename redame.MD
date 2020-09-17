Database

- data_buku
- data_peminjaman
- data_anggota
- data_petugas


field table
- data_buku
	- id
	- judul
	- isbn
	- penerbit
	- penulis
	- tahun_terbit

- data_peminjaman
	- id
	- tanggal_pinjam
	- tanggal_kembali
	- id_anggota
	- id_buku
	- jlh_pinjam
	- id_petugas
	- status_pinjam

- data_anggota
	- id
	- nama
	- alamat
	- tgl_lahir

- data_petugas
	- id
	- nama
	- alamat
	- tgl_lahir
	- group
