# Discussion Board 💬

A full-stack web application built using **PHP**, **MySQL**, **HTML**, **CSS**, and **Bootstrap** that allows users to post, answer, and engage in community-driven discussions.

---

## 🌟 Features

- ✅ User Registration and Login
- 📝 Post Questions to the Community
- 💬 Answer Existing Questions
- 👍 Like / Upvote Answers
- 🔍 Display Related Questions
- 📁 Organized Project Structure
- 💾 MySQL Database Integration
- 🎨 Responsive UI using Bootstrap

---

## 🚀 Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 4
- **Backend:** PHP (Core PHP)
- **Database:** MySQL
- **Other Tools:** XAMPP / WAMP / LAMP (for local server)

---

## 🛠️ Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/anil-sidhu/php-project-discuss.git
   ```

2. **Move to Server Directory**
   - Copy the project folder to your `htdocs` (XAMPP) or `www` (WAMP) directory.

3. **Import Database**
   - Open **phpMyAdmin** and create a database (e.g., `discussion_board`).
   - Import the provided `.sql` file from the `database` folder.

4. **Update DB Configuration**
   - Open `db_connect.php` (or similar file) and update the DB credentials if needed:
     ```php
     $conn = new mysqli("localhost", "root", "", "discussion_board");
     ```

5. **Run the Application**
   - Start Apache and MySQL from XAMPP/WAMP.
   - Visit `http://localhost/php-project-discuss` in your browser.

---

## 📂 Folder Structure

```
php-project-discuss/
├── css/
├── js/
├── includes/
├── pages/
├── db_connect.php
├── index.php
└── README.md
```

---

## ✍️ Author

- **Anil Sidhu**  
  GitHub: [@anil-sidhu](https://github.com/anil-sidhu)

---

## 📄 License

This project is for educational purposes and open for contributions, improvements, or customization.
