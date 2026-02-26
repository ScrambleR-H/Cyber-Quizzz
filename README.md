# CyberQuiz — Cybersecurity Awareness Challenge

A browser-based cybersecurity awareness quiz application built as a single self-contained HTML file. The project is designed to help users test and reinforce their knowledge across core cybersecurity domains through an interactive, timed quiz experience with a sleek cyberpunk-inspired interface.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Quiz Categories](#quiz-categories)
- [Difficulty Levels](#difficulty-levels)
- [Scoring System](#scoring-system)
- [Grading](#grading)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Author](#author)

---

## Overview

CyberQuiz presents users with 10 randomly selected multiple-choice questions drawn from a pool of 30 questions per category. Each session is unique due to question shuffling. The application runs entirely in the browser with no backend, no dependencies to install, and no build tools required. Simply open the HTML file and start learning.

---

## Features

- Fully self-contained single-file application with no external dependencies
- Six distinct cybersecurity topic categories, each with 30 curated questions
- Three difficulty modes with different time limits and point values
- Live countdown timer with visual color-coded warnings
- Real-time score tracking throughout each session
- Instant per-question feedback indicating correct or incorrect answers
- Detailed post-quiz results screen with grade, score, accuracy, and breakdown
- Answer review panel showing correct answers for every missed question
- Retry and return-to-home options for repeated practice
- Responsive layout compatible with desktop and mobile browsers
- Cyberpunk-themed UI with animated grid background, scanline overlay, and glowing accents

---

## Quiz Categories

The quiz covers the following six cybersecurity domains, each containing 30 questions:

**Phishing and Social Engineering** — Covers tactics used by attackers to manipulate individuals into revealing sensitive information, including email phishing, spear phishing, pretexting, and vishing.

**Passwords and Authentication** — Tests knowledge of password best practices, multi-factor authentication, password managers, credential stuffing, and account security hygiene.

**Malware and Ransomware** — Focuses on types of malicious software, how ransomware operates, infection vectors, and appropriate response and prevention strategies.

**Network Security** — Addresses concepts such as firewalls, VPNs, secure Wi-Fi practices, man-in-the-middle attacks, and network monitoring fundamentals.

**Data Privacy and Compliance** — Covers data protection principles, privacy regulations such as GDPR, data handling responsibilities, and organizational compliance requirements.

**Incident Response** — Examines the phases of incident response, containment and eradication procedures, forensic preservation, and post-incident analysis.

---

## Difficulty Levels

| Difficulty | Time Per Question | Points Per Correct Answer | Questions Per Session |
|------------|-------------------|---------------------------|----------------------|
| Easy       | 30 seconds        | 10 points                 | 10                   |
| Medium     | 20 seconds        | 20 points                 | 10                   |
| Hard       | 15 seconds        | 30 points                 | 10                   |

The timer bar changes color as time decreases, transitioning from blue to amber and finally to red during the final five seconds. Unanswered questions when the timer expires are counted as incorrect.

---

## Scoring System

Points are awarded only for correct answers. Incorrect answers and timeouts receive no points. The live score is displayed throughout the quiz session and updated immediately after each answer is submitted.

Maximum possible scores per difficulty level:

- Easy: 100 points
- Medium: 200 points
- Hard: 300 points

---

## Grading

At the end of each session, performance is evaluated based on accuracy percentage and assigned a grade and title:

| Accuracy   | Grade | Title             |
|------------|-------|-------------------|
| 90% - 100% | A+    | Elite Operator    |
| 80% - 89%  | A     | Security Expert   |
| 70% - 79%  | B     | Strong Defender   |
| 60% - 69%  | C     | Developing Skills |
| Below 60%  | D     | Needs Improvement |

The results screen displays the final score, total correct answers, total incorrect answers, overall accuracy, a grade-specific feedback message, and an expandable answer review panel.

---

## Tech Stack

- HTML5
- CSS3 with custom properties, animations, and responsive grid layout
- Vanilla JavaScript with no frameworks or libraries
- Google Fonts — Orbitron, Rajdhani, Share Tech Mono

---

## Getting Started

No installation or build process is required.

1. Download or clone the repository.
2. Open `index.html` in any modern web browser.
3. Select a quiz category from the available topic cards.
4. Choose a difficulty level.
5. Click the launch button to begin the quiz.

The application works entirely offline after the initial load. An internet connection is only needed to fetch the Google Fonts stylesheet on first use; the quiz itself functions without it.

---

## Project Structure

```
cyberquiz/
└── index.html       # Complete application — markup, styles, and logic in one file
```

The entire application is contained within a single HTML file. The structure within the file is organized as follows:

- Head section with meta tags and Google Fonts import
- Embedded CSS covering theming, layout, animations, and responsive breakpoints
- HTML body with three screen containers: home, quiz, and results
- Embedded JavaScript containing question data, quiz state management, timer logic, scoring, and result rendering

---

## Author

**ScrambleR**

GitHub: [https://github.com/ScrambleR-H]
LinkedIn: [www.linkedin.com/in/scrambler-hhh-7826b13a6]

---

## License

This project is open source and available for personal and educational use. Attribution is appreciated.
