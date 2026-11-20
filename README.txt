AI CREATIVE STUDIO v1.0

WEB:
- Upload index.html, manifest.webmanifest, sw.js to GitHub Pages root.
- Enable Pages: main / root.
- The PWA can be installed from Chrome > menu > Install app / Add to Home screen.

REAL GENERATION:
IMAGE:
- Uses the legacy public Pollinations image URL route (image.pollinations.ai) as an experimental free/no-key route.
- It is community/public and may be rate-limited, changed, unavailable, or return different quality/resolutions.
- No guarantee of commercial rights: check model/provider terms before stock submission.
VIDEO:
- Official Pollinations video API requires an authorized secret key and model access; not guaranteed free.
- Add key in Settings. The app queries the live video model catalog and sends a synchronous video request.
- LTX Studio / Higgsfield links open their official websites; they are not embedded free APIs.
- LTX API itself requires credits and API key.

ANDROID:
- This ZIP includes Capacitor config and GitHub Actions workflow to build a debug APK.
- Upload contents to GitHub repository, then open Actions > Build Android APK > Run workflow.
- Download artifact ai-creative-studio-debug-apk after successful workflow.
- Debug APK is for testing/sideloading, not Play Store release.
- A signed release APK requires a signing keystore and secure GitHub secrets.

SECURITY:
- API key is stored in localStorage on this device only; not safe for a public multi-user app.
- For production, use a backend proxy and secret manager. Never hardcode private API keys in source.
- Browser/local app storage is not cloud sync. Download generated assets to back them up.

LIMITS:
- OPPO F11 Pro is only the client; image/video generation runs on provider servers.
- Free image route is experimental and may be slow or rate-limited.
- No stable, high-quality, unlimited, no-key video generation API is promised. Paid cloud GPU APIs typically charge by duration/credits.
- This package was code-checked only; provider APIs and Android build must be tested in your deployment.
