# Portfolio Checklist – Course Requirements & Best Practices

Use this to align your portfolio with the course instructions and rubric.

---

## Best practices (quick check)

| Practice | Your status | Action |
|----------|-------------|--------|
| **Short URL** | Repo: `portfolio`; README says `vinisha231.github.io/portfolio_capstone` | Keep deploy URL short for LinkedIn/resume. |
| **PARC** | ✅ In `css/style.css` (proximity, alignment, repetition, contrast) | None. |
| **Clear navigation** | ✅ Same nav on all 5 pages | None. |
| **Clear titles** | ✅ Each page has `<title>` and subtitle | None. |
| **High contrast** | ✅ CSS uses high-contrast colors | None. |
| **Connect images to text** | ⚠️ Some artifacts have "Description." below | Put **reflective narrative right next to each image** (same section). Avoid long scroll to match text to image. Consider one figure + its narrative, then next figure + narrative. |
| **Alt text** | ✅ `<img alt="...">` present | Make alt text **describe the image** for screen readers (what the diagram/screenshot shows), not just "Diagram" or "Screenshot." |
| **Plan first** | ✅ Five pages and nav exist | None. |

---

## Required pages (all present ✓)

1. **Capstone landing page** – `index.html` ✓  
2. **The User** – `the-user.html` ✓  
3. **Capstone Experience** – `capstone-experience.html` ✓ (can add more pages linked from here)  
4. **Annotated Bibliography** – `annotated-bibliography.html` ✓  
5. **Overall Capstone** – `overall-capstone.html` ✓  

---

## The User page

- Borrow/adapt from your **Description and Deliverables** in the Design Specification.
- Apply any **instructor comments** from the graded Final Design Specification so those issues don’t repeat.
- **2nd person** (“you”) so the reader feels part of the capstone ✓ (you already do this).
- Answer: **What it is**, **Why they would want to use it**, **How it works** ✓ (you already do this).

---

## Capstone Experience page

- **Goal:** Show major parts of the work (themes = headings) and **how it evolved** (artifacts + short narratives).
- **For each theme:**  
  - Major heading → description of that section.  
  - Sub-headings for artifacts.  
  - Artifacts (diagrams, screenshots, code, etc.).  
  - **Short narrative per artifact:** relevance, changes over time, what worked/didn’t, pivots.  
- **Writing:** Avoid repeating “I included this because…”. Dive into the artifact, its significance, and how it fits the story.
- **Layout:** Keep **narrative next to the image** it describes (same block or right below the figure) so the reader doesn’t scroll to match text to image.
- **Optional:** Arrows or boxes on artifacts, then discuss that detail in the neighboring text.
- **Optional:** Link to separate pages per theme if you prefer.

**Artifact ideas from the instructions (use what fits):**

- Screenshots of final product (+ link to run it)  
- Architectural diagram(s) – original and updated  
- UML (e.g. database)  
- Use cases / misuse cases  
- Context/activity/dataflow diagrams, domain models  
- Requirements & constraints  
- Methodology summary (borrowed ideas + citations)  
- **Source code** of key algorithms or tricky sections  
- Screenshots of key areas  
- README (or excerpt)  
- Test plan & testing analysis  
- User survey + analysis of results  
- Competition comparison table  
- Stakeholder survey results  
- Schedule (methodology)  
- **Future plans** (short)  

**Your current placeholders to replace:**  
All “Description.” under Early Architecture, First Design, Database and API, AI Prompts, Data Model, Pivots and Iteration, Testing and Quality, Results and Future Plans. Add real artifact content (code snippets, prompts, etc.) where the instructions say “Key code or API design” and “Prompts or evaluation logic.”

**Images to add (or paths to fix):**  
`images/architecture.png`, `images/screenshot-setup.png`, `images/screenshot-interview.png`, `images/screenshot-dashboard.png`, `images/data-model.png`

---

## Annotated Bibliography page

- Export from **Zotero** (or your reference manager).
- **MLA or APA** – pick one and use it consistently.
- **Group by theme** (e.g. API/backend, AWS, databases, frontend/UX, LLMs). Sort **theme headings A–Z**.
- Under each heading:  
  - **Annotation:** A few sentences that apply to **all** sources in that theme (what you were doing with these resources; how you learned).  
  - **List of citations** in **alphabetical order** for that theme.
- **Goal:** Show how you learn.

**Your current placeholders:**  
Replace each “Description. Short paragraph…” with a real theme annotation, and replace “Author. *Title*…” with real citations from your capstone work.

---

## Overall Capstone page (reflective narrative)

- **Purpose:** Reflective narrative about the **experience** (motivation, challenges, stakeholders, time management, growth, next steps). Focus on **what you learned about yourself**, not only technology.
- **Do not** use the brainstorm list as your section headings (e.g. avoid organizing only as “Motivation,” “Challenges,” “Stakeholders,” “Time Management,” “Growth,” “Future Plans”). The instructions say this becomes a list, not a narrative.
- **Do:**  
  1. **Brainstorm** (use the course’s list, including all **bolded** items).  
  2. **Create themes** that are **narrative themes** emerging from your experience (e.g. “Learning to Ship in Small Steps,” “When the Stack Didn’t Stick,” “Stakeholders as Co-designers”).  
  3. **Order themes** in a **building-information, narrative order**.  
  4. **Write** about **5–7 themes**, **3–4 paragraphs each**.  
  5. **End with a Conclusion** (or “Conclusions” / “Next Steps”) – where you plan to take the capstone after the course.

**Content to include somewhere (from the bolded brainstorm list):**  
Why you picked this project, how you approached it, motivation/focus, use of outside information/research, connection to future goals, what worked (successes), challenges/disappointments/missed opportunities, finding and working with experts/stakeholders and skills you’ll take forward, what you’d do differently, what you’d do with more time, and **next steps** (in the conclusion).

**Your current structure:**  
You have Motivation, Challenges, Working with Stakeholders, Time Management, Growth, Future Plans. Consider **renaming and merging** into 5–7 **narrative themes** and moving “next steps” into a final **Conclusion** or **Next Steps** section.

---

## Optional: Extra best practices you could add

- **Skip-link:** Add a “Skip to main content” link at the top for keyboard/screen-reader users.  
- **Print-friendly:** A `@media print` block in CSS so the portfolio prints cleanly.  
- **Heading hierarchy:** Ensure a single `<h1>` per page and logical order (h2 → h3, no skips).  
- **Link affordance:** Make “Try the app” and external links visually distinct (e.g. icon or “opens in new tab” where appropriate).

---

*Generated from the course portfolio instructions and your current repo.*
