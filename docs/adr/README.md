# Architecture Decision Records

Status as of Phase 0 close. Each decision gets a full record when it is first implemented.

| ADR | Decision | Status |
|---|---|---|
| 001 | Brand: The Hesstimations; technical id `hesstimations`; brand tokens in one config file | Accepted |
| 002 | Permanent-$0 rule: no trials, no card on file, services must reject requests at their limits | Accepted |
| 003 | Public repo; MIT covers code only; no data in the repo; logs never contain data | Accepted |
| 004 | Git: feature/* to development (squash), development to master (merge commit); master is default and production | Accepted |
| 005 | Supabase Free, us-east-2; hesstimations-prod plus free hesstimations-dev; no Docker | Accepted |
| 006 | Data API on; auto-expose off; auto-RLS on; internal schemas not exposed; explicit grants | Accepted |
| 007 | Supabase GitHub integration: deploy to production off, automatic branching off; manual migrations | Accepted |
| 008 | Auth: Supabase magic link, sign-ups disabled, allowlist enforced by RLS | Accepted |
| 009 | Credentials: Bitwarden to GitHub Secrets or git-ignored .env; secret scanning | Accepted |
| 010 | Odds: The Odds API, regions=us, 3 markets, all books kept; DraftKings reference; regulated-US consensus benchmark | Accepted |
| 011 | Odds scheduling: adaptive and prioritized; trigger_reason; First Observed Line; pregame vs post-kickoff | Accepted |
| 012 | Object storage: Backblaze B2 rejected; Supabase Storage primary; GitHub backup repo pending validation | Accepted (backup provisional) |
| 013 | Sources: nflverse, CFBD (1,000 calls/month), Open-Meteo; OddsPapi supplemental candidate | Accepted |
| 014 | Scheduling: GitHub Actions plus Healthchecks dead-man checks; 60-day keepalive pending verification | Accepted (keepalive pending) |
| 015 | Evidence Profile with versioned, transparent rules; no composite brand score | Accepted |
