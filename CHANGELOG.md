# Changelog

All notable releases and updates of Tap & Trace (TapNTrace) are documented here.

## [v2.0.1] - 2026-11-02 (Maintenance & UX Update) 🚀
- **Network URL Actions Dialog:** Tapping any request URL in the Network section now shows options to **Open Link in New Tab**, **Copy Link**, **View Request Details**, **Copy as cURL**, and **Replay Request**.
- **Fixed Network Selection Crash:** Resolved recursive invocation in cURL generation that previously caused stack overflow when tapping network items.
- **Request Details Quick Actions:** Added direct "Open in New Tab" and "Copy URL" buttons to the Network Request details action bar and assist chips.

## [v2.0.0] - 2026-09-05 (Major Feature Release - Free Forever) 🚀
- **Network Throttling & Offline Simulation:** Real-time mobile network condition emulation: Fast 3G (1.5 Mbps), Slow 3G (400 Kbps), and 1-tap Offline mode with sticky alert banners and request interception.
- **Strict GDPR & Privacy Mode:** 1-tap zero-logging mode that automatically clears cookies, storage, cache, DOM trees, and console history on page navigation or tab close. Visual shield badge in address bar.
- **User Scripts & Extensions Framework:** Built-in modular extension injector supporting custom JS/CSS tools including CSS Layout Debugger, A11y Accessibility Outliner, and Smart Dark Mode.
- **1-Tap Markdown Bug Report Exporter:** Formats current page URL, device specs, emulation profile, console error logs with AI diagnostics, and network failure summaries into clean Markdown for GitHub / GitLab / Slack.
- **Save Page for Offline Inspection:** Capture full page DOM outerHTML snapshot for offsite/offline debugging and analysis.
- **Enhanced Network Tooling:** Direct dropdown throttling switcher, bulk HAR JSON export, and Postman Collection generator directly from the Network toolbar.
- **Updated DevTools Engine:** Upgraded target SDK to 35, Jetpack Compose Material 3 UI enhancements, and improved Android WebView client handling.

## [v1.0.0] - 2026-08-25 (Initial Release - 100% Free)
- **Elements Panel:** Visual Tap-to-Inspect bounding box overlays and live DOM hierarchy tree.
- **Live Editor:** In-place HTML attribute editing, inline CSS styling, and live DOM node deletion.
- **Console REPL:** Interactive JavaScript evaluation environment with syntax highlighting and runtime log interception.
- **Network Monitor:** Visual waterfall timeline, latency timings, and one-tap "Copy as cURL" exporter.
- **Storage Viewer:** Inspect cookies, LocalStorage, and SessionStorage keys/values.
- **Emulation & Fingerprinting:** User-Agent switching and screen dimension emulation.
- **Playwright CDP Bridge:** On-device Chrome DevTools Protocol automation connector.
- **Pricing:** 100% Free APK to use and download worldwide.

