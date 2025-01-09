# 🚀 Full Stack Blog Platform

Modern blog platform built with React and Hono.js

## ⚡ Tech Stack

### Frontend
- ⚛️ **React** with Vite
- 🛣️ **React Router** for navigation
- 🎨 **Material UI** for components
- 🔄 **Axios** for API calls

### Backend
- 🎯 **Hono.js** - Web Framework
- 🔋 **Prisma** - ORM
- 🗄️ **Neon DB** - Postgres Database
- 🔑 **JWT** - Authentication

## ⏱️ Implementation Timeline

### Backend Development 
1. **Initial Setup** 
   - Backend initialization
   - Handler configuration

2. **Database** 
   - Prisma setup
   - Schema design
   - Client initialization

3. **API Routes** 
   - Authentication
   - Blog endpoints
   - Middleware
   - Testing

### Frontend Development 
1. **Setup & Auth**
   - Router configuration
   - Auth components
   - Sign up/in implementation
   - Testing

2. **Blog Features** 
   - Blog components
   - Navigation bar
   - Backend integration
   - Full blog view
   - Publishing interface

3. **UI Polish** 
   - Loading states
   - Deployment
   - GitHub push

## 🚀 Getting Started

### Backend Setup
```bash
cd backend
npm install
cp .env.example .env
npx prisma generate
npx prisma db push
npm run dev
```

### Frontend Setup
```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

## 🔑 Environment Variables

### Backend `.env`
```env
DATABASE_URL="neon-db-connection-string"
JWT_SECRET="jwt-secret"
```

### Frontend `.env`
```env
VITE_API_URL="backend-url"
```

## 📝 Features

### Authentication
- User registration
- Login/Logout
- JWT token management

### Blog Management
- View all blogs
- Read full blog
- Create new blog
- Edit/Delete blogs
- Loading states

## 🔒 API Routes

### Public
- `GET /api/posts` - List blogs
- `GET /api/posts/:id` - Single blog
- `POST /api/auth/register` - Register
- `POST /api/auth/login` - Login

### Protected
- `POST /api/posts` - Create blog
- `PUT /api/posts/:id` - Update blog
- `DELETE /api/posts/:id` - Delete blog

## 🧪 Testing

```bash
# Backend tests
cd backend && npm test

# Frontend tests
cd frontend && npm test
```

## 📈 Performance
- Server-side connection pooling
- React component optimization
- Loading states for better UX

## 📜 License
MIT

---
Made with ❤️ using React & Hono.js
