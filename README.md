# GameCritic

GameCritic is a static, dark-themed front-end demo for a gaming reviews platform. It features animated hero statistics, a trending games grid, and a responsive partners/sponsors marquee optimized for high-contrast logos.

Features
- Animated counters with K/M formatting and IntersectionObserver-based lazy start.
- Responsive partners marquee with dark-logo detection and light "plate" fallback.
- Accessible ESRB text badge fallback when an official logo isn't available.
- Mobile-friendly layout and modern cyberpunk-inspired visual design.

Quick start
1. Open `index.html` in a modern browser (no build step required).
2. Place additional images in `assets/images/` and update `index.html` if needed.

Notes
- The site is intentionally static and uses only HTML, CSS, and JavaScript.
- For logos loaded from external domains, the runtime dark-logo detection may be blocked by CORS; use explicit `logo-plate` classes for guaranteed results.

Contributing
- Feel free to open issues or create PRs. Keep image filenames Git-friendly (lowercase, hyphens, no spaces).

License
- MIT License (see LICENSE file).