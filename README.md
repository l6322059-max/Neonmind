# NeonMind 3.0

A black-and-neon AI chat assistant built with Flutter for Android and Windows desktop.

## What it does

- Many AI providers, including Claude, ChatGPT, Gemini, Grok, DeepSeek, Mistral, Groq and OpenRouter.
- Liquid-glass panels, aurora background and animated neon effects.
- Supported photo and file attachments.
- AI-generated documents, spreadsheets, presentations, text, CSV, HTML, SVG and code files.
- Multilingual interface and a PIN-protected admin panel.
- Basic offline functions.

## Build for Windows PC

1. Open this repository on GitHub and select Actions.
2. Run Build Windows PC App, or push a commit to main.
3. Open the completed workflow run and download the NeonMind-Windows-x64 artifact.
4. Extract NeonMind-Windows-x64.zip into a folder.
5. Run neonmind.exe. Keep the other files and folders beside the EXE; they are required.

This workflow builds a Windows x64 desktop application. It does not produce an MSI installer.

## Build the Android APK

1. Open Actions and run Build APK.
2. Download NeonMind-apk from the completed run.
3. Install app-release.apk on your Android device.

## Main source files

- lib/main.dart — chat screen and message interface
- lib/effects.dart — glass, aurora and rainbow effects
- lib/ai_engine.dart — AI providers, attachments and offline functions
- lib/admin.dart — settings and admin panel

## Privacy and accuracy

NeonMind is an AI assistant and can make mistakes. When you configure a provider, messages and selected attachments are sent to that provider and handled under its terms. Keep API keys private and do not commit them to this repository.
