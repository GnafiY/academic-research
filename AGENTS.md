# Repository Guidelines

## Project Structure & Module Organization

This repository contains Haoyu Li’s bilingual academic website, built with Jekyll 3.9 and the Not Pure Poole theme.

- Root Markdown files contain pages: `index.md` and `index-zh.md` are the English and Chinese homepages; `resume.md` and `resume-zh.md` contain resumes.
- `_posts/` contains dated blog posts. `_layouts/` defines page templates; `_includes/` contains reusable Liquid/HTML fragments.
- `_sass/` holds SCSS partials, and `assets/styles.scss` assembles the styles. Root WebP images and `Resume-zh.pdf` are site assets.
- `_data/` configures navigation, social links, and archives. `_config.yml` controls site metadata and plugins.
- `scripts/` provides content and preview helpers. `_site/` is generated output and must remain untracked.

## Build, Test, and Development Commands

Run commands from the repository root with Ruby and Bundler installed:

- `bundle install`: install dependencies from `Gemfile` and the theme gemspec.
- `bundle exec jekyll build`: compile the site into `_site/` and catch template or configuration errors.
- `bundle exec jekyll serve`: preview at `http://localhost:4000` with automatic regeneration.
- `sh scripts/serve`: preview with drafts and error traces enabled.
- `sh scripts/draft my-post`: create a draft with Jekyll Compose.
- `sh scripts/publish _drafts/my-post.md`: convert a draft into a dated post.

## Coding Style & Naming Conventions

Follow `.editorconfig`: two-space indentation, UTF-8, LF endings, a final newline, and no trailing whitespace. Preserve intentional Markdown line breaks. Use YAML front matter for page metadata and Liquid for shared rendering. Name posts `YYYY-MM-DD-descriptive-title.md` and SCSS partials `_component.scss`. Keep corresponding English and Chinese pages consistent. No dedicated formatter or linter is configured.

## Testing Guidelines

No automated test suite or coverage threshold is configured. Build the site, then inspect affected pages locally. Check desktop/mobile layouts, language switching, navigation, publication links, resume downloads, and light/dark styling when relevant. Verify links under the `/academic-research/` deployment path. Restart the preview server after configuration changes.

## Commit & Pull Request Guidelines

Recent commits use `[Done] <completed change>. [Todo] <remaining work>.`; follow this format where applicable. Keep commits focused. Pull requests should describe the change, link related issues, list build and preview checks, and include screenshots for visual changes. Avoid committing generated output, caches, or packaged `.gem` files.
