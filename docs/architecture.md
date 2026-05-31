# Architecture

Frontend:
- Next.js App Router

Auth:
- Clerk handles authentication + sessions

Database:
- Supabase Postgres

Backend:
- Next.js API routes OR server actions

ORM:
- Prisma (optional layer over Supabase)

Flow:
User → Clerk Auth → Next.js App → API → Supabase DB
