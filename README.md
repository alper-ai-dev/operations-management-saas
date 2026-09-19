# Orbit — Operations Management SaaS
Full-stack portfolio application for persistent operations workflows.

## Architecture
Next.js frontend and server-side route handlers expose CRUD endpoints. Supabase provides PostgreSQL persistence. Database credentials stay server-side.

## Features
- Real PostgreSQL persistence
- REST-style GET, POST, PATCH and DELETE operations
- Create, move and delete tasks
- Workflow status and priority constraints
- Server-side database access
- Responsive operations board

## Setup
1. Create a Supabase project.
2. Run supabase.sql in SQL Editor.
3. Add SUPABASE_URL and SUPABASE_SERVICE_ROLE_KEY to the deployment environment.
4. Deploy.

## Security note
The service-role key is server-only and must never be exposed in browser code. This portfolio demo has no authentication; a production deployment should add authentication, authorization/RLS and organization-level tenancy.

Built by Alper Sancar · 2026.