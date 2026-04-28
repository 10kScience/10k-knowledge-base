# Structured Data Snippets

These files describe Dynamoid, 10k Science, and the public knowledge base in machine-readable formats.

## JSON-LD Structured Data

JSON-LD files describe entities and FAQ content for search engines and other structured data consumers:

- `organization-dynamoid.jsonld`: Dynamoid home page and 10k Knowledge Base home page.
- `software-application-10k-science.jsonld`: 10k Science product, pricing, and knowledge-base product pages.
- `faq-10k-science.jsonld`: FAQ and topic pages where the same questions are answered visibly on the page.

Structured data matches visible page content. Pricing is URL-based.

## Knowledge File Schemas

JSON schema files describe the public corpus and adaptive content files:

- `chunk.schema.json`: page-level knowledge chunks in `knowledge/chunks/`.
- `corpus.schema.json`: the combined `knowledge/corpus.json` file.
- `card.schema.json`: adaptive homepage cards in `knowledge/cards.json`.
- `policies.schema.json`: retrieval and response policies in `knowledge/policies.json`.

Schemas are intentionally flexible because some chunks need page-specific fields.
