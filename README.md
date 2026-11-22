# Feelings Wheel

Created by Olink Technologies.

## What it is

A free, interactive feelings wheel. Tap a feeling, see the need underneath it, and build one small habit around it. 12 core feelings, 48 families, 97 specific feelings — the full Nonviolent Communication inventory, turned into a page anyone can open and use. No account, no sign-up, nothing uploaded anywhere.

## Why I built it

I found a paper magnet-board feelings wheel — "Feelings when your needs are met / not met" — and kept thinking it should be something people could actually use, not just look at. Naming what you feel is a skill, and most of us were never taught it. I wanted a tool that doesn't just label the feeling but shows you the need behind it and what helps — something simple enough to open in the middle of a hard moment, and practical enough to build a habit from.

So I built this: free, for anyone. If it helps one person name what they're feeling and do one small thing about it, it's done its job.

## How it's built

One self-contained page — `index.html`. No server, no database, no account, no tracking. Everything runs in your browser, and nothing you type or say leaves it.

- **The wheel** — 12 core feelings, 48 families, 97 specific feelings. Tap any feeling to see the need behind it and what helps.
- **Deep dives** — every feeling has a page of its own: what it usually means, what need it points to, and what to try.
- **Habit Lab** — pick a feeling and build a small habit around it: a cue, an if-then plan, and a 7-day tracker.
- **Check-in** — a guided "I feel… because I need…" sentence, in under a minute.
- **My Notes** — a private pad with rotating prompts, word count, and voice dictation.
- **Light and dark themes** — dark by default, cream one tap away.

The type is set in Instrument Serif, Schibsted Grotesk, and DM Mono, and the design draws on the Kintale design system.

## Who it's for

- **Anyone working on themselves** — if you want to get better at naming what you feel instead of just reacting to it.
- **Coaches and therapists** — a free tool to hand a client between sessions, or to open together in one.
- **Teams and organizations** — people-skills and clinical development work, workshops, check-ins.
- **Teachers and parents** — emotional literacy starts with having the words.

## Use it

Open https://olitamrat.github.io/feelings-wheel/ — or download `index.html` and open it in any browser. It works offline once saved, except the fonts and the first Whisper model download, which need a connection — and the built-in dictation, which needs a supported browser.

## Honest limits

- Notes, goals and habits save in your browser, on your device — they are never sent anywhere, and you can erase them any time from My Notes. Copy or Download still works as a backup. Saving is per device and per browser: what you save on your phone won't appear on your laptop.
- Voice dictation has two modes. The built-in one uses your browser's speech recognition and needs a supported browser (Chrome works best). Whisper dictation runs OpenAI's open-source Whisper model entirely on your device — no API key, no server — after a one-time ~40 MB model download; it works in browsers the built-in mode doesn't. Nothing you say is recorded or sent by this page in either mode.

## Credits

- Feelings inventory: the Nonviolent Communication (NVC) feelings list, from Marshall Rosenberg's work.
- Typography: Instrument Serif, Schibsted Grotesk, DM Mono.
- Visual design draws on the Kintale design system.

## License

MIT — Copyright (c) 2026 Olink Technologies. Use it, share it, adapt it. If it helps someone, that is the point.
