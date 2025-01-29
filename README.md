# Learn With StudyNotion

**Learn With StudyNotion** is a full-stack web application designed to help users easily access and manage learning resources, with features like secure authentication, payment integration, and data visualization. Built with the powerful MERN stack (MongoDB, Express, React, Node.js), this project aims to provide a modern, responsive, and secure learning platform.

## 🚀 Key Features

- **MERN Stack**: MongoDB, Express, React, Node.js for building the full-stack application.
- **Tailwind CSS**: Sleek, responsive UI design with utility-first CSS framework.
- **Authentication & Authorization**: Secure user authentication with JWT (JSON Web Tokens) and role-based authorization.
- **Password Security**: Advanced hashing and encryption (bcrypt) for storing passwords securely.
- **OTP-based Account Verification**: Enhance security and user experience with One-Time Passwords for account verification.
- **RazorPay Integration**: Seamless payment gateway integration to handle payments securely.
- **Shopping Cart**: Fully functional shopping cart for users to manage their purchases.
- **Data Visualization**: Visualize learning statistics with interactive charts using ChartJS.
- **Optimized LocalStorage**: Smooth and efficient navigation and state management through LocalStorage.

## 🛠️ Technologies Used

- **Frontend**:
  - React.js
  - Tailwind CSS
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - JWT (JSON Web Tokens)
  - bcrypt.js for password hashing
  - RazorPay API for payment integration
- **Deployment**:
  - Vercel (Frontend)
  - Render (Backend)
  - GitHub (Code)

## 💻 Installation

### Prerequisites

- Node.js (v14.x or later)
- MongoDB
- npm (Node Package Manager)

### Steps to Run Locally

1. **Clone the repository**:

   ```bash
   git clone https://github.com/bansalrachit19/Learn_With_StudyNotion.git
   cd Learn_With_StudyNotion
   
2. **Install server dependencies**:

   ```bash
   cd server
   npm i

3. **Install frontend dependencies**:

   - In the root directory
     
     ```bash
     npm i

5. **Set up environment variables**:
   - Create a .env file in the server folder and add your database URI, JWT secret, RazorPay API keys (all variables given in .env.example) etc.
   - Create a .env file in root folder with REACT_APP_BASE_URL = http://localhost:<your_server_port_number>/api/v1

4. **Run the Project**:
   
   - your server and frontend will run concurrently
   - can explore scripts in package.json in root directory of project.

     ```bash
     npm run dev

### 📈 Live Demo
You can explore the live version of the application: 
https://learn-with-study-notion-frontend.vercel.app/

### 👨‍💻 Contributing
If you'd like to contribute to the project, feel free to open an issue or create a pull request. Contributions are always welcome!
