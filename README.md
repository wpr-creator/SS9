# SS9 — 9TH GRADE SOCIAL SCIENCE
## OCS Summer School | World Geography (S1) + Ethnic Studies (S2)

This repository contains all lesson webpages, image assets, and course materials for the 9th Grade Social Science summer school course. The course is split into two semesters: Semester 1 covers World Geography and Semester 2 covers Ethnic Studies.

---

## COURSE OVERVIEW

| Semester | Course | Standards | Days |
|---|---|---|---|
| S1 | World Geography | National Geography Standards | 8 lessons + final |
| S2 | Ethnic Studies | CA Ethnic Studies Model Curriculum | 8 lessons + final |

---

## FILE NAMING CONVENTION

All lesson HTML files follow this pattern:

```
SS9_S[semester]L[lesson].html
```

Examples:
- `SS9_S1L01.html` — Semester 1, Lesson 1 (World Geography Day 1)
- `SS9_S2L08.html` — Semester 2, Lesson 8 (Ethnic Studies Day 8)

Lesson numbers are always zero-padded: L01 not L1.

---

## LESSON INDEX

### SEMESTER 1: WORLD GEOGRAPHY

| Day | File | Title | EQ | Standards |
|---|---|---|---|---|
| 1 | SS9_S1L01.html | Reading the World: Maps and Geographic Tools | How do geographers read the world, and why does the way we draw maps matter? | Nat. Geo. Standards 1, 2 |
| 2 | SS9_S1L02.html | Physical Geography: The Earth Beneath Our Feet | How do landforms, climate, and natural resources determine where people settle and how they survive? | Nat. Geo. Standards 3, 4, 7 |
| 3 | SS9_S1L03.html | Human Geography: People, Place, and Movement | Why do people move, and how does migration reshape the places people leave and the places they arrive? | Nat. Geo. Standards 9, 12, 17 |
| 4 | SS9_S1L04.html | Africa and the Middle East | How has geography shaped the conflict, culture, and wealth of Africa and the Middle East? | Nat. Geo. Standards 4, 10, 13 |
| 5 | SS9_S1L05.html | Asia and the Pacific | How has geography made Asia the center of the world's population, production, and power? | Nat. Geo. Standards 4, 9, 11 |
| 6 | SS9_S1L06.html | Europe and Russia | How has geography shaped war, cooperation, and economic power in Europe and Russia? | Nat. Geo. Standards 4, 13, 17 |
| 7 | SS9_S1L07.html | The Americas | How does geography connect and divide North, Central, and South America? | Nat. Geo. Standards 4, 9, 12 |
| 8 | SS9_S1L08.html | Globalization and Geographic Change | How are climate change, mass migration, and economic integration remaking the world's map right now? | Nat. Geo. Standards 14, 16, 18 |
| 9 | SS9_S1L09_Final.html | Final Exam | — | Cumulative S1 |

### SEMESTER 2: ETHNIC STUDIES

| Day | File | Title | EQ | Standards |
|---|---|---|---|---|
| 1 | SS9_S2L01.html | What Is Ethnic Studies and Why Does It Exist? | Who gets to tell the story of America, and what happens when whole communities are left out? | CA ES Framework — Units 1 & 2 |
| 2 | SS9_S2L02.html | Native American Peoples: Sovereignty, Survival, and Presence | How did Indigenous peoples survive colonization, and how do they assert their sovereignty today? | CA ES Framework — Native American Studies |
| 3 | SS9_S2L03.html | African American Experience: From Enslavement to Power | How did enslaved people and their descendants resist, survive, and transform American democracy from the inside? | CA ES Framework — African American Studies |
| 4 | SS9_S2L04.html | Chicano and Latino Identity: Border, Culture, and Power | How has the history of the U.S.-Mexico border shaped the lives, culture, and political power of Latino communities? | CA ES Framework — Chicana/o/x & Latina/o/x Studies |
| 5 | SS9_S2L05.html | Asian American and Pacific Islander Experience | How did Asian immigrants build American infrastructure, face systematic exclusion, and fight for belonging over two centuries? | CA ES Framework — AAPI Studies |
| 6 | SS9_S2L06.html | Intersectionality: When Identities Overlap | How do race, gender, class, and other parts of identity combine to shape a person's experience of power and opportunity? | CA ES Framework — Units 3 & 4 |
| 7 | SS9_S2L07.html | Resistance, Social Movements, and the Power of Organizing | How have communities of color organized, protested, and permanently changed American laws and culture? | CA ES Framework — Unit 5 |
| 8 | SS9_S2L08.html | Ethnic Studies Today: Narrative, Power, and Your Story | What does it mean to have power over your own story, and how does that connect to who you are becoming? | CA ES Framework — Unit 6 |
| 9 | SS9_S2L09_Final.html | Final Exam | — | Cumulative S2 |

---

## IMAGE FOLDER STRUCTURE

Images are organized by semester and lesson:

```
images/
  S1/
    L01/
      S1L01_HeaderBg.jpg
      S1L01_ImageName.jpg
      ...
    L02/
    L03/
    L04/
    L05/
    L06/
    L07/
    L08/
  S2/
    L01/
      S2L01_HeaderBg.jpg
      S2L01_ImageName.jpg
      ...
    L02/
    L03/
    L04/
    L05/
    L06/
    L07/
    L08/
  header_geo.jpg
  header_eth.jpg
```

---

## IMAGE NAMING CONVENTION

All lesson images follow this pattern:

```
S[semester]L[lesson]_DescriptiveName.jpg
```

Examples:
- `S1L01_WorldMap1570.jpg`
- `S1L04_SaharaDesert.jpg`
- `S2L03_GreatMigration.jpg`
- `S2L05_ChineseRailroadWorkers.jpg`

Index page header images are named:
- `header_geo.jpg` — World Geography hero image (placed in images/)
- `header_eth.jpg` — Ethnic Studies hero image (placed in images/)

---

## GOING LIVE: HOW TO ACTIVATE A LESSON CARD

All lesson cards on the index page are live by default and link to their respective HTML files. When a lesson file is built and pushed to the repo the card becomes fully functional.

If you need to temporarily deactivate a card before a lesson is ready, change the anchor tag from:
```html
<a class="day-card-geo fade-in" href="SS9_S1L01.html">
```
to:
```html
<a class="day-card-geo fade-in" aria-disabled="true" style="pointer-events:none;opacity:0.5;">
```
Remove those attributes when the lesson is ready to go live.

---

## GITHUB PAGES

After pushing to GitHub, enable GitHub Pages:
1. Go to Settings in this repository
2. Click Pages in the left sidebar
3. Set Branch to main, folder to / (root)
4. Click Save

Your live site will be available at:
`https://wpr-creator.github.io/SS9`

---

## HEADER IMAGES TO DOWNLOAD

| File | What It Shows | Source |
|---|---|---|
| images/header_geo.jpg | NASA Blue Marble — full Earth from space, 2002 | https://commons.wikimedia.org/wiki/File:The_Blue_Marble.jpg |
| images/header_eth.jpg | The Problem We All Live With — Norman Rockwell, 1964 | https://commons.wikimedia.org/wiki/File:The_Problem_We_All_Live_With.jpg |

---

## REPOSITORY SUMMARY

- **Total lesson files:** 18 (9 per semester including finals)
- **Total semesters:** 2
- **Image folders:** 16 lesson folders plus root images folder
- **Repo prefix:** SS9
- **GitHub:** https://github.com/wpr-creator/SS9
