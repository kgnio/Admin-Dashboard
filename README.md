# ⚡ Advanced Dashboard (MERN Stack)

![License](https://img.shields.io/github/license/kgnio/Admin-Dashboard)
![Stars](https://img.shields.io/github/stars/kgnio/Admin-Dashboard)
![Issues](https://img.shields.io/github/issues/kgnio/Admin-Dashboard)
![Last Commit](https://img.shields.io/github/last-commit/kgnio/Admin-Dashboard)

An advanced **device and sensor management dashboard** built with the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
It features real-time updates, dynamic dropdowns, authentication, and a modern responsive design.

---

## 🚀 Features

- 👤 **User Management** – Registration, login, profile handling  
- 🔌 **Device CRUD** – Add, update, and manage devices, sensors, and relays  
- 📍 **Dynamic Dropdowns** – Cascading menus (city → district)  
- 🔎 **Filtering** – Filter devices by type, status, etc.  
- 🔔 **Notifications** – Manual control of user alerts  
- ⚡ **Real-Time Updates** – Instant UI changes via state updates  
- 🌓 **Dark/Light Theme** – Theme switch support  
- 📱 **Responsive UI** – Works seamlessly across devices  

---

## 🛠️ Tech Stack

### Frontend
- ⚛️ **React.js** – Component-based UI  
- 🎨 **Tailwind CSS** – Utility-first styling  
- 🧩 **DaisyUI** – Tailwind UI components  

### Backend
- 🟢 **Node.js** – Runtime environment  
- 🚀 **Express.js** – Web framework for REST APIs  
- 🍃 **MongoDB** – NoSQL database for device/user data  
- 🔐 **JWT Authentication** – Secure user sessions  

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/kgnio/Admin-Dashboard.git
```

### 2. Navigate into the project
```bash
cd Admin-Dashboard
```

### 3. Backend setup
```bash
cd backend
npm install
```

### 4. Frontend setup
```bash
cd frontend
npm install
```

### 5. Configure environment variables
Create a `.env` file in the **backend** folder:

```env
PORT=3000
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret
NODE_ENV=development
PASS=your_password
REACT_APP_API_BASE_URL=http://localhost:5173
```

---

## ▶️ Running the Project

### Start backend
```bash
cd backend
npm run dev
```

### Start frontend
```bash
cd frontend
npm start
```

### Access the app
👉 Open [http://localhost:5173](http://localhost:5173)

---

## 📂 Project Structure

```
Admin-Dashboard/
├── backend/
│   ├── routes/         # Express routes
│   ├── models/         # Mongoose models
│   ├── controllers/    # Business logic
│   └── index.js        # App entry
├── frontend/
│   ├── src/components/ # Reusable UI components
│   ├── src/pages/      # Main app pages
│   └── src/context/    # Global state/context
```

---

## 🤝 Contributing

1. Fork the repository  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:  
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to your branch:  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request  

---

## 👤 Author

- **Kagan Mamak** – [@kgnio](https://github.com/kgnio)

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
