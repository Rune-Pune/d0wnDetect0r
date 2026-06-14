# d0wnDetect0r

A SaaS application for monitoring website uptime and sending alerts.

## Tech Stack

- **Backend**: ASP.NET Core 9 (C#) with Clean Architecture
- **Frontend**: React 19 with TypeScript
- **Database**: PostgreSQL
- **Authentication**: JWT + Google OAuth
- **Notifications**: SMTP (Brevo)

## Getting Started

See [CLAUDE.md](CLAUDE.md) for development guidelines.

## Project Structure

```
d0wnDetect0r/
├── src/
│   ├── backend/           # ASP.NET Core API
│   └── frontend/          # React app
├── infra/                 # Docker & deployment configs
└── docs/                  # Documentation
```
