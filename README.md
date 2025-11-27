# Backend API

Production-ready backend with Node.js, Express, JWT, MongoDB Atlas

## 📦 Install Dependencies

```bash
npm install express mongoose bcryptjs jsonwebtoken cors dotenv
npm install nodemon --save-dev
```

## 🚀 Run Server

Development:
```bash
npm run dev
```

Production:
```bash
npm start
```

## 🔐 Environment Variables

Create `.env` file:

```
PORT=5000
MONGODB_URI=mongodb+srv://jithingowda51_db_user:DdqHwv7UTTbIiIh8@backend.pjrplny.mongodb.net/auth_db?retryWrites=true&w=majority
JWT_SECRET=your-secret-key-change-in-production
REFRESH_SECRET=your-refresh-secret-key-change-in-production
TOKEN_EXPIRES_IN=15m
REFRESH_EXPIRES_IN=7d
```

## 📡 API Endpoints

### Public Routes
- POST `/api/auth/register` - Register user
- POST `/api/auth/login` - Login user
- POST `/api/auth/refresh` - Refresh access token

### Protected Routes
- GET `/api/auth/profile` - Get user profile
- POST `/api/auth/logout` - Logout user

## 🌐 Git Commands

```bash
git init
git add .
git commit -m "Initial backend"
git remote add origin https://github.com/username/repo.git
git push -u origin main
```

Update:
```bash
git add .
git commit -m "Updated backend"
git push
```

## 🚀 Render Deployment

Build Command:
```
npm install
```

Start Command:
```
npm start
```

Environment Variables (Add in Render):
```
PORT=10000
MONGODB_URI=mongodb+srv://jithingowda51_db_user:DdqHwv7UTTbIiIh8@backend.pjrplny.mongodb.net/auth_db?retryWrites=true&w=majority
JWT_SECRET=your-secret-key-change-in-production
REFRESH_SECRET=your-refresh-secret-key-change-in-production
TOKEN_EXPIRES_IN=15m
REFRESH_EXPIRES_IN=7d
```

