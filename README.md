# 💬 Real-Time Chat Engine | Full-Stack MERN

A high-performance, real-time communication platform built with the MERN stack. This project focuses on solving the "Latency Gap" using Optimistic UI updates and persistent WebSocket connections, ensuring a seamless, zero-lag user experience.



## 🚀 Key Features

* **Real-Time Messaging:** Instant message delivery using Socket.io with bi-directional communication.
* **Optimistic UI:** Messages appear instantly on the sender's screen before database confirmation, eliminating perceived latency.
* **Presence Tracking:** Real-time "Online/Offline" status updates using a dynamic server-side socket map.
* **Media Support:** Image sharing powered by Cloudinary integration and Base64 processing.
* **Auth System:** Secure JWT-based authentication stored in `httpOnly` cookies to prevent XSS/CSRF attacks.
* **Responsive Design:** Fully mobile-responsive UI built with Tailwind CSS and DaisyUI.

## 🛠️ Tech Stack

**Frontend:** React.js, Zustand (State Management), Tailwind CSS, DaisyUI, Axios.
**Backend:** Node.js, Express.js, Socket.io.
**Database:** MongoDB (Mongoose ODM).
**Authentication:** JWT (JSON Web Tokens) with Cookie-based storage.


## 🚦 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas Account
- Cloudinary Account (for image uploads)

### Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/chat-engine.git](https://github.com/your-username/chat-engine.git)
   cd chat-engine
2. **Setup Environment Variables Create a .env file in the root directory:**
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   CLOUDINARY_CLOUD_NAME=your_name
   CLOUDINARY_API_KEY=your_key
   CLOUDINARY_API_SECRET=your_secret
   CLOUDINARY_API_SECRET=your_secret
   PORT=5001
   CLOUDINARY_API_SECRET=your_secret
   NODE_ENV=development
3. **Install Dependencies**
   ```
   npm install
   cd frontend && npm install
4. **Run the Application**
   ```
   # From the root directory
   npm run dev
