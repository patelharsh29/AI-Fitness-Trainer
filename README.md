## AI Fitness Trainer

An AI-powered fitness coaching platform that generates fully personalized workout and diet plans based on a user’s physical attributes, fitness goals, experience level, injuries, and availability. The system simulates a real fitness and nutrition coach by intelligently structuring muscle group splits, recovery-aware workout schedules, and balanced meal plans tailored to each individual.

The platform enforces strict data schemas to ensure consistency, reliability, and safety of AI-generated plans, making the output production-ready and easy to integrate into frontend and analytics systems. This application has been tested and valued by hundreds of users, helping them follow structured, goal-driven fitness and nutrition routines without the cost of a personal trainer.

**Technical Implementation**

The application is built using TypeScript/JavaScript with a modern full-stack architecture. User inputs such as age, height, weight, injuries, dietary restrictions, workout frequency, fitness level, and goals are collected on the frontend and securely processed on the backend.

On the backend, I engineered prompt-driven AI workflows using a large language model API to generate structured fitness and nutrition plans. Each AI response is constrained by strict JSON schemas, enforcing numeric validation for sets, reps, and calorie values to prevent invalid or unsafe outputs. All AI-generated data is parsed, validated, and sanitized before being stored or returned to the client.

The workout generation logic intelligently avoids muscle overuse by applying split-based training logic, while the nutrition engine calculates daily calorie targets and produces balanced meals that respect dietary constraints. Additional validation layers ensure schema correctness even when the AI output deviates from expectations.

## Tech Stack

**Frontend:** React / Next.js, Tailwind CSS  
**Backend:** TypeScript, REST APIs  
**AI Integration:** Google Gemini / LLM API (prompt-engineered with strict schema enforcement)  
**AI Orchestration & Voice:** Vapi (assistant workflows, API requests, voice interaction)  
**Database & Logic:** Convex (real-time database, queries, mutations, user-aware logic)  
**Validation:** Custom JSON schema validation & runtime safety checks  
**Authentication:** Clerk (user-aware personalization)  
**Deployment & Infrastructure:** Deployed on Vercel using serverless API routes with automatic scaling

## Running Application

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open (http://localhost:3000) with your browser to see the result.

## Running Database

Run the server:

```bash
npx convex dev
```
