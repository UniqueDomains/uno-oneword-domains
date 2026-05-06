# Available .UNO One-Word Domains (12,359)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C359%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .uno one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,359 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,359 domains · **Median ask:** $255.56 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `uno.csv` — public CSV extract (1,000 rows)
- `uno.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/uno-oneword-domains/main/uno.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| Godzilla.uno     | available | $31.98    | —             | 80             | 63     | 8      | namecheap        |
| pandora.uno      | resell    | —         | —             | 78             | 36     | 7      | GoDaddy.com, LLC |
| hotels.uno       | premium   | $3,125    | —             | 64             | 82     | 6      | name.com         |
| RedSox.uno       | available | $31.98    | —             | 72             | 60     | 7      | namecheap        |
| travelers.uno    | premium   | $156.25   | —             | 58             | 61     | 9      | name.com         |
| matcha.uno       | available | $31.98    | —             | 86             | 39     | 6      | namecheap        |
| cars.uno         | premium   | $3,125    | —             | 66             | 47     | 4      | name.com         |
| neuroscience.uno | available | $31.98    | —             | 80             | 37     | 12     | namecheap        |
| skills.uno       | premium   | $625      | —             | 58             | 47     | 6      | name.com         |
| howto.uno        | available | $31.98    | —             | 76             | 35     | 6      | namecheap        |
| Ryan.uno         | premium   | $700      | $700          | 60             | 44     | 4      | namecheap        |
| letsgo.uno       | available | $31.98    | —             | 57             | 31     | 7      | namecheap        |
| Tools.uno        | premium   | $3,500    | $3,500        | 56             | 40     | 5      | namecheap        |
| inhouse.uno      | available | $31.98    | —             | 70             | 23     | 8      | namecheap        |
| WiFi.uno         | premium   | $1,400    | $1,400        | 83             | 37     | 5      | namecheap        |
| smartest.uno     | available | $3.99     | $27.99        | 64             | 20     | 8      | namesilo         |
| tickets.uno      | premium   | $3,125    | —             | 64             | 34     | 7      | name.com         |
| stronger.uno     | available | $31.98    | —             | 67             | 19     | 8      | namecheap        |
| etc.uno          | premium   | $156.25   | —             | 58             | 34     | 3      | name.com         |
| lostandfound.uno | available | $31.98    | —             | 64             | 19     | 14     | namecheap        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,359 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/uno?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/uno?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .uno domains. The words range from broad dictionary terms like while.uno and laugh.uno to more descriptive options like textile.uno and traveling.uno. For founders, the key question is whether the word is memorable enough to offset a less common extension. For investors, the test is stricter: the word must be strong enough to support resale interest despite narrower buyer familiarity. With a median ask of 255.56, pricing sits in an accessible range, so the real separator is word quality: clarity, commercial relevance, and how naturally the term pairs with .uno.

- Prioritize words that stay clear on a non-mainstream TLD
- Favor memorable terms like queen.uno or laugh.uno
- Check if the word feels commercial, generic, and reusable
- Use price discipline when weaker words ask near the median

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .UNO One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .UNO page](https://unique.domains/domains/tld/uno?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uno_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
