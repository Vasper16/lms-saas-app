# 📚 Learnify: AI-Powered LMS SaaS App

📅 Duration: May 2025 – Present  
📍 Status: In Progress  
🌐 Live Demo: Coming soon on Vercel

---

## 💡 Overview

Learnify is a full-stack Learning Management System (LMS) SaaS platform built to simulate a real-world EdTech product. It combines scalable architecture, modern UI design, voice-based AI integration, and subscription billing — all while following best practices for SaaS development.

---

## 🚀 Key Contributions

- Built using Next.js 14 App Router for modular, performant routing
- Integrated Clerk for secure user authentication and role-based access control
- Configured Stripe for seamless subscription billing and payments
- Connected to Vapi.ai for AI voice assistant integration in learning sessions
- Used Supabase for real-time data and backend management
- Designed UI with shadcn/ui components and Tailwind CSS
- Set up Sentry for full-stack observability and error tracking
- Entire project written in TypeScript for improved type safety and maintainability

---

## 🔍 Unique Features

- 🎙️ AI-powered vocal learning assistant with voice interaction
- 📚 Real-time lesson creation and delivery system
- 💳 Full SaaS-ready architecture using Stripe & Clerk
- 🎨 Clean, accessible, and responsive design-first UI

---

## 🧱 Tech Stack

| Category       | Tools Used                           |
|----------------|--------------------------------------|
| Frontend       | Next.js 14, React, Tailwind CSS      |
| Auth           | Clerk                                |
| Payments       | Stripe                               |
| AI Integration | Vapi.ai                              |
| Database       | Supabase                             |
| UI             | shadcn/ui                            |
| Monitoring     | Sentry.io                            |
| Language       | TypeScript                           |

---

## 📁 Project Structure

/app
/companions
/new → Create a learning companion
/[id] → View individual session
/sign-in → Custom sign-in page via Clerk
/components → Shared UI components (Nav, Cards, etc.)
/lib → Supabase client and utility functions


---


---

## ⚙️ Deployment Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/learnify-saas-app.git
cd learnify-saas-app

2. Install dependencies
npm install

3. Set up environment variables
Create a .env.local file and add:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key

VAPI_API_KEY=your_vapi_key

4. Run the development server
npm run dev
Your app will be live at http://localhost:3000

🧑‍💻 Author
Jyotiraditya
B.Tech ECE @ BIT Mesra

🧪 MVP development in progress. Voice session handling and final deployment coming soon.

