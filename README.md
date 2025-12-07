# lms-stem-platform-ISAM
FOR onsite
# LMS STEM Platform — ISAM (Education SaaS)

A full-stack learning management system built for STEM education across multiple schools.
Features: role-based auth, courses, assessments, progress tracking, certificate generation, and admin analytics.

## Tech
Frontend: React, Tailwind
Backend: Node.js, Express, MongoDB
Auth: JWT, bcrypt
Storage: Cloudinary / S3
Dockerized for production.

## Quickstart (dev)
1. Clone repo
2. Backend:
   cd backend
   cp .env.example .env  # set MONGO_URI, JWT_SECRET, CLOUD_*
   npm install
   npm run dev
3. Frontend:
   cd frontend
   npm install
   npm run dev
4. Visit http://localhost:3000

## Deploy
- Frontend: Vercel or Netlify
- Backend: Render / Railway / Docker on VPS
- DB: MongoDB Atlas
- Optional: use Docker Compose in /infra for local full-stack

## Notes
- Add `ADMIN_EMAILS` in .env for super-admins
- Seed script: backend/src/seed.js

## License
MIT
