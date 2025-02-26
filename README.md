# FinSmart

FinSmart is a personal finance management application built with Next.js, Prisma, and Tailwind CSS.

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Set up environment variables:
```bash
cp .env.example .env
```
4. Run database migrations:
```bash
npx prisma migrate dev
```
5. Start the development server:
```bash
npm run dev
```

## Environment Variables

The following environment variables are required:

- DATABASE_URL: PostgreSQL database connection string
- NEXTAUTH_SECRET: Secret for NextAuth.js
- NEXTAUTH_URL: URL of the application

## Available Scripts

- `dev`: Start the development server
- `build`: Build the application for production
- `start`: Start the production server
- `lint`: Run ESLint
- `migrate`: Run database migrations
- `generate`: Generate Prisma client
- `seed`: Seed the database with sample data

## Technologies Used

- Next.js
- Prisma
- Tailwind CSS
- NextAuth.js
- Inngest
- Sonner
- React Hook Form
- Zod

