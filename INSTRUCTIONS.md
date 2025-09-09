# ⚙️ Setup & Run Instructions – Laptop E-Shop

Follow these steps to set up and run the project on your local machine:

---

## 1. Prerequisites
- Install **XAMPP** (or WAMP/LAMP depending on OS).  
  - [Download XAMPP](https://www.apachefriends.org/index.html)  

---

## 2. Project Setup
1. Copy the `shopping` folder into your web server root:
   - For **XAMPP** → `C:/xampp/htdocs/`  
   - For **WAMP** → `C:/wamp/www/`  
   - For **LAMP** → `/var/www/html/`

2. Open [phpMyAdmin](http://localhost/phpmyadmin).  
3. Create a database named:
   ```
   shopping
   ```
4. Import the provided SQL file:
   ```
   /SQL/shopping.sql
   ```
   (Path may differ if included in another folder like `db/`.)

---

## 3. Run the Project
- **Frontend (User Portal):**  
  👉 [http://localhost/shopping](http://localhost/shopping)  

- **Admin Panel:**  
  👉 [http://localhost/shopping/admin](http://localhost/shopping/admin)  

---

## 4. Default Login Details
- **Admin:** (Provide default credentials if available)  
- **User:** Register directly from the website.  

---

## 5. Notes
- Ensure **Apache** and **MySQL** are running in XAMPP/WAMP.  
- You may update database credentials in `config.php` (or similar) if required.  
- Upload folders can be cleaned before committing to GitHub; keep only sample images.  
