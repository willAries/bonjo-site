---
title: Privacy Policy
---

# Bonjo Privacy Policy

Last updated: 2026-10-16

Bonjo ("the App") is a personal weekly planner. This policy explains what data the App handles and why. In short: **almost everything stays on your device; a minimal amount is sent to our server only to run AI features, and it is never used to track you or sold to anyone.**

## What stays on your device

Your directions, goals, routine, energy preferences, collected items, plans, check-ins and reviews are stored **locally** on your device (SwiftData). They are not uploaded as a database. You can delete them at any time by deleting the App or the data inside it.

## What is sent to our server, and why

To generate weekly plans, auto-classify saved links, or complete onboarding, the App sends the relevant context (your profile answers, saved item titles/excerpts, and your note) to our own backend service, which calls an AI model and returns the result. This content is:

- used **only** to produce the feature you asked for (App Functionality);
- not linked to your identity — the App has no accounts and no login;
- not used for advertising or tracking;
- queued links you collect via the Share Sheet are stored on our server until the App fetches them, then marked consumed.

## Device identifier

The App generates a random local identifier (a UUID) and sends it with AI requests so we can enforce a fair daily usage quota per device. It is not derived from any hardware ID, is not linked to you, and cannot be used to track you across apps.

## Third-party AI processing

AI features are powered by a third-party model API (MiniMax) called by our own server. Only the content described above is transmitted for processing. We do not send your contacts, photos, location, or any other data.

## Data retention

Locally stored data persists until you delete it. Server-side request content is processed transiently; collected-link queue rows are retained until consumed. Quota counters store only the random device identifier, a route name and a count, and are naturally bounded to daily rows.

## Children

The App is not directed at children under 4 and contains no age-restricted content.

## Your choices

- Use the App fully offline in Demo Mode (no data leaves the device).
- Delete all local data by deleting the App.
- Clear the server configuration any time in Settings ("我" → AI 设置).

## Contact

Questions or privacy requests: [open an issue](https://github.com/willAries/bonjo-site/issues).
