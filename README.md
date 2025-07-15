# 🏨 Royal Hotel Booking System

**Royal Hotel** is a web-based hotel management and room booking system. This project allows guests to book rooms online and lets administrators manage room availability, guest information, and feedback. The hotel offers various facilities and accommodates different room types like Single/Double AC & Non-AC. It's built using HTML, CSS, PHP, MySQL, and Bootstrap.

---

## 🌐 Live Preview

> You can run this project locally using XAMPP/WAMP:

```
http://localhost/royal-hotel/index.html
```

---

## ✨ Project Features

* Room Booking System
* Admin Panel with secure login
* Display of room types, prices, and availability
* Contact and Feedback Form
* Gallery and Blog Section
* Responsive Layout (Mobile/Desktop)
* Newsletter Subscription

---

## 📷 Screenshots

*Add homepage, room listings, booking form, admin dashboard screenshots here*

---

## 🛠️ Technology Stack

| Component  | Technology                                   |
| ---------- | -------------------------------------------- |
| Frontend   | HTML5, CSS3, Bootstrap 4, JavaScript, jQuery |
| Backend    | PHP (Procedural)                             |
| Database   | MySQL (MariaDB via phpMyAdmin)               |
| Web Server | Apache (XAMPP/WAMP)                          |

---

## 📁 Folder Structure

```
project/
├── index.html
├── about.html
├── accomodation.html
├── gallery.html
├── blog.html
├── blog-single.html
├── contact.html
├── elements.html
├── rooms.php
├── admin/
│   └── book_room.php
├── css/
├── js/
├── image/
├── vendors/
├── bootstrap-4.4.1/
└── database/
    └── royal_hotel.sql
```

---

## 📂 Database Information

* **Database Name:** `royal_hotel`
* **Tables:** `admin`, `single_ac`, `double_ac`, `single_non_ac`, `double_non_ac`, `contact`, `feedback`

**Import Instructions:**

1. Open **phpMyAdmin**
2. Create a new database named `royal_hotel`
3. Click **Import** and select the `royal_hotel.sql` file

> Note:
>
> * Passwords are stored as plaintext (for demo). Use hashing in production.
> * Dates are stored as VARCHAR. For better filtering, use DATE format.

---

## ⚙️ Installation / Setup Instructions

### Prerequisites:

* XAMPP/WAMP
* PHP ≥ 7.0
* MySQL

### Setup Steps:

1. Clone or Download this repository
2. Move the folder to `htdocs/` (if using XAMPP)
3. Import `royal_hotel.sql` into phpMyAdmin
4. Start Apache & MySQL from XAMPP Control Panel
5. Open in browser: `http://localhost/royal-hotel/index.html`

---

## 🤔 Usage Instructions / Admin Login

* Email: `admin@gmail.com`
* Password: `admin@123`

> You can change this in the `admin` table inside the database.

---

## ⚠️ Known Issues / Limitations

* No session-based login implemented (add for security)
* Passwords are not hashed
* Room tables are split; should be unified for scalability

---

## 👥 Contributors

* Ruji Akther — ID: `0562210005101021`
* Taufiqur Rahman Rabby — ID: `0562220005101027`
* Popy Talukder — ID: `0562220005101007`

Department of CSE, North East University Bangladesh

---

## 📄 License

This project uses the Colorlib template under the [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) license. Free for personal and educational use with attribution.

---

## 💭 Suggestions for Future Improvement

* Merge all room types into a single table using `room_type` field
* Add session-based secure login system for admin
* Use prepared SQL statements to prevent SQL injection
* Implement AJAX for room booking without page reload
* Create RESTful APIs for third-party booking integration
