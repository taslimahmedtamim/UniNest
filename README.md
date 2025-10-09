
# UniNest

UniNest is an all‑in‑one campus platform with a primary focus on canteen automation. We will ship canteen features first, then add other student‑life modules iteratively so students and staff get immediate value while we expand.

## Why UniNest?
- One app instead of many systems
- Shorter queues and faster canteen service
- Reduced food waste via demand forecasting
- Clear campus information and simple reminders
- Real‑time campus services (library occupancy, chats, notices)

## Core Feature: Canteen Automation
UniNest's canteen automation will streamline ordering, reduce queues and waste, and surface useful nutrition information:

- Digital Menu & Availability
  - A digital menu with prices and real‑time availability per item (sold out, low stock).
  - Estimated calorie counts shown for menu items to help users make informed choices.

- Ordering & Payments
  - Food pre‑order and scheduled pickup to reduce wait times.
  - Online payment system with multiple gateways and receipts.
  - Order status and ready-to-pickup notifications.

- Feedback & Reviews
  - Food review and feedback option for each meal to improve offerings.
  - Upvotes/ratings and comments to highlight favorites and issues.

- Alerts & Requests
  - Alert system for order status, menu changes, and promotions.
  - Food request option where users can request items or special preparations (subject to canteen approval).

- AI-driven Demand Prediction & Waste Reduction
  - We will use historical user ordering data and AI to predict day‑wise food demand.
  - Predictions enable smarter batching and ingredient ordering to minimize food waste.

- Kitchen & Inventory
  - Kitchen dashboard for batching, prep, and pacing orders.
  - Inventory signals (low/out of stock) and suggested restock quantities.

- Analytics & Optimization
  - Analytics for peak hours, popular items, and demand trends.
  - Demand prediction models to optimize menu planning and reduce waste.

## Library Automation (new)
UniNest will include a Library Automation module to make library access seamless, safe, and data-driven:

- Membership Issuance
  - Smart membership issuance: when a student registers for library membership, UniNest generates a scannable QR or barcode (digital card in-app and printable option).
  - Membership IDs integrate with other campus services (single sign-on where available).

- Entry / Exit Scanning
  - Scanner devices at library entrances/exits (or turnstile integrations) read member QR/barcodes on entry and on exit.
  - Each scan writes an entry or exit timestamp to the library visit log.
  - Scans allow quick verification and reduce manual checks at doors.

- Seat Management & Capacity Limits
  - Library capacity is enforced by the system: current occupancy is derived from entry and exit events.
  - When capacity is reached, the library shows "Full" in-app and on status pages; further entries can be blocked or placed in a hold queue.
  - Optional timed reservations for study rooms or high-demand areas (auto-release after no-shows).

- Visibility & User Experience
  - Live availability status visible in the UniNest app and web dashboard so users can see whether the library is full before heading over.
  - Personal visit history and receipts (for auditing or stats).
  - Admin dashboard for librarians: real-time occupancy, daily logs, peak hour analytics, and exportable reports.

- Analytics & Integrations
  - Full logs of visits (entry and exit timestamps) for auditing, space planning, and usage analytics.
  - Usage heatmaps and peak-hour predictions to inform staffing and opening hours.
  - Possible integration with the library catalog and overdue notifications (optional).

## Centralized Campus Chat (new)
A campus-wide, centralized chat system will help the community surface problems, coordinate, and improve campus life:

- Verified Campus Users
  - Only verified campus accounts (students, staff) can participate by default to keep the space relevant and safe.
  - Role-based access for admins, moderators, club leaders, and guests.

- Channels & Topics
  - Channels for departments, courses, clubs, dorms, and topics (events, lost & found, maintenance).
  - Public suggestion threads and dedicated feedback channels for reporting campus issues.

- Conversation Features
  - Threaded discussions, replies, mentions, and rich text support.
  - Upvotes/likes and pinning announcements for important posts.
  - Searchable history with filters by channel, author, and date.

- Moderation & Safety
  - Lightweight moderation tools: warn/mute/report, channel moderators, and basic auto-moderation rules.
  - Reporting workflows and admin dashboards for complaint resolution.
  - Privacy controls: default campus-only visibility with per-channel privacy options.

- Integrations & Notifications
  - Integrations with Notice Board, Lost & Found, and library notifications.
  - Push and email notifications for mentions, channel announcements, and emergency alerts.

## Additional Modules (iterative)
- Notice Board: exams, transport, fees, holidays; filters and alerts
- Campus‑only Chat: verified users, channels, moderation (expanded into Centralized Campus Chat)
- Weather Alerts: local snapshot and severe weather warnings
- Lost & Found: post items, search, resolve
- Smart Timetable: today’s classes, room numbers, personal schedule
- Exam & Deadline Countdown: track items and receive reminders

## Roadmap
- Phase 1: Auth, canteen basics (menu, ordering, payments, notifications)
- Phase 2: Library Automation (membership QR/barcode, entry/exit scanning, occupancy & seat limits)
- Phase 3: Centralized Campus Chat, Notice Board, Lost & Found, analytics enhancements, integrations, mobile apps

## Development Model (Agile)
- Iterative, incremental delivery in short sprints
- Frequent releases and user feedback
- Backlog reprioritized as we learn; canteen automation remains the main focus

## Tech Overview (planned)
- Frontend: Web (React or similar); mobile clients later (iOS/Android)
- Backend: Node.js (REST + WebSockets) for realtime features (chat, live occupancy)
- Database: PostgreSQL (events, logs, analytics); Redis for realtime counters and caches
- Integrations: Payment gateways, weather APIs, email/push providers, QR generator services
- Hardware: QR/barcode scanners or camera-based scanning at entry/exit points (edge device integration)

## Contributing
1. Create a branch: `feat/short-description`
2. Write clean, focused commits
3. Open a Pull Request describing what changed and why

## Tone & Design Principles
- Clear over clever
- Fewer clicks
- Helpful defaults (auto reminders)
- Ship small, iterate

## Team
| Name | Profession | GitHub |
|------|------------|--------|
| Taslim Ahmed Tamim | Student | [taslimahmedtamim](https://github.com/taslimahmedtamim) |
| Salman Kabir Sany  | Student | [salmankabirsany](https://github.com/salmankabirsany) |
| Majharul Islam     | Student | [MrMajharul](https://github.com/MrMajharul) |

## License
To decide.

## Status
Early planning. This README will be updated as implementation progresses.
```
