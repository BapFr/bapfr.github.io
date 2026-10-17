# Baptiste Ferrere – Personal Academic Website

This repository contains the source code for my academic website, built with [Jekyll](https://jekyllrb.com/) and the [academicpages](https://github.com/academicpages) template, and hosted via GitHub Pages.

🔗 **Live website**: [bapfr.github.io](https://bapfr.github.io/)

## About Me

I am a PhD student in Mathematics at Université de Toulouse, working in collaboration with EDF R&D through a CIFRE agreement. My research focuses on explainable AI, uncertainty quantification and statistical learning, particularly using decomposition techniques.

## Site Structure

The site includes:
- An overview of my research and academic background
- A CV
- Teaching activities (coming soon)
- Future publications and talks (coming soon)

## Contact

- Email : [baptiste706@gmail.com](mailto:baptiste706@gmail.com)
- Email (EDF): [baptiste.ferrere@edf.fr](mailto:baptiste.ferrere@edf.fr)
- Website: [bapfr.github.io](https://bapfr.github.io/)
- GitHub: [@BapFr](https://github.com/BapFr)  
- LinkedIn: [Baptiste Ferrere](https://www.linkedin.com/in/baptisteferrere/)

## Editing the website

The public pages use a shared dark layout compatible with GitHub Pages and Jekyll.

- **Home:** `_pages/about.md` (introduction, news and research directions).
- **Publications:** one Markdown file per paper in `_publications/`. The `authors`, `summary`, `arxivurl`, `paperurl` and optional `codeurl` fields populate the publication list. Set `selected: true` and `selected_order` to feature a paper on the home page.
- **Talks and scientific events:** `_data/academic.yml`.
- **Teaching:** `_pages/teaching.html`.
- **CV:** `_pages/cv.md` and `files/cv_baptiste.pdf`.
- **Appearance:** `assets/css/academic.css`; the first block defines the colors. Shared templates are `_layouts/academic.html` and `_includes/academic-profile.html`.
- **Navigation:** `_data/navigation.yml`.

AcademicPages demonstration content is retained in the repository and excluded from the generated site in `_config.yml`.

For normal local development, use a recent Ruby version (3.1 or newer), install Bundler and run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local address printed by Jekyll. Publishing uses the repository's existing GitHub Pages configuration.
