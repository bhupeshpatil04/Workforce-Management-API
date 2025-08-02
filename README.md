# 🚀 Workforce Management Backend – Railse Assignment

This project is a backend API built as part of the **Railse Backend Coding Challenge**. It’s designed to manage and track tasks assigned to staff, with features like reassignment, prioritization, comment tracking, and date-based filtering — all using in-memory storage.

---

## 🧠 Features Implemented

✅ **Bug Fixes**
- **Duplicate Task on Reassignment:** Now prevents duplication by marking the old task as `CANCELLED`.
- **Cluttered Task View:** Date-based task fetch excludes `CANCELLED` tasks.

✨ **New Features**
- **Smart Daily View:** Shows all active tasks created within the range **and** those created earlier but still open.
- **Task Priority System:** Tasks can be labeled as `HIGH`, `MEDIUM`, or `LOW`; includes update & filter APIs.
- **Comments & Activity History:** Tracks task comments and automatically logs changes to status or priority.

---

## 🛠️ Tech Stack

- **Language:** Java 17  
- **Framework:** Spring Boot 3.0.4  
- **Build Tool:** Gradle  
- **Other Tools:** Lombok, MapStruct  
- **Database:** None — uses in-memory `Map` and `List`

---

## 📁 Project Structure

