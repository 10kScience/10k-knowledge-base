# 10k Knowledge Base

This repository contains public information about Dynamoid and 10k Science.

The knowledge base includes product information, audience pages, evidence, source links, structured content, and topic pages for common science learning interests.

## Canonical Naming

- Dynamoid is the company.
- 10k Science is the flagship product and platform.
- 10k Viewer, 10k Creator, Educator Dashboard, AI Guides, and the content library are product surfaces or features of 10k Science.
- Public content uses "10k Science" as the product name.

## Core Files

- `index.md`: home page for the public knowledge base.
- `faq.md`: public FAQ about 10k Science.
- `llms.txt`: concise public summary.
- `knowledge/index.json`: structured knowledge-base index.
- `knowledge/corpus.json`: combined machine-readable corpus for retrieval systems.
- `knowledge/cards.json`: adaptive homepage cards with audience, topic, CTA, and source metadata.
- `knowledge/policies.json`: public response guidance for pricing, naming, claims, CTAs, and freshness.
- `knowledge/queries.json`: discovery topic map.
- `knowledge/chunks/`: page-level public knowledge chunks.
- `content/`: public knowledge-base pages.
- `schema/`: JSON-LD structured data snippets and JSON schemas for knowledge files.

## Deployment Signals

The knowledge base includes:

- `llms.txt` for concise public facts.
- `robots.txt` for public crawler access.
- `sitemap.xml` generated from knowledge-base pages.
- JSON-LD snippets and a default HTML layout with Organization and SoftwareApplication structured data.
- `knowledge/queries.json` connecting discovery topics to knowledge-base pages.
- `knowledge/corpus.json`, `knowledge/cards.json`, and `knowledge/policies.json` for RAG systems and adaptive content surfaces.
- JSON schemas for chunks, corpus, cards, and retrieval policies.

The current GitHub Pages URL is configured in `_config.yml`.
