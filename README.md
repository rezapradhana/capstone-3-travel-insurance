Problem Statement :
Perusahaan ingin mengetahui customer mana saja yang akan mengajukan klaim asuransi untuk pertanggungan

Data Cleansing
Secara umum, kita bisa melihat bahwa: *Dataset Travel Insurance memiliki 11 kolom dan 4.4328 Baris. *Hapus Kolom Gender yang tidak terpakai. *Pembuatan Kelompok Group Age *Pembuatan Kelompok Duration *Pembersihan kolom Net Sales

Data Preparation
Merubah fitur/kolom Agency menggunakan Binary Encoding.
Merubah fitur/kolom Agency Type menggunakan One Hot Encoding.
Merubah fitur/kolom Distribution Channel menggunakan One Hot Encoding.
Merubah fitur/kolom Product Name menggunakan Binary Encoding.
Merubah fitur/kolom Destination menggunakan Binary Encoding.
Merubah fitur/kolom Group_Age menjadi integer 0-4 dengan Ordinal Encoding.
Merubah fitur/kolom Group_Duration menjadi integer 0-4 dengan Ordinal Encoding.
