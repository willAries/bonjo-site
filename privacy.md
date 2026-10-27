---
title: Privacy Policy
---

# Bonjo Privacy Policy

Last updated: 2026-10-28

Bonjo ("the App") is a personal weekly planner. This policy explains what data the App handles and why. In short: **almost everything stays on your device; a minimal amount is sent to our server only to run AI features, and it is never used to track you or sold to anyone.**

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

The App generates a random local identifier (a UUID) and sends it with AI requests so we can enforce a fair daily usage quota per device. It is not derived from any hardware ID, is not linked to you, and cannot be used to track you across apps.

The same identifier lets our server count how often a given device uses each feature, so it can enforce per-device daily limits. It is not combined with any other identifier, and we do not use it to recognize you across apps or devices.

## Optional improvement program (anonymous usage data)

The App includes an opt-in improvement program (off by default, similar in spirit to Apple's developer improvement programs). If you turn it on, the App periodically sends a small amount of **anonymous behavioral metadata about the focus-guard feature**: which app was being intercepted, the outcome of that interception (e.g. picked a small task, set a timer, walked away without tapping anything, or went back), how many times that app was reopened within a short window, and timestamps. This helps us understand whether the interception moment genuinely helps people step away, and which kinds of suggestions work.

- Data is collected **only after you explicitly opt in** (asked once during onboarding; changeable any time in Settings). Turning it off stops all collection and upload going forward.
- It **never includes content**: no goals, schedule or task titles, notes, saved items, or anything you type or that AI generates — only the metadata listed above.
- The device identifier is the same random UUID described above; it is not linked to your identity.
- Events are uploaded in small batches only while the App is open. Nothing is collected or sent while the App is closed.

## Third-party AI processing

AI features are powered by a third-party model API (MiniMax) called by our own server. Only the content described above is transmitted for processing. We do not send your contacts, photos, location, or any other data.

Speech recognition for saved videos runs **on your device** (the system speech recognizer). The resulting text may then be sent to our server as part of that saved item so it can be summarized, but the audio itself is never uploaded. If you do not grant speech-recognition permission, the feature is skipped and the rest of the summary still works.

## Data retention

Locally stored data persists until you delete it. Server-side request content is processed transiently; collected-link queue rows are retained until consumed. Quota counters store only the random device identifier, a route name and a count, and are naturally bounded to daily rows. Opt-in improvement-program events are retained in our database for product research and deleted on request.

## Children

The App is not directed to children under 4 and contains no age-restricted content.

## Your choices

- Use the App fully offline in Demo Mode — switch it on at Settings → Me → AI Setup ("我" → AI 设置) and clear the server configuration. From then on no data leaves your device, and weekly plans are generated locally.
- Delete all local data by deleting the App.
- Clear the server configuration any time in Settings ("我" → AI 设置).
- Turn the improvement program on or off any time in Settings ("我" → 分享匿名使用数据); before you opt in, nothing is collected or sent.

## Contact

Questions or privacy requests: [open an issue](https://github.com/willAries/bonjo-site/issues).
