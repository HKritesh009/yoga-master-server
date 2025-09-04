# 🧘 Yoga Master – Full-Stack Course Management Platform

[![Project Banner](https://your-animation-link.com/banner.gif)](https://your-animation-link.com)  

*Experience immersive learning with Yoga Master – the ultimate platform for discovering, enrolling, and managing online classes in yoga and wellness.*

---

## 🌟 Overview

**Yoga Master** is a full-stack web application built using **Node.js, Express.js, MongoDB, and Stripe** for payments. The platform enables instructors to create courses, students to browse and enroll, and admins to manage content efficiently. The application features modern design, authentication, role-based access, real-time updates, and integrated payment processing.

---

## 🎯 Key Features

### 🧑‍💻 User Management
- Secure **JWT-based authentication**.
- Role-based access:
  - **Admin** – Manage users and approve classes.
  - **Instructor** – Add and manage classes.
  - **Student** – Browse, enroll, and pay for classes.
- Full CRUD operations for user profiles.

### 📚 Class Management
- Instructors can **create, update, and manage classes**.
- Admin approval system for quality control.
- Real-time tracking of **available seats** and **total enrollments**.

### 🛒 Cart & Enrollment System
- Add classes to a **cart** before enrollment.
- Remove or update cart items.
- Automatic enrollment after **successful payment**.

### 💳 Payment Integration
- **Stripe API** for secure payments.
- Store payment history and transaction IDs.
- Calculate **total revenue, enrolled classes, and more**.

### 📈 Analytics & Dashboard
- **Popular classes** sorted by enrollments.
- **Top instructors** aggregation with MongoDB pipelines.
- Admin dashboard for **quick stats**:
  - Total classes (approved/pending)
  - Total enrollments
  - Total instructors

### 🏆 Instructor Applications
- Students can apply to become instructors.
- Track application status directly from the dashboard.

---

## 🚀 Tech Stack

- **Frontend:** EJS, Bootstrap, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas)
- **Authentication:** JWT
- **Payments:** Stripe
- **3D Animation & UI:** Three.js or Lottie.js (optional)

---

## 🔥 3D Animation Demo

Experience interactive 3D animations on the homepage and dashboards:

```html
<!-- Example using Lottie -->
<div id="animation"></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/bodymovin/5.9.7/lottie.min.js"></script>
<script>
  lottie.loadAnimation({
    container: document.getElementById('animation'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'https://assets10.lottiefiles.com/packages/lf20_x62chJ.json' // link to your animation JSON
  });
</script>
```
## ⚙️ Installation & Setup
 
### Clone the repo
```
git clone https://github.com/HKritesh009/YogaMaster.git
```
### Navigate to project folder
cd YogaMaster

### Install dependencies
```
npm install
```

### Create .env file
### Example:
### PORT=5000
### DB_USER=<your_mongo_user>
### DB_PASS=<your_mongo_pass>
### ACCESS_SECRET=<your_jwt_secret>
### PAYMENT_SECRET=<your_stripe_secret>

# Run the server
```
npm start
```

## Project Structure

YogaMaster/
│
├── app.js
├── package.json
├── .env
├── routes/
│   ├── users.js
│   ├── classes.js
│   └── payments.js
├── views/
│   ├── layouts/
│   ├── dashboard.ejs
│   └── ...
├── public/
│   ├── css/
│   ├── js/
│   └── images/
└── README.md

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.  
Make sure to follow the coding conventions and include clear commit messages.

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🎨 Demo & Animation


---

### Optional Badges

```markdown
![Node.js](https://img.shields.io/badge/Node.js-v20-green)
![MongoDB](https://img.shields.io/badge/MongoDB-v6.0-brightgreen)
![Stripe](https://img.shields.io/badge/Stripe-v11.14-blue)
```