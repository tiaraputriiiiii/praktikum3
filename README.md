Nama    : Tiara Putri
NIM     : 312210064
Kelas   : TI.22.A1

# Cara Installasi Pycharm
Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows  , Dan anda pilih yang Community

![2022-10-31 (2)](https://user-images.githubusercontent.com/115775237/198932831-83182560-3117-4469-8e45-924b8cd7887d.png)

next saja semua perintahnya 

![2022-10-31 (3)](https://user-images.githubusercontent.com/115775237/198933464-45381f87-f77d-4ace-bc48-0bef2d8e66a0.png)

tunggu hingga selesai

![2022-10-31 (4)](https://user-images.githubusercontent.com/115775237/198933506-e6659704-6c9f-48ea-bdc9-5b44ceadc8a3.png)

Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm 
# Latihan 1

Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini

![2022-10-31 (5)](https://user-images.githubusercontent.com/115775237/198933905-c2ae0ccd-7314-4c31-b29d-65ba89f636d8.png)

![2022-10-31 (7)](https://user-images.githubusercontent.com/115775237/198934143-2f924b1e-5ea6-45de-8951-85f8e477f672.png)

Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

![2022-10-31 (8)](https://user-images.githubusercontent.com/115775237/198934387-0fe36386-208d-4ef2-a31d-075c791a91f7.png)

masukan code dari latihan1 anda lalu Run

	# penggunaan end

	print('A', end='')
	print('B', end='')
	print('C', end='')
	print()
	print('X')
	print('Y')
	print('Z')

	# penggunaan separator
	w, x, y, z = 10, 15, 20, 25
	print(w, x, y, z)
	print(w, x, y, z, sep=',')
	print(w, x, y, z, sep='')
	print(w, x, y, z, sep=':')
	print(w, x, y, z, sep='-----')

	# string format
	print(0, 10 ** 0)
	print(1, 10 ** 1)
	print(2, 10 ** 2)
	print(3, 10 ** 3)
	print(4, 10 ** 4)
	print(5, 10 ** 5)
	print(6, 10 ** 6)
	print(7, 10 ** 7)
	print(8, 10 ** 8)
	print(9, 10 ** 9)
	print(10, 10 ** 10)

	# string format
	print('{0:>3} {1:>16}'.format(0, 10 ** 0))
	print('{0:>3} {1:>16}'.format(1, 10 ** 1))
	print('{0:>3} {1:>16}'.format(2, 10 ** 2))
	print('{0:>3} {1:>16}'.format(3, 10 ** 3))
	print('{0:>3} {1:>16}'.format(4, 10 ** 4))
	print('{0:>3} {1:>16}'.format(5, 10 ** 5))
	print('{0:>3} {1:>16}'.format(6, 10 ** 6))
	print('{0:>3} {1:>16}'.format(7, 10 ** 7))
	print('{0:>3} {1:>16}'.format(8, 10 ** 8))
	print('{0:>3} {1:>16}'.format(9, 10 ** 9))
	print('{0:>3} {1:>16}'.format(10, 10 ** 10))

![2022-10-31 (10)](https://user-images.githubusercontent.com/115775237/198934894-9eadb8fb-bf4b-47cd-bfac-a1027f06ac3c.png)
![2022-10-31 (11)](https://user-images.githubusercontent.com/115775237/198934948-5ad82e04-afc7-4470-8a03-4f2d885a9305.png)

lalu hasil run nya

![2022-10-31 (13)](https://user-images.githubusercontent.com/115775237/198935226-cad7e53c-cd33-4516-878c-8c2be9dce648.png)

# Latihan 2 
buat latihan baru "latihan2"

lalu masukkan code program

	a=input("masukkan nilai a:")
	b=input("masukkan nilai b:")
	print("variabel a=",a)
	print("variabel b=",b)
	print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

	#konversi nilai variabel
	a=int(a)
	b=int(b)
	print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
	print("hasil penjumlahan {1}/{0}=%s".format(a,b) %(a/b))

![2022-10-31 (14)](https://user-images.githubusercontent.com/115775237/198935539-aa9e1779-1e2a-49c7-aafe-a2a9df4a4fa3.png)

lalu hasil run nya menjadi

![2022-10-31 (15)](https://user-images.githubusercontent.com/115775237/198935716-5385feda-0640-41f4-9d2f-81cca1875b91.png)

# Latihan 3
buat file baru "latihan3"

![2022-10-31 (16)](https://user-images.githubusercontent.com/115775237/198935852-a75da9bf-dfb4-495d-a952-10d7fe51b41d.png)

masukkan code programnya

	string = ""

	x = int(input("Masukkan angka :"))
	bar = x
	# Looping Baris
	while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1

	string = string + "\n\n"
	bar = bar - 1

	bar = 1
	# Looping Baris
	while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
	print (string)

![2022-10-31 (17)](https://user-images.githubusercontent.com/115775237/198936187-68ac9e99-41a0-47f4-b13c-73aeab015353.png)

![2022-10-31 (18)](https://user-images.githubusercontent.com/115775237/198936210-438e0ecf-327f-45b0-a7c6-8be9c9d609a7.png)

*Hasil Run*

![2022-10-31 (19)](https://user-images.githubusercontent.com/115775237/198936591-1d85e5e0-bfab-4b30-abfd-ab3a8cffd542.png)

# Menghitung Luas Dan Keliling Lingkaran
buat file baru "praktikum3"

	print('menghitung luas dan keliling lingkarang')
	print('________________________________________')

	r=float(input('masukkan nilai jari - jari :'))

	phi=3.14
	diameter=2*r

	print('\nluasnya =', str("%.2f" % luas))
	print('kelilingnya =', str("%.2f" % keliling))

![2022-10-31 (20)](https://user-images.githubusercontent.com/115775237/198937031-381eab4c-c619-48e3-b6b1-2b26d58ea5d9.png)

*Hasil Run*

![2022-10-31 (21)](https://user-images.githubusercontent.com/115775237/198937108-6674b88a-4277-4f76-8802-52dbf5a07503.png)

# Flowchart Menghitung luas dan keliling lingkaran

![2022-10-31 (22)](https://user-images.githubusercontent.com/115775237/199132888-b964fb68-df4c-4b40-a824-8365a2337d9c.png)

