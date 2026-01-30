# 💰 BDJOBBOX Client - Job Portal Frontend

A modern, responsive React application for BDJOBBOX, a comprehensive job portal system. Built with React 18, Vite, Tailwind CSS, and React Router.

## 🌐 Live URL

- **Frontend:** [https://bdjobbox-client.vercel.app](https://bdjobbox-client.vercel.app)
- **Backend API:** [https://bdjobbox-server.vercel.app](https://bdjobbox-server.vercel.app)

---

## 🎯 Overview

BDJOBBOX Client is a feature-rich, production-ready frontend application that connects job seekers with employers. It features role-based dashboards, job posting capabilities, application management, and a clean, responsive user interface.

### Key Highlights

- ✅ **Modern UI/UX** - Built with Tailwind CSS and Responsive Design
- ✅ **Role-Based Dashboards** - Separate interfaces for Job Seekers, Employers, and Admins
- ✅ **Job Management** - Post, edit, and manage job listings
- ✅ **Application Tracking** - Track job applications and status
- ✅ **Form Validation** - React Hook Form for robust form handling
- ✅ **Real-Time Feedback** - React Toastify for notifications
- ✅ **Secure Authentication** - JWT-based authentication
- ✅ **Responsive Design** - Mobile-first approach

---

## 🚀 Features

### 🔐 Authentication

- **Sign In/Sign Up** - Secure authentication with JWT
- **Role Selection** - Register as Job Seeker, Employer, or Admin
- **Session Management** - Secure token storage

### 👨‍💼 Job Seeker Features

- **Browse Jobs** - View and filter available job listings
- **Apply for Jobs** - Submit applications to posted jobs
- **Saved Jobs** - Bookmark interesting opportunities
- **Applied Jobs History** - Track status of past applications
- **Profile Management** - Update personal information and resume

### 🏢 Employer Features

- **Post Jobs** - Create detailed job listings
- **Manage Jobs** - Edit or remove job posts
- **View Applications** - Review candidates for posted jobs
- **Company Profile** - Manage company information

### 👮 Admin Features

- **Job Monitoring** - View and manage all job postings
- **User Management** - Oversee all registered users (Employers & Seekers)
- **Dashboard Overview** - System-wide statistics
- **Content Moderation** - Ensure quality of listings

### 🎨 Shared Features

- **Home Page** - Featured jobs and companies
- **Company Directory** - Browse top hiring companies
- **Contact & About** - Information and support pages
- **Responsive Navigation** - Intuitive routing

---

## 🛠️ Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **React** | UI framework | v18.x |
| **Vite** | Build tool | v5.x |
| **Tailwind CSS** | Styling | v4.x |
| **React Router** | Routing | v7.x |
| **Axios** | HTTP client | v1.x |
| **React Hook Form** | Form handling | v7.x |
| **React Toastify** | Notifications | v11.x |
| **React Icons** | Icons | v5.x |
| **Date-fns** | Date formatting | v4.x |

---

## 📁 Project Structure

```
BDJOBBOX-Client/
├── src/
│   ├── pages/                # Page components
│   │   ├── Admin/            # Admin dashboard pages
│   │   ├── Employer/         # Employer dashboard pages
│   │   ├── JobSeeker/        # Job Seeker pages
│   │   ├── Auth/             # Authentication pages
│   │   ├── Home/             # Landing page
│   │   ├── JobList/          # Job listing pages
│   │   ├── Profile/          # User profile components
│   │   └── CompaniesPage/    # Company directory
│   ├── components/           # Reusable UI components
│   ├── layout/               # Layout wrappers (Main, Dashboard)
│   ├── Router/               # Route configuration (AllRoutes.jsx)
│   ├── hooks/                # Custom React hooks
│   ├── assets/               # Static assets (images, icons)
│   ├── App.jsx               
│   └── main.jsx
├── public/                   # Static public assets
├── .env                      # Environment variables
├── vite.config.js
└── package.json
```

---

## 🚦 Routes

### Public Routes

| Path | Component | Description |
|------|-----------|-------------|
| `/` | Home | Landing page |
| `/jobsAll` | JobList | Browse all jobs |
| `/companies` | CompaniesPage | Company directory |
| `/signIn` | SignIn | User login |
| `/signUp` | SignUpFlow | User registration |
| `/about` | AboutPage | About BDJOBBOX |
| `/contact` | ContactPage | Contact support |

### Protected Dashboard Routes

| Path | Description | Access |
|------|-------------|--------|
| `/dashboard/post-job` | Post a new job | Employer |
| `/dashboard/jobs` | Manage posted jobs | Employer |
| `/dashboard/applications` | View received applications | Employer |
| `/dashboard/appliedJobs` | View applied jobs | Job Seeker |
| `/dashboard/saved` | View saved jobs | Job Seeker |
| `/dashboard/allJobs` | Manage all system jobs | Admin |
| `/dashboard/allUsers` | Manage all users | Admin |

---

## ⚙️ Environment Variables

Create a `.env` file in the frontend root directory to configure the API connection:

```env
# API Configuration (Example)
VITE_API_BASE_URL=http://localhost:9000
```

> **Note:** Ensure this matches your running backend server URL.

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Farhad25906/BDJOBBOX-Client
   cd BDJOBBOX-Client/frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file as shown above.

4. **Run development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

The app will start on `http://localhost:5173`

---

## 🎮 Demo Usage

To test the application, you can register new accounts with different roles:

1. **Job Seeker**: Register to browse and apply for jobs.
2. **Employer**: Register to post jobs and manage applications.
3. **Admin**: (Requires database verification or specific setup).

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the ISC License.

---

## 👨‍💻 Author

**Farhad Hossen**
- GitHub: [@Farhad25906](https://github.com/Farhad25906)
- Email: farhadhossen2590@gmail.com

---

## 📞 Support

For support, email farhadhossen2590@gmail.com.
