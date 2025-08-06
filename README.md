# Grocery List React App (with JSON Server)

This is a simple grocery list app built using **React**. The app uses **JSON Server** to simulate a backend API for fetching and updating data.

---

## 🚀 Features

- View a list of grocery items
- Mark items as completed
- Add new items
- Delete existing items
- Fetch and update data via a local JSON server

---

## 📁 Project Structure

```
├── public/
├── src/
│   ├── components/
│   ├── App.js
│   ├── index.js
│   └── ...
├── data/
│   └── db.json        # JSON Server data file
├── package.json
└── README.md
```

---

## 🛠 Requirements

Make sure you have:

- [Node.js and npm](https://nodejs.org/) installed
- `json-server` installed (globally or locally)

---

## 📦 Install Dependencies

```bash
npm install
```

If you don't have `json-server` installed yet:

```bash
npm install -g json-server
```

---

## ▶️ Run the App

In **one terminal**, start the JSON Server:

```bash
json-server -p 3500 -w data/db.json
```

In **another terminal**, start the React app:

```bash
npm start
```

---

## 🌐 Accessing the App

- React App: `http://localhost:3000`
- JSON Server API: `http://localhost:3500/items`

---

## 🤔 What if someone clones this repo?

If someone clones this project from GitHub, they just need to:

1. Install dependencies:  
   ```bash
   npm install
   ```

2. Install JSON Server (if not already installed):  
   ```bash
   npm install -g json-server
   ```

3. Start JSON Server:  
   ```bash
   json-server -p 3500 -w data/db.json
   ```

4. Start the React App:  
   ```bash
   npm start
   ```

---

## 📌 Notes

- JSON Server is used to simulate a RESTful API using a simple JSON file.
- This project is for learning/demo purposes only.
