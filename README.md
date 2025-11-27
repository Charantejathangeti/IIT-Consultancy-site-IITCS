# IIT-Consultancy-site-IITCS
IIT Consultancy - Purpose &amp; Importance IIT Consultancy bridges the gap between elite IIT graduates and top employers through a modern, secure job matching platform. Candidates access verified job listings and personalized dashboards, while employers efficiently discover and hire premium talent.
# IIT Consultancy

A full-stack job portal connecting IIT graduates with employers through a modern, responsive platform featuring glassmorphism design, secure JWT authentication, and role-based dashboards (admin, employer, candidate).

## Features

- User registration and login with JWT authentication
- Role-based dashboards for different users
- Real-time job posting and application tracking
- Glassmorphism UI with mobile-first responsive design
- Deployment-ready for Vercel with MongoDB Atlas support

## Demo Credentials

| Role      | Email              | Password    |
| --------- | ------------------ | ----------- |
| Admin     | admin@iit.com      | admin123    |
| Employer  | hr@technova.com    | employer123 |
| Candidate | anjali@email.com   | candidate123|

## Tech Stack

- Frontend: HTML5, CSS3 (Glassmorphism), Vanilla JS
- Backend: Node.js, Express.js, MongoDB with Mongoose
- Authentication: JWT, bcryptjs

## Installation

1. Clone the repo
2. Navigate to `/backend` and run `npm install`
3. Configure `.env` with your MongoDB URI and JWT secret
4. Run `npm run seed` to load demo data
5. Run `npm run dev` to start the server at http://localhost:5000

## Deployment

- Use Vercel for hosting
- Connect your MongoDB Atlas cluster
- Set environment variables in Vercel dashboard
- Deploy using `vercel --prod`

## License

MIT License

---

⭐ Star this repository if you find it useful!
