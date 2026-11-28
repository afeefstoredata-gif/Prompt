Technical Requirements Document (TRD)
System Architecture

Frontend → Backend API → Database → Google Sheets API → Email Service

Technology Stack
Frontend
Next.js
React.js
Tailwind CSS
Axios
Backend
Node.js
Express.js
Database
MongoDB
Authentication
JWT Authentication
bcrypt password hashing
APIs
Google Sheets API
Nodemailer
Hosting
Frontend: Vercel
Backend: Railway / Render
Database: MongoDB Atlas
Security Requirements
Password hashing
JWT validation
Protected admin APIs
Input validation
Secure environment variables
Performance Requirements
Optimized image loading
Lazy loading
API caching
Responsive rendering
Email Service

Use Nodemailer SMTP configuration to send customer order details.

Google Sheets Integration
Append customer orders automatically
Maintain formatted rows
Handle API failures
Required Environment Variables
MONGODB_URI=
JWT_SECRET=
ADMIN_EMAIL=
ADMIN_PASSWORD=
EMAIL_USER=
EMAIL_PASS=
GOOGLE_SHEET_ID=
GOOGLE_CLIENT_EMAIL=
GOOGLE_PRIVATE_KEY=