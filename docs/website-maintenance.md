# Maintaining the NDS Lab website

The site is built with Jekyll and GitHub Pages. The production source is the `master` branch of `byungjincho/byungjincho.github.io`.

## Main files

| Content | File |
| --- | --- |
| Home introduction and research overview | `_pages/about.md` |
| Research descriptions | `_pages/research.md` |
| News, newest first | `_data/news.yml` |
| People | `_pages/people.md` |
| Publications | `_pages/publications.md` |
| Teaching | `_pages/teaching.html` |
| Talks and professional service | `_pages/talks.html` |
| Contact and recruitment | `_pages/contact.md` |
| Main navigation | `_data/navigation.yml` |
| Shared layout and metadata | `_layouts/lab.html`, `_config.yml` |
| Typography and responsive styling | `assets/css/lab.css` |

## Adding news

Add an entry at the top of `_data/news.yml`. The homepage shows the first four items; `/news/` shows the complete archive. Both use the same data.

```yaml
- date_label: "Oct. 2026"
  text: "A confirmed update written in Markdown."
  link: /research/
  link_label: Read more
```

Use a year, month, or academic semester according to what is known. Do not infer an acceptance date from a publication date. An optional `source` URL records the evidence for a news item without displaying it as another link.

## Publication records

Keep published papers separate from work in progress and proposals. Verify bibliographic changes against a publisher or institutional record. The 2025 TMC and TIV records and three older bibliographic entries were updated from Aalto University's publication database. The news entries retain source URLs. AcademicPages demonstration posts, example CV, and other sample pages are excluded from publishing in `_config.yml`; their source remains in git.

## Design assets

The homepage uses `assets/images/nds-research-hero.webp`, a decorative conceptual illustration, not a photograph of a campus or a scientific diagram. Its generation prompt is recorded in `docs/hero-image-prompt.txt`.

Source Sans 3 and Source Serif 4 are self-hosted as Latin-subset variable WOFF2 fonts. Their SIL Open Font Licenses are stored alongside the fonts in `assets/fonts/`. The page uses no external font service.

## Preview and deployment

With Ruby and Bundler installed, run `bundle install`, then `bundle exec jekyll serve`. Check the homepage and navigation at desktop and mobile widths. Pushing to the GitHub Pages source branch triggers the repository's Pages build.
