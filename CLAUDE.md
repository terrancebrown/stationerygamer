Repo: ~/Sites/stationerygamer (branch: main)
Theme: Blowfish
Hugo version: 0.161.1+extended+withdeploy
Deployment: Cloudflare Pages via GitHub push to main. Build command: hugo --minify. HUGO_VERSION env var is set to 0.161.1.
Editor: VSCodium (primary), micro in terminal.

Content structure:
- All posts are flat .md files organised into topic sections
- Sections: content/stationery/, content/board-games/, content/video-games/, content/about/
- No date prefix on slugs
- Front matter is YAML (--- delimiters)
- Archetype scaffolds: date, draft, title only — additional fields added manually
- New post commands:
  hugo new content/stationery/slug.md
  hugo new content/board-games/slug.md
  hugo new content/video-games/slug.md

Front matter convention:
```yaml
date: 'YYYY-MM-DDTHH:MM:SS+02:00'
draft: true
title: Post Title
tags: ["tag"]
```

The site covers stationery, pens/inks, journaling, and gaming. All content sections are currently empty — early stage. The owner is South African, writes in South African English (en-GB spelling). Enthusiastic but considered tone.
