# CodeAlpha_PhishingAwareness

Phishing Awareness Training created for the CodeAlpha Cyber Security
Internship (Task 2).

**Author:** Muhammad Rizwan
**Student ID:** CA/DF1/172886

## Contents

| File | Description |
|---|---|
| `CodeAlpha_PhishingAwareness.pptx` | 13-slide presentation covering phishing types, red flags, social engineering tactics, real-world case studies, and best practices |
| `phishing_quiz.html` | Standalone interactive quiz — 10 realistic scenarios with instant feedback and a results screen. Runs entirely in the browser, no install needed |

## What the training covers

- **What phishing is**, and why it's the #1 initial access method in breaches
- **Types of phishing**: email phishing, spear phishing, whaling, smishing, vishing, clone phishing
- **How to recognize phishing emails**: sender mismatch, urgency, generic greetings, spelling errors, suspicious links, unexpected attachments — illustrated with an annotated example
- **How to recognize fake websites**: URL scrutiny, the HTTPS padlock myth, poor design, unexpected credential prompts
- **Social engineering tactics**: authority, urgency, scarcity, familiarity, fear, curiosity
- **Real-world case studies**: the Google/Facebook $100M vendor scam, the 2020 Twitter Bitcoin hack, the Target vendor breach
- **Best practices**: verifying senders, hovering before clicking, MFA, password managers, keeping software updated, reporting suspicious messages
- **What to do if you're phished**: immediate incident-response steps

## Running the quiz

Just open `phishing_quiz.html` in any modern browser — double-click the file, or:

```bash
# macOS
open phishing_quiz.html

# Linux
xdg-open phishing_quiz.html

# Windows
start phishing_quiz.html
```

No server, build step, or dependencies required.

## Quiz format

10 scenario-based multiple-choice questions covering everything from the
slides — phishing emails, lookalike URLs, smishing/vishing calls, whaling
attempts, malicious attachments, MFA-fatigue attacks, and incident
reporting. Each answer gives instant feedback with an explanation, and the
final screen shows a score-based summary with the option to retake.
