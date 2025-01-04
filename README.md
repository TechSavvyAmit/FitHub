<p align="center">
  <img src="https://github.com/TechSavvyAmit/FitHub/blob/main/logo192.png" alt="FitHub Logo" width="150">
</p>

# FitHub 🏋️‍♀️

FitHub is a fitness tracking platform built using the MERN stack, where users can manage their workout plans. It provides secure user authentication with JWT, password hashing using bcrypt with salt, and full CRUD functionality for workout management.

---

## Features ✨

- **Authentication & Security**:
  - User login and signup with JWT-based authentication.
  - Passwords are hashed using bcrypt with added salt for security.

- **Workout Management**:
  - **Create**: Add new workouts to your fitness plan.
  - **Read**: View all workouts linked to your account.
  - **Update**: Modify existing workout details.
  - **Delete**: Remove workouts you no longer need.

- **Personalized**: All workouts and data are securely linked to the authenticated user.

---

## Technologies Used 🛠️

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT), bcrypt
- **Styling**: CSS 
  
---

## Screenshots 📸

Take a look at the key features of FitHub through these screenshots:

---

### Authentication Screens
<p align="center">
  <img src="https://raw.githubusercontent.com/TechSavvyAmit/FitHub/main/images/Screenshot%202025-01-04%20195744.png" alt="Authentication Screenshot" width="500" style="border: 3px solid black;">
</p>

---

### Workouts Added
<p align="center">
  <img src="https://github.com/TechSavvyAmit/FitHub/blob/main/images/Screenshot%202025-01-04%20195651.png" alt="Workouts Added" width="500" style="border: 3px solid black;">
</p>

---

### Edit Workout
<p align="center">
  <img src="https://github.com/TechSavvyAmit/FitHub/blob/main/images/Screenshot%202025-01-04%20195730.png" alt="Edit Workout" width="500" style="border: 3px solid black;">
</p>

---

### Different User
<p align="center">
  <img src="https://github.com/TechSavvyAmit/FitHub/blob/main/images/Screenshot%202025-01-04%20195925.png" alt="Another User's Screenshot" width="500" style="border: 3px solid black;">
</p>

---

## Installation & Setup 🚀

Follow the steps below to set up and run the project locally:

### Prerequisites
Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [Git](https://git-scm.com/)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/FitHub.git
   cd FitHub
   ```

2. **Install Dependencies**:
   - Navigate to the backend folder and install server dependencies:
     ```bash
     cd backend
     npm install
     ```
   - Navigate to the frontend folder and install client dependencies:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the `backend` folder with the following keys:
     ```
     PORT=5000
     MONGO_URI=your-mongodb-connection-string
     SECRET=your-secret-key
     ```

4. **Start the Application**:
   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application**:
   - Open your browser and navigate to `http://localhost:3000`.

---

## API Endpoints 🐂

### **Authentication**
- `POST /api/auth/signup`: Register a new user.
- `POST /api/auth/login`: Login and receive a token.

### **Workout Management**
- `GET /api/workouts`: Fetch all workouts of the authenticated user.
- `POST /api/workouts`: Create a new workout.
- `PUT /api/workouts/:id`: Update an existing workout.
- `DELETE /api/workouts/:id`: Delete a workout.

---

## Contribution 🛠️

We welcome contributions! Follow these steps to get started:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

---

## Feedback & Support 💬

We'd love to hear from you! If you come across any issues, or if you have any suggestions to make things better, don't hesitate to share your thoughts. Open an [Issue](https://github.com/TechSavvyAmit/FitHub/issues) or reach out directly via email at [amitk70200@gmail.com](mailto:amitk704200@gmail.com). Your feedback helps us grow and improve!

---

### Thank You for Checking Out **FitHub**! Let's stay fit and productive! 💪
