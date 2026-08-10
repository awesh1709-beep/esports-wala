# eSports Wala — Database Starter

## Requirements
- Node.js 18+
- PostgreSQL database

## Setup
1. Copy `.env.example` to `.env`.
2. Put your PostgreSQL connection string in `DATABASE_URL`.
3. Run `npm install`.
4. Run `npx prisma generate`.
5. Run `npx prisma db push`.
6. Create at least one Tournament row in PostgreSQL/Prisma Studio.
7. Run `npm run dev`.

## Important security
The admin page is read-only and has no authentication. Before public launch, implement secure server-side authentication/authorization, session protection, validation, rate limiting, audit logs and proper privacy/terms pages. Do not put an admin password in client-side JavaScript.

This platform is independent and is not affiliated with Garena. Use only trademarks/assets you have permission to use.
