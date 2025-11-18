# MicroNetworks (Production Starter)

This is a production-oriented starter for **MicroNetworks**, a social avatar
network with:

- Supabase authentication
- Main + proxy account system (schema-level)
- Avatar builder (paperdoll, main account)
- Feed (posts from you + followed accounts)
- Account switcher
- Notifications scaffold

## Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create a Supabase project and set env vars:

   - `NEXT_PUBLIC_SUPABASE_URL`
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`

3. Apply the SQL schema from `database/schema.sql` (you must create this in Supabase).

4. Run dev server:

   ```bash
   npm run dev
   ```

5. Visit `http://localhost:3000/feed`.
