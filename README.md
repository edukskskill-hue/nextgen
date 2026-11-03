# KSK Academy

A responsive public website and launch-dashboard preview for KSK Academy, a new learning initiative by KSK Skill. The site uses an honest startup-school identity: zero students, zero teachers, admissions coming soon, and no fabricated school history or results.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the repository with any static web server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## What’s included

- Responsive homepage with mobile navigation, visual hero, academy approach, announcements, and launch information.
- Register-interest dialog with client-side validation. It does **not** transmit or persist personal data; the submit action only shows a demo confirmation.
- Launch dashboard preview with intentional zero-state statistics. It is a visual prototype, not an authenticated administration system.
- Accessibility considerations including semantic sections, keyboard-dismissable dialog, live status message, and reduced-motion support.

## Production notes

This repository is a frontend prototype. It does not include a database, secure authentication, role enforcement, email delivery, file storage, or a functioning admissions system. Do not use the dashboard preview to manage real student data. Before launch, connect a server-side API and database, implement server-enforced Super Admin and Chairman permissions, add appropriate privacy/security controls, and publish only verified contact, campus, curriculum, and admissions details. Never place passwords, API keys, or email credentials in frontend code.

The site references Google Fonts and Lucide icons from CDNs; those visual enhancements require an internet connection. System fonts and page content remain available if the CDNs cannot be reached.
