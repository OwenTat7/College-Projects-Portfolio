# Owen Tatlonghari Portfolio

A Quarto-powered portfolio showcasing projects, videos, and documents.

## Live site

- GitHub Pages (enable in repo Settings → Pages): main branch, folder `/docs`
- After enabling, your site will be at: `https://<your-username>.github.io/College-Projects-Portfolio/`

## Portfolio overview

### Creative Video Project — Freshman Year
- Essays:
  - [Generational Influence of Technology Research Essay.docx](assets/docs/Generational%20Influence%20of%20Technology%20Research%20Essay.docx)
  - [English Research Project.docx](assets/docs/English%20Research%20Project.docx)

### Case 1 — Liz Motors — Junior Year
- [Case 1 - Liz Motors.xlsx](assets/Case%201%20-%20Liz%20Motors%20copy.xlsx)
- [Case 1 Liz Motors.docx](assets/Case%201%20Liz%20Motors%20copy.docx)

### Case II — M&M Pizza — Junior Year
- [Case II M&M Pizza.xlsx](assets/Case%20II%20M%26M%20Pizza.xlsx)
- [M&M Pizza copy.pdf](assets/M%26M%20Pizza%20copy.pdf)

### Scoring Model / AHP Model Project — Junior Year
- [Presentation video (720p MP4)](Tatlonghari%20Owen%20PPT%20720p.mp4)

## How this repo is organized
- `_quarto.yml`: site configuration; output goes to `docs/` for GitHub Pages
- `index.qmd`, `projects.qmd`, `about.qmd`: site pages
- `assets/`: source files (docs, sheets, PDFs, media)
- `docs/`: generated website (don’t edit directly)

## Working locally
- Preview during editing:
  ```bash
  quarto preview
  ```
- Render the site:
  ```bash
  quarto render
  ```

## Publish to GitHub Pages
1. Commit changes and push to `main`.
2. In GitHub → Settings → Pages: Source = Branch `main`, Folder `/docs`.
3. Wait for Pages to build, then open the Live site link above.
