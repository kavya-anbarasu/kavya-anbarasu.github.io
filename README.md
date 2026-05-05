# Kavya Personal Website

A minimal static personal website for GitHub Pages. It has a sticky header,
an intro/about section, icon links, experience, projects/research, a resume PDF,
and link slots for code, papers, PDFs, DOIs, and demos.

Live site: <https://kavya-anbarasu.github.io/>

## Quick Edits

The site is plain HTML/CSS, so there is no build step. For simple content
changes, edit `index.html` directly in GitHub:

- Social links: search for `icon-links`.
- Intro/about copy: search for `id="about"`.
- Experience entries: search for `id="experience"`.
- Project/research entries: search for `id="projects"`.
- Contact email: search for `id="contact"`.
- Styling: edit `styles.css`.
- Photo: upload a cropped image into the `assets/` folder, then change the
  `.portrait-photo` `src` in `index.html` to that file path. A clear filename
  would be `assets/kavya-photo-cropped.jpg`.
- Resume: replace `assets/kavya-anbarasu-resume.pdf`.
- PDFs: upload files into the `papers/` folder, then link to them from
  `index.html`.

In GitHub, open the file, click the pencil icon, make the change, then commit.
GitHub Pages will republish automatically.

For larger edits, layout changes, or copy polishing, it is still easiest to give
Codex the change you want and let it update the files.

## GitHub Pages

This repo is named `kavya-anbarasu.github.io`, so GitHub Pages serves it from
the default branch at <https://kavya-anbarasu.github.io/>.
