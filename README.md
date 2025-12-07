# lms-stem-platform-ISAM
Elevator description
Scalable Learning Management System for STEM education used by schools — courses, assessments, analytics, and role-based access.

Tech stack
Frontend: React, React Router, Tailwind CSS
Backend: Node.js, Express
DB: MongoDB (Mongoose)
Auth: JWT + bcrypt
Storage: Cloudinary (media) or S3
Extras: Webhooks, Redis (caching), Docker

Priority feature list

Auth: student/teacher/admin (JWT)

Course and module CRUD, video embedding

Assessment engine: timed quizzes, auto-grading

Progress tracking & reports per student/school

Certificate generation (PDF)

School-wise multi-tenancy (isolation)

Admin analytics dashboard (charts)

Offline support (service worker + IndexedDB)

Deployment with DockerElevator description
Scalable Learning Management System for STEM education used by schools — courses, assessments, analytics, and role-based access.

Tech stack
Frontend: React, React Router, Tailwind CSS
Backend: Node.js, Express
DB: MongoDB (Mongoose)
Auth: JWT + bcrypt
Storage: Cloudinary (media) or S3
Extras: Webhooks, Redis (caching), Docker

Priority feature list

Auth: student/teacher/admin (JWT)

Course and module CRUD, video embedding

Assessment engine: timed quizzes, auto-grading

Progress tracking & reports per student/school

Certificate generation (PDF)

School-wise multi-tenancy (isolation)

Admin analytics dashboard (charts)

Offline support (service worker + IndexedDB)

Deployment with Docker
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
   FOR DEMO
5. Visit https://quantum-leap-stem-2cac4d4f.base44.app

## Deploy
- Frontend: Vercel or Netlify
- Backend: Render / Railway / Docker on VPS
- DB: MongoDB Atlas
- Optional: use Docker Compose in /infra for local full-stack

## Notes
- `abdulhanif722@gmail.com` in .env for super-admins
- Seed script: backend/src/seed.js

## License
MIT
