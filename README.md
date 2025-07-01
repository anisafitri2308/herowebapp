# Mobile Legends Hero List Web App
by Anisa Fitriyani (NIM: SSI202303557)

![Mobile Legends Logo]([https://static.wikia.nocookie.net/mobile-legends/images/4/4e/Mobile_Legends_Bang_Bang_Logo.png/revision/latest?cb=20210831080814](https://wallpaperaccess.com/full/4597740.png))

## 📌 Deskripsi Proyek
Aplikasi web ini menampilkan daftar hero Mobile Legends dengan fitur *CRUD (Create, Read, Update, Delete)*. Dibangun menggunakan:  
- *IntelliJ IDEA* (IDE Pengembangan)  
- *Java* (Backend)  
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
| *Frontend*    | Thymeleaf                 |
| *Database*    | MySQL                     |
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
