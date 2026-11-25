# 0299008 PDP TECH SVC PROV — PDPA Exam Review

🔐 Interactive, mobile-friendly study site for **0299008 Personal Data Protection for Technology Service Providers** (Chula MOOC Flexi). It covers the Thai Personal Data Protection Act B.E. 2562 (PDPA) and is built around the official PDPA Practitioner exam format.

**Live site:** https://drasogo.github.io/0299008-PDP-TECH-SVC-PROV/

## Exam format the site follows

| | |
|---|---|
| Questions | 100 in 90 minutes, computer-based, pass mark 60 |
| Multi-answer | About 20%; all correct choices must be selected to score |
| Levels | Basic 50 · Deep 23 · Application 27 |

| Group | Basic | Deep | Application | Total |
|---|---|---|---|---|
| 1. Intro | 10 | 5 | 5 | 20 |
| 2. ROP (personal data & processing activities) | 5 | 2 | 3 | 10 |
| 3. Bases (lawful bases) | 10 | 5 | 5 | 20 |
| 4. Controller (controller / state agency duties) | 10 | 5 | 5 | 20 |
| 5. DPA (data processing agreements) | 5 | 2 | 3 | 10 |
| 6. Rights (data subject rights) | 5 | 2 | 3 | 10 |
| 7. Transfer (cross-border transfer) | 5 | 2 | 3 | 10 |

## Features

- **Lessons for all 7 groups** in exam order, written for beginners. They lean on visuals more than text: color-coded cards, comparison tables, flow diagrams and step-by-step boxes, plus key exam points, a short quiz and flashcards in every module.
- **Question bank of 428 questions**, each tagged with its exam group and level. The bank includes the real course quizzes, questions drawn from the tutoring sessions and course videos, and questions written from the PDPA Act and TDPG 3.0.
- **Random exam** that draws a full 100-question set matching the official table cell by cell, or a 50-question short set. It prefers questions you have not seen yet, shuffles the options, and runs a 90-minute timer.
- **Practice by group:** a 15-question drill for any single group.
- **Real exam mode:** answers stay hidden until you submit.
- **After every answer:** a recap of the concept that question tests, the reason for the correct answer with its legal reference, and a link to the matching lesson.
- **Results** by group, with a filter that shows only the questions you got wrong.
- **Progress saved** in the browser, so a reload does not lose your current set.

## Sources

- Personal Data Protection Act B.E. 2562 (2019) and the royal decree that postponed enforcement to 1 June 2022 (B.E. 2565)
- Thailand Data Protection Guidelines 3.0 (TDPG 3.0)
- The course's online lessons, end-of-chapter quizzes and review sessions

Answers to the course quizzes are not published by the course; they were worked out and checked against the Act. This is a study aid, not legal advice.

## Structure

```text
index.html   # the whole app: data, lessons, and quiz engine in one file
.nojekyll
```

Open `index.html` in any modern browser; it works offline except for the icon and font CDNs.
