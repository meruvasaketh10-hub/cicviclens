# CivicLens AI

One-line description: what it does and for whom.

## Problem
Describe the civic issue you're solving (2-4 sentences).

## Solution
How CivicLens solves it. Explain what the user does and what the AI does.

## Google Technologies Used
- **Google AI Studio / Gemini API**: used in classify.mjs to classify citizen reports
- **Firebase Firestore**: stores reports and results
- **Firebase Cloud Functions**: runs the backend logic
- **Firebase Hosting**: hosts the web app

## Architecture
User → Web app (Firebase Hosting) → Cloud Function → Gemini API → Firestore → Dashboard

## Live Demo
https://your-project.web.app

## Demo Video
https://youtube.com/...

## Setup
1. Clone the repo
2. Run `npm install` inside `functions/`
3. Add your own key: `GEMINI_API_KEY=your_key_here`
4. Run `firebase deploy`

## Team
Names and roles
