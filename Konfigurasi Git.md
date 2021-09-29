# Konfigurasi Git

Secara minimal, user harus memberitahu Git tentang username serta email yang digunakan setiap kali terjadi perubahan pada repo Git. Username serta email ini yang akan dimasukkan oleh Git ke catatan perubahan di repo.sistem operasi Windows, konfigurasi ini akan disimpan di *C:\Document and Settings\NamaUser dengan nama file .gitconfig.* 
Secara minimal, ada 2 hal yang perlu dikonfigurasi yaitu username dan email. 

Gunakan perintah berikut:
```
  $ git config --global user.name *"Nama Anda di GitHub"*

  $ git config --global user.email *email*
```
Atas untuk mengisi *username* Bawah untuk mengisi *email*

*username* dan *email* harus sama seperti di github.

![image](https://user-images.githubusercontent.com/91442260/135112067-f67f4589-b082-429d-92dd-b569ede15f19.png)

Dan untuk melihat apakah sudah terisi atau belum dengan: 
```
$ git config --list
```
![image](https://user-images.githubusercontent.com/91442260/135113220-1e286ac2-d6d9-4af9-bee6-0346faeef519.png)

Lakukan sekali saja! kecuali jika ingin menggantinya.

