# Obsidian

The official app for **Obsidian** — an independent, members-only venture (18+), separate from SMX TV. Presented by Corey Jones, Executive Producer, SENOJ Media X.

- Android WebView shell, package `com.senojmediax.obsidian`
- The Obsidian site is bundled as local assets (`app/src/main/assets/`) — the app does not load the SMX TV site.
- CI: GitHub Actions downloads Gradle 8.10.2 directly and runs `gradle assembleDebug`; the debug APK is uploaded as the `obsidian-debug` artifact.
