# 📚 Learnify: AI-Powered LMS SaaS App  

![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)  
![Clerk](https://img.shields.io/badge/Auth-Clerk-blueviolet)  
![Stripe](https://img.shields.io/badge/Payments-Stripe-635BFF?logo=stripe&logoColor=white)  
![Supabase](https://img.shields.io/badge/Database-Supabase-3ECF8E?logo=supabase&logoColor=white)  
![Sentry](https://img.shields.io/badge/Monitoring-Sentry-black?logo=sentry&logoColor=white)  

📅 **Duration:** May 2025 – Present 

---

## 💡 Overview  

Learnify is a **full-stack SaaS-based Learning Management System (LMS)** designed as a real-world **EdTech simulation**. It merges:  

✨ **Modern UI/UX** → Clean, responsive, and accessible  
🤖 **AI-Powered Voice Interaction** → Seamless learning with speech-based assistant  
💳 **Subscription Billing** → Fully SaaS-ready using Stripe  
⚙️ **Scalable Architecture** → Built with best practices for SaaS apps  

---

## 🚀 Key Contributions  

- ⚡ **Next.js 14 App Router** → Modular, performant routing  
- 🔐 **Clerk Authentication** → Secure login & role-based access control  
- 💸 **Stripe Payments** → Recurring subscriptions and one-time billing  
- 🗣️ **Vapi.ai Voice Assistant** → Real-time AI vocal companion in sessions  
- 🗄️ **Supabase** → Real-time database + backend APIs  
- 🎨 **shadcn/ui + Tailwind CSS** → Reusable components & design-first styling  
- 🛡️ **Sentry** → Full-stack error monitoring and observability  
- 📝 **TypeScript-first Development** → Strict typing for scalability  

---

## 🔍 Unique Features  

- 🎙️ **Voice-first learning assistant** → Natural voice conversation in lessons  
- 📝 **Dynamic lesson creation & delivery** → Real-time and scalable  
- 💳 **End-to-end SaaS setup** → Authentication + Subscription + Payments  
- 🎨 **Design-first approach** → Modern, minimal, and responsive  

---

## 🧱 Tech Stack  

| 🏗️ Category     | ⚙️ Tools Used                         |
|-----------------|--------------------------------------|
| 🌐 Frontend     | Next.js 14, React, Tailwind CSS      |
| 🔐 Auth         | Clerk                                |
| 💳 Payments     | Stripe                               |
| 🤖 AI Assistant | Vapi.ai                              |
| 🗄️ Database     | Supabase                             |
| 🎨 UI Library   | shadcn/ui                            |
| 📊 Monitoring   | Sentry.io                            |
| 💻 Language     | TypeScript                           |

---

## 📂 Project Structure  

/app
/companions → Learning companions
/new → Create a new learning companion
/[id] → View an individual learning session
/sign-in → Custom sign-in page (Clerk)

/components → Shared UI components (Navbar, Cards, etc.)
/lib → Supabase client, utils & helpers


---

## ⚙️ Getting Started  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/learnify-saas-app.git
cd learnify-saas-app
2️⃣ Install Dependencies
npm install
2️⃣ Install Dependencies
npm install

3️⃣ Configure Environment Variables

Create .env.local in the root and add:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key

VAPI_API_KEY=your_vapi_key

4️⃣ Run the Development Server
npm run dev

👨‍💻 Author

Jyotiraditya
🎓 B.Tech. ECE @ BIT Mesra
🔗 GitHub
 | LinkedIn
