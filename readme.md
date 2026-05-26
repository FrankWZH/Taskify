<div align="center">

# 🚀 Taskify Enhanced

### A Customized Task Management Platform

Built with **Node.js**, **Express.js**, and **MongoDB**

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white">
  <img src="https://img.shields.io/badge/Security-Enhanced-blue?style=for-the-badge">
</p>

<p align="center">
  <b>Enhanced authentication • Automated testing • Backend optimization • Security improvements</b>
</p>

</div>

---

# 📖 Overview

Taskify Enhanced is a customized and improved version of the original open-source Taskify project.

This version focuses on:

- 🔐 Authentication and security enhancements
- 🧪 Automated testing with Jest
- ⚙️ Backend optimization and maintainability
- 🗂 Improved project organization
- ☁️ MongoDB integration
- 📤 File upload support

The project was modified and extended for educational, research, and personal development purposes.

---

# 🙏 Acknowledgement

This project is based on the open-source **Taskify** project.

### Original Repository
https://github.com/sptin2002/Taskify

The original project provided the foundation for this customized version.  
Additional modifications, testing, restructuring, and security-related improvements were implemented independently.

---

# ✨ Features

## ✅ Core Features

- User authentication and authorization
- Task creation and management
- RESTful API support
- MongoDB database integration
- File upload functionality
- Responsive frontend interface

---

## 🔒 Security Enhancements

This customized version includes several backend security improvements:

- Improved authentication workflow
- Password hashing enhancements
- Session validation improvements
- Additional backend verification logic
- Safer request handling
- Improved error handling mechanisms

---

# 🛠 Tech Stack

| Technology | Usage |
|---|---|
| Node.js | Backend runtime |
| Express.js | Web framework |
| MongoDB | Database |
| JavaScript | Programming language |
| HTML5 / CSS3 | Frontend structure |
| Bootstrap | UI styling |
| Jest | Automated testing |

---

# 📂 Project Structure

```text
├── src
│   ├── cloudinary
│   ├── db
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── tests
│   └── app.js
│
├── static
│   ├── assets
│   ├── js
│   └── styles
│
├── views
│   └── partials
│
├── package.json
├── package-lock.json
├── .env
├── .gitignore
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/FrankWZH/Taskify.git
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Configure Environment Variables

Create a `.env` file in the project root directory:

```env
ENV=development
PORT=3000

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret
EXPIRY=your_jwt_expiry
SECRET=your_session_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret

X_RAPIDAPI_HOST=your_rapidapi_host
X_RAPIDAPI_KEY=your_rapidapi_key

SENDGRID_EMAIL=no-reply@example.com
```

---

## 4️⃣ Start the Application

```bash
npm start
```

---

# 🚀 Custom Improvements

Compared with the original upstream repository, this customized version includes:

- ✅ Authentication improvements
- ✅ Additional backend validation
- ✅ Session security enhancements
- ✅ Automated testing support
- ✅ Refactored backend structure
- ✅ MongoDB integration improvements
- ✅ Bug fixes and stability enhancements
- ✅ Improved maintainability and readability

---

## 🧪 Testing Support

- Automated testing using Jest
- Backend validation testing
- Improved error detection
- Coverage report support

Run tests using:

```bash
npm test
```

Generate coverage reports:

```bash
npm test -- --coverage
```

---

# ⚠️ Disclaimer

This repository is a customized educational project derived from the original open-source Taskify repository.

All original credits belong to the respective upstream contributors.

This project is intended for:

- Educational purposes
- Research purposes
- Personal development
- Software engineering practice

---

# 📜 License

This project is based on the original open-source Taskify repository and follows the original MIT License.

Please refer to the original license file here:

[MIT License](https://github.com/DSCKGEC/Taskify/blob/main/LICENSE)

Additional modifications and custom implementations in this repository are provided for educational and personal development purposes.

---

# 🔗 Repository Links

### Customized Repository
https://github.com/FrankWZH/Taskify

### Original Upstream Repository
https://github.com/sptin2002/Taskify

---

# 👥 Team Members & Contributions

This project was collaboratively developed and enhanced by the following contributors:

| Name | GitHub | Main Contribution |
|------|------|------|
| Zihang Wu | [@FrankWZH](https://github.com/FrankWZH) | Project integration, backend development, testing, documentation, deployment |
| Xiaofei Chen | [@xiaofei1412](https://github.com/xiaofei1412) | System feature development and frontend collaboration |
| Zhuozhi Li | [@GeorgeNum7](https://github.com/GeorgeNum7) | Security enhancement for Broken Authentication vulnerabilities |
| Zhiling Liang | [@Qiqi0312](https://github.com/Qiqi0312) | Security enhancement for CSRF and Access Control vulnerabilities |

---

<div align="center">

### ⭐ If you find this project useful, feel free to star the repository!

</div>
