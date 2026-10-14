# Lumio — E-Learning Platform

An interactive learning workspace that brings course discovery, revision sheets, quiz practice, and learner progress together, with a dedicated workspace for teachers.

**[Explore the live demo →](https://tutos-chi.vercel.app/)**

Built with **React · TypeScript · Vite · Tailwind CSS** and hosted on **Vercel**.

## Overview

Lumio is a frontend portfolio project exploring the experience of an online learning platform. Learners can browse courses, organize their learning, practice quizzes, and review their progress. Teachers have a separate workspace for viewing their courses, students, reviews, and simulated revenue.

This public repository is a project showcase. It contains documentation only; the application source code is private.

## Features

### Course discovery

- Browse courses using search and category filters.
- Explore course details, learning outcomes, prerequisites, and sample video previews.
- Save courses, enroll in free courses, and explore a cart with demo promo codes.
- Browse mentoring profiles.

### Learner workspace

- View enrolled courses and learning progress.
- Practice quizzes with grading, explanations, retries, and saved attempt history.
- Read revision sheets and create personal study notes.
- Manage profile details, saved courses, and account preferences.

### Teacher workspace

- View owned courses, including draft courses.
- Review a sample student roster and enrollment progress.
- Explore course reviews and simulated sales, revenue charts, and payout history.
- Filter revenue reports by course and reporting period.

### Interface and experience

- Responsive layouts with mobile navigation.
- Light and dark themes.
- Browser-based persistence for demo accounts, preferences, and learning activity.
- A learning assistant drawer with simulated replies and saved conversations.
- Keyboard-aware controls, focus management, loading states, and reduced-motion support.

## Try the demo

1. Open [Lumio](https://tutos-chi.vercel.app/).
2. Browse the public course catalog or open **Log in**.
3. Select **Try as learner** or **Try as teacher** to explore a populated demo workspace.
4. Try quizzes, saved courses, revision sheets, or the teacher revenue reports.

Demo activity is stored in the current browser. To restore the sample workspace, use **My profile → Account → Reset demo data**.

## Technology

| Area | Technology |
| --- | --- |
| UI | React 18, TypeScript |
| Build tooling | Vite |
| Styling | Tailwind CSS, CSS theme variables |
| Navigation | React Router |
| State management | Zustand |
| Charts | Recharts |
| Icons | Lucide React |
| Localization foundation | i18next, react-i18next |
| Demo persistence | Async services backed by localStorage |
| Hosting | Vercel |

## Engineering highlights

- Separate learner and teacher experiences with role-based route guards.
- Reusable components for courses, quizzes, study sheets, dialogs, and charts.
- Asynchronous service interfaces that separate UI behavior from browser storage.
- Serialized storage writes and workspace migrations to preserve local demo data.
- Lazy-loaded page bundles, including the teacher reporting views.
- Centralized brand configuration, theme tokens, and localization resources.

## Demo scope

Lumio currently uses seeded data and browser storage with mock authentication. It does not connect to a production backend, payment processor, email service, or AI API. The interface currently uses English, with a localization foundation in place.

Checkout, full lesson playback, course editing, certificate issuance, and mentoring bookings are planned features or preview placeholders. Revenue and payout figures are simulated; no money is transferred.

## Portfolio summary

> Lumio is a responsive e-learning platform built with React and TypeScript, featuring course discovery, learner and teacher workspaces, interactive quizzes, revision sheets, progress tracking, and simulated revenue reporting. The project demonstrates reusable UI components, role-based navigation, persistent browser state, and light/dark theming.

**Live application:** [tutos-chi.vercel.app](https://tutos-chi.vercel.app/)
# lumio-showcase
