
Latar Belakang Masalah
Sistem Informasi Geografis adalah suatu sistem basis data dengan kemampuan khusus untuk menangani data spatial, data geografis yaitu data yang mengacu pada lokasi geografis dan juga bisa diartikan sebagai sistem informasi yang didesain untuk bekerja dengan data yang berkaitan dengan aspek spatial dimuka bumi ini.

Rumusan Masalah
1.	Bagaimana cara create shapefile?
2.	Bagaimana cara edit shapefile?
3.	Bagaimana cara hapus shapefile?
4.	Bagaimana cara menampilkan shapefile?
Pembahasan
Cara membuat data geometri shapefile adalah sebagai berikut:
	--Buka python di command prompt
	--import shapefile
	--sf = shapefile.Writer(shapeType=1)
	--sf.shapeType -> untuk mengecek
	--sf.field('NAMA','C','40')
	--sf.field('PEMILIK','C','40')
	--sf.record('WARTEG','Jajang Kusendar')
	--sf.point(10,10,0,0) -> disini point bisa diganti line atau polygon sesuai keinginan
	--sf.save('warteg.shp') -> untuk menyimpan

Cara Mengedit data geometri shapefile adalah sebagai berikut:
	--Buka python di command prompt
	--import shapefile
	--sf = shapefile.Editor(shapefile='warteg.shp')
	--sf.point(19,19,0,0)
	--sf.record('Warung Padang','Ucok')
	--sf.save('warteg')

Cara menghapus data geometri shapefile adalah sebagai berikut:
	--Buka python di command prompt
	--import shapefile
	--e = shapefile.Editor('warteg.shp')
	--e.shape(1) -> record ke berapa
	--e.delete(1)
	--e.save('warteg')

Cara menampilkan data geometri shapefile adalah sebagai berikut:
	--Buka python di command prompt
	--import shapefile
	--sf = shapefile.Reader('warteg.shp')
	--sf.record() -> semua record
	--sf.record(0) -> record ke 1
	--sf.record(1) -> record ke 2
	--sf.shapes()(0).points -> menampilkan
Penutup
Kesimpulan
Kesimpulan Dari pembahasan diatas dapat disimpulkan dalam data geometri shapefile dapat melakukan penambahan , pengeditan, penghapusan dan penampilan data geometri shapefile dengan mudah menggunakan python.
Saran
Saran saya agar sebaiknya lebih dipahami lagi tentang pembahasan mengenai sistem informasi geografis terlebih pada esri shapefile tersebut dikarenakan mudah dan menggunakan bahasa pemomrograman pyhton.
Link Github :

Nama : MUH AKBAR TAMRIN
Npm : 1144012
Kelas : D4 Teknik Informatika 3C
Matakuliah : Sistem Informasi Geografis

Link Matakuliah :

Referensi :

Scan Plagiarisme :
