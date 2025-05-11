# GitHub Markdown Blog Viewer

This repository serves as a structured knowledge base and content hub built entirely using Markdown. Each `.md` file acts as a self-contained article, study note, or technical blog that can later be rendered through a viewer app or served as an API-backed blog system.

## Why this project?

This repo allows me to:

- Prepare interview-ready notes in markdown format
- Maintain structured learning materials across key topics (JS, React, System Design, etc.)
- Build content for a future blog site or viewer app
- Keep all notes version-controlled and accessible from anywhere

## Structure

The content is organized by top-level topics inside the `topics/` folder. These folders will serve as route paths in the future viewer or API.

topics/
├── javascript/
│   ├── prototypes.md
│   └── closures.md
├── react/
│   ├── hooks-deep-dive.md
├── system-design/
│   └── caching-strategies.md
├── interview-prep/
│   └── top-array-questions.md
└── notes/
└── ai-ideas.md

## Usage (Future Plan)

- This repo may later be connected to a Next.js blog app that fetches and renders markdown content based on the folder and filename.
- Possible metadata integration (`metadata.json`) to enrich SEO or viewer filters.
- Lightweight content management flow for solo developers or learners.

## License

MIT © [Anusua Roy](https://github.com/anusua-roy)
