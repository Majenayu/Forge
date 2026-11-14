# Forge API reference

The Express server in `server.js` serves the prototype UI and exposes these JSON routes:

| Method | Path | Purpose |
| --- | --- | --- |
| `POST` | `/register` | Create a user record after hashing the password |
| `POST` | `/login` | Check login credentials |
| `GET` | `/dashboard` | Serve the dashboard page |

The request and response shapes are defined directly in `server.js`. Use local, non-production data when exercising the routes. Authentication, authorization, validation, rate limiting, and secure session handling still require production hardening.
