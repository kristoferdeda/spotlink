# 🚗 SpotLink

**SpotLink** is a point-based parking exchange platform where users can list, book, and manage parking spots in real time. The app uses geolocation and a live map to help users find available spots nearby and communicate instantly through built-in chat.

🔗 **Live Website**: [https://spotlink-frontend.onrender.com](https://spotlink-frontend.onrender.com)

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, TailwindCSS, Google Maps JavaScript API, Socket.IO Client
- **Backend**: Node.js, Express, MongoDB, Mongoose, JWT, Socket.IO
- **Deployment**: Render (both frontend and backend), GitHub for version control

---

## 📦 Backend Highlights

- JWT-based authentication
- MongoDB for storing users, parking spots, and chat messages
- WebSocket support using Socket.IO for real-time chat
- API endpoints for:
  - Register/login
  - List/search/book parking spots
  - View and clear chat conversations

---

## 🖼️ Frontend Highlights

- Interactive Google Map for listing and booking spots
- Real-time messaging with unread indicators
- Location-based search and "use my location" support
- Responsive design with Tailwind CSS

---

## 🚀 Deployment Notes

- **Frontend**: Deployed as a static site on Render with proper `_redirects` rule for React Router.
- **Backend**: Deployed as a web service on Render with WebSocket support enabled.

---

## 📂 Getting Started Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/kristoferdeda/spotlink.git
   cd spotlink
2. Set up backend:
   ```bash
   cd spotlink-backend
   npm install
   npm run dev

4. Set up frontend:
   ```bash
   cd spotlink-frontend
   npm install
   npm run dev

5. Create .env files for both with required API keys and database URLs.

