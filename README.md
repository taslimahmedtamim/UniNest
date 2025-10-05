# UniNest

UniNest is a friendly all‑in‑one campus app idea. Instead of jumping between many scattered systems (canteen menu, library site, random chat groups, paper notices), students and staff get one clean place to do daily tasks.

Our goal: Save time, reduce confusion, help new students feel included, and make campus life smoother.

---

## Why UniNest?

- One app instead of many bookmarks.
- Less waiting in canteen lines.
- No “When is the exam?” panic.
- Friendly place to ask seniors for help.
- Quick way to track lost items.
- Simple reminders so you don’t forget returns or deadlines.

---

## Main Features (Plain and Simple)

### 1. Canteen
- See the menu with availability and prices.
- Pre‑order food and pay online.
- Get an alert when it’s ready.
- See an estimated calorie count.
- Rate meals so the canteen can improve.

### 2. Library
- Check if a book is available.
- Get a reminder before the due date.
- Access digital books (when allowed).
- Reserve a book if it’s taken.

### 3. Notice Board
- All campus notices in one list: exams, bus times, fees, holidays.
- Filter by type (Exam, Transport, Finance, etc.).
- Important notices can send a push alert.

### 4. Chat (Campus Only)
- Only verified university members.
- Channels for batches, departments, courses, help.
- Freshers can ask seniors questions.
- Basic moderation (future: report / mute).

### 5. Weather Alerts
- Local campus weather snapshot.
- Rain or severe weather warnings.

### 6. Lost & Found
- Post found or lost items with photos.
- Mark as claimed when resolved.
- Search by category (Electronics, ID card, etc.).

### 7. Smart Timetable
- Shows today’s classes with room numbers.
- Highlights overlaps (if any).
- Lets you view your personal schedule.

### 8. Exam & Deadline Countdown
- Add class tests, assignments, midterms, finals.
- See a countdown.
- Get reminders before the date.

---

## How It Helps a Student Day

Morning: Open app → See today’s classes + weather → Decide to bring umbrella.  
Before lunch: Pre-order food → Skip queue.  
Afternoon: Check a library book → Reserve it.  
Evening: Add upcoming assignment → Timer starts.  
Anytime: Ask seniors “How to register for lab?” → Quick answer.  
Lost wallet? → Check Lost & Found.

---

## Simple User Stories

- As a fresher, I want to ask seniors questions without feeling shy.
- As a busy student, I want reminders so I don’t miss deadlines.
- As a canteen vendor, I want to know orders ahead of peak time.
- As a librarian, I want fewer late returns.
- As a student, I want to quickly see if it will rain before a long walk.

---

## Future Ideas (Nice to Have Later)

- AI helper that answers common campus questions.
- Seat availability (library / labs).
- Meal suggestions based on calories & past choices.
- Reputation points for helpful chat answers.
- Calendar sync with Google.

---

## Very Light Tech Overview (For Now)

Planned:
- Frontend: Web (React or similar) + maybe mobile later.
- Backend: Node.js (REST + real‑time for chat).
- Database: PostgreSQL.
- Real‑time: WebSockets.
- Extras: Weather API, Payment API, Email / Push notifications.
(We will adjust as we build.)

---

## Development (Early Stage Plan)

1. Start with Auth + Notice Board (foundation).
2. Add Canteen basic menu + ordering.
3. Add Library search + reminders.
4. Add Chat + Lost & Found.
5. Add Timetable + Exam countdown.
6. Polish, test, demo.

---

## Contributing (Team Flow)

1. Create a branch: `feat/short-description`
2. Write clean, simple commits.
3. Open a Pull Request with:
   - What changed
   - Why it matters
4. Get review → Merge.

We’ll keep things simple at the start (maybe just a single repo).

---

## Tone & Design Principles

- Clear over clever.
- Fewer clicks.
- Friendly wording.
- Helpful defaults (auto reminders).
- Lightweight first, optimize later.

---

## Team

| Name | Role | Focus |
|------|------|-------|
| Taslim Ahmed Tamim | Team Lead / Backend | Core APIs, auth, structure |
| Salman Kabir Sany | Frontend | UI, user experience, responsive design |
| Majharul Islam | Full Stack / Data | Database design, logic modules, deployments |

---

## License

(To decide) — Likely MIT so others can learn from it.

---

## Quick Demo Flow (Future)

1. Login as student.
2. See today’s timetable & next exam countdown.
3. Order a meal → Get ready alert.
4. Search a book → Reserve it.
5. Post a question in chat → Senior replies.
6. Check weather → Rain warning shown.
7. Mark a found USB as “claimed”.

---

## Status

This is the human-friendly project overview. As we implement, we’ll keep this file updated so it matches reality.

Thanks for reading. Let’s build something students actually enjoy using. 💡
