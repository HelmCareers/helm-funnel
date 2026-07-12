# Helm — Founding Cohort Funnel

Static validation landing page for [helmcareers.com](https://helmcareers.com).

- `index.html` — the entire page (self-contained; leads + analytics events write to the Helm Supabase project via an insert-only anon key)
- `og-image.png` — social preview card (1200×630)

Deployed on Vercel. Lead/event tables and scoring queries: see `supabase/funnel.sql` in the main helm repo.
