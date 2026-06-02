# SS9 — ETHNIC STUDIES
## OCS Summer School | 9th Grade Social Science

This repository contains all lesson webpages, image assets, and course materials for the Ethnic Studies summer school course. The course covers the California Ethnic Studies Model Curriculum across 8 instructional days plus a final exam.

---

## COURSE OVERVIEW

| Course | Standards | Days |
|---|---|---|
| Ethnic Studies | CA Ethnic Studies Model Curriculum | 8 lessons + final |

---

## FILE NAMING CONVENTION

All lesson HTML files follow this pattern:

```
SS9_L[lesson].html
```

Examples:
- `SS9_L01.html` — Lesson 1
- `SS9_L08.html` — Lesson 8
- `SS9_L09_Final.html` — Final Exam

Lesson numbers are always zero-padded: L01 not L1.

---

## LESSON INDEX

| Day | File | Title | EQ | Standards |
|---|---|---|---|---|
| 1 | SS9_L01.html | What Is Ethnic Studies and Why Does It Exist? | Who gets to tell the story of America, and what happens when whole communities are left out? | CA ES Framework — Units 1 & 2 |
| 2 | SS9_L02.html | Native American Peoples: Sovereignty, Survival, and Presence | How did Indigenous peoples survive colonization, and how do they assert their sovereignty today? | CA ES Framework — Native American Studies |
| 3 | SS9_L03.html | African American Experience: From Enslavement to Power | How did enslaved people and their descendants resist, survive, and transform American democracy from the inside? | CA ES Framework — African American Studies |
| 4 | SS9_L04.html | Chicano and Latino Identity: Border, Culture, and Power | How has the history of the U.S.-Mexico border shaped the lives, culture, and political power of Latino communities? | CA ES Framework — Chicana/o/x & Latina/o/x Studies |
| 5 | SS9_L05.html | Asian American and Pacific Islander Experience | How did Asian immigrants build American infrastructure, face systematic exclusion, and fight for belonging over two centuries? | CA ES Framework — AAPI Studies |
| 6 | SS9_L06.html | Intersectionality: When Identities Overlap | How do race, gender, class, and other parts of identity combine to shape a person's experience of power and opportunity? | CA ES Framework — Units 3 & 4 |
| 7 | SS9_L07.html | Resistance, Social Movements, and the Power of Organizing | How have communities of color organized, protested, and permanently changed American laws and culture? | CA ES Framework — Unit 5 |
| 8 | SS9_L08.html | Ethnic Studies Today: Narrative, Power, and Your Story | What does it mean to have power over your own story, and how does that connect to who you are becoming? | CA ES Framework — Unit 6 |
| 9 | SS9_L09_Final.html | Final Exam | — | Cumulative |

---

## IMAGE FOLDER STRUCTURE

Images are organized by lesson:

```
images/
  header_eth.jpg
  L01/
    L01_HeaderBg.jpg
    L01_ImageName.jpg
    ...
  L02/
  L03/
  L04/
  L05/
  L06/
  L07/
  L08/
```

---

## IMAGE NAMING CONVENTION

All lesson images follow this pattern:

```
L[lesson]_DescriptiveName.jpg
```

Examples:
- `L01_RubyBridges.jpg`
- `L02_TrailOfTears.jpg`
- `L03_GreatMigration.jpg`
- `L04_ChicanoMural.jpg`

The index page header image is named:
- `header_eth.jpg` — placed in images/ at the root

---

## GOING LIVE

All lesson cards on the index page are live by default and link to their respective HTML files. When a lesson file is built and pushed the card becomes fully functional.

To temporarily deactivate a card change:
```html
<a class="day-card fade-in" href="SS9_L01.html">
```
to:
```html
<a class="day-card fade-in" aria-disabled="true" style="pointer-events:none;opacity:0.5;">
```
Remove those attributes when ready to go live.

---

## GITHUB PAGES

After pushing to GitHub enable GitHub Pages:
1. Go to Settings in this repository
2. Click Pages in the left sidebar
3. Set Branch to main, folder to / (root)
4. Click Save

Live site: `https://wpr-creator.github.io/SS9`

---

## HEADER IMAGE

| File | What It Shows | Source |
|---|---|---|
| images/header_eth.jpg | The Problem We All Live With — Norman Rockwell, 1964 | https://commons.wikimedia.org/wiki/File:The_Problem_We_All_Live_With.jpg |

---

## REPOSITORY SUMMARY

- **Total lesson files:** 9 (8 lessons + final)
- **Image folders:** 8 lesson folders plus root images folder
- **Repo prefix:** SS9
- **GitHub:** https://github.com/wpr-creator/SS9
