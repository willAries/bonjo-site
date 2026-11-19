---
title: Privacy Policy
---

# Bonjo Privacy Policy

Last updated: 2026-11-19

Bonjo ("the App") is a personal weekly planner. This policy explains what data the App handles and why. In short: **almost everything stays on your device; a minimal amount is sent to our server to run AI features and to send anonymous usage statistics, and it is never used to track you or sold to anyone.**

## What stays on your device

Your directions, goals, routine, energy preferences, collected items, plans, check-ins and reviews are stored **locally** on your device (SwiftData). They are not uploaded as a database. You can delete them at any time by deleting the App or the data inside it.

## What is sent to our server, and why

To generate weekly plans, auto-classify saved links, or complete onboarding, the App sends the relevant context to our own backend service, which calls an AI model and returns the result. Depending on the feature you use, that context can include:

- your questionnaire answers (directions, routine, time allocation, energy preferences) and any free-text note you write;
- the titles, excerpts and body text of items you saved, plus the text extracted from those pages (including OCR text and, for videos, a speech-to-text transcription — the **audio file itself is never uploaded**);
- your check-ins (how you said you felt) and short journal entries you write.

This content is:

- used **only** to produce the feature you asked for (App Functionality);
- not linked to your identity — the App has no accounts and no login;
- not used for advertising or tracking;
- queued links you collect via the Share Sheet are stored on our server until the App fetches them, then marked consumed.

## Device identifier

The App generates a random local identifier (a UUID) and sends it with AI requests and with anonymous usage events, so we can enforce a fair daily usage quota per device and count how often a given device uses each feature. It is not derived from any hardware ID, is not linked to you, and cannot be used to track you across apps. It is not combined with any other identifier, and we do not use it to recognize you across apps or devices.

## Anonymous usage data (improvement program)

The App includes an anonymous usage-data program (similar in spirit to Apple's developer improvement programs). **It is on by default** — for anyone who has never touched the switch; if you turned it off before, it stays off. You can change it any time in Settings ("我" → 分享匿名使用数据), and turning it off stops all collection and upload going forward.

While it is on, the App periodically sends a small amount of **anonymous behavioral metadata about the focus-guard and recovery features**:

- which app was being intercepted, the outcome of that interception (e.g. picked a small task, set a timer, walked away without tapping anything, or went back), and how many times that app was reopened within a short window;
- the state you picked at that moment (tired / restless / low on energy …), the type and length of the activity that was suggested, and whether you pinned it or asked for another one;
- how busy or how free your day was at that time.

- All of it is **enumerations and numbers**. It **never includes content**: no goals, schedule or task titles, notes, saved items, the text of the activity that was shown to you, or anything you type or that AI generates.
- The device identifier is the same random UUID described above; it is not linked to your identity.
- Events are uploaded in small batches only while the App is open. Nothing is collected or sent while the App is closed.
- This is independent of the data transfers the AI features need (see above) — turning the anonymous program off does not change how the AI features work.

## Third-party AI processing

AI features are powered by a third-party model API (MiniMax) called by our own server. Only the content described above is transmitted for processing. We do not send your contacts, photos, location, or any other data.

Speech recognition for saved videos runs **on your device** (the system speech recognizer). The resulting text may then be sent to our server as part of that saved item so it can be summarized, but the audio itself is never uploaded. If you do not grant speech-recognition permission, the feature is skipped and the rest of summary still works.

## Data retention

Locally stored data persists until you delete it. Server-side request content is processed transiently; collected-link queue rows are retained until consumed. Quota counters store only the random device identifier, a route name and a count, and are naturally bounded to daily rows. Anonymous usage events are retained in our database for product research and deleted on request.

## Children

The App is not directed to children under 4 and contains no age-restricted content.

## Your choices

- Delete all local data by deleting the App.
- Turn the anonymous usage program off (or back on) any time in Settings ("我" → 分享匿名使用数据). It is **on by default**, so if you would rather nothing be collected, switching it off is enough — no further action is needed.

## Contact

Questions or privacy requests: [open an issue](https://github.com/willAries/bonjo-site/issues).
