# BuildMyCV - Resume Builder

A full-stack web application for creating, editing, and managing professional resumes with multiple templates and PDF export functionality.

## 🚀 Features

- **User Authentication**: Secure signup and login system
- **Resume Creation**: Easy-to-use form-based resume builder
- **Multiple Templates**: Choose from various professional resume templates
- **Real-time Editing**: Live preview while editing your resume
- **PDF Export**: Download your resume as a PDF file
- **Dashboard**: Manage all your resumes in one place
- **Image Upload**: Add profile pictures and other images
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Tech Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **JWT** - Authentication
- **bcryptjs** - Password hashing
- **multer** - File upload handling

### Frontend
- **React** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling framework
- **Axios** - HTTP client
- **React Router** - Client-side routing
- **html2pdf.js & jsPDF** - PDF generation
- **React Hot Toast** - Notifications

## 📋 Prerequisites

Before running this application, make sure you have the following installed:

- **Node.js** (v16 or higher)
- **MongoDB** (local installation or MongoDB Atlas)
- **npm** or **yarn**

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/BuildMyCV.git
   cd BuildMyCV
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Set up environment variables**

   Create a `.env` file in the `backend` directory:
   ```env
   JWT_SECRET=your_jwt_secret_key
   MONGODB_URI=mongodb://localhost:27017/Resume
   ```

5. **Start MongoDB**

   Make sure MongoDB is running on your system:
   ```bash
   # On Windows
   net start MongoDB

   # Or use MongoDB Compass/Atlas
   ```

## 🚀 Running the Application

1. **Start the backend server**
   ```bash
   cd backend
   npm start
   ```
   The backend will run on `http://localhost:4000`

2. **Start the frontend development server**
   ```bash
   cd frontend
   npm run dev
   ```
   The frontend will run on `http://localhost:5173`

3. **Open your browser**

   Navigate to `http://localhost:5173` to use the application.

## 📖 Usage

1. **Sign Up**: Create a new account or log in if you already have one
2. **Dashboard**: View all your created resumes
3. **Create Resume**: Click "Create New Resume" to start building
4. **Edit Resume**: Fill in your personal information, work experience, education, etc.
5. **Choose Template**: Select from available resume templates
6. **Preview & Download**: Preview your resume and download as PDF

## 🏗️ Project Structure

```
BuildMyCV/
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── resumeController.js
│   │   └── uploadImages.js
│   ├── middlewares/
│   │   ├── authMiddleware.js
│   │   └── uploadMiddleware.js
│   ├── models/
│   │   ├── Resume.js
│   │   └── User.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── resumeRoutes.js
│   ├── uploads/
│   ├── package.json
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── package.json
│   ├── vite.config.js
│   └── README.md
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

If you have any questions or suggestions, feel free to open an issue or contact the maintainers.

---

**Happy Resume Building! 🎉**
