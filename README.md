# 📦 Inventory Management System

##[🌐 Live App Expense Tracker](https://inventory-management-system-3kay.onrender.com)
Test-> email:exampdles@gmail.com, password: 123

A full-stack **Inventory Management System** built with **Node.js**, **Express**, **MongoDB (Mongoose)**, and vanilla JavaScript for frontend handling. It helps businesses manage products, categories, suppliers, and track profit and stock with ease.

---

## 💡 Technologies Used

### Backend:
- **Node.js** with **Express.js**
- **MongoDB** using **Mongoose**
- **JWT** for secure routes
- **bcrypt.js** for password hashing

### Frontend:
- **HTML/CSS**
- **JavaScript (Fetch API)**
- **Chart.js** for reports and analytics (e.g. pie/bar charts)

### Tools:
- **dotenv** for environment config
- **Nodemon** for live backend development
- **MongoDB Atlas** (or local MongoDB)

---
# Inventory Management System - Project Structure

```
INVENTRY-MANAGEMENT-SYSTEM/
├── controller/               
│   ├── adminControllers.js
│   ├── productController.js
│   └── userController.js
│
├── lib/                     
│   └── utils.js
│
├── middleware/               
│   ├── adminAuth.js
│   └── userAuth.js
│
├── model/                   
│   ├── db.js
│   ├── employee.js
│   └── product.js
│
├── public/                  
│   ├── admin.html
│   ├── admin.js
│   ├── adminLogin.html
│   ├── authentication.html
│   ├── index.html
│   ├── script.js
│   └── styles.css
│
├── routes/                  
│   ├── admin.js
│   ├── product.js
│   └── user.js
│
├── .env                      
├── .gitignore               
├── package-lock.json         
├── package.json              
├── server.js                
└── README.md
```

# .env file example
```
MONGO_URL=mongodb+srv://username:password@cluster.mongodb.net/dbname
PORT=3000
JWT_SECRET_ADMIN=
JWT_SECRET_USER=
```



## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Unseen-Coder/Inventory-Management-System.git
cd Inventory-Management-System

# Install dependencies
npm install

# Create .env file as described above

# Run the server
npm run dev

After running `npm run dev`, the server will be running at:
👉 http://localhost:3000
