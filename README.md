# Full Stack AI Career Coach with Next JS, Neon DB, Tailwind, Prisma, Inngest, Shadcn UI


An AI-powered full-stack web application built using **Next.js** and **NeonDB** that helps users explore industry insights, assess their skills with mock tests, and generate professional CVs and cover letters using **Gemini (Google AI)**.

---

## 🚀 Features

- 🔐 **User Authentication** – Secure sign-up and login system with clerk.
- 📊 **Industry Insights Dashboard** – Real-time analysis of different industry sectors using AI-generated data.
- 🧪 **Skill-Based Mock Tests** – Users can choose a skill and take mock tests with instant feedback.
- 📝 **AI CV Generator** – Instantly generate a professional resume tailored to user input.
- 💼 **AI Cover Letter Generator** – Create personalized, job-specific cover letters using Gemini AI.
- 📥 **Downloadable Documents** – Users can download their CVs and cover letters as PDF files.
- 🎯 **Responsive UI** – Built with Tailwind CSS for a mobile-friendly and modern interface.

---

## 🛠️ Tech Stack

| Layer        | Technology                 |
|--------------|-----------------------------|
| Frontend     | Next.js, Tailwind CSS       |
| Backend      | Node.js, REST API           |
| Database     | NeonDB (PostgreSQL)         |
| Authentication | NextAuth              |
| AI Services  | Gemini (Google AI)          |
| PDF Generation | jsPDF / react-to-pdf       |
| Deployment   | Vercel                       |

---



---

## 🧠 How AI Is Used

- **Gemini (Google AI)** is used to:
  - Generate real-time industry insights.
  - Create personalized CVs and cover letters.
  - Evaluate user performance in mock tests.
- Integrated via RESTful API calls, processed and rendered on the client dynamically.

---

## 🧪 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ShradhaSuman12220474/skillsenseAI.git
   cd skillsenseAI
   ```


2.  **Make sure to create a `.env` file with following variables**:

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```


3. **Run the migration.**
```bash
 npx prisma migrate dev --name  create-models
```

4. **Now its all done just run the project.**
```bash
npm run dev
```