## Installation

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [Git](https://git-scm.com/)

### Steps to Run Locally
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/hotel-management-app.git
   cd hotel-management-app
   ```

2. **Install Dependencies**:
   - For the Backend:
     ```bash
     cd backend
     npm install
     ```
   - For the Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up Environment Variables**:
   - In the `backend` folder, create a `.env` file and add:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     PORT=5000
     ```

4. **Start the Application**:
   - Start MongoDB server locally or use an online database service like MongoDB Atlas.
   - Run the backend server:
     ```bash
     cd backend
     npm run dev
     ```
   - Run the frontend server:
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000` for the frontend.

---

## Folder Structure
```
hotel-management-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
├── README.md
└── p
