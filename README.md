# 📋 Daily Planner (Curses + SQLite)

A lightweight **terminal-based daily planner** built with Python, SQLite, and Curses.  
Easily add, track, filter, and complete todos — all in your terminal with a clean TUI.

---
<img width="840" height="433" alt="Screenshot 2025-09-06 at 8 26 38 PM" src="https://github.com/user-attachments/assets/cff1a749-f794-4094-8076-31c2a52c8428" />

## ✨ Features
- **Todos with tags & due dates**
  - Supports natural input: `today`, `tomorrow`, `+3d`, `+1w`
  - Categories displayed as hashtags (e.g. `#study`)
- **Dashboard**
  - Shows all unfinished todos
  - Navigation with ↑/↓ keys
  - Overdue, due today, and future todos highlighted (red, yellow, green)
  - Progress bar (completion percentage)
- **Filtering & Search**
  - `/` → search by title
  - `f` → filter by tag (`#tag`)
  - `b` → reset view
- **Completed & Deleted views**
  - Mark tasks as **done** (`d`)
  - Soft delete tasks (`x`) — still available in completed view
- **Keyboard shortcuts**
  - `a` → add a new todo
  - `d` → mark selected todo as done
  - `x` → soft delete a todo
  - `c` → view completed todos
  - `/` → search by keyword
  - `f` → filter by category
  - `b` → back to full dashboard
  - `q` → quit

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/adnair2024/termplanner.git
   cd daily-planner
