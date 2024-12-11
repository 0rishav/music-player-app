# Music Player App 🎶

## About the Project  
Music Player App is a feature-rich application that provides an immersive music experience.  
- Users can create and manage playlists effortlessly.  
- Supports both offline and online playback modes.  
- Designed to deliver high-quality audio output.  

## Time Duration  
**Development Period:**  
```plaintext
1st December 2024 – 10th December 2024
```

# How to Run the Project
This project has two main parts:

**Frontend** - Handles the user interface.
**backend** - Manages the server-side logic and APIs.

### 1. Clone the Repository  
Run the following command to clone the repository:  
```bash
https://github.com/0rishav/music-player-app.git
cd music-player-app
```

### 2. Set Up the Environment Variables  
 **backend** require environment variables.

#### Backend Environment Variables  
Create a `.env` file in the `backend/` folder and add the following variables:

```env
PORT=8000
MONGO_URL=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret-key
```

### 3. Install Dependencies  
To install the necessary dependencies for both the **frontend** and **backend**, follow these steps:

#### For Backend  
Navigate to the `backend/` directory and install the dependencies:

```bash
cd backend
npm install
```

#### For Frontend
Navigate to the `frontend/` directory and install the dependencies:

```bash
cd frontend
npm install
```

### Start the Frontend Development Server  
Navigate to the `frontend/` folder and run the following command to start the frontend development server:

```bash
npm run dev
```

### Start the Backend Development Server  
Navigate to the `frontend/` folder and run the following command to start the frontend development server:

```bash
Nodemon index.js
```

### Technologies Used  

#### Frontend:  
- **React**  
- **Axios** for HTTP requests  
- **React Router** for navigation  

#### Backend:  
- **Node.js** with **Express**  
- **MongoDB** for data storage  

#### Other Tools:   
- **CORS** for handling cross-origin requests  
- **Dotenv** for managing environment variables  


