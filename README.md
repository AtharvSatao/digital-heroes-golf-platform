# Digital Heroes Golf Platform

2-day assignment MVP based on the Digital Heroes PRD.

## Run
npm install
cp .env.example .env
npm run dev

Without Supabase environment variables the app runs in demo mode using localStorage. For submission, create a new Supabase project, run `supabase.sql`, add `.env` values, then deploy to a new Vercel project.

## Admin demo
Login/signup and click **Admin demo** in the dashboard. This is intentionally a UI/demo switch for the assignment; production should enforce admin role through Supabase RLS/server-side checks.
