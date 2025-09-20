# Chat Application

A full-stack real-time chat application built with Node.js, Express, Socket.io, and React. This project supports user authentication, messaging, media sharing, and even a simple game feature.

---

## Features

- **User Authentication:** Sign up and log in securely.
- **Real-Time Messaging:** Chat instantly with other users.
- **Media Support:** Send images, documents, audio, and video.
- **User Search:** Find and start conversations with other users.
- **Profile Viewer:** View and update your profile.
- **Game Feature:** Play a simple game with other users.
- **Status Updates:** See user statuses and activity.
- **Responsive UI:** Works well on desktop and mobile.

---

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- MongoDB (local or cloud)

### Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/chat-application.git
   cd chat-application/ashwani
   ```

2. **Backend Setup:**
   - Go to the backend folder:
     ```
     cd backend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Create a `.env` file (see `.env.txt` for required variables):
     ```
     cp ../.env.txt .env
     # Edit .env and fill in your values
     ```
   - Start the backend server:
     ```
     npm start
     ```

3. **Frontend Setup:**
   - Go to the frontend folder:
     ```
     cd ../frontend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Create a `.env` file (see `.env` for required variables):
     ```
     cp .env.example .env
     # Edit .env and fill in your values
     ```
   - Start the frontend:
     ```
     npm run dev
     ```

---

## Environment Variables

**Backend (`backend/.env`):**
- `MONGO_URI` - MongoDB connection string
- `JWT_SECRET` - Secret for JWT authentication
- `PORT` - Server port

**Frontend (`frontend/.env`):**
- `VITE_API_URL` - Backend API URL

*Do not share your `.env` files publicly.*

---

## Folder Structure

- `backend/` - Node.js/Express API, Socket.io server, authentication, controllers, models
- `frontend/` - React app, components, context, hooks, assets
- `public/` - Static files for frontend
- `src/` - Main React source code

---

## Author

Ashwani Kumar Chaurasiya

---

## License

MIT License

Copyright (c) 2025 Ashwani Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## Contact

For questions or feedback, reach out to [Ashwani Kumar Chaurasiya](mailto:ashwani763400@gmail.com).