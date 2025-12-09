# 📌 **Kanban Todo Board (TypeScript + Drag & Drop + LocalStorage)**

![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

A lightweight Kanban-style task board built with **TypeScript**, **ES Modules**, and **no external frameworks**.
The application runs entirely in the browser and supports task creation, drag & drop, priority levels, and local data persistence.

---

## 🖼️ Screenshot

> *(Add a screenshot here when ready)*
> `![App Screenshot](./screenshot.png)`
> <img width="1907" height="779" alt="Screenshot 2025-12-09 141232" src="https://github.com/user-attachments/assets/707c66a4-c68f-43e1-923e-17eb37dbabe0" />


---

## ✨ Features

* Create tasks with a title and priority level
* Four workflow columns:

  * **Todo**
  * **Work in Progress**
  * **Testing**
  * **Done**
* Drag & Drop task movement between columns
* Visual highlight when a task is moved to *Done*
* Delete tasks instantly
* Tasks saved automatically using **localStorage**
* Works completely offline — no server required
* Clean, modular architecture using TypeScript and ES modules

---

## 📦 Installation

Clone the repository and install dependencies:

```sh
git clone <repository-url>
cd <project-folder>
npm install
```

---

## 🔧 Build

Compile TypeScript into JavaScript:

```sh
npm run build
```

Development mode (watch for changes):

```sh
npm run dev
```

The compiled files are located in the **dist/** directory.

---

## ▶️ Run the Application

Simply open:

```
index.html
```

in any modern web browser.
The application runs locally and does **not** require a server.

---

## 📁 Project Structure

```
src/
  main.ts         # App logic and event handling
  ui.ts           # UI generation and Drag & Drop logic
  storage.ts      # LocalStorage handling
  types.ts        # Shared TypeScript types

dist/
  main.js
  ui.js
  storage.js
  types.js

index.html        # App interface
styles.css        # Styling
tsconfig.json     # TypeScript configuration
package.json      # NPM scripts & dependencies
README.md
```

---

## 🛠 Technologies Used

* **TypeScript**
* **HTML5 Drag & Drop API**
* **LocalStorage**
* **ES Modules**
* **CSS**

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Contributions

Pull requests and suggestions are welcome!
Feel free to open an issue if you'd like a new feature or want to report a bug.

---
