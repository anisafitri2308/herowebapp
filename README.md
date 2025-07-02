# Mobile Legends Hero List Web App
by Anisa Fitriyani (NIM: SSI202303557)

## 📌 Deskripsi Proyek
Aplikasi web ini menampilkan daftar hero Mobile Legends dengan fitur *CRUD (Create, Read, Update, Delete)*. Dibangun menggunakan:  
- *IntelliJ IDEA* (IDE Pengembangan)  
- *Java* Language  
- *MySQL Workbench* (Database)  
- *Thymeleaf/HTML/CSS/JS* (Frontend)  

*Fitur:*  
✔ Menampilkan daftar hero MLBB  
✔ Menambah hero baru  
✔ Mengedit informasi hero  
✔ Menghapus hero    

## 🛠 Teknologi yang Digunakan
| Komponen        | Teknologi               |
|-----------------|-------------------------|
| *Backend*     | Java                      |
| *Database*    | MySQL                     |
| *Tools*       | IntelliJ IDEA, MySQL Workbench, Git |

## 📋 Struktur Database
Tabel heroes:
```sql
CREATE DATABASE tm_hero;

USE tm_hero;

CREATE TABLE hero (
    id_hero INT AUTO_INCREMENT PRIMARY KEY,
    nama_hero VARCHAR(100) NOT NULL,
    kategori ENUM('MAGE', 'ASSASIN', 'FIGHTER', 'TANK', 'MARKSMAN', 'SUPPORT') NOT NULL,
    gender ENUM('MALE', 'FEMALE') NOT NULL
);
