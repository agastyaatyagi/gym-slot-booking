# Gym Slot Booking

Gym Slot Booking is a learning project for managing one-hour gym sessions, member bookings, waitlists, and staff check-in.

## Project status

This repository is at the foundation milestone. The React and Express development scaffolds are being set up. Booking, authentication, database schema, seed data, and the required pages are not implemented or verified yet.

## Planned stack

- Frontend: React and TypeScript, built with Vite.
- Backend: Node.js, Express, and TypeScript.
- Database: SQLite, using relational tables and database transactions for booking changes.

## Design note

The frontend is a React application built with Vite.
The backend exposes a JSON API using Express and TypeScript.
SQLite will store related users, sessions, bookings, and waitlist entries.
Foreign keys will connect bookings and waitlist entries to users and sessions.
Booking and waitlist operations will use transactions to preserve capacity and promotion rules.

## Requirements tracking

| Requirement | Status |
| --- | --- |
| Project scaffolding | In progress |
| Registration, login, and roles | Not implemented |
| Session creation and browsing | Not implemented |
| Booking, cancellation, and capacity protection | Not implemented |
| Waitlist and automatic promotion | Not implemented |
| Check-in and attendance | Not implemented |
| Required frontend pages and accessibility | Not implemented |
| Seed data and test credentials | Not implemented |
| Manual verification | Not started |

Only mark a requirement complete after you have implemented and personally verified its behavior.

## Setup

Setup instructions will be completed after the project scaffolding milestone. Copy `.env.example` to `.env` for local configuration; never commit `.env` or real credentials.

## Assumptions

- All session start times are interpreted in one documented gym-local timezone.
- Session capacity is fixed at 20.
- Cancelled bookings are retained as history and are not considered active bookings.
- HTTP errors will use one consistent JSON shape.

## Test accounts and sample data

Not available yet. Add development-only admin and member credentials here after creating and verifying seed data. Do not use real passwords.

## Known limitations

All challenge features are currently pending implementation. Deployment is optional and has not been configured.

## Repository and deployment

Repository: https://github.com/agastyaatyagi/gym-slot-booking

Live links: none; deployment is optional.
