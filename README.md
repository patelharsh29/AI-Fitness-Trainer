# 🏋️‍♂️ AI Fitness Trainer

🔗 **Live Demo:** https://ai-fitness-trainer-phi.vercel.app/

An **AI-powered fitness coaching platform** that generates fully personalized **workout and diet plans** based on a user’s physical attributes, fitness goals, experience level, injuries, and availability.

The system simulates a real fitness and nutrition coach by intelligently designing **muscle group splits**, **recovery-aware workout schedules**, and **balanced meal plans** tailored to each individual.

To ensure reliability and safety, the platform enforces **strict JSON schemas** on all AI-generated outputs, making the data production-ready and easy to integrate with frontend and analytics systems.  
This application has been tested and valued by **hundreds of users**, helping them follow structured, goal-driven fitness and nutrition routines without the cost of a personal trainer.

---

## ✨ Key Features

- 🧠 **AI-generated workout plans** with structured sets, reps, and weekly schedules  
- 🥗 **Personalized diet plans** with calorie targets and balanced meals  
- 🛡 **Strict schema enforcement** for safe, consistent AI outputs  
- 🔁 **Real-time backend** with user-aware data handling  
- 🎙 **AI assistant orchestration & voice workflows**  
- 🔐 **Secure authentication** with personalized user profiles  
- ☁️ **Serverless deployment** with automatic scaling  

---

## 🧑‍💻 Technical Implementation

The application is built using **TypeScript/JavaScript** with a modern full-stack architecture. User inputs such as age, height, weight, injuries, dietary restrictions, workout frequency, fitness level, and goals are collected on the frontend and securely processed on the backend.

On the backend, I engineered **prompt-driven AI workflows** using a large language model API to generate structured fitness and nutrition plans. Each AI response is constrained by **strict JSON schemas**, enforcing numeric validation for sets, reps, and calorie values to prevent invalid or unsafe outputs. All AI-generated data is parsed, validated, and sanitized before being stored or returned to the client.

The workout generation logic avoids muscle overuse by applying **split-based training logic**, while the nutrition engine calculates daily calorie targets and produces balanced meals that respect dietary constraints. Additional runtime validation layers ensure schema correctness even when AI outputs deviate from expectations.

---

## 🧰 Tech Stack

| Category | Technology |
|--------|------------|
| **Frontend** | React, Next.js, Tailwind CSS |
| **Backend** | TypeScript, Serverless REST API routes |
| **AI Model** | Google Gemini (LLM API) |
| **AI Orchestration & Voice** | Vapi (assistant workflows, API requests, voice interaction) |
| **Database & Backend Logic** | Convex (real-time database, queries, mutations, user-aware logic) |
| **Validation** | Custom JSON schema validation & runtime safety checks |
| **Authentication** | Clerk (secure, user-aware personalization) |
| **Deployment** | Vercel (serverless functions, automatic scaling) |

---

## 🚀 Running the Application Locally

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open **http://localhost:3000** in your browser to view the app.

---

## 🗄 Running the Database (Convex)

```bash
npx convex dev
```

---

## 🖥 Application Screenshots

### Front Page
<img width="1718" height="885" alt="Front Page" src="https://github.com/user-attachments/assets/f160bd27-2c69-4cb7-980f-a5d0967d0cb2" />
<img width="1689" height="879" alt="Front Page Alt" src="https://github.com/user-attachments/assets/1ccd845e-cfd1-4e52-ba9c-6b6bce79a60d" />

---

### Sign-in / Sign-up Pages
<img width="1633" height="882" alt="Sign In" src="https://github.com/user-attachments/assets/9a1cd1ab-4f0d-48d5-9313-94322e77fa60" />
<img width="1627" height="880" alt="Sign Up" src="https://github.com/user-attachments/assets/ae397b28-3e3e-4ccf-af94-51d5457d2569" />

---

### Generating a Plan
<img width="1606" height="823" alt="Generate Plan" src="https://github.com/user-attachments/assets/d69a73e2-256b-478d-a7f0-5bd3b32f067d" />

---

### Profile Page (Workout & Diet Plans)
<img width="938" height="858" alt="Profile Page" src="https://github.com/user-attachments/assets/dd7f2726-b456-4766-a48c-39fed15b0d5b" />
<img width="605" height="724" alt="Profile Page Alt" src="https://github.com/user-attachments/assets/58da4ab5-b875-48bd-a343-3f31aadc9740" />
