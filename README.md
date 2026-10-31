# Modern Next.js SaaS Starter Kit 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Next.js 14](https://img.shields.io/badge/Next.js-14.1-black.svg)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.4-38bdf8.svg)](https://tailwindcss.com/)

An opinionated, production-grade template designed for indie hackers and startup teams to build, validate, and scale web applications with minimal boilerplate.

## Features
- **App Router & Server Actions:** Built natively on Next.js 14 paradigm.
- **Authentication:** Turnkey Supabase Auth (SSR sessions, magic link, OAuth).
- **Billing Architecture:** Pre-configured Stripe Checkout sessions and webhook handlers for recurring subscriptions.
- **UI & Accessibility:** Tailwind CSS paired with Radix UI primitives.
- **Type-Safe Database Access:** PostgreSQL schema managed via Supabase / Prisma.

## Getting Started

### 1. Clone repository
```bash
git clone https://github.com/louis1-cmd/nextjs-saas-starter.git
cd nextjs-saas-starter
```

### 2. Configure Environment
```bash
cp .env.example .env.local
# Add your NEXT_PUBLIC_SUPABASE_URL and STRIPE_SECRET_KEY
```

### 3. Run Development Server
```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

## License
MIT License.
