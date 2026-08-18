# Simple LMS

A simple modern full-stack Learning Management System using Next.js App Router, TypeScript, Tailwind CSS and Supabase.

## Features
- Student registration/login
- Separate admin login
- Student dashboard
- Public course listing
- Admin course creation/deletion
- Supabase PostgreSQL schema with RLS
- Vercel-ready deployment

## Setup
1. Create a Supabase project.
2. Run `supabase/schema.sql` in the Supabase SQL Editor.
3. Create an Auth user for the first administrator.
4. After the profile is created, change that profile's role to `admin` in the Supabase table editor.
5. Copy `.env.example` to `.env.local` and add the Supabase URL and anon key.
6. Run `npm install` and `npm run dev`.

## Environment
`NEXT_PUBLIC_SUPABASE_URL`
`NEXT_PUBLIC_SUPABASE_ANON_KEY`

Never commit `.env.local` or the Supabase service-role key.

## Deployment
Import this GitHub repository into Vercel and configure the two public Supabase environment variables. Deploy with the Next.js framework preset.

## Repository
https://github.com/tamilrocky10/simple-lms
