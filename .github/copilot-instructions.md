# aeo-demo-accounting

## Project
HTML template for accounting industry with Schema.org, llms.txt, FAQ, and AI-friendly markup for AEO demos.

## Conventions
- Use semantic HTML5 elements (`<header>`, `<main>`, `<article>`, `<section>`, `<footer>`)
- Include Schema.org JSON-LD in `<script type="application/ld+json">` tags
- Place scripts at end of `<body>` for performance
- Use lowercase kebab-case for file names
- Keep FAQ content in structured `<details>`/`<summary>` elements

## Naming
- Use descriptive, lowercase file names: `index.html`, `faq.html`, `llms.txt`
- Name Schema.org types following schema.org vocabulary (Organization, FAQPage, BreadcrumbList)
- Use semantic class names: `.faq-item`, `.schema-markup`, `.breadcrumb`

## Architecture
- Single HTML pages with clear semantic structure
- JSON-LD Schema.org data embedded in `<head>`
- llms.txt for AI crawler discovery in root
- FAQ section using structured markup for rich results

## Commands
- No build commands required — plain HTML files
- Validate HTML with W3C Validator
- Test Schema.org with Google Rich Results Test

## Do Not
- Do not use inline JavaScript for Schema.org data
- Do not omit `<meta name="description">` for SEO
- Do not create unnecessary subdirectories — keep structure flat
- Do not use non-semantic `<div>` wrappers where semantic elements exist