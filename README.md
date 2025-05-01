# 📛 Project Name: CampusClock

## 📝 Description
**CampusClock** is a student time tracking system designed specifically for educational institutions. It allows students to manually sign in using their student ID (*no password required*) and provides them with two simple options: **Clock In** and **Clock Out**.

The system ensures integrity by enforcing the following rules:

- Students can only **Clock Out** if they have **Clocked In**, and vice versa.
- All time entries are logged and saved to an **Excel sheet**, which administrators can export for recordkeeping or auditing.

**Admins** can log in with a static username and password (`admin` / `pass`) to manage records and monitor activity.

**Students are only allowed to clock in/out when they are:**

- Connected to the **school Wi-Fi**
- Physically present within the school's geographic boundaries (**geofencing**)

---

## ⚙️ Key Features
- Manual **Student ID** entry for flexibility in managing access.
- **Admin-only access** to exported data and logs.
- Simple and **intuitive interface** for student time tracking.
- Prevents falsified check-ins via **geolocation and network verification**.

---

## 🔒 Security Note
This project is built with **integrity** in mind but is designed for **internal/institutional use only**. For production use, additional security layers and **data protection mechanisms** should be implemented.
