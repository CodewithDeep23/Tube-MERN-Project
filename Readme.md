# 🔥 TubeEngine (YouTube x Twitter)

**TubeEngine** is a MERN stack project that combines core functionalities of **YouTube (videos, subscriptions, playlists)** and **Twitter (tweets, likes, comments)** into one robust API. Built using **Node.js**, **React, **Express**, and **MongoDB**, it provides RESTful endpoints for media-based applications.

---

## 🌐 Resources

| Resource            | Link                                                                 |
|---------------------|----------------------------------------------------------------------|
| 🧪 Postman Docs     | [View API Documentation](https://documenter.getpostman.com/view/39785896/2sB2izDt48) |
| 🧠 DB Schema Model  | [Eraser Diagram](https://app.eraser.io/workspace/OJQXZCrbUtiEVt8QAo5G) |
| 🚀 Live Frontend    | [View on Vercel](https://tube-mern-project.vercel.app/)              |

---

## 🔥 Features

### 👤 User Management
- Signup, login, logout, change password
- JWT-based authentication
- Avatar & profile updates
- Watch history tracking and clearing
- Liked video tracking

### 🎥 Video Handling
- Upload & publish/unpublish videos
- Delete/edit videos
- Search & pagination support
- Cancel upload with auto-cleanup
- Stream in various resolutions

### 🐦 Tweet System
- Post, update, delete tweets
- Like/dislike tweets
- View all tweets by user

### 🔔 Subscriptions
- Subscribe/unsubscribe to channels
- View subscribers and subscriptions

### 🎶 Playlists
- Create, update, delete playlists
- Add/remove videos from playlist (with undo)

### ❤️ Likes & Comments
- Like/unlike videos, tweets, comments
- Add/update/delete comments on videos

### 📊 Dashboard Stats
- View video/channel stats (views, likes, comments)
- Detailed data on uploaded videos

### 🩺 Health Check
- GET `/healthcheck` — returns `{ status: "Ok" }` to verify server health

---

## 🧰 Tech Stack

- ⚛️ **Frontend**: React, Axios, React Router, Tailwind CSS  
- 🛠️ **Backend**: Node.js, Express.js  
- 🗄️ **Database**: MongoDB + Mongoose  
- 🔐 **Authentication**: JWT (JSON Web Tokens)  
- ☁️ **Media Storage**: Cloudinary (for video/image handling)  
- 🧪 **API Testing**: Postman  
- 🚀 **Frontend Deployment**: Vercel  
- 🔧 **Backend Deployment**: Render 

---

## 📦 Installation and Setup

### 🔧 Backend Setup  and 💻 Frontend Setup (React)

1. **Clone the repository:**

    ```bash
    git clone https://github.com/CodewithDeep23/Tube-MERN-Project
    ```

2. **Install dependencies For Backend:**
    ```bash
    cd Tube-Backend
    npm install
    ```

3. **Install dependencies For Frontend:**
    ```bash
    cd Tube-Frontend
    npm install
    ```

4. **Set up environment variables:**
    Create a `.env` file in the root of the project and fill in the required values using the `.env.sample` file.

5. **Start the server:**
    ```bash
    npm run dev
    ```

---

## 🙏 Acknowledgments

Thanks to all my instructors.

## 📝 Credits & Acknowledgments

This project is inspired by the tutorials from [ChaiAurCode](https://www.youtube.com/@chaiaurcode). Big thanks for the valuable content and guidence.