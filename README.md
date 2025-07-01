# Mobile Legends Hero List Web App
by Anisa Fitriyani (NIM: SSI202303557)

![Mobile Legends Logo](https://static.wikia.nocookie.net/mobile-legends/images/4/4e/Mobile_Legends_Bang_Bang_Logo.png/revision/latest?cb=20210831080814)

## 📌 Deskripsi Proyek
Aplikasi web ini menampilkan daftar hero Mobile Legends dengan fitur *CRUD (Create, Read, Update, Delete)*. Dibangun menggunakan:  
- *IntelliJ IDEA* (IDE Pengembangan)  
- *Java + Spring Boot* (Backend)  
- *MySQL Workbench* (Database)  
- *Thymeleaf/HTML/CSS/JS* (Frontend)  

*Fitur:*  
✔ Menampilkan daftar hero MLBB  
✔ Menambah hero baru  
✔ Mengedit informasi hero  
✔ Menghapus hero  
✔ Pencarian & filter hero  

## 🛠 Teknologi yang Digunakan
| Komponen        | Teknologi               |
|-----------------|-------------------------|
| *Backend*     | Java, Spring Boot       |
| *Frontend*    | Thymeleaf, Bootstrap    |
| *Database*    | MySQL                   |
| *Tools*       | IntelliJ IDEA, MySQL Workbench, Git |

## 📋 Struktur Database
Tabel heroes:
```sql
CREATE TABLE heroes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    role VARCHAR(50) NOT NULL,
    lane VARCHAR(50),
    difficulty VARCHAR(50),
    release_year INT
);
