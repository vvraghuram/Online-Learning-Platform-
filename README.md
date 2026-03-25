
<div align="center">

```
██╗     ███████╗ █████╗ ██████╗ ███╗   ██╗██╗  ██╗██╗   ██╗██████╗
██║     ██╔════╝██╔══██╗██╔══██╗████╗  ██║██║  ██║██║   ██║██╔══██╗
██║     █████╗  ███████║██████╔╝██╔██╗ ██║███████║██║   ██║██████╔╝
██║     ██╔══╝  ██╔══██║██╔══██╗██║╚██╗██║██╔══██║██║   ██║██╔══██╗
███████╗███████╗██║  ██║██║  ██║██║ ╚████║██║  ██║╚██████╔╝██████╔╝
╚══════╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝
```

### 🎓 A Full-Stack Online Learning Platform — Built with the MERN Stack

<br/>

[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://restfulapi.net/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

<br/>

![GitHub repo size](https://img.shields.io/github/repo-size/vvraghuram/Longterm?color=6c63ff&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/vvraghuram/Longterm?color=ff6584&style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/vvraghuram/Longterm?style=flat-square&color=ffc107)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

<br/>

> *"An intelligent, responsive learning platform designed to deliver structured educational content with secure authentication, real-time data insights, and seamless user experience across all devices."*

<br/>

[🚀 Live Demo](#-live-demo) · [📸 Screenshots](#-ui-preview) · [⚙️ Installation](#️-installation) · [📊 Data Analysis](#-data-analysis-module) · [🤝 Contributing](#-contributing)

---

</div>

<br/>

## 📌 Table of Contents

- [✨ Overview](#-overview)
- [📸 UI Preview](#-ui-preview)
- [🏗️ Architecture](#️-architecture)
- [🔥 Key Features](#-key-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📊 Data Analysis Module](#-data-analysis-module)
- [⚙️ Installation & Setup](#️-installation--setup)
- [🔐 Environment Variables](#-environment-variables)
- [📁 Project Structure](#-project-structure)
- [📡 API Endpoints](#-api-endpoints)
- [🚀 Live Demo](#-live-demo)
- [🤝 Contributing](#-contributing)
- [👤 Author](#-author)

---

<br/>

## ✨ Overview

**LearnHub** is a production-ready, full-stack online learning platform engineered using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It empowers learners to browse courses, track their progress, and engage with content — while administrators manage the learning ecosystem through a rich dashboard backed by data analytics.

The platform integrates a **Python + SQL + Excel data analysis module** that surfaces actionable insights on user engagement, course performance, and platform growth trends.

<br/>

---

## 📸 UI Preview

> **📷 Replace the placeholder blocks below with actual screenshots from your app.**

<br/>

### 🏠 Home / Landing Page
```
┌─────────────────────────────────────────────────────────────────┐
│                                                                   │
│   🎓  LearnHub                          [Login]  [Sign Up]        │
│  ─────────────────────────────────────────────────────────────  │
│                                                                   │
│         Learn Anything.                                           │
│         Build Everything.                                         │
│                                                                   │
│         [ Browse Courses ]   [ Get Started Free ]                 │
│                                                                   │
│   ──────────────────────────────────────────────────────────    │
│   📚 250+ Courses    👥 1,200+ Learners    ⭐ 4.8 Avg Rating     │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

> 📌 *Add screenshot: `docs/screenshots/homepage.png`*

---

### 📚 Course Dashboard
```
┌─────────────────────────────────────────────────────────────────┐
│  Dashboard          Search courses...        🔔  👤 Raghu Ram    │
│  ─────────────────────────────────────────────────────────────  │
│                                                                   │
│  [My Courses]  [Explore]  [Progress]  [Analytics]                │
│                                                                   │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐        │
│  │  MERN    │  │  Python  │  │  AWS     │  │  Data    │        │
│  │  Stack   │  │  for DS  │  │  Cloud   │  │  Science │        │
│  │  ████░░  │  │  ██████  │  │  ██░░░░  │  │  ████░░  │        │
│  │  68%     │  │  100% ✅  │  │  32%     │  │  71%     │        │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘        │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

> 📌 *Add screenshot: `docs/screenshots/dashboard.png`*

---

### 🔐 Authentication Pages

| Login | Register |
|-------|----------|
| ![Login Page](docs/screenshots/login.png) | ![Register Page](docs/screenshots/register.png) |

> 📌 *Replace with actual screenshots*

---

### 📊 Analytics & Insights Dashboard
```
┌─────────────────────────────────────────────────────────────────┐
│  📊 Platform Analytics                    Last 30 Days ▾        │
│  ─────────────────────────────────────────────────────────────  │
│                                                                   │
│   Total Users      Active Courses    Completions   Avg Score     │
│   ┌──────────┐    ┌──────────┐    ┌──────────┐   ┌──────────┐  │
│   │  1,248   │    │    87    │    │   342    │   │  78.4%   │  │
│   │  ↑ 12%  │    │  ↑ 5%   │    │  ↑ 23%  │   │  ↑ 3%   │  │
│   └──────────┘    └──────────┘    └──────────┘   └──────────┘  │
│                                                                   │
│   Enrollment Trend (Monthly)                                      │
│   ▓▓░░░▓▓▓░░▓▓▓▓▓░░░▓▓▓▓▓▓▓░▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓               │
│   Jan   Feb   Mar   Apr   May   Jun   Jul   Aug                   │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

> 📌 *Add screenshot: `docs/screenshots/analytics.png`*

---

### 📱 Mobile Responsive View
```
  ┌─────────────┐
  │ 🎓 LearnHub │
  │  ─────────  │
  │  Welcome    │
  │  back,      │
  │  Raghu! 👋  │
  │  ─────────  │
  │  ▶ My MERN  │
  │    Course   │
  │    ████░ 68%│
  │  ─────────  │
  │  ▶ Python   │
  │    ██████✅  │
  │  ─────────  │
  │  [+ Explore]│
  └─────────────┘
```

> 📌 *Add screenshot: `docs/screenshots/mobile.png`*

---

<br/>

## 🏗️ Architecture

```
                        ┌─────────────────────────────────┐
                        │         CLIENT (Browser)         │
                        │   React.js  +  CSS3  +  HTML5    │
                        │    Reusable Components | Hooks   │
                        └────────────────┬────────────────┘
                                         │  HTTP / REST API
                        ┌────────────────▼────────────────┐
                        │       SERVER (Node.js)           │
                        │   Express.js Middleware Stack    │
                        │   Auth → Validate → Route →      │
                        │   Controller → Model → DB        │
                        └────────────────┬────────────────┘
                                         │  Mongoose ODM
                        ┌────────────────▼────────────────┐
                        │         DATABASE                  │
                        │        MongoDB Atlas             │
                        │  Users | Courses | Enrollments   │
                        └─────────────────────────────────┘

                        ┌─────────────────────────────────┐
                        │     DATA ANALYSIS MODULE         │
                        │  Python  |  SQL  |  Excel        │
                        │  Pandas  |  Matplotlib | OpenPyXL│
                        └─────────────────────────────────┘
```

**Design Pattern:** MVC (Model → View → Controller)

```
src/
├── models/        ← MongoDB Schemas (Mongoose)
├── controllers/   ← Business Logic
├── routes/        ← Express REST API Routes
└── client/src/    ← React Components (View Layer)
```

---

<br/>

## 🔥 Key Features

### 👨‍🎓 Learner Experience
- 🔐 **Secure JWT Authentication** — Register, Login, Protected routes
- 📚 **Course Browsing & Enrollment** — Filter by category, difficulty, rating
- 📈 **Progress Tracking** — Visual progress bars per course & module
- 📱 **Fully Responsive UI** — Optimized for mobile, tablet, and desktop
- ⚡ **Fast Load Times** — Reusable React components with lazy loading

### 🛠️ Admin / Instructor Panel
- ➕ **CRUD for Courses** — Create, edit, delete courses and modules
- 👥 **User Management** — View all enrolled users and their activity
- 📊 **Analytics Dashboard** — Enrollment stats, completion rates, trends

### 🔧 Technical Highlights
- 🏛️ **MVC Architecture** — Clean separation of concerns across all layers
- 🌐 **RESTful API** — Stateless endpoints following REST conventions
- 🔒 **Password Hashing** — bcrypt encryption for credential safety
- 📡 **CORS Configured** — Cross-origin resource sharing with Express middleware
- 🧩 **Modular Codebase** — Reusable components, scalable folder structure

---

<br/>

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | React.js 18 | Component-based UI |
| **Frontend** | HTML5 + CSS3 | Semantic markup & styling |
| **Frontend** | JavaScript (ES6+) | Client-side logic |
| **Backend** | Node.js | Server runtime |
| **Backend** | Express.js | REST API framework |
| **Database** | MongoDB + Mongoose | NoSQL data persistence |
| **Auth** | JSON Web Tokens (JWT) | Stateless authentication |
| **Security** | bcrypt.js | Password hashing |
| **Data Analysis** | Python (Pandas, Matplotlib) | Insight generation |
| **Data Analysis** | MySQL | Structured query analysis |
| **Data Analysis** | Excel (OpenPyXL) | Export & reporting |
| **Version Control** | Git + GitHub | Source management |
| **Dev Tools** | VS Code, Postman | Development & API testing |

---

<br/>

## 📊 Data Analysis Module

> A standalone analytics layer built with **Python**, **SQL**, and **Excel** to turn raw platform data into actionable insights.

### 📁 Location: `analysis/`

```
analysis/
├── notebooks/
│   ├── user_engagement.ipynb      # Enrollment & activity trends
│   ├── course_performance.ipynb   # Completion rates per course
│   └── revenue_insights.ipynb     # Growth & retention analysis
├── sql/
│   ├── top_courses.sql            # Most enrolled courses
│   ├── user_retention.sql         # 30/60/90-day retention
│   └── completion_funnel.sql      # Module drop-off analysis
├── exports/
│   └── platform_report.xlsx       # Auto-generated Excel dashboard
└── data_pipeline.py               # ETL: MongoDB → CSV → Analysis
```

### 🔍 Sample Insights Generated

```python
# Top 5 Most Enrolled Courses
df.groupby('course_name')['enrollment_count'] \
  .sum().sort_values(ascending=False).head(5).plot(kind='bar')

# Monthly Active Users Trend
df['signup_date'] = pd.to_datetime(df['signup_date'])
df.resample('M', on='signup_date')['user_id'].count().plot()

# Completion Rate by Category
df.groupby('category')['completed'].mean().mul(100).round(2)
```

### 📈 Key Metrics Tracked

| Metric | Description |
|--------|-------------|
| **Enrollment Rate** | New enrollments per week/month |
| **Completion Rate** | % of users who finish a course |
| **Drop-off Points** | Modules with highest abandonment |
| **User Retention** | 30/60/90-day return rates |
| **Top Courses** | Highest rated & most enrolled |
| **Active Hours** | Peak usage times across platform |

---

<br/>

## ⚙️ Installation & Setup

### Prerequisites

```bash
node -v    # v18+ required
npm -v     # v9+ required
python -v  # v3.8+ for analysis module
mongod     # MongoDB running locally or Atlas URI ready
```

### 1. Clone the Repository

```bash
git clone https://github.com/vvraghuram/Longterm.git
cd Longterm
```

### 2. Install Server Dependencies

```bash
npm install
```

### 3. Install Client Dependencies

```bash
cd client
npm install
cd ..
```

### 4. Install Python Analysis Dependencies

```bash
pip install pandas matplotlib seaborn openpyxl mysql-connector-python jupyter
```

### 5. Configure Environment Variables

```bash
cp .env.example .env
# Edit .env with your values (see section below)
```

### 6. Run the Application

```bash
# Run both server + client concurrently
npm run dev

# Or separately:
npm run server     # Express API on :5000
npm run client     # React app on :3000
```

### 7. Run Data Analysis

```bash
cd analysis
jupyter notebook
# Open any .ipynb file to explore insights
```

---

<br/>

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
# Server
PORT=5000
NODE_ENV=development

# MongoDB
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/learnhub

# Authentication
JWT_SECRET=your_super_secret_jwt_key_here
JWT_EXPIRE=7d

# MySQL (for analysis module)
MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=yourpassword
MYSQL_DATABASE=learnhub_analytics

# Client
REACT_APP_API_URL=http://localhost:5000/api
```

> ⚠️ **Never commit `.env` to version control.** It is already listed in `.gitignore`.

---

<br/>

## 📁 Project Structure

```
Longterm/
│
├── 📂 client/                      # React Frontend
│   ├── public/
│   └── src/
│       ├── components/             # Reusable UI Components
│       │   ├── Navbar.jsx
│       │   ├── CourseCard.jsx
│       │   ├── ProgressBar.jsx
│       │   └── ProtectedRoute.jsx
│       ├── pages/                  # Route-level Pages
│       │   ├── Home.jsx
│       │   ├── Dashboard.jsx
│       │   ├── CourseDetail.jsx
│       │   ├── Login.jsx
│       │   └── Register.jsx
│       ├── context/                # React Context (Auth State)
│       └── App.jsx
│
├── 📂 models/                      # MongoDB Mongoose Schemas
│   ├── User.js
│   ├── Course.js
│   └── Enrollment.js
│
├── 📂 controllers/                 # Route Business Logic
│   ├── authController.js
│   ├── courseController.js
│   └── enrollmentController.js
│
├── 📂 routes/                      # Express API Routes
│   ├── authRoutes.js
│   ├── courseRoutes.js
│   └── enrollmentRoutes.js
│
├── 📂 middleware/                  # Express Middleware
│   ├── authMiddleware.js           # JWT Verification
│   └── errorHandler.js
│
├── 📂 analysis/                    # Data Analysis Module
│   ├── notebooks/
│   ├── sql/
│   ├── exports/
│   └── data_pipeline.py
│
├── 📂 docs/
│   └── screenshots/                # UI Screenshots
│
├── server.js                       # Entry Point
├── .env.example
├── package.json
└── README.md
```

---

<br/>

## 📡 API Endpoints

### 🔐 Auth Routes — `/api/auth`

| Method | Endpoint | Description | Auth |
|--------|----------|-------------|------|
| `POST` | `/register` | Register new user | ❌ |
| `POST` | `/login` | Login & get JWT | ❌ |
| `GET` | `/profile` | Get logged-in user | ✅ |

### 📚 Course Routes — `/api/courses`

| Method | Endpoint | Description | Auth |
|--------|----------|-------------|------|
| `GET` | `/` | Get all courses | ❌ |
| `GET` | `/:id` | Get course by ID | ❌ |
| `POST` | `/` | Create new course | ✅ Admin |
| `PUT` | `/:id` | Update course | ✅ Admin |
| `DELETE` | `/:id` | Delete course | ✅ Admin |

### 📝 Enrollment Routes — `/api/enrollments`

| Method | Endpoint | Description | Auth |
|--------|----------|-------------|------|
| `POST` | `/` | Enroll in a course | ✅ |
| `GET` | `/my` | Get my enrollments | ✅ |
| `PATCH` | `/:id/progress` | Update progress % | ✅ |

---

<br/>

## 🚀 Live Demo

| 🌐 Platform | 🔗 Link |
|------------|--------|
| GitHub Repository | [github.com/vvraghuram/Longterm](https://github.com/vvraghuram/Longterm) |
| Live Demo | *(Deploy to Vercel / Render — link coming soon)* |
| API Docs | *(Postman Collection — link coming soon)* |

> 💡 **Deployment Tip:** Frontend → Vercel · Backend → Render · DB → MongoDB Atlas

---

<br/>

## 🗺️ Roadmap

- [x] User Authentication (JWT)
- [x] Course CRUD Operations
- [x] Enrollment & Progress Tracking
- [x] Responsive React UI
- [x] Data Analysis Module (Python + SQL + Excel)
- [ ] Video Lecture Streaming
- [ ] Payment Gateway Integration
- [ ] Email Notifications (NodeMailer)
- [ ] Admin Panel with Charts
- [ ] Mobile App (React Native)

---

<br/>

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "feat: add your feature description"

# 4. Push to your fork
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

Please follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

---

<br/>

## 👤 Author

<div align="center">

### Veeravalli Venkata Raghu Ram

*B.Tech — Electrical & Electronics Engineering*
*Godavari Institute of Engineering & Technology (GIET), Rajahmundry*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vvraghuram)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vvraghuram)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vraghuram104@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@2in1_gamer)

</div>

---

<br/>

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ If this project helped you or inspired you, please consider giving it a star!**

*Built with ❤️ by [Raghu Ram](https://github.com/vvraghuram)*

</div>
