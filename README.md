# CHAT Lab website starter

This is a starter Quarto website for **CHAT Lab — Cognition, Human Factors, and Applied Technology**.

## Why this setup

This site is designed so that you mostly edit plain text files ending in `.qmd`. You do not need to write JavaScript or advanced HTML/CSS for routine updates.

## Folder structure

- `_quarto.yml`: site navigation, title, footer, output settings
- `index.qmd`: home page
- `research.qmd`: research overview
- `people.qmd`: lab members
- `publications.qmd`: selected publications
- `teaching.qmd`: teaching and mentoring
- `joining.qmd`: prospective student information
- `contact.qmd`: contact information
- `projects/`: project-specific pages
- `assets/`: CV, headshot, lab photos, approved logos
- `styles.css`: visual styling

## Recommended workflow

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open this folder in RStudio or VS Code.
3. Preview locally:

```bash
quarto preview
```

4. Edit the `.qmd` files.
5. Render the website:

```bash
quarto render
```

The rendered website will appear in the `docs/` folder because `_quarto.yml` sets `output-dir: docs`.

## Publishing option A: GitHub Pages

1. Create a GitHub repository, for example `chat-lab`.
2. Upload/push these files.
3. Run `quarto render` so the `docs/` folder exists.
4. In GitHub, go to Settings > Pages.
5. Choose source: main branch, `/docs` folder.
6. Save. GitHub will publish the site.

## Publishing option B: Netlify

Netlify is also a good option if you want easy deploy previews and simple custom-domain management. Connect the GitHub repository, set the build command to `quarto render`, and set the publish directory to `docs`.

## Immediate edits to make

- Replace `[replace with UAH email]` in `contact.qmd`.
- Replace office and lab space placeholders.
- Add your latest CV to `assets/Louis_Liu_CV.pdf`.
- Replace the placeholder logo or keep the simple text logo.
- Add your official UAH faculty profile link once it exists.
- Update `joining.qmd` with whether you are accepting students.

## Suggested update rhythm

- Every semester: update people, openings, current projects.
- Every accepted paper: update publications.
- Every year: update CV PDF, research overview, and project pages.
