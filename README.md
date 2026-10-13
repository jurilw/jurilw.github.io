# jurilw.github.io

Personal website for [Juri Westendorf](https://jurilw.github.io), published
via GitHub Pages from the `main` branch of this repository.

## Structure

```
├── index.html        # Home
├── projects.html     # Projects
├── plans.html        # Plans
├── cv.html           # CV
├── css/
│   └── site.css      # Shared styling
└── README.md
```

The site is plain HTML and CSS with no JavaScript, no build step, no
frameworks, no external font services, analytics or trackers. All links are
relative, as required for GitHub Pages.

## Local preview

No dependencies are needed. Serve the repository root with any static file
server and open the printed URL:

```sh
cd jurilw.github.io
python3 -m http.server 8000
# then open http://localhost:8000/
```

Any other static server works too (e.g. `npx serve .` or
`php -S localhost:8000`).

## Editing and publishing

1. Make your changes locally (all pages share `css/site.css` for styling).
2. Review the diff:

   ```sh
   git diff
   ```

3. Commit and push to `main`. GitHub Pages deploys automatically from this
   branch, usually within a minute or two:

   ```sh
   git add -A
   git commit -m "Describe the change"
   git push
   ```

4. Verify the live site at <https://jurilw.github.io>.

Keep pages semantic and simple; the design deliberately avoids animation,
icons, and external services.

## Content checklist (to be filled in)

- [ ] **CV:** email address and location (if to be published).
- [ ] **CV:** education history (degrees, institutions, dates).
- [ ] **CV:** prior positions and experience.
- [ ] **CV:** publications, preprints or working papers.
- [ ] **CV:** awards, grants or fellowships.
- [ ] **CV:** skills (languages, programming, tools).
- [ ] **CV:** a CV PDF, if a downloadable copy is wanted (then a download
      link can be added).
- [ ] **Plans:** future directions and upcoming work.
- [ ] **Projects:** more projects, plus per-project repository links,
      descriptions and status updates as they become public.
- [ ] **Home:** any additional one-line background you want on the landing
      page.
