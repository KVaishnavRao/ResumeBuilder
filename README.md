# 📄 Resume Builder (HTMLPro)

A web-based **Resume Builder Application** built using **PHP, MySQL, HTML, CSS, and JavaScript**.  
This project allows users to easily **create, manage, and download resumes** with customizable templates.

---

## 🚀 Features
- 🔑 **User Authentication** – Register, login, email verification, password reset.  
- 📝 **Resume Creation** – Add personal info, education, experience, skills.  
- 🎨 **Customization** – Change fonts, backgrounds, and styles.  
- 📂 **Resume Management** – Create multiple resumes, update, clone, or delete.  
- 💾 **Database Integration** – Stores user profiles and resumes in MySQL.  

---

## 🗂️ Project Structure
- `index.php` → Homepage / Login page  
- `register.php` → User registration  
- `login.php` → User login  
- `createresume.php` → Resume builder interface  
- `myresumes.php` → Manage saved resumes  
- `resume.php` → View/Download resume  
- `database.sql` → Database schema for MySQL  
- `actions/` → Handles backend logic (add skills, update profile, etc.)  

---

## ⚙️ Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL  
- **Server**: XAMPP / WAMP / LAMP  

---

## 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/htmlpro.git
   ```
2. Move project files to your server directory (e.g., `htdocs` in XAMPP).  
3. Import the `database.sql` file into MySQL using phpMyAdmin.  
4. Update database credentials in config file (if exists).  
5. Start Apache & MySQL from XAMPP/WAMP.  
6. Open in browser:  
   ```
   http://localhost/htmlpro
   ```

---

## 📌 Use Cases
- Students creating resumes for job applications.  
- Job seekers managing multiple resume versions.  
- Colleges offering resume-building tools for placement.  
