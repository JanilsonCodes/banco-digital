# 💳 Digital Bank - Zustand

![Digital Bank](./logo_bai.png)

A small banking system developed with **React** and **Zustand** to practice global state management in a simple, fast, and efficient way.

The project simulates a digital wallet where users can view their balance, make deposits, withdraw money, update personal information, and track transaction history.

---

## 🚀 Project Objective

This project was developed with the goal of studying and applying **Zustand** as a state management solution in React.

The application was created to understand in practice:

- Creating stores with Zustand;
- Managing global states;
- Creating actions inside the store;
- Updating data across different components;
- Data persistence;
- Organization of React components.

---

# 🛠️ Technologies Used

## ⚛️ React

A library used to build the user interface.

React was chosen because of its ease of creating reusable components and its wide adoption in modern Front-End development.

---

## 🐻 Zustand

A library used for global state management.

Zustand was chosen because it is a simpler and lighter alternative to Redux, allowing application state control without the need for complex configurations.

Used to manage:

- User name;
- Account balance;
- Transaction history;
- Deposit and withdrawal actions.

---

## ⚡ Vite

A tool used for project creation and build process.

Vite was chosen because it provides:

- Fast development environment startup;
- Faster development experience;
- Hot Module Replacement (HMR);
- Optimized production builds.

---

## 🎨 CSS

Used for interface styling.

A responsive design was created with:

- Cards;
- Custom buttons;
- Organized layout;
- Interface similar to a real banking application.

---

## 💾 LocalStorage

Used to store user data in the browser.

It allows the application to keep:

- Name;
- Balance;
- Transaction history;

even after closing or refreshing the page.

---

# 📂 Project Structure

```text
src
│
├── components
│   ├── Perfil.jsx
│   ├── Saldo.jsx
│   ├── Controles.jsx
│   └── Historico.jsx
│
├── store
│   └── bancoStore.js
│
├── App.jsx
├── main.jsx
└── style.css
```

---

# ⚙️ Features

✅ View current balance

✅ Change user name

✅ Deposit money

✅ Withdraw money

✅ Add quick amounts

✅ Transaction history

✅ Save data in the browser

✅ Reset account

---

# 📦 Installation

Clone the project:

```bash
git clone https://github.com/yourusername/digital-bank-zustand.git
```

Enter the project folder:

```bash
cd digital-bank-zustand
```

Install dependencies:

```bash
npm install
```

Run the project:

```bash
npm run dev
```

---

# 🏗️ Production Build

To generate the optimized version of the project:

```bash
npm run build
```

Vite will create a folder:

```text
dist/
```

containing the files prepared for deployment.

---

# 🌐 Build Preview

To test the production version locally:

```bash
npm run preview
```

Vite will start a local server using the generated build files.

---

# 📈 Future Improvements

Possible improvements:

- 🔐 Login system;
- 🗄️ Real database integration;
- ☁️ Backend API;
- 📱 Mobile application;
- 📊 Financial charts;
- 🔔 Transaction notifications.

---

# 👨‍💻 Author

Developed by **Janilson Pereira**

Project created to study state management with Zustand and React.