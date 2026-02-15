# notes-hub-web

React + TypeScript web client for **Notes Hub** — authentication flow and a simple UI for personal notes management.

## 📌 Overview
**notes-hub-web** is the SPA (Single Page Application) for Notes Hub. It provides:
- Sign up / Sign in screens
- Protected routes (authenticated area)
- Notes dashboard (create, list, view, edit, delete)
- Integration with the Notes Hub API via JWT

## ✅ Features (MVP)
- Register account
- Login with email or username + password
- Logout
- Notes CRUD UI (create, list, view, edit, delete)
- Basic UX states (loading, empty state, error feedback)

## 🧰 Tech Stack
- React
- TypeScript
- Vite
- npm

## 📂 Project Structure (initial)
- `src/app/` — app setup (routing, auth guard, global config)
- `src/pages/` — pages (Login, Register, Notes)
- `src/components/` — reusable UI components
- `src/services/` — API integration (auth, notes)
- `src/types/` — shared TypeScript types

## ⚙️ Configuration
The frontend needs the backend API base URL.
Recommended: use environment variables (e.g. `.env.local`) and keep local files out of Git.

Typical config:
- API base URL (e.g. `VITE_API_URL`)

## 🚀 How to Run (local)
Prerequisites:
- Node.js
- npm

Steps (high level):
1. Install dependencies
2. Start the dev server
3. Open the local URL shown by Vite

## 🔗 Related Repository
Backend repo: **notes-hub-api**
