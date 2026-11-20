---
title: Privacy Policy
---

# Bonjo Privacy Policy

Last updated: 2026-11-20

Bonjo ("the App") is a personal recovery app. This policy explains what data the App handles and why. In short: **almost everything stays on your device. In this internal-test build, no content you write is processed on our server; what can still leave the device is a small amount of anonymous usage metadata, and — only if you use the collection shortcut — the link or text you chose to share. It is never used to track you or sold to anyone.**

## What stays on your device

Your directions, goals, routine, energy preferences, collected items, plans, check-ins, journal entries and reviews are stored **locally** on your device (SwiftData). They are not uploaded as a database. You can delete them at any time by deleting the App or the data inside it.

## What is sent to our server, and why

This build of the App is deliberately self-contained. The features that used to send your answers and notes to our server for AI processing — weekly planning, collection summaries, onboarding templates — are **turned off in this internal-test version**. Nothing you write or choose is sent to a model, and no content leaves your device for processing, with two exceptions:

**1. Anonymous usage events.** Numbers and enumerations only — see the section below.

**2. The collection queue.** If you use the official 「收藏到好周」 shortcut to share a link from another app, the link and any text you shared are sent to our server and queued there until the App fetches them; queued rows are then marked consumed. For an item that includes pictures, the App may send a small set of images (and, for videos, a few extracted frames) so our server can describe them for you. **Video and audio files are never uploaded** — speech recognition for saved videos runs on your device with the system recognizer. If you never use the shortcut, none of this happens.

Whatever is sent:

- is used **only** to produce the feature you asked for (App Functionality);
- is not linked to your identity — the App has no accounts and no login;
- is not used for advertising or tracking.

## Device identifier

The App generates a random local identifier (a UUID) and sends it with the anonymous usage events described below and with links you share through the collection shortcut, so we can count how often a given device uses each feature and keep our service within fair-use limits. It is not derived from any hardware ID, is not linked to you, and cannot be used to track you across apps. It is not combined with any other identifier, and we do not use it to recognize you across apps or devices.

## Anonymous usage data (improvement program)

The App includes an anonymous usage-data program (similar in spirit to Apple's developer improvement programs). **It is on by default** — for anyone who has never touched the switch; if you turned it off before, it stays off. You can change it any time in the app ("我" → 偏好与数据 → 分享匿名使用数据), and turning it off stops all collection and upload going forward.

While it is on, the App periodically sends a small amount of **anonymous behavioral metadata about the interception (拦一下) and recovery features**:

- which app was being intercepted, the outcome of that interception (e.g. picked a small task, set a timer, walked away without tapping anything, or went back), and how many times that app was reopened within a short window;
- the state you picked at that moment (tired / restless / low on energy …), the type and length of the activity that was suggested, and whether you pinned it or asked for another one;
- how busy or how free your day was at that time.

- All of it is **enumerations and numbers**. It **never includes content**: no goals, schedule or task titles, notes, saved items, the text of the activity that was shown to you, or anything you type.
- The device identifier is the same random UUID described above; it is not linked to your identity.
- Events are uploaded in small batches only while the App is open. Nothing is collected or sent while the App is closed.
- This is independent of the collection queue described above — turning the anonymous program off does not change how the collection shortcut works.

## Third-party AI processing — none in this version

None in this version. The App does not call any third-party model API in this internal-test build: the model service is not reached, and no content is sent for it to process. If those features return in a future version, this section will be updated before that version ships and will describe exactly what is sent, and why.

## Data retention

Locally stored data persists until you delete it. Server-side content is limited to the collection queue: queued rows are retained until the App consumes them and are then marked consumed. Quota counters store only the random device identifier, a route name and a count, and are naturally bounded to daily rows. Anonymous usage events are retained in our database for product research and deleted on request.

## Children

The App is not directed to children under 4 and contains no age-restricted content.

## Your choices

- Delete all local data by deleting the App.
- Turn the anonymous usage program off (or back on) any time in the app ("我" → 偏好与数据 → 分享匿名使用数据). It is **on by default**, so if you would rather nothing be collected, switching it off is enough — no further action is needed.
- Simply not use the 「收藏到好周」 shortcut: then no content of yours is sent to our server at all.

## Contact

Questions or privacy requests: [open an issue](https://github.com/willAries/bonjo-site/issues).
