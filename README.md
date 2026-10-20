# racspeed-be (Rotaract Club Operations Backend)

The Rotaract Club Operations Platform utilizes a modular Next.js 16 App Router monolith with server-side Route Handlers and Supabase PostgreSQL.

All backend services, server actions, route handlers, SQL migrations, and tests are housed in:
`../racspeed-fe`

- **Database Migrations & RLS**: `../racspeed-fe/supabase/migrations/`
- **Backend Services & Workflows**: `../racspeed-fe/src/lib/services/`
- **Route Handlers**: `../racspeed-fe/src/app/api/`
- **Automated Tests**: `../racspeed-fe/tests/`

See `../racspeed-fe/docs/architecture.md` for the system design.