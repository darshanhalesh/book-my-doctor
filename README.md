# Book ur Doctor

A modern doctor appointment platform built with Next.js, Clerk authentication, Prisma, and Tailwind CSS.

## Features
- User authentication (patients & doctors) via Clerk
- Book, manage, and view appointments
- Doctor onboarding and verification
- Admin dashboard for managing doctors and payouts
- Video call integration for remote consultations
- Responsive, dark-themed UI

## Tech Stack
- Next.js 15
- React 19
- Clerk for authentication
- Prisma ORM
- Tailwind CSS
- Vonage Video API

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd doctors-appointment-platform-main
   cd doctors-appointment-platform-main
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**
   - Copy `.env.example` to `.env` and fill in the required Clerk and database credentials.

4. **Run database migrations:**
   ```sh
   npx prisma migrate deploy
   ```

5. **Start the development server:**
   ```sh
   npm run dev
   ```

6. **Open the app:**
   Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment
- Deploy easily on Vercel.
- Set the root directory to `doctors-appointment-platform-main` in Vercel project settings.
- Add all required environment variables in the Vercel dashboard.
- Live: https://book-my-doctor-nu.vercel.app/

## Credits
Made with 💗 by Darsh

