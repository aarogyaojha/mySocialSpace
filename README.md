# mySocialSpace

**mySocialSpace** is a full-stack social networking application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to connect, share posts, and engage with a community in real-time.

## 🌟 Features

* **User Authentication**: Secure sign-up and login functionality.
* **Profile Management**: Users can create and edit their profiles.
* **Post Creation**: Ability to create, edit, and delete posts.
* **Interactive Feed**: Real-time updates of posts from all users.
* **Commenting System**: Users can comment on posts.
* **Like Functionality**: Users can like and unlike posts.
* **Responsive Design**: Optimized for both desktop and mobile devices.

## 🛠️ Technologies Used

* **Frontend**:

  * React.js
  * Redux (for state management)
  * React Router
  * Axios (for API calls)
  * Bootstrap / Material-UI (for styling)

* **Backend**:

  * Node.js
  * Express.js
  * MongoDB with Mongoose
  * JWT (JSON Web Tokens) for authentication
  * bcrypt.js (for password hashing)

## 📁 Project Structure

```
mySocialSpace/
├── client/             # React frontend
├── server/             # Express backend
├── classifier_server/  # Additional server (e.g., for ML tasks)
├── resources/          # Static assets and resources
├── .gitignore
├── LICENSE
└── README.md
```

## 🚀 Getting Started

### Prerequisites

* Node.js and npm installed
* MongoDB installed and running

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/aarogyaojha/mySocialSpace.git
   cd mySocialSpace
   ```



2. **Install server dependencies**:

   ```bash
   cd server
   npm install
   ```



3. **Install client dependencies**:

   ```bash
   cd ../client
   npm install
   ```



4. **Set up environment variables**:

   Create a `.env` file in the `server` directory with the following content:

   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```



5. **Run the application**:

   In the `server` directory:

   ```bash
   npm start
   ```



In the `client` directory:

```bash
npm start
```



The client will run on `http://localhost:3000` and the server on `http://localhost:5000`.

## 🧪 Testing

To run tests (if implemented), navigate to the respective directories and use:

```bash
npm test
```



## 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/aarogyaojha/mySocialSpace/blob/main/LICENSE) file for details.

---
