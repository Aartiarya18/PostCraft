# 📝 PostCraft – Full-Stack Blog Platform with Admin Dashboard

PostCraft is a full-stack blogging platform that allows users to register, create, and manage blog posts through a modern admin dashboard. Built using Node.js, Express, MongoDB, and EJS, it includes features like image uploads, responsive layouts, and dynamic routing – all wrapped in a clean and functional UI.

---

## 🚀 Features

- 👤 User Registration & Login
- 🧠 Custom Admin Dashboard
- ✍️ Create, Edit, and Delete Posts
- 🖼️ Blog & Profile Image Uploads using Multer
- 🧩 Modular Layouts with EJS Templating
- 📱 Responsive Design with Clean UI

---

## 🔧 Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS, HTML, CSS, JavaScript
- **Database**: MongoDB
- **Other Tools**: Multer (file upload), Method Override, Dotenv

---

## 📂 Folder Structure

```
PostCraft/
├── public/
│   └── css/style.css
│   └── uploads/
├── server/
│   ├── config/db.js
│   ├── helpers/
│   ├── models/
│   ├── routes/
├── views/
│   ├── admin/
│   ├── layouts/
│   ├── partials/
├── app.js
├── .env
├── package.json
```

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aartiarya18/PostCraft.git
   cd PostCraft
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root folder and add:
   ```
   MONGO_URI=your_mongo_connection_string
   PORT=5000
   ```

4. **Run the application**
   ```bash
   npm start
   ```

5. Visit: `http://localhost:3000`

---


## 📬 Contact

Made with ❤️ by [me](https://github.com/Aartiarya18).  
For feedback or suggestions, feel free to open an issue or reach out to me at [aarti18499@gmail.com](aarti18499@gmail.com).

