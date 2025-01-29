# Realtime Chat App (MERN + Socket.io)

A **real-time chat application** built with the **MERN stack**, featuring **Socket.io** for instant messaging, **JWT authentication**, and **Zustand** for state management. Styled using **TailwindCSS + Daisy UI** and deployed for **FREE**!  

---

## 🌟 Features  
- ✅ **Authentication & Authorization** (JWT)  
- ✅ **Real-time messaging** with **Socket.io**  
- ✅ **Online user status** tracking
- ✅ **Profile photos & image sharing** via **Cloudinary**  
- ✅ **Global state management** using **Zustand**  
- ✅ **Responsive UI** with **TailwindCSS + Daisy UI**  
- ✅ **Error handling** (both client & server)  

---

## 🛠 Tech Stack  
- **Frontend**: React.js, TailwindCSS, Daisy UI, Zustand  
- **Backend**: Node.js, Express.js, MongoDB  
- **Real-time Communication**: Socket.io  
- **Authentication**: JSON Web Tokens (JWT)
- **Image Uploads & Storage**: Cloudinary  
- **Deployment**: Render

---

## 🎯 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/amank1902/chat_app.git
cd chat-app
```

### 2️⃣ Install Dependencies
🔹 Backend
```bash
cd backend
npm install
```
🔹 Frontend
```bash
cd frontend
npm install
```
3️⃣ Set Up Environment Variables
Create a .env file in the backend/ folder and configure:
```bash
PORT = 5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

```
## 🚀 Running the App

🔹 Start the Backend
```bash
cd backend
npm start
```
🔹 Start the Frontend
```bash
cd frontend
npm run dev
```
The app will be running at http://localhost:5173 🚀
