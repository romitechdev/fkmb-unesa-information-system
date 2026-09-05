# FKMB UNESA - Information System

Information system for the UNESA Banyuwangi Student Family Forum (Forum Keluarga Mahasiswa Banyuwangi UNESA).

## Project Structure

```
fkmb/
├── frontend/    # React + Vite + TypeScript
└── backend/     # Express + TypeScript + Drizzle ORM
```

## Tech Stack

### Frontend
- React 19 + TypeScript
- Vite 7 (bundler)
- TailwindCSS 4
- React Router DOM
- Axios
- Recharts (charts)
- react-hot-toast

### Backend
- Express.js
- TypeScript
- Drizzle ORM
- PostgreSQL
- JWT Authentication
- Multer (file upload)

## Deployment

### Frontend (Vercel)
Deploy the frontend directly to Vercel. Set the environment variable:
- `VITE_API_URL`: backend API URL

### Backend
The backend must be deployed separately on a platform that supports Node.js (Railway, Render, etc.).

Set the environment variables:
- `DATABASE_URL`: PostgreSQL connection string
- `JWT_SECRET`: secret for JWT (min 32 characters)
- `JWT_REFRESH_SECRET`: secret for refresh tokens (min 32 characters)
- `FRONTEND_URL`: frontend URL (for CORS)
- `NODE_ENV`: production

## Development

```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend
cd backend
npm install
npm run dev
```

<!-- last-updated -->
_Last updated: 2026-09-05_

