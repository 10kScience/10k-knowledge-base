# 10k Corpus

This repository contains the public knowledge corpus for Dynamoid and 10k Science.

The corpus is designed for people, search engines, LLMs, and future adaptive homepage experiments. It includes human-readable pages, machine-readable JSON chunks, structured data, and `llms.txt`.

The corpus also includes search and AI discovery pages for non-branded questions such as "good science VR apps," "interactive 3D science," "VR biology app," "NGSS-aligned immersive science," and "AI-guided formative assessment."

## Canonical Naming

- Dynamoid is the company.
- 10k Science is the flagship product and platform.
- 10k Viewer, 10k Creator, Educator Dashboard, AI Guides, and the content library are product surfaces or features of 10k Science.
- Public content uses "10k Science" as the product name.

## Core Files

- `index.md`: home page for the public corpus.
- `faq.md`: public FAQ about 10k Science.
- `llms.txt`: concise LLM-readable public summary.
- `knowledge/index.json`: machine-readable corpus index.
- `knowledge/queries.json`: non-branded query intent map.
- `content/`: public corpus pages.
- `schema/`: structured data snippets.

## Deployment Signals

The corpus includes:

- `llms.txt` for LLM-readable canonical facts.
- `robots.txt` that allows public crawlers, including `OAI-SearchBot`.
- `sitemap.xml` generated from corpus pages.
- JSON-LD snippets and a default HTML layout with Organization and SoftwareApplication structured data.
- `knowledge/queries.json` mapping non-branded user queries to canonical corpus pages.

The current GitHub Pages URL is configured in `_config.yml`.
