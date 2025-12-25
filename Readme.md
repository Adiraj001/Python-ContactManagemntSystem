# 📇 Contact Management System (Python + Tkinter)

A desktop-based **Contact Management System** built using **Python**, **Tkinter**, and **SQLite**.
This application allows users to **add, view, update, and delete contacts** through a simple graphical user interface.

---

## ✨ Features

* 📌 Add new contacts with details:

  * First Name
  * Last Name
  * Gender
  * Age
  * Address
  * Contact Number
* ✏️ Update existing contact records
* 🗑️ Delete contacts with confirmation
* 📊 View all contacts in a sortable table
* 💾 Persistent storage using SQLite database
* 🖥️ User-friendly Tkinter GUI

---

## 🛠️ Technologies Used

* **Python 3**
* **Tkinter** – GUI framework
* **SQLite3** – Lightweight database
* **ttk (Treeview)** – Table display widget

---
### 2️⃣ Run the Application

```bash
python index.py
```

> ⚠️ Make sure **Python 3** is installed on your system.

---

## 🗄️ Database Details

* Database file: `pythontut.db`
* Table name: `member`
* Table schema:

```sql
CREATE TABLE member (
    mem_id INTEGER PRIMARY KEY AUTOINCREMENT,
    firstname TEXT,
    lastname TEXT,
    gender TEXT,
    age TEXT,
    address TEXT,
    contact TEXT
);
```

The database is **automatically created** when the app runs for the first time.

---

## 🖱️ How to Use

* **Add New Contact**
  Click `+ ADD NEW`, fill in the form, and click **Save**.

* **Update Contact**
  Double-click a contact in the table, edit the details, and click **Update**.

* **Delete Contact**
  Select a contact and click **DELETE**.

---

## 🚀 Future Enhancements

* 🔍 Search and filter contacts
* 📤 Export contacts to CSV
* 🔐 User authentication
* 🎨 Improved UI styling

---
