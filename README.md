# HKUST-GZ MPhil Thesis LaTeX Template (2026)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![LaTeX](https://img.shields.io/badge/Built%20with-LaTeX-008080.svg)](https://www.latex-project.org/)
[![Template](https://img.shields.io/badge/Type-Thesis%20Template-blue.svg)](#)

A clean, publication-ready, and privacy-safe thesis template for HKUST-GZ MPhil students.
This repository is intentionally anonymized and contains **no personal thesis content**.

## Why This Template

- Ready-to-use thesis structure with front matter, chapters, appendix, and bibliography
- Clean placeholders for title, author, advisor, and defense date
- Privacy-friendly: no real names, no sensitive text, no personal publications
- Lightweight references (`references.bib`) for immediate compilation
- Minimal and extensible chapter templates for fast customization

## Quick Start

1. Clone the repository.
2. Open `000_thesis.tex`.
3. Replace metadata placeholders:
   - `Your Thesis Title`
   - `Your Name`
   - `Your Subject`
   - `Your Department`
   - advisor / defense date comments
4. Replace chapter placeholder text in `text/*.tex`.
5. Add your own references to `references.bib`.
6. Compile with XeLaTeX + BibTeX.

## Recommended Compile Commands

```bash
xelatex 000_thesis.tex
bibtex 000_thesis
xelatex 000_thesis.tex
xelatex 000_thesis.tex
```

## Project Structure

```text
.
├── 000_thesis.tex                      # Main entry file
├── 00I_dedication.tex                  # Optional dedication
├── 00II_acknowledgments.tex            # Acknowledgments
├── 00III_abstract.tex                  # Abstract
├── 00IV_publications.tex               # Optional publications appendix
├── references.bib                      # Minimal bibliography examples
├── text/
│   ├── chapter01_introduction.tex
│   ├── chapter02_literature_review.tex
│   ├── chapter03_methodology.tex
│   ├── chapter04_experiments.tex
│   ├── chapter05_discussion.tex
│   └── chapter06_conclusion.tex
└── ustthesis.cls / ustthesis.sty        # Thesis class files
```

## Privacy and Open-Source Safety

Before publishing your thesis repo:

- Remove personal acknowledgments and unpublished content
- Replace all names with placeholders in public branches
- Remove private figures/tables/data files if they contain sensitive information
- Keep only representative references and examples

This template has already applied those principles.

## FAQ

### 1) Can I keep figures and tables?
Yes. This public template removes them by default. You can add your own in your private or final thesis version.

### 2) Can I use this for PhD?
Yes, but check your program's latest formatting requirements and update metadata accordingly.

### 3) Why are some sections minimal?
The goal is to provide a safe, reusable starter template rather than a filled thesis sample.

## Contributing

Issues and pull requests are welcome for:

- style improvements
- class compatibility fixes
- better automation scripts
- multilingual documentation

If this template helps you, please consider starring the repo.
