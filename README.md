# Available .UNO One-Word Domains (17,327)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C327%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .uno one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,327 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,327 domains · **Median ask:** $155.76 · **High-demand under $2,500:** 45

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/uno`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/uno?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./uno.csv">CSV</a> / <a href="./uno.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .UNO search](https://unique.domains/domains/tld/uno?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .UNO search](https://unique.domains/domains/tld/uno?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .UNO one-word domain catalog.

### Files

- `uno.csv`, public CSV extract (1,000 rows)
- `uno.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/uno-oneword-domains/main/uno.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| ague.uno | available | $4.98     | $31.98        | low            | low    | 4      | namecheap        |
| ding.uno | resell    | —         | —             | medium         | low    | 4      | GoDaddy.com, LLC |
| ana.uno  | premium   | $156.25   | —             | high           | low    | 3      | name.com         |
| ahuh.uno | available | $3.99     | $27.99        | high           | low    | 4      | namesilo         |
| bow.uno  | premium   | $156.25   | —             | high           | low    | 3      | name.com         |
| arum.uno | available | $3.99     | $27.99        | low            | low    | 4      | namesilo         |
| clv.uno  | premium   | $156.25   | $312.50       | low            | low    | 3      | name.com         |
| brow.uno | available | $31.98    | —             | medium         | low    | 4      | namecheap        |
| cue.uno  | premium   | $312.50   | —             | medium         | low    | 3      | name.com         |
| cock.uno | available | $3.99     | $27.99        | medium         | low    | 4      | namesilo         |
| dip.uno  | premium   | $156.25   | $312.50       | high           | low    | 3      | name.com         |
| ecru.uno | available | $3.99     | $27.99        | low            | low    | 4      | namesilo         |
| DIY.uno  | premium   | $1,562.50 | —             | high           | low    | 3      | name.com         |
| eyry.uno | available | $3.99     | $27.99        | low            | low    | 4      | namesilo         |
| dog.uno  | premium   | $1,562.50 | —             | high           | low    | 3      | name.com         |
| flee.uno | available | $3.99     | $27.99        | medium         | low    | 4      | namesilo         |
| don.uno  | premium   | $156.25   | —             | high           | low    | 3      | name.com         |
| flew.uno | available | $3.99     | $27.99        | high           | low    | 4      | namesilo         |
| eye.uno  | premium   | $625      | —             | medium         | low    | 3      | name.com         |
| halt.uno | available | $19.99    | $27.99        | medium         | low    | 4      | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,327 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 45 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/uno?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/uno?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers 12,362 one-word .uno domain names, drawn from short, ownable words rather than long compound phrases. The median asking price across the set is about $249, giving a practical benchmark for comparing individual listings. Because .uno domains are compact and easy to pronounce, they suit founders looking for a clean, brandable name as well as anyone evaluating pricing patterns across a newer top-level domain. Use length, clarity, and asking price together when narrowing down which of these domains fits your budget and brand direction.

- 12,362 one-word .uno domain names in this list
- Median asking price is about $249 per domain
- Short, single-word names built for brandable startups
- Compare price against length and renewal before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .UNO One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .UNO page](https://unique.domains/domains/tld/uno?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
