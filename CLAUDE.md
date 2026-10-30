# HUSH — project direction

- **Platform target: iPhone only, mobile only.** Optimize every change for iOS Safari / Home Screen (standalone) mode on iPhone screens. Desktop and Android are not targets; keyboard controls may stay but must never drive design decisions.
- **Future plan:** this will be wrapped as a native iPhone app (e.g. WKWebView / Capacitor). Prefer approaches that will survive that wrap: no reliance on browser chrome, keep everything self-contained and offline-capable, respect safe-area insets, avoid web-only APIs that iOS lacks.
- **Only the GitHub repo is updated.** Do not republish the claude.ai artifact.
- iOS notes: `navigator.vibrate` is unsupported on iPhone (native haptics come with the app wrap). WebAudio needs a user gesture to start and is muted by the ring/silent switch. Test layouts at 390×844 and 430×932 with notch/home-indicator safe areas.
- Workflow: commit straight to `main`, bump `VER` in index.html and `VERSION` in sw.js on each release, and add a CHANGELOG entry.
