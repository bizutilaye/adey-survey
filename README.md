# Adey Beshale Survey

Telegram Mini App for **@AdeyBeshaleSurveyBot** — the interior-finishing survey for Adey Beshale customers.

- `index.html` — the form (number of houses 1–7, one of 4 choices per house). Served by GitHub Pages.
- Backend: Supabase Edge Function `adey-survey` (verifies Telegram's signed init data, one submission per person per group, no edits).
- Results: admins send `/results` to the bot in a private chat (summary + Excel).

This page contains no secrets; the bot token lives only in Supabase.
