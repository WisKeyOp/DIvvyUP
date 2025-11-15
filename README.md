# DivvyUp 💸  
Smart shared expense & group finance manager

DivvyUp is a full-stack web app that makes splitting bills, tracking group expenses, and understanding your spending painless. Create groups with friends, log transactions, upload receipts, and see who owes whom in seconds.

---

## ✨ Features

- 🧾 **Record daily transactions** (personal & group)
- 👥 **Create groups with friends** and split expenses
- 🔁 **Auto-simplify debts** inside a group (who owes whom)
- 📊 **Visual analytics** for income, savings & expenditure
- 🧸 **Upload & store bills/receipts** as PDFs
- 📍 **Track expenses over time** with clear history
- 🌍 **Real-time currency conversion** for foreign spending
- 📈 **Easy-to-understand charts** (Recharts)
- 🔔 **Payment reminders / due notifications**
- 📤 **Export expenses to spreadsheets** for backup or sharing
- 🔐 **JWT-based authentication** + optional Google login

---

## 🧱 Tech Stack

**Frontend**

- React (Create React App)
- TailwindCSS
- Material UI (MUI)
- Recharts
- @react-oauth/google (Google login)
- Axios, React Icons, etc.

**Backend**

- Node.js
- Express.js
- MongoDB + Mongoose
- Multer (file uploads)
- JSON Web Tokens (`jsonwebtoken`)
- bcrypt / bcryptjs (password hashing)
- dotenv, cors, morgan

**Other**

- MongoDB Atlas (recommended for production)
- Deployed on Vercel (frontend + backend as separate projects)

---

## 📸 Screenshots

> (These paths work on GitHub if the `Screenshots` folder is at the repo root.)

![Dashboard](Screenshots/1.jpeg)
![Groups](Screenshots/2.jpeg)
![Expenses](Screenshots/3.jpeg)
![Analytics](Screenshots/4.jpeg)
![Receipts](Screenshots/5.jpeg)
![Auth](Screenshots/6.jpeg)

---

## 📂 Project Structure

```bash
DIvvyUP-master/
├── client/              # React frontend (CRA)
│   ├── src/
│   ├── public/
│   └── package.json
├── server/              # Node/Express backend
│   ├── config/          # DB config (Mongo connection)
│   ├── middleware/      # Auth middleware (JWT)
│   ├── modal/           # Mongoose models (User, Group, Expense, Pdf, etc.)
│   ├── router/          # Route handlers (user, group, friends, expense...)
│   ├── services/        # Business logic (expenseServices)
│   ├── files/           # Uploaded PDFs (receipts/bills)
│   ├── server.js        # Express app entry
│   └── package.json
├── Screenshots/         # App screenshots
├── LICENSE              # MIT License
└── README.md
```

This Project is managed By **Aayush Shukla**
