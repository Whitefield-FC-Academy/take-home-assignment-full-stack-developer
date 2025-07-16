# Player Attendance Tracker (Take-Home Assignment)

Welcome!
This take-home assignment is designed to simulate a real-world system at our football club academy, where coaches track player attendance across scheduled sessions.

---

## Problem Statement

We run daily football training sessions split into **morning** and **evening**. Each player is assigned to an **age group**, managed by a specific coach.

Every player books a training plan with a fixed number of regular sessions (e.g., 12 sessions/month) and can get up to **3 complimentary sessions** if they miss any.

We need a system where coaches can:
- Log in and see only the sessions and players for their assigned age group.
- Mark player attendance (regular or complimentary).
- Take a group photo of the players during attendance (only camera).
- Track how many sessions each player has attended, and how many complimentary sessions are used.

---

## Requirements

### Core Features

- [ ] Coach login (username/password)
- [ ] See today's morning/evening sessions
- [ ] View players in assigned age group
- [ ] Mark player as:
  - Present (Regular)
  - Present (Complimentary)
  - Absent
- [ ] Take or upload a photo during attendance
- [ ] Show session stats per player:
  - Booked sessions used
  - Complimentary sessions used (max 3)

---

## Technical Requirements

- Frontend: React, Next.js or ReactNative, Tailwind CSS, Shadcn or any other frontend libraries of your choice (mobile responsive)
- Backend: Node.js (Express) or Nest.js (TypeScript)
- Database: PostgreSQL or MongoDB
- Auth: Simple login (JWT or session-based)
- File Handling: Store image per attendance (can be base64, cloud storage, or local)

---

## Bonus Features (Optional)

- Export attendance data to CSV
- Player profile with attendance history
- Email/SMS alert if attendance is low
- Dashboard showing upcoming session count and stats
- Dockerize the entire project  
  → The system should work with a single command:  
  docker-compose up --build -p 3000:3000

---

## Submission Guidelines

1. Fork this repo or create your own.
2. Include setup instructions in a README.md.
3. Seed with sample data (2 coaches, 10 players).
4. Push to a public GitHub repo and share the link.

---

## Time Estimate

We expect the core version to take 24–36 hours spread across a few days. Don’t worry if it’s not perfect—focus on clean code, good architecture, and problem-solving.

---

## Evaluation Criteria

- Functionality: Are the core features implemented correctly?
- Code structure and clarity
- API design and data modeling
- UI/UX (clean, functional UI)
- Use of modern dev practices (e.g., hooks, modular routes, services)
- (Bonus) Dockerization and ease of setup

---

## Questions?

Feel free to reach out to us if you have any doubts or clarifications!

Happy coding!
