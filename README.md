# Arabic News & Discover SEO Editorial Checklist and QA System

> Review Arabic publisher pages against practical Google Discover and News editorial and technical checks. Passing this checklist cannot guarantee traffic, eligibility, or legal compliance.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Format: TEMPLATE_FRAMEWORK](https://img.shields.io/badge/Format-TEMPLATE--FRAMEWORK-green.svg)](#)
[![Tier: 1](https://img.shields.io/badge/Tier-1-orange.svg)](#)
[![Region: MENA](https://img.shields.io/badge/Region-Egypt%20%7C%20GCC%20%7C%20Saudi-purple.svg)](#)
[![Tests: Passing](https://img.shields.io/badge/Tests-Passing-brightgreen.svg)](#)
[![Owner: mahmoudabdelnaby1](https://img.shields.io/badge/Owner-mahmoudabdelnaby1-blue.svg)](https://github.com/mahmoudabdelnaby1)

---

## 📌 Problem Statement & Target Persona

### Target Persona
**BOTH** operating in high-growth e-commerce, digital publishing, and direct-response marketing across Saudi Arabia, UAE, and Egypt.

### Core Problem
Build an exhaustive Google Discover and Google News optimization toolkit for Arabic publishers: 1) editorial pre-publish checklist, 2) Technical template requirements (high-res images, NewsArticle schema, AMP/mobile responsiveness), 3) E-E-A-T author bio and editorial transparency templates, 4) Discover traffic drop recovery diagnostic workflow.

---

## 🛠️ Repository Architecture & Deliverables

This repository provides self-contained, documented implementations and specifications:

- `checklists/editorial-prepublish-checklist.md`
- `checklists/technical-discover-audit.md`
- `LICENSE`
- `playbooks/discover-traffic-recovery.md`
- `README.md`
- `templates/author-transparency-page.md`
- `templates/news-article-schema.json`
- `tests/test_data_integrity.py`


---

## 🚀 Quick Start & How to Run Locally

### Run Test Suite Locally
```bash
# Ensure no bytecode generation
export PYTHONDONTWRITEBYTECODE=1  # Linux / macOS
$env:PYTHONDONTWRITEBYTECODE="1"  # Windows PowerShell

# Run Python unittest discovery
python -m unittest discover -s tests
```

---

## 📊 Sample Input & Output Fixtures

> **Data Disclosure:** Any included sample data is illustrative and may be synthetic; it is not a measured customer result or market benchmark unless a source and collection method are stated alongside it. These files run offline with standard libraries and require no paid third-party API credentials.

```json
{
  "domain": "seo",
  "repository": "arabic-news-discover-seo-checklist",
  "status": "READY_FOR_LOCAL_REVIEW",
  "license": "MIT"
}
```

---

## ⚠️ Known Technical & Domain Constraints

- **High-Resolution Featured Images:** Articles require image assets at least 1200px wide with max-image-preview:large robots setting for Discover eligibility.
- **Bilingual Editorial Accuracy:** News headlines must avoid sensational clickbait while maintaining compelling emotional engagement in Arabic.
- **Author Transparency & Schema:** Every news item requires explicit NewsArticle schema with Person author entity and publisher verification.

---

## 📚 Primary Documentation & Verifiable References

- [Google Search Central: Google Discover Guidelines](https://developers.google.com/search/docs/appearance/google-discover) - Official content eligibility and image sizing standards for Discover feed.
- [Google News Publisher Center Guidelines](https://support.google.com/news/publisher-center/answer/9607025) - Publishing standards and technical requirements for news content.
- [Schema.org NewsArticle Specification](https://schema.org/NewsArticle) - Structured data definitions for news reporting and author attribution.

---


## 👤 Maintainer & License

- **Author & Maintainer:** [Mahmoud Abdelnaby](https://github.com/mahmoudabdelnaby1) (`@mahmoudabdelnaby1`)
- **License:** [MIT License](LICENSE) - Open-source, auditable, and freely adaptable for internal enterprise or commercial use.
