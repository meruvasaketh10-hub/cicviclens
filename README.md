# CivicLens AI

An AI-powered app that helps citizens report civic problems in their city or town, and sends them to the local municipal office to be resolved.

## Problem
People often face issues like water supply problems and damaged roads, but there is no simple way to report them to the right authority. Complaints get lost, delayed, or reach the wrong department.

## Solution
CivicLens AI lets citizens submit a complaint about any civic issue (water, roads, and more). The AI classifies the complaint, and it is forwarded to the local municipal office, which can view it and take action.

## How It Works
1. A citizen submits a complaint in the web app.
2. AI classifies the complaint by type (for example water, roads).
3. The complaint is saved in the database.
4. The municipal office views the complaint and acts on it.

## Google Technologies Used
- **Gemini API (Google AI Studio):** classifies complaints (classify.mjs)
- **Firebase Cloud Functions:** backend logic
- **Cloud Firestore:** stores complaints
- **Firebase Hosting:** hosts the web app

## Live Demo
https://civiclens-ai-f82bb.web.app

## Demo Video
https://youtu.be/7qsffJgNit4?si=wV_lEWbgqBkftl1i

## Setup
1. Clone this repository
2. Run `npm install` inside the `functions` folder
3. Add your own Gemini API key as an environment variable (never commit it)
4. Run `firebase deploy`

## Team
Add your name and team members here
