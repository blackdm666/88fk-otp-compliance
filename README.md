# 88FK OTP Compliance Site

This repository contains a GitHub Pages-ready static site for 88FK OTP.

The content positions 88FK as an enterprise OTP and SMS verification service for authorized first-party business workflows. It intentionally avoids promoting anonymous code receiving, third-party account verification bypass, bulk registration, or platform rule evasion.

## Pages Setup

1. Open the repository settings on GitHub.
2. Go to **Pages**.
3. Set the source to **Deploy from a branch**.
4. Select the `main` branch and `/root`.
5. Save and wait for GitHub Pages to publish the site.

## Local Files

- `index.html` - landing page and compliance copy
- `styles.css` - responsive visual design

## Compliance Notes

Recommended operating rules:

- Use only for authorized first-party business verification workflows.
- Do not use for bypassing third-party platform verification or creating fake accounts.
- Apply request frequency limits by account, phone number, IP, device, and scene.
- Keep necessary audit logs for order checks, security review, and abuse handling.
- Suspend or reject suspicious, fraudulent, or abusive requests.
