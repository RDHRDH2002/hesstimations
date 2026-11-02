# Security

- This repository is public. It must never contain secrets, credentials, API keys, tokens,
  passwords, private user data, database dumps, or third-party data.
- Secrets live in a password manager and are injected through GitHub Actions secrets or a local
  `.env` file, which Git ignores. `.env.example` lists variable names only.
- Automated job logs are public. Jobs must log counts and statuses only, never payloads or values.
- If you find a security issue, please contact the repository owner privately through GitHub
  rather than opening a public issue.
