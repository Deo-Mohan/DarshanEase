# 🙏 DarshanEase

DarshanEase is a premium, all-in-one spiritual travel platform designed to simplify pilgrimage journeys across India. It empowers devotees to seamlessly book Darshan slots, travel tickets (bus, train, flight), and manage their spiritual itinerary through a unified, aesthetically pleasing interface.

## ✨ Key Features

- **🚠 Journey Planner**: A comprehensive booking engine for Darshan slots, buses, trains, and flights.
- **🤖 Spiritual Chatbot**: An intelligent AI assistant to answer spiritual queries and guide users through the platform.
- **🕉️ Immersive Experience**: Premium 3D visualizations (Three.js), ambient audio, and smooth animations (Framer Motion).
- **📍 Interactive Temple Maps**: Explore temple locations and nearby services with integrated Leaflet maps.
- **📊 Real-time Notifications**: Stay updated with booking statuses and spiritual alerts.
- **📱 Responsive Dashboard**: Dedicated portals for Users, Organizers, and Admins to manage bookings and services.
- **📜 Mantra Scroll**: A dynamic, scrolling interface for spiritual chants and verses.

## 🛠️ Technology Stack

### Frontend
- **Framework**: React.js with Vite
- **Styling**: Vanilla CSS, Bootstrap, TailwindCSS (for utility)
- **3D Graphics**: Three.js, @react-three/fiber, @react-three/drei
- **Animations**: Framer Motion, React Spring
- **Mapping**: Leaflet, React Leaflet
- **Data Visualization**: Recharts
- **State/Routing**: React Router DOM, Context API

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (Mongoose ODM)
- **File Handling**: Multer for image/document uploads
- **Communication**: CORS, Axios

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16.x or higher)
- [MongoDB](https://www.mongodb.com/) (Local or Atlas)

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd Darshan-Ease
   ```

2. **Frontend Setup**
   ```bash
   cd Frontend
   npm install
   npm run dev
   ```
   *The app will be available at `http://localhost:5173`*

3. **Backend Setup**
   ```bash
   cd ../backend
   npm install
   # Ensure your MongoDB URI is configured in server.js or a .env file
   npm start
   ```
   *The server will run on `http://localhost:7000`*

## 📁 Project Structure

```text
Darshan Ease/
├── Frontend/           # React + Vite application
│   ├── src/
│   │   ├── Components/ # UI components (Home, Chatbot, Planner, etc.)
│   │   ├── Admin/      # Admin dashboard modules
│   │   ├── Users/      # User booking and profile modules
│   │   └── Organizer/  # Temple/Service organizer modules
│   └── public/         # Static assets
└── backend/            # Express.js + Mongoose backend
    ├── models/         # MongoDB Schemas
    ├── routes/         # API endpoints
    ├── controllers/    # Business logic
    └── config/         # Database configuration
```

## 📜 License

This project is licensed under the ISC License.
