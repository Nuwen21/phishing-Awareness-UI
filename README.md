# URL & Login Page Verification Study (Security Awareness Demo)

> **Educational Purpose Only**  
> This project is a static UI study created to raise awareness about phishing and lookalike login pages. Its goal is to show how easily a webpage can mimic a familiar sign-in flow and why users should always inspect the browser address bar and URL before entering any credentials.  
> **Do not enter real usernames, emails, or passwords into this demo.**

## Why This Study Exists

Many people rely on visual cues—familiar logos, colors, floating input labels, and layout—to decide whether a login page is legitimate. However, front-end design alone can be replicated with plain HTML and CSS.

This study demonstrates that **visual appearance is not proof of authenticity**, and encourages users to pause and check the URL before typing sensitive information.

## What to Check Before Entering Credentials

1. **Inspect the full domain name:** A legitimate Google sign-in page is hosted on `accounts.google.com`—not `localhost`, a GitHub Pages subdomain (`*.github.io`), an IP address, or a misspelled domain.
2. **Watch how password managers behave:** Password managers match saved credentials against the actual origin domain. If your password manager does not offer to auto-fill on a familiar-looking page, treat that as a major warning sign.
3. **Check navigation and links:** Look closely at where buttons, "Forgot email?", "Create account", and "Learn more" links point.
4. **Never rely on HTTPS alone:** A padlock icon only means traffic to *that* server is encrypted—lookalike sites can also have valid HTTPS certificates.

## Project Structure

- `google-signin.html` — Simulated email/phone entry screen
- `google-password.html` — Simulated password entry screen
- `google-forgot-email.html` — Simulated account recovery screen
- `google-create-account.html` — Simulated account creation screen

## Safe Usage Guidelines

- Run and review this project **locally only** in an isolated study/classroom environment.
- **Do not** deploy this to a public URL to collect real user input, and **do not** commit live database keys or credential-logging logic.
- Always disclose the educational purpose clearly to anyone participating in a security awareness walkthrough.

## Disclaimer

This project is intended strictly for defensive security education and user awareness research. Google and Gmail are trademarks of Google LLC; this repository is not affiliated with or endorsed by Google.
