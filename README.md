#  Studi Kasus: ERD Karyawan
- Tabel karyawan memiliki relasi many-to-one dengan tabel departemen, dimana setiap karyawan terhubung ke satu departemen dan setiap departemen dapat memiliki banyak karyawan. Selain itu, tabel karyawan juga memiliki relasi many-to-one dengan tabel karyawan (alias manager), dimana setiap karyawan dapat memiliki satu manajer dan setiap manajer juga merupakan karyawan. Tabel project memiliki relasi many-to-one dengan tabel departemen, dimana setiap proyek terhubung ke satu departemen dan setiap departemen dapat memiliki banyak proyek. Selain itu, terdapat tabel many-to-many karyawan project yang menghubungkan karyawan dengan proyek yang sedang dikerjakan atau pernah dikerjakan. Terakhir, tabel supervisor memiliki relasi many-to-one dengan tabel departemen dan tabel karyawan, dimana setiap supervisor terhubung ke satu departemen dan satu karyawan yang diawasinya
