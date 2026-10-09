# يقظ | Yaqez — Cybersecurity Awareness Lab

An Arabic, mobile-friendly cybersecurity awareness experience for students.

## Features
- Interactive phishing quiz with email and SMS examples.
- Password-strength feedback and a cryptographically random password generator.
- Two-factor authentication (2FA) checklist and practical guidance.
- Responsive layout, keyboard focus indicators, and light/dark theme support.

## Run locally
Open `index.html` in a modern browser. No build step or server is required.

## GitHub Pages
The `.github/workflows/pages.yml` workflow publishes the repository root to GitHub Pages whenever changes are pushed to `main`, and can also be run manually from the Actions tab.

Once deployment succeeds, the site should be available at:
https://nour2013hossam.github.io/Cybersecurity/

## Privacy and safety
- The password checker runs locally in your browser. Never enter a real password; use a sample.
- The password generator uses the browser's Web Crypto API.
- The phishing examples are educational simulations. Do not enter real credentials or one-time codes.
