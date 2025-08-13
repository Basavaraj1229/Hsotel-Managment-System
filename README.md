Hi, 🙋‍♂️ This Basavaraj Kokane

# 🏨 Hostel Management System

A web-based application designed to manage hostel operations such as room booking, student registration, complaints, feedback, and admin control.  
Built with **PHP**, **MySQL**, **HTML/CSS**, and **JavaScript**.

---

## 📌 Features

### Student Module
- User registration and login
- View and book hostel rooms
- Check availability of rooms
- Submit complaints and feedback
- Update personal profile
- View complaint status

### Admin Module
- Manage student records
- Approve or reject room bookings
- View and respond to complaints
- Maintain hostel room details
- Access logs for monitoring

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Apache (XAMPP/WAMP/MAMP)

---

## 📂 Project Structure
```
Hostel-Management-System/
│
├── hostel/               # Main application files
│   ├── *.php              # PHP scripts for various modules
│   ├── hostel.css         # Stylesheet
│
├── admin/                # Admin-specific scripts
├── database/             # Database dump (SQL file)
└── readme.txt            # Original project notes
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/hostel-management-system.git
   ```

2. **Move to server directory**:
   - For XAMPP: Move project folder to `htdocs`
   - For WAMP: Move to `www`

3. **Import the database**:
   - Open **phpMyAdmin**
   - Create a new database (e.g., `hostel`)
   - Import the provided `.sql` file from the `database` folder

4. **Configure database connection**:
   - Open `includes/config.php` (or similar)  
   - Set your DB host, username, password, and database name

5. **Run the project**:
   - Start Apache and MySQL in XAMPP/WAMP
   - Visit:  
     - **User Panel:** `http://localhost/hostel/`
     - **Admin Panel:** `http://localhost/hostel/admin/`

---

## 🔑 Default Credentials

**Admin Login**  
- Username: `admin`  
- Password: `admin123`

**Student Login**  
- Create a new account via the registration page.

---

## 📸 Screenshots
*(Add screenshots of login, dashboard, booking pages here)*

---

## 📜 License
This project is for educational purposes. Modify and use as needed.

---

## 👨‍💻 Author
Developed by **[Basavaraj]**
