# Tugas1-ADJ
ugas1 ADJ - membuat web static dan mengaplikasikan kedocker container

Nama	: Nanda Amelia

Nim	: 191402015

Langkah – langkah membuat website static dan mengaplikasikan Docker
1.	Membuat website, disini saya membuat website biodata yang berisikan data diri saya dan juga sedikit penjelasan tentang docker
Saya menggunakan html , css dan bootsrap

![Screenshot (322)](https://user-images.githubusercontent.com/66839985/133056195-9a174201-f318-4c3a-a026-8dcca98f975f.png)

2.	Install docker, disini saya menggunakan docker windows
Untuk menggunkan docker windows ini didampingi dengan WSL 2 
Docker Windows : https://docs.docker.com/desktop/windows/install/

![docker](https://user-images.githubusercontent.com/66839985/133056157-b328a452-513e-4d83-8ba0-dd520b321b74.png)

Install WSL2 : https://docs.microsoft.com/id-id/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package

![wsl2](https://user-images.githubusercontent.com/66839985/132997067-80315de5-6009-496a-a189-4e104ed92a1b.png)

Sign in ke docker, jika belum memiliki akun bisa membuat nya di https://hub.docker.com/
![login](https://user-images.githubusercontent.com/66839985/132997060-a08e2255-8c37-49ba-8361-a92eff82d9b6.png)

•	Tampilan sebelum didocker container

![ts1](https://user-images.githubusercontent.com/66839985/132997064-6df34637-7dbd-484d-a328-a185fe2d1048.png)
![ts2](https://user-images.githubusercontent.com/66839985/132997065-298891ab-3b2a-4845-9809-1dc802fe0bc2.png)

3.	Buat file yang bernama “Dockerfile” di visual studio code 
Kemudian isi seperti gambar dibawah ini

![3](https://user-images.githubusercontent.com/66839985/132997005-936c06b3-76ef-4d99-b8f0-055ef6776d1e.png)

4.	Jalan kan perintah berikut untuk 

![4](https://user-images.githubusercontent.com/66839985/132997007-bb64fb9a-bff9-4841-bef3-5aab7e7e88cc.png)

5. Login keakun github kemudian buat repository baru

![5](https://user-images.githubusercontent.com/66839985/132997009-f4249db8-c5c9-4e6e-a2a2-0ed6a69d24d5.png)

6.	Setelah membuat repository baru langkah selanjutnya yaitu membuat token
Buka setting kemudian klik Developer setting – personal accses tokens seperti gambar dibawah ini

![6 1](https://user-images.githubusercontent.com/66839985/132997011-2d433756-a2dd-4325-886b-be61dddd94a1.png)
![6 2](https://user-images.githubusercontent.com/66839985/132997014-2a1f328a-3a12-44e6-abd7-68f5647455c9.png)
![6 3](https://user-images.githubusercontent.com/66839985/132997015-76a72406-6efa-4872-807f-39b67a45bc3d.png)
![6 4](https://user-images.githubusercontent.com/66839985/132997017-60f22460-13b2-4c4d-ac4e-be72182dca52.png)

7.	Buka kembali terminal di vscode kemudian masukan perintah seperti gambar berikut
Untuk password nya paste kan personal tokens yang telah dicopy pada github.

Tambahkan juga comman didalam Dockerfile dan link repository github yang telah dibuat

![7](https://user-images.githubusercontent.com/66839985/132997018-09d3b170-e922-454c-a1a1-8525ea4c5046.png)

8.	Setelah login berhasil masukan perintah berikut untuk membuat v2

![8](https://user-images.githubusercontent.com/66839985/132997020-7f0ff127-cad2-44af-9b40-58877a403704.png)

9.	Pada gambar berikut ini tertulis docker tag dan memasukkan kode v2

![9 2](https://user-images.githubusercontent.com/66839985/132997026-a28a9ebd-a6ca-4421-837d-daf5435f58c1.png)

Kemudian isi dengan command seperti gambar dibawah

![9 2](https://user-images.githubusercontent.com/66839985/132997026-a28a9ebd-a6ca-4421-837d-daf5435f58c1.png)

Tampilan images didocker setelah mambuat v1 dan v2

![9 3](https://user-images.githubusercontent.com/66839985/132997028-03275fe0-6f62-4541-ba20-a765044cdd06.png)

10.	Membuat packeges pirivat yang telah dibuat ke public
Packeges-setting

![10](https://user-images.githubusercontent.com/66839985/132997032-59fbce4a-473d-4354-9f08-358b555e0994.png)

11.	Menjalankan container yang telah dibuat

![11](https://user-images.githubusercontent.com/66839985/132997034-05154f7e-3fdd-4c72-9c1e-f40092f17889.png)

12.	Melihat tampilan web untuk memastikan server berjalan
localhost:80
•	Tampilan ketika server berhasil berjalan

![12 1](https://user-images.githubusercontent.com/66839985/132997035-34303bfa-76e0-4aba-9525-5767c8141735.png)
![12 2](https://user-images.githubusercontent.com/66839985/132997037-40d928b1-c42e-4c1c-a887-7bc682097049.png)
![12 3](https://user-images.githubusercontent.com/66839985/132997039-8047fe30-7917-489c-a3c7-0fed698e02df.png)
![12 4](https://user-images.githubusercontent.com/66839985/132997044-1d6628c3-d265-4f5e-a9de-f2836dc81956.png)

