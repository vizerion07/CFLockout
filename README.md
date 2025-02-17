# CfLockOut

## 🚀 Overview
CfLockOut is a web-based platform designed to facilitate competitive coding contests using the **Lockout Format**, where two users compete against each other to solve problems quickly and efficiently. Built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js), CfLockOut provides a seamless user experience for Codeforces users.

## ✨ Features
- **Competitive Lockout Mode**: Users can challenge each other in a one-on-one coding battle.
- **Codeforces Integration**: Fetches problems dynamically from Codeforces API.
- **Real-time Updates**: Uses WebSockets for instant updates on match status.
- **User Authentication**: Secure login and authentication system.
- **Leaderboard & Stats**: Track rankings and performance.
- **Responsive UI**: Optimized for both desktop and mobile devices.

## 🏗️ Tech Stack
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **APIs**: Codeforces API, WebSockets

## 🔧 Installation & Setup

Follow these steps to set up CfLockOut on your local machine:

### 1️⃣ Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [Git](https://git-scm.com/)

### 2️⃣ Clone the Repository
```sh
$ git clone https://github.com/prayutsu/cflockout.git
$ cd cflockout
```

### 3️⃣ Set Up Environment Variables
- Duplicate `.env.example` and rename it to `.env`
- Update the required variables, including `MONGO_URI` and authentication keys.

### 4️⃣ Install Dependencies
#### Install Backend Dependencies
```sh
$ cd server
$ npm install
```
#### Install Frontend Dependencies
```sh
$ cd ../client
$ npm install
```

### 5️⃣ Run the Application
#### Start the Backend Server
```sh
$ cd server
$ npm start
```
#### Start the Frontend Client
```sh
$ cd ../client
$ npm start
```

### 6️⃣ Open the App
Visit [http://localhost:3000](http://localhost:3000) in your browser.

## 🛠️ Usage Guide
1. Sign up or log in with your Codeforces account.
2. Create or join a Lockout match.
3. Compete by solving Codeforces problems before your opponent.
4. Track your progress on the leaderboard.

## 🤝 Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch (`feature/your-feature`)
3. Commit your changes and push to your fork.
4. Open a pull request.

## 📩 Contact
For any queries or feedback, feel free to reach out:
- **GitHub**: [@vizerion07](https://github.com/vizerion07)

---
### 🌟 Don't forget to star the repository if you like this project! ⭐

