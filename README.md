# Interview Simulator – Capstone Portfolio

A static portfolio site showcasing the **Interview Simulator** capstone project. It is intended to be a **separate repository** from the main capstone codebase and is designed to be published on **GitHub Pages**.

## Title

**Interview Simulator**

## Required Pages

1. **Landing (index.html)** – Entry point with links to all other pages.
2. **The User** – Stakeholder perspective: what it is, why use it, how it works (2nd person).
3. **Capstone Experience** – Expert perspective: themes, artifacts, and short narratives on how the project was built and evolved.
4. **Annotated Bibliography** – Resources by theme with annotations (MLA or APA).
5. **Overall Capstone** – Reflective narrative (5–7 themes, ~3–4 paragraphs each, plus Conclusion/Next Steps).

## Using This as a Separate Repo

1. Copy or move the `portfolio` folder to a new directory (or create a new repo and add these files).
2. Initialize git and push to GitHub:
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial portfolio for Interview Simulator capstone"
   git branch -M main
   git remote add origin https://github.com/vinisha231/portfolio.git
   git push -u origin main
   ```
3. Enable GitHub Pages:
   - Repo → **Settings** → **Pages**
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `gh-pages` if you prefer)
   - **Folder**: `/ (root)` if your HTML files are at the repo root
   - Save. The site will be at **https://vinisha231.github.io/portfolio/**

## Short URL Tip

Use a short repo name (e.g. `interview-sim-capstone` or `capstone-portfolio`) so the URL is easy to share on LinkedIn or your resume.

## Customization

- **The User**: Edit `the-user.html`; the current text is based on the capstone app and is in 2nd person. Adjust if your Design Specification or deliverables differ.
- **Capstone Experience**: Replace the italic placeholder text in `capstone-experience.html` with your themes, artifact images (place in `images/` and reference as `images/your-file.png`), code snippets, and narratives.
- **Annotated Bibliography**: In `annotated-bibliography.html`, add your Zotero (or other) exports, grouped by theme, with annotations. Use MLA or APA and sort alphabetically within each theme.
- **Overall Capstone**: In `overall-capstone.html`, replace the theme placeholders with your reflective narrative. Organize by themes, not by the brainstorm list; end with Conclusion or Next Steps.

## Design

- **PARC**: Proximity, alignment, repetition, and contrast are applied in `css/style.css`.
- **Accessibility**: High-contrast colors, semantic headings, nav, and alt text for images (add when you insert screenshots).
- **Navigation**: Same header and nav on every page for clear, consistent navigation.

## Images

Put screenshots and diagrams in the `images/` folder. The Capstone Experience page expects these filenames (or update the `src` in the HTML to match your files):

- `images/architecture.png` – system architecture diagram
- `images/screenshot-setup.png` – interview setup screen
- `images/screenshot-interview.png` – question/answer/feedback view
- `images/screenshot-dashboard.png` – dashboard
- `images/data-model.png` – data model or UML diagram

Add descriptive `alt` text when you add or change images.

## Reminder

- **Overall Capstone themes**: Change the theme subheadings in `overall-capstone.html` later to match your own narrative (replace the generic titles with your chosen themes).
- **Live app**: When the Interview Simulator is deployed, replace the placeholder “Try the app” link on the landing page with your real URL.
