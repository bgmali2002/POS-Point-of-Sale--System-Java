# 🛒 POS (Point of Sale) System - Java (Swing + JDBC + MariaDB)

This is a complete POS (Point of Sale) System developed using **Java Swing** for GUI, **JDBC** for database connectivity, and **MariaDB** as the backend. The project includes modules like user authentication, product management, sales billing, and report generation — making it suitable for small to medium retail shops.

---

## 🔧 Tech Stack

- ✅ Java (Swing for GUI)
- ✅ JDBC (Java Database Connectivity)
- ✅ MariaDB (Database)
- ✅ iText (for PDF reports/invoices)
- ✅ IntelliJ IDE

---

## ✨ Features

### 🔐 User Authentication
- Login system for Admin and Staff
- Basic user role management

### 📦 Product Management
- Add, update, delete products
- Product inventory view with category and price

### 💰 Sales Module
- Add products to cart
- Auto calculation of total
- Bill generation and inventory update

### 📊 Reports
- View sales history by date
- Generate PDF reports using iText

### 🧑‍💼 Admin Dashboard
- Quick access to all modules
- User-friendly Swing-based GUI

---

## 📂 Project Structure

```
POSSystem/
│
├── src/
│   ├── DBConnection.java
│   ├── LoginFrame.java
│   ├── Dashboard.java
│   ├── ProductPanel.java
│   ├── SalesPanel.java
│   ├── ReportPanel.java
│
├── lib/                  # External JARs
├── pos_db.sql            # SQL file to create DB schema
└── README.md
```

---

## 🗃️ Database Tables

- `users` – Stores login credentials
- `products` – Product info and stock
- `sales` – Sales transactions
- `sales_items` – Items sold per transaction

---

## 📸 Screenshots

> All screenshots inside the `/images` folder 
---

## 🙋‍♂️ Author

**Bherunath Gehlot**  
📧 E-mail: bhanwarm99@gmail.com 
🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/bherunath-gehlot)  
💻 GitHub: [github.com/bgmali2002](https://github.com/bgmali2002)

---

## 🌟 Support

If this project helped you, give it a star ⭐ on GitHub!  
For suggestions or contributions, feel free to fork or submit a pull request.

