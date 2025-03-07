# Task Management System  

**Disclaimer**
This system relies on caching for optimal performance. Ensure that caching is enabled for proper functionality.*

**Deployed Link:** [Task Management System](https://task-management-system-frontend-two.vercel.app/)  

## Installation  

### 1. Clone the Repository  
Run the following command to clone the repository:  
```bash
git clone https://github.com/adityadixit29/task-management-system.git
```

### 2. Set Up the Frontend  
Navigate to the frontend directory:  
```bash
cd frontend
```
Modify the server URL inside `main.jsx` (located in the `src` folder):  
```js
export const server = "https://mytodos-skie.onrender.com/api/v1";
```
Run the frontend development server:  
```bash
npm install
npm run dev
```

### 3. Set Up the Backend  
Navigate to the backend directory:  
```bash
cd backend
```
Create a `.env` file in the `backend` folder and add the following environment variables:  
```env
PORT=4000
JWT_SECRET=dskfhdhkhsdkfh
NODE_ENV=Development
FRONTEND_URL=http://localhost:5173
MONGO_URI=mongodb://localhost:27017
```
Install dependencies and start the backend server:  
```bash
npm install
npm start
```

### 4. Usage  
- As a new user, you need to **sign up** first.  
- After signing in, you can **create and manage tasks**.

---

