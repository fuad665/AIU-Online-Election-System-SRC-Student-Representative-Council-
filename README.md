

---

## 📌 Overview

**VoteSphere** is an online voting platform built to facilitate transparent and secure elections for the **Student Representative Council (SRC)** at Albukhary International University (AIU). The system enables students to vote electronically using their student IDs, eliminating the need for traditional paper ballots and ensuring real-time vote counting and integrity.

---

## 🎯 Objectives

- Allow students to vote online using a secure login.
- Prevent duplicate voting using session tracking.
- Enable admins to manage candidates, control voting windows, and view results.
- Display real-time results after polls close.
- Create a user-friendly and responsive platform for voters and admins.

---

## 🔧 Features

### 🔐 Admin Panel
- Login with secure credentials.
- Add/edit/delete candidates.
- Open/close voting session.
- Monitor votes and participation.
- Export results as reports.

### 🧑‍🎓 Student Panel
- Login using student ID and password.
- View list of candidates per position.
- Cast vote once per position.
- Get confirmation of successful vote.
- View results after the election ends.

---

## 🗂️ Project Structure

```

/aiu-vote-sphere/
│
├── /admin/               → Admin dashboard & controls
├── /student/             → Student voting interface
├── /includes/            → Database connection and auth
├── /assets/              → CSS, JS, images
├── /sql/                 → SQL database file (aiu\_election\_db.sql)
├── index.php             → Entry page / login redirect
├── README.md             → Project documentation
└── LICENSE               → (Optional) License info

````

---

## 🛠️ Technologies Used

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | HTML, CSS, JavaScript |
| Backend      | PHP                |
| Database     | MySQL              |
| Tools        | phpMyAdmin, XAMPP or WAMP |

---

## 🚀 Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/aiu-vote-sphere.git


2. **Place Folder in Server Directory:**

   * For XAMPP: `htdocs/aiu-vote-sphere`
   * For WAMP: `www/aiu-vote-sphere`

3. **Import Database:**

   * Open `phpMyAdmin`
   * Create a new DB (e.g., `aiu_election_db`)
   * Import `sql/aiu_election_db.sql`

4. **Configure DB Settings:**

   * Open `includes/connection.php`
   * Update DB name, username, and password

5. **Launch in Browser:**


   http://localhost/aiu-vote-sphere/
   ```


## ⚙️ Security Measures

* Passwords stored using `password_hash()`
* SQL injection prevention with `prepared statements`
* Session-based access control for both voters and admins
* One-vote-per-user enforced at the DB and session level

---

## 📊 Future Improvements

* Two-factor authentication (2FA) for admin access
* Mobile responsiveness for all user pages
* Email confirmation after voting
* Analytics dashboard for voting patterns
* Candidate profile pages with bios and campaigns

---

## 👥 Contributors

* \[Your Full Name] – Developer & System Designer
* \[Supervisor Name] – Project Supervisor

---

## 📃 License

This project is intended for academic purposes at Albukhary International University.
All rights reserved © 2025.



## 🙏 Acknowledgements

Thanks to:

* AIU SRC Committee
* Supervisor and advisors
* Fellow students for testing and feedback


