# Kinfile website

Static landing page and early-access waitlist for Kinfile, served by GitHub Pages at https://alisohail683.github.io/kinfile/.

- `index.html`: landing page, free 30-day access checklist, waitlist form
- `privacy.html`: privacy notice for the waitlist
- The form calls the `join_waitlist` RPC on the Kinfile Supabase project (`fztwuutssvbmssddlwsb`). The `waitlist` table has RLS with no policies, so the publishable key can only add an entry, never read the list.
