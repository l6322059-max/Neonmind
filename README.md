# NeonMind 3.0

A black-and-neon AI chat assistant for Android, built with Flutter.

## What it does

- **Many AIs in one app.** Claude, ChatGPT, Gemini, Grok, DeepSeek, Mistral, Groq, OpenRouter, or any OpenAI-compatible server. Each keeps its own key and model.
- **Liquid glass and rainbow light.** Frosted glass panels over a drifting aurora, animated rainbow borders, a rainbow orb.
- **Photos and files.** The yellow + button sends photos (gallery or camera), PDFs, and text or code files to the AI.
- **The AI makes real files.** Ask for a PowerPoint (neon-themed slides), a Word document or an Excel sheet (with working formulas) and it appears as a file card with a Save button. It also writes text, CSV, HTML, SVG and code files.
- **100+ languages.** Settings > Language. The AI answers in your language, and the app translates its own screens using your AI (RTL languages supported). You can also type any other language.
- **The AI sends things back.** It can create files (notes, code, CSV...) with a Save button, and `/image a neon city` makes pictures with ChatGPT or Gemini.
- **Live activity.** After you send, a card shows each step with a timer while the AI works.
- **Key and credit check.** Saving a new key checks it once and shows your credit where the provider shares it (DeepSeek, OpenRouter).
- **Admin panel.** PIN-locked: usage stats, effect switches, the AI's system prompt, image models, chat export, erase all data.
- **Offline brain.** With no key it still does math, time, date and jokes.

## Declaration

NeonMind is an AI assistant. It can be wrong, so double-check anything important. It is not a substitute for professional medical, legal, or financial advice. When an API key is set, your messages, photos and files are sent to the AI company you picked and handled under that company's terms. Keys and the admin PIN hash are stored only on your device. The AI's identity and behavior rules live in `kPersona` in `lib/ai_engine.dart` and can be edited in the Admin panel.

## Get the APK (no setup on your computer)

1. Upload everything to a GitHub repo (keep the folder layout: `lib/` with 4 Dart files, `pubspec.yaml`, `.github/workflows/build-apk.yml`).
2. Open **Actions**, run **Build APK**.
3. Download **NeonMind-apk** from the finished run, unzip, install `app-release.apk`.

## Files

- `lib/main.dart` chat screen, + menu, message bar, live activity
- `lib/effects.dart` glass, aurora, rainbow light
- `lib/ai_engine.dart` providers, attachments, images, key check, offline brain
- `lib/admin.dart` Settings and Admin panel
