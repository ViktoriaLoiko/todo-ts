# 🔤 Multilingual README  
**This project README is available in two languages: English and Russian.**  
**Информация в этом README доступна на двух языках: английском и русском.**

---

# 📌 **Kanban Todo Board (TypeScript + Drag & Drop + LocalStorage)**

![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

A lightweight Kanban-style task board built with **TypeScript**, **ES Modules**, and **no external frameworks**.

The application runs entirely in the browser and supports task creation, drag & drop (Todo → WIP → Testing → Done.), priority levels (Low-Medium-High), and local data persistence.

---

## 🖼️ Screenshot

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
git clone  https://github.com/ViktoriaLoiko/todo-ts.git
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

The files are located in the **dist/** directory.

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

# 🚀 **Possible Improvements**

* Add improved UI/UX design, including modern color themes, animations, and enhanced task card styling.
* Add editing mode for tasks
* Add sorting or filtering by priority
* Add drag handle indicators for better usability
* Add GitHub Pages demo with a public URL

---

# 🇷🇺 **Полная версия README на русском языке**

---

# 📌 **Kanban Todo Board (TypeScript + Drag & Drop + LocalStorage)**

![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

Облегчённая Kanban-доска задач, созданная на **TypeScript**, **ES Modules** и без использования внешних фреймворков.

Приложение полностью работает в браузере, поддерживает создание задач, перетаскивание (Drag & Drop) между колонками (Todo → WIP → Testing → Done), уровни приоритета (Low-Medium-High) и автоматическое сохранение данных в LocalStorage.

---

## 🖼️ Скриншот

> <img width="1907" height="779" alt="Screenshot 2025-12-09 141232" src="https://github.com/user-attachments/assets/707c66a4-c68f-43e1-923e-17eb37dbabe0" />

---

## ✨ Возможности

* Создание задач с заголовком и приоритетом
* Четыре колонки рабочего процесса:

  * **Todo**
  * **Work in Progress**
  * **Testing**
  * **Done**
* Перетаскивание задач между колонками (Drag & Drop)
* Визуальная подсветка при переносе задачи в *Done*
* Удаление задач
* Автоматическое сохранение задач в **localStorage**
* Полностью офлайн — сервер не требуется
* Чистая модульная архитектура на TypeScript

---

## 📦 Установка

Клонируйте репозиторий и установите зависимости:

```sh
git clone  https://github.com/ViktoriaLoiko/todo-ts.git
cd <project-folder>
npm install
```

---

## 🔧 Сборка проекта

Скомпилировать TypeScript → JavaScript:

```sh
npm run build
```

Режим разработки:

```sh
npm run dev
```

Готовые файлы находятся в папке **dist/**.

---

## ▶️ Запуск приложения

Откройте:

```
index.html
```

Приложение работает локально и **не требует сервера**.

---

## 📁 Структура проекта

```
src/
  main.ts
  ui.ts
  storage.ts
  types.ts

dist/
  main.js
  ui.js
  storage.js
  types.js

index.html
styles.css
tsconfig.json
package.json
README.md
```

---

## 🛠 Используемые технологии

* **TypeScript**
* **HTML5 Drag & Drop API**
* **LocalStorage**
* **ES Modules**
* **CSS**

---

## 📄 Лицензия

Проект распространяется по лицензии **MIT**.

---

## 🙌 Вклад

Pull request'ы и предложения приветствуются!
Можно создавать issue для новых идей или сообщений об ошибках.

---

# 🚀 **Возможные улучшения**

* Разработка улучшенного дизайна: современные цветовые темы, анимации, улучшенный внешний вид карточек
* Возможность редактировать задачи
* Сортировка или фильтрация по приоритету
* Улучшенные подсказки для перетаскивания задач
* Публикация демо-версии через GitHub Pages

---

