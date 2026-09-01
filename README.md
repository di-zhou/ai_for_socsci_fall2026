# AI for Social Science Research — Fall 2026

PhD seminar on generative AI methods for social science research.

## Course Website

📎 **[https://dizhou.github.io/ai_for_socsci_fall2026/](https://dizhou.github.io/ai_for_socsci_fall2026/)**

## Structure

```
weeks/
├── week01/          # Introduction & Set-up
│   ├── slides.qmd   # Lecture slides (Quarto → reveal.js)
│   └── lab.qmd      # Lab exercise (Quarto + Python)
├── week02/          # How LLMs Work
├── week03/          # LLM Annotation for CSS
├── week04/          # LLM for Social Simulation
├── week05/          # AI Agents for Research
├── week06/          # LLM for Qualitative Research
└── week07/          # Wrap-Up & Presentations
```

## Local Development

```bash
# Install Quarto: https://quarto.org/docs/get-started/
# Then:
quarto preview
```

This launches a live-preview server. The site auto-rebuilds when you save changes.

## Deployment

The site is built and deployed to GitHub Pages automatically on every push to `main` via the GitHub Actions workflow in `.github/workflows/publish.yml`.

## License

Course materials are shared under the [MIT License](LICENSE).
