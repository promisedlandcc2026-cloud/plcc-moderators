# plcc-moderators

Front door for the PLCC moderation team: one page with links to every moderator tool
and a short "during a gathering" guide.

- **Ka Link prayer rooms**: plcc-chat (moderate from inside the call)
- **Overflow Moderator Room**: plcc-sanctum `/dashboard/prayer-rooms` → room → Moderator Room
- **Ka Link Team & rights**: PLCC Canaan `/#/admin/ka-link-team`
- **Overflow entrance**: plcc-overflow

The Moderator Room itself lives in **plcc-sanctum** (one copy of the room code). This repo is
static HTML/CSS with no build step.

## Deploy (Vercel)

1. Vercel → Add New → Project → import `promisedlandcc2026-cloud/plcc-moderators`.
2. Framework preset: **Other**. Leave Build Command and Output Directory empty.
3. Deploy. Every push to `main` redeploys.
