# Chat-App

This project is a full-stack chat application built using the MERN (MongoDB, Express.js, React, Node.js) stack, designed to facilitate real-time, bi-directional conversations between users. It simulates a modern messaging platform, offering secure authentication, live chat functionalities, and dynamic online user tracking.

## ✨ Features

* **Secure User Authentication:** Users can securely sign up and log in using JSON Web Tokens (JWT) for robust authentication and route protection.

* **Real-Time Messaging:** Integrated with Socket.IO, the application enables seamless, live communication, allowing users to send and receive messages instantly.

* **Online Status Tracking:** Leverages WebSockets to provide real-time updates on user online/offline status, instantly reflecting presence across all connected clients.

* **Persistent Conversations:** All messages and user data are stored in MongoDB Atlas, a cloud-hosted database, ensuring that conversations are persistent and accessible at any time.

* **Intuitive User Interface:** A responsive and user-friendly interface built with React provides a smooth chat experience.

## 🚀 Technologies Used

* **Frontend:**

    * React.js: For building dynamic and responsive user interfaces.

* **Backend:**

    * Node.js: The JavaScript runtime environment.

    * Express.js: A fast, unopinionated, minimalist web framework for Node.js.

    * Socket.IO: For real-time, bi-directional event-based communication.

* **Database:**

    * MongoDB: A NoSQL database for storing chat messages and user data.

    * MongoDB Atlas: Cloud-hosted database service for scalability and reliability.

* **Authentication:**

    * JSON Web Tokens (JWT): For secure user authentication and authorization.

## 🛠️ Installation and Setup

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js (LTS version recommended)

* MongoDB Atlas account (or a local MongoDB instance)

### Backend Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aanandmrh222/Chat-App](https://github.com/aanandmrh222/Chat-App)
    cd Chat-App/backend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Create a `.env` file** in the `backend` directory and add your environment variables:
    ```
    PORT=5000
    MONGO_URI=your_mongodb_atlas_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```
    * Replace `your_mongodb_atlas_connection_string` with your actual MongoDB Atlas URI.
    * Replace `your_jwt_secret_key` with a strong, random string.
4.  **Start the backend server:**
    ```bash
    npm start
    ```

### Frontend Setup

1.  **Navigate to the frontend directory:**
    ```bash
    cd ../frontend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Create a `.env` file** in the `frontend` directory (if needed, for example, if your backend runs on a different port than default):
    ```
    REACT_APP_BACKEND_URL=http://localhost:5000
    ```
4.  **Start the frontend development server:**
    ```bash
    npm run dev
    ```

The application should now be running on `http://localhost:3000` (frontend) and `http://localhost:5000` (backend API).

## 💡 Learning Outcomes

This project provided invaluable hands-on experience in:

* Building robust real-time systems using WebSockets and Socket.IO.

* Managing bi-directional communication between clients and servers.

* Implementing secure authentication flows with JWT.

* Working with cloud-hosted databases like MongoDB Atlas for persistent data storage.

* Developing full-stack applications from scratch using the MERN stack.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project

2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)

3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)

4.  Push to the Branch (`git push origin feature/AmazingFeature`)

5.  Open a Pull Request
