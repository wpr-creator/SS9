# Ethnic Studies — OCS Summer School
### Course Hub · `index.html`

---

## Overview

Student-facing landing page for the OCS Summer School Ethnic Studies course (CA Ethnic Studies Model Curriculum). Opens directly in any browser — no server or build tools required.

---

## Structure

```
/
├── index.html          ← Main course hub (this file)
├── README.md           ← This file
└── images/
    └── header_eth.jpg  ← Hero banner image (see below)
```

---

## Lesson Files

Naming convention: `SS9_Lxx.html`

| Day | File          | Title                                                                 | Framework Unit                      |
|-----|---------------|-----------------------------------------------------------------------|-------------------------------------|
| 1   | SS9_L01.html  | Who Gets Erased? The History Behind the History                       | Units 1 & 2                         |
| 2   | SS9_L02.html  | Native American Peoples: Sovereignty, Survival, and Presence         | Native American Studies             |
| 3   | SS9_L03.html  | African American Experience: From Enslavement to Power               | African American Studies            |
| 4   | SS9_L04.html  | Chicano and Latino Identity: Border, Culture, and Power               | Chicana/o/x & Latina/o/x Studies    |
| 5   | SS9_L05.html  | Asian American and Pacific Islander Experience                        | AAPI Studies                        |
| 6   | SS9_L06.html  | South Asian Americans: Farmworkers, Exclusion, and the Punjabi-Mexican Community | AAPI Studies Expanded   |
| 7   | SS9_L07.html  | Jewish American Experience: Immigration, Identity, and Belonging      | Expanded Community Studies          |
| 8   | SS9_L08.html  | Arab American and Middle Eastern Experience                           | Expanded Community Studies          |
| 9   | SS9_L09.html  | San Diego's Hidden Communities: Filipino, Somali, Hmong, and Chaldean | Local Community Studies            |
| 10  | SS9_L10.html  | **Ethnic Studies Final Exam**                                         | All Units                           |

---

## Card Display Logic

Cards are ordered by instructional relevance each day:

- **Today's card** (Day 5) appears first — red TODAY badge, full color bar, animated pulse border
- **Upcoming cards** (Days 6–9) follow in order
- **Completed cards** (Days 1–4) appear at the end — slightly muted
- **Day 10 Final** always anchors the end with a FINAL badge

To update for a new day: move that day's card block to the top, change its class to `today`, update the badge, and update the pip JS (`i < 5` becomes `i < 6` for Day 6, etc.).

---

## Header Image

```
FILENAME:  header_eth.jpg
FOLDER:    images/
SOURCE:    Wikimedia Commons
TITLE:     "The Problem We All Live With" — Norman Rockwell, 1964
URL:       https://commons.wikimedia.org/wiki/File:The_Problem_We_All_Live_With.jpg
```

Download the full-size JPG and save as `images/header_eth.jpg`. Falls back to a warm near-black background if missing.

---

## Community Color System

Each card has its own color via CSS custom property `--c`:

| Day | Community            | Hex       |
|-----|----------------------|-----------|
| 1   | Foundations          | #1a6640   |
| 2   | Native American      | #7a3010   |
| 3   | African American     | #1a3070   |
| 4   | Chicano / Latino     | #c03010   |
| 5   | AAPI                 | #982208   |
| 6   | South Asian          | #c07000   |
| 7   | Jewish American      | #1c4878   |
| 8   | Arab American        | #155a42   |
| 9   | San Diego Local      | #56288a   |

---

## Design & JS Notes

- **Fonts**: Syne (headings/labels), Instrument Serif (card titles), Inter (body)
- **Background**: Warm ivory #f5ede0 — no gray — with animated color orbs and diagonal grain
- **JS/CSS enhancements**:
  - Gradient scroll-progress bar pinned to top
  - Session progress pips (Day X of 10)
  - Intersection Observer scroll-reveal with staggered card delays
  - Community name tooltip top-right on hover (CSS attr trick, no JS)
  - Animated pulse on today's card color bar
  - Footer dots and color-strip segments expand on hover

---

*Ethnic Studies · OCS Summer School · SS9*
