# QuickAI

**Full Stack AI SaaS App**  
Live Demo: [quick-ai-ivory.vercel.app](https://quick-ai-ivory.vercel.app)


QuickAI is a robust full-stack SaaS platform integrating cutting-edge AI tools and sleek UI components to deliver an all-in-one productivity suite. Designed to assist content creators, job seekers, and developers, it combines real-time AI generation with modern media processing and document parsing.

---

## Tech Stack

### Backend
- Node.js + Express – RESTful API server
- PostgreSQL – Structured data storage
- Clerk Auth – Secure email-based authentication
- pdf-parse + Axios – Document parsing and HTTP requests
- Multer + Cloudinary – Media upload and cloud storage

### AI & APIs
- Google Gemini API – AI Article Writer, Blog Title Generator, Resume Reviewer
- ClipDrop API – Object & Background Removal

### Frontend
- Vite + React.js – Lightning-fast frontend development
- Tailwind CSS – Utility-first styling
- Lucide-React – Iconography
- React Hot Toast – User-friendly toast notifications

---

## Features

- AI Content Suite
  - Article & Blog Title Generator
  - Resume Review Assistant
  - Image Generator (Gemini-powered)

- Media Tools
  - Background & Object Remover (via ClipDrop API)
  - Resume Parser (PDF)

- Authentication & User Flow
  - Clerk-managed sign-in & CRUD routes
  - Personalized session handling

- Deployment
  - Hosted seamlessly on Vercel

---

## Preview


<img width="1899" height="909" alt="image" src="https://github.com/user-attachments/assets/e1225c90-05a6-4b83-9dd4-bdbcec930ca0" />

---

## Getting Started

1. Clone the Repo
   ```bash
   git clone https://github.com/yourusername/quickai.git
   cd quickai
   
2. Install Dependencies
   npm install
   
3. Environment Setup-
  Create a .env file and configure:
  1. CLERK_SECRET_KEY=your_clerk_secret
  2. CLIPDROP_API_KEY=your_clipdrop_key
  3. GEMINI_API_KEY=your_gemini_key
  4. CLOUDINARY_URL=your_cloudinary_url
  5. DATABASE_URL=your_postgres_url

4. Run the App
   npm run dev

## Deployment
  1. The app is deployed via Vercel. For your own deployment:
  2. Push the repo to GitHub.
  3. Connect GitHub repo in Vercel dashboard.
  4. Add required environment variables in Vercel settings.
  5. Hit Deploy
