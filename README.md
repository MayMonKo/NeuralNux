# NeuralNux — Phase 1

NeuralNux is a student-led, portfolio-driven technology initiative focused on building and showcasing real-world **data science and cyber security projects** using clean engineering practices and modern frontend architecture.

Phase 1 establishes NeuralNux as a **production-ready public platform**, intentionally optimized for clarity, maintainability, and zero deployment cost.

---

## Phase 1 Objective

The objective of Phase 1 is to deliver a credible, professional, and maintainable public-facing platform that:

- Presents the NeuralNux identity and mission
- Showcases services, features, and team structure
- Enables external users to contact the team
- Uses modern frontend best practices
- Operates with zero backend and zero infrastructure cost

Phase 1 is complete by design and does not require server-side logic.

---

## Architecture Overview

Next.js (React)
│
├── Component-based UI
├── Modular CSS architecture
├── Serverless contact form
└── Static deployment



This architecture prioritizes simplicity, performance, maintainability, and future extensibility.

---

## Tech Stack

### Frontend
- Language: JavaScript
- Framework: Next.js (React)
- Styling: CSS Modules with global theme files
- Hosting: Vercel (Free Tier)

### Email / Contact
- Service: Formspree (Serverless)
- Purpose: Contact form → direct email delivery
- Backend required: No

### Cost
- Total cost: RM0
- Custom domain: Deferred

---

## Project Structure

neuralnux/
├── pages/
│ └── index.js
│
├── components/
│ ├── Header.jsx
│ ├── Hero.jsx
│ ├── About.jsx
│ ├── Stats.jsx
│ ├── Services.jsx
│ ├── Features.jsx
│ ├── Team.jsx
│ ├── FAQ.jsx
│ ├── Contact.jsx
│ └── Footer.jsx
│
├── styles/
│ ├── globals.css
│ ├── theme.css
│ ├── animations.css
│ └── components/
│ ├── hero.module.css
│ ├── services.module.css
│ ├── team.module.css
│ ├── faq.module.css
│ └── footer.module.css
│
├── public/
│ └── images/
│
└── README.md


---

## Styling Philosophy

- Cyber / neon-inspired aesthetic applied intentionally
- Visual hierarchy prioritized over excessive animation
- Animations limited to high-impact sections
- Readability and professionalism emphasized
- No global CSS pollution

---

## Contact Functionality

The contact form uses a serverless workflow:

- Submissions are sent directly via Formspree
- Messages are delivered to the official NeuralNux email
- No backend, database, or authentication required
- Easily replaceable with a backend API in future phases

---

## Deployment

- Platform: Vercel
- Deployment model: Static + serverless
- URL format: https://neuralnux.vercel.app - Automatic HTTPS
- Continuous deployment via GitHub

---

## Engineering Principles

- Build only what is required
- Defer complexity intentionally
- Prefer clarity over cleverness
- Treat UI as a product, not a demo
- Design with future phases in mind

---

## Status

- Phase: 1
- Backend: Not implemented (by design)
- Cost: RM0
- Deployment: Ready
- Purpose: Public platform and portfolio showcase


