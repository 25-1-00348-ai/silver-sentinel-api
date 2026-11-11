# Dasaka API

The backend and database for Dasaka, a crowdsourced bus app where riders share live bus info.

> Part of the Dasaka project for CSIT 105, Visayas State University.

## Owner

- Backend Developer: [NAME]

## Planned Endpoints

| Method | Endpoint | Purpose |
|--------|----------|---------|
| GET | /buses/nearby | List nearby buses |
| GET | /buses/{id} | Bus details, arrival time, crowding |
| GET | /routes | List and search routes |
| POST | /reports | Submit a bus report |
| POST | /reports/{id}/confirm | Confirm a report |
| POST | /auth/login | Log in (if time allows) |

Endpoints may change once the group agrees on the design.

## Tech Stack

- Language / framework: [TO BE DECIDED]
- Database: [TO BE DECIDED]
- Used by: [dasaka-android](ADD LINK) and [dasaka-web](ADD LINK)

## Setup

[ADD INSTRUCTIONS: install steps, how to run the server]

Never commit passwords or API keys. Keep them in a `.env` file that is listed in `.gitignore`.

## How We Work

1. Pick a task from the Issues tab of this repo.
2. Pull the latest `main`.
3. Make your own branch, e.g. `feature/bus-map`.
4. Commit your work, then open a **Pull Request**.
5. A teammate reviews and approves it before it is merged.

Never commit directly to `main`. Use your own GitHub username so your commits can be traced.

## Links

- Project documents and designs: [dasaka-specs](ADD LINK)
- Figma design: [ADD LINK]
