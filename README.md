# Career Navigator — AI Resume Builder

A full resume builder with landing page, sign up / log in, and PDF export.

## User flow

1. **Landing** (`/`) — Get Started & Log in
2. **Sign up** (`/signup`) — Create account
3. **Log in** (`/login`) — Access your resumes
4. **My Resumes** (`/resumes`) — List all resumes
5. **Create** (`/resumes/new`) — Resume title + **Student** or **Professional** mode
6. **Builder** (`/resumes/:id/edit`) — Fill details, live preview, **Download PDF**

## Run locally

```bash
cd C:\Users\KIIT\Projects\ai-resume-builder
npm install
npm run dev
```

Open **http://localhost:5173**

## Build for production

```bash
npm run build
npm run preview
```

Data is stored in the browser (localStorage) — no backend required for demo use.
