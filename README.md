# shaynestdenis.github.io

Personal website for Shayne St. Denis, built with [Quarto](https://quarto.org) and published to GitHub Pages.

## Editing

Each page is a plain-text file:

| Page | File |
|---|---|
| Home | `index.qmd` |
| Research | `research.qmd` |
| Consulting (WWGD) | `consulting.qmd` |
| Golf | `golf.qmd` |

Edit a file (on github.com, click the pencil icon) and commit. The site rebuilds and goes live automatically in about two minutes. Check progress on the **Actions** tab.

- **Add a paper:** in `research.qmd`, copy an existing `::: {.paper}` block and change the text.
- **Link a PDF:** upload it to the `files/` folder, then add a line such as `[PDF](files/my-paper.pdf)` inside the paper's block.
- **Update the CV:** replace `files/St_Denis_CV.pdf` with a new file of the same name.
- **Colours and fonts:** `styles.scss`. **Menu and footer:** `_quarto.yml`.

## Preview locally

With Quarto installed (RStudio includes it): `quarto preview`
