# To-Do List Application

Aplikasi yang umumnya digunakan untuk mengelola tugas sehari-hari user atau membuat daftar semua yang harus user lakukan, dengan tugas paling penting di daftar teratas, dan tugas paling tidak penting di bagian bawah. Aplikasi ini membantu dalam merencanakan jadwal harian user. Jika tugas sudah selesai maka akan hilang dari list.

## Development Env
JavaFX - MySQL - IntelliJ IDEA

## Database Structure

Database project ini dibuat dengan sifat Relational Database untuk menjaga data integrity, sehingga dari dua database yang dibuat yaitu user dan task database, nantinya akan saling terhubung. Hal itu dikarenakan adanya Foreign Key (FK) pada userid table, yang mana data userid pada user database akan sama dengan data userid pada task database.       

### 1. User Database
Berikut adalah contoh data yang akan muncul dari input user di dalam page user MySQL:

| userid | nama depan | nama belakang | password | lokasi | jenis kelamin |
| :---: | :---: | :---: | :---: | :---: | :---: | 
| 1 | Rafli | Hadiana | 290tugas | Bandung | Laki-Laki | 
| 2 | Naufal | Rizieq | 245java | Bekasi | Laki-Laki | 
| 3 | Sofvi | Aprillani | 264besar | Bogot | Perempuan | 

### 2. Task Database
Berikut adalah contoh data yang akan muncul dari input user di dalam page task MySQL:

| taskid | userid | tanggal & waktu | deskripsi | task |
| :---: | :---: | :---: | :---: | :---: | 
| 1 | 2 | 2022-12-17 09:21:27 | bersama teman | mengerjakan tugas |
| 2 | 2 | 2022-12-18 11:25:21 | di kantin cowo | beli makan | 
| 1 | 3 | 2022-12-18 10:30:05 | harga 20k | beli baju | 289 | 

## Fitur Aplikasi
Aplikasi ini akan memiliki beberapa sistem, yaitu:
1. Page Log in
<img src="https://github.com/raflihadiana/java-project/blob/main/app-ui/Login%20Page.png" width="350" height="200" /> 

2. Page Sign Up
<img src="https://github.com/raflihadiana/java-project/blob/main/app-ui/SignUp%20Page.png" width="350" height="200" />

3. Page Add New Task
<img src="https://github.com/raflihadiana/java-project/blob/main/app-ui/Add%20Task.png" width="350" height="200" />

4. Page Add, Edit, Delete, dan Sorting Task
<img src="https://github.com/raflihadiana/java-project/blob/main/app-ui/Edit%20Task.png" width="350" height="200" />

