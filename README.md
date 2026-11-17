# ClerksWell Delivery Hub prototypes

Two clickable prototypes for the delivery dashboard. Use the tabs at the top to switch between them.

- **Original prototype** (`original/`): the full Delivery Hub, lo-fi wireframes V2. It covers projects, SLAs and retainers, people and utilisation, support, pipeline, lessons and an AI assistant.
- **Simplified MVP** (`mvp/`): a Power BI model that uses only the spreadsheets and lists we have today. Float and Zendesk are left out and no data clean-up is needed first.

All data is anonymised. Client names are replaced with placeholders, project names are generalised and money figures are scaled. Percentages and counts are as in the source files. Float and Zendesk figures in the original prototype are dummy data.

## Publishing on GitHub Pages

1. Upload the contents of this folder (`index.html`, `original/`, `mvp/`, `.nojekyll`, `README.md`) to the root of the repository's `main` branch.
2. In **Settings > Pages**, set the source to *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. The site appears at `https://<account>.github.io/<repository>/` after a minute or two.

Direct links: add `#original` or `#mvp` to the address to open a specific tab.
