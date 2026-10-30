# HUSH — project direction

- **Platform target: mobile only — all phones (iPhone and Android).** Optimize every change for touch on phone screens, in mobile browsers and Home Screen (standalone/fullscreen) mode. Desktop is not a target: keyboard controls may stay but must never drive design decisions.
- **Future plan:** this will be wrapped as a native mobile app (e.g. Capacitor / WebView). Prefer approaches that survive that wrap: no reliance on browser chrome, keep everything self-contained and offline-capable, respect safe-area insets, feature-detect platform APIs.
- **Only the GitHub repo is updated.** Do not republish the claude.ai artifact.
- Platform notes:
  - iOS Safari: `navigator.vibrate` is unsupported (show vibration settings only where supported; native haptics come with the app wrap). WebAudio is muted by the ring/silent switch and needs a user gesture to start.
  - Android Chrome: vibration works; `display: fullscreen` manifest is honored; watch for varied aspect ratios and gesture-nav insets.
  - Test layouts at 360×800, 390×844 and 430×932 with notch/home-indicator safe areas.
- Workflow: commit straight to `main`, bump `VER` in index.html and `VERSION` in sw.js on each release, and add a CHANGELOG entry.
