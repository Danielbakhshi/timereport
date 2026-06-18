# TimeReport

Internal time tracking app, connected to Supabase.

## Local development
```
npm install
npm run dev
```

## Deployment
Deploy directly via Vercel — connect this GitHub repo and Vercel will auto-detect
the Vite + React setup. No environment variables needed; Supabase credentials
are already in `src/App.jsx`.

## Accounts
Employee accounts and the admin account are stored in the Supabase `users` table.
To add a new employee, insert a new row into that table with a username and password.
