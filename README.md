# LATIHAN5DPBO2023

## *Janji*
Saya Mohammad Labib Husain NIM 2101989 mengerjakan Latihan 5 dalam mata kuliah Desain Pemrograman Berbasis Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.
## *Soal*
Download this starter project: https://drive.google.com/file/d/1TEnEay74nhGcSS9PPzQcxksIlaQhTiZ2/view?usp=sharing 
* Add more property (component type: any, except text field)
* Add method to reset form
* Refresh table after update and delete
* Add confirmation prompt before delete
* Build project (generate .jar file)
## *Desain Program*
Program teridiri dari 2 kelas :
1. class Mahasiswa

  Kelas ini adalah kelas untuk membuat objek mahasiswa. Berisikan 5 atirbut ,yaitu nim (string),nama(string),nilai(string),angkatan(string) dan gender(string).Terdapat setter dan getter untuk masing-masing atribut.

2. class Menu
  
  Kelas ini berisi method-method untuk menampilkan tampilan program.Terdapat beberapa method:
  * SetTable -> method untuk membuat table
  * insertData -> method untuk menambahkan data pada tabel
  * updateData > method untuk mengubah data yang ada pada tabel
  * deleteData -> method untuk menghapus data dari tabel
  * resetForm -> method untuk mengembalikan tampilan menjadi seperti semula
  * dll.
## *Desain GUI*
![design](https://user-images.githubusercontent.com/119772365/226432274-63c1999d-d594-43b9-ad70-6f3d49061ac8.png)

  #### Penjelasan :
  Untuk judul "Daftar Mahasiswa" menggunakan swing controls label.Untuk "nim","nama","nilai", "angkatan",dan "gender" juga menggunakan swing controls label.Pada masing-masing kolom text menggunakan swing controls textfield.Pada tombol "add" ,"cancel" dll itu menggunakan swing controls button.Terdapat juga dropdown menu angkatan pada program menggunakan swing controls combo box.Untuk mengisi atau menambahkan elemen pada combo box,bisa melalui properties pada item,lalu isi elemen yang diinginkan dengan mengatur atau mengubah kolom model.Selanjutnya untuk pemilihan gender itu menggunakan swing controls radio button.Ada sedikit pengaturan tambahan agar dapat memilih salah satu diantara beberapa radio button yang dimasukkan ke dalam design.Yaitu dengan menambahkan swing controls button grup ,lalu klik salah satu dari radio button yang ingin dimasukkan,kemudian ke properties radio buttonnya,lalu ubah kolom button group yang ada pada properties radio button menjadi nama button group yang telah dibuat.Lakukan hal yang sama untuk radio button berikutnya.Kemudian untuk menu yang terakhir ada tabel,menu tersebut menggunakan swing controls table. 
## *Hasil*
![Result](https://user-images.githubusercontent.com/119772365/226434852-5d372ade-eab8-4368-b2b6-8f8ee4eb2497.png)

## *Alur*
* Tampilan awal program :

![Result](https://user-images.githubusercontent.com/119772365/226442020-6010fa82-399e-46c4-ac11-eddd81fc9945.png)
* Add Data

User bisa mengisi kolom nim,nama dan nilai serta memilih beberapa pilihan pada angkatan dan gender,contoh :

 ![Screenshot 2023-03-21 021206](https://user-images.githubusercontent.com/119772365/226442526-b347be34-f94b-4222-a056-087929c612d5.png)
 
lalu klik add,maka program akan menambahkan baris table yang berisikan inputan dari user :

![Screenshot 2023-03-21 021644](https://user-images.githubusercontent.com/119772365/226443233-839241fb-d4f5-41d8-ac52-b189c7a8586c.png)

dan semua kolom inputan akan kembali ke tampilan awal (reset).
* Update Data

User bisa mengklik atau memilih baris yang akan diubah pada tabel

![Screenshot 2023-03-21 022035](https://user-images.githubusercontent.com/119772365/226444128-489acdee-70e0-4822-b94c-34aa71c1ce58.png)

isi kembali data yang ingin diubah,lalu klik update.Maka tampilan pada tabel akan kembali berubah.

![Screenshot 2023-03-21 022142](https://user-images.githubusercontent.com/119772365/226444420-04b02725-d75a-47cc-b0fb-7bcec3aed1a7.png)

* Delete Data

Klik baris yang akan diubah (sama seperti update),lalu klik tombol delete.Maka program akan memberikan sebuah konfirmasi apakah data jadi dihapus atau tidak.
 
 ![Screenshot 2023-03-21 022436](https://user-images.githubusercontent.com/119772365/226444965-fc021238-195b-44a5-85e4-fcc17f88f1ba.png)
 
klik yes untuk menghapus data.Maka program akan menghapus baris objek yang telah dipilih.

![Screenshot 2023-03-21 022559](https://user-images.githubusercontent.com/119772365/226445274-571a54b6-d937-4ab0-abeb-78f5595ccffd.png)

Sekian,Terima kasih .
