---
title: Support
---

# Bonjo Support

Bonjo (好周Bonjo) is a personal recovery app for iOS. When you open a distracting app, it can catch you and offer one small, concrete break — a breathing exercise, a short walk, a few minutes of quiet — and afterwards you can note how it went.

Everything in this internal-test build runs on your device. There is no cloud AI feature in it: nothing you write or choose is processed on our servers.

Note: the app interface is available in Simplified Chinese and English. Change it in 「我」→偏好与数据→语言 (it applies the next time the app starts).

## Quick answers

**What does this build actually do?**

One loop: you get interrupted → Bonjo offers a small recovery experience → you try it → you tell it how it felt (a bit better / about the same / more tired). On top of that you can browse a library of recovery methods, write a short journal entry, and look back at what you did. The weekly planner is not part of this build.

**How do I set up 拦一下 (Blocky)?**

In the app: 「我」→ 拦一下 → 设置教程. It walks you through two steps: (1) install the official 「拦一下 Blocky」 shortcut, (2) create one automation yourself — "when this app is opened → run 拦一下". iOS only lets you create automations by hand, so it takes a minute, once. When you pick a timed break, Bonjo can take you back to where you were: for 40+ common apps (抖音 / 小红书 / 微信 / Instagram / Facebook / TikTok …) it does that automatically.

**Where is my data?**

Your profile, journal entries, notes and everything else stay on your device — no account, no login, no tracking. Two things can still leave the device in this build:

- **Anonymous usage events** — numbers and enumerations only, never the content you wrote. They are sent while the app is open so we can see which parts people actually use. You can switch them off in 「我」→偏好与数据→分享匿名使用数据.
- **The collection queue** — only if you use the 「收藏到好周」 shortcut to share a link. The link and the text you shared are queued on our server until the app picks them up, and pictures from that page may be sent along so the app can describe them for you. Video and audio files are never uploaded: speech recognition runs on your device with the system recognizer.

**How do I turn the anonymous data program off?**

「我」→偏好与数据→分享匿名使用数据. It is on by default; switching it off stops all collection and upload from then on.

**Can I collect things while browsing?**

The in-app collection list is being simplified out of this beta, so the app does not show it right now. The 「收藏到好周」 shortcut still works if you already installed it, and shared items are saved on your device — but there is no in-app list to browse them in yet.

**Can I change the language?**

「我」→偏好与数据→语言 — 跟随系统 / 中文 / English. It applies the next time the app starts.

## Contact

Report a bug or request a feature: [open an issue](https://github.com/willAries/bonjo-site/issues).
