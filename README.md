# TASKSPARK
✅ 1) RUN BACKEND (Node + Express)
Open Terminal 1 (PowerShell / CMD)

Go to backend folder:

cd "C:\Users\suhas\OneDrive\Desktop\Task manager\backend"


Install packages (only first time):

npm install


✅ Create .env file in backend folder:
backend/.env

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/taskpulse
JWT_SECRET=taskpulse_super_secret_123
CLIENT_URL=http://localhost:5173


Start backend:

npm run dev


✅ Backend will run at:
👉 http://localhost:5000

✅ 2) RUN MONGODB

Backend needs MongoDB running.

If MongoDB is installed:

Open Terminal 2 and run:

mongod


(Or start MongoDB service from Windows Services)

✅ 3) RUN FRONTEND (React Vite)
Open Terminal 3 (New)

Go to frontend folder:

cd "C:\Users\suhas\OneDrive\Desktop\Task manager\frontend"


Install packages (only first time):

npm install


Start frontend:

npm run dev


✅ Frontend will run at:
👉 http://localhost:5173

✅ 4) OPEN IN BROWSER

Frontend:
👉 http://localhost:5173/auth

✅ Important Notes

✅ Backend terminal must keep running

✅ Frontend terminal must keep running

✅ MongoDB must keep running

If you close any of them → app stops working
