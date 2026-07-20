# Chapimo

Chapimo is a Firebase-hosted progressive web app that helps people find rental housing in Abidjan by connecting clients with real estate agencies.

## What It Does

- Lets clients search by property type, commune, neighborhood, and budget.
- Lets clients send an active housing request when available listings do not fit.
- Lets agencies view client requests and propose matching homes.
- Lets agencies publish housing listings with images and rent.
- Includes admin validation for agency collaborators.
- Tracks visits, unique devices, app installs, and notification activation.

## Live Demo

https://chapimo.com

## Tech Stack

- HTML, CSS, and JavaScript
- Firebase Hosting
- Firestore
- Firebase Cloud Functions
- Web Push / PWA support

## Local Setup

Install dependencies:

```bash
npm install
```

Build the app:

```bash
npm run build
```

Deploy to Firebase:

```bash
firebase deploy --only hosting --project chapimo
```

## How Codex And GPT-5.6 Were Used

Codex was used as a full development partner to design, implement, debug, and deploy Chapimo. It helped build the client flow, agency flow, admin validation, Firebase hosting, PWA behavior, notifications, image handling, request/listing storage, mobile UI refinements, and analytics counters.

GPT-5.6/Codex also helped refine the product wording, UX decisions, competition submission material, and the explanation of how the application solves the housing-search problem in Abidjan.

## Project Focus

Chapimo starts with Abidjan, Cote d'Ivoire, and focuses on local communes and neighborhoods. The long-term business model is to let real estate agencies pay a fixed fee to unlock high-intent client contacts while keeping the client experience simple.
