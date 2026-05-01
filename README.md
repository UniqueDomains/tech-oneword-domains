# Available .TECH One-Word Domains (71,256)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-71%2C256%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tech one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **71,256 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 71,256 domains

**Last updated:** 2026-05-01  
**Canonical page:** `https://unique.domains/domains/tld/tech`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/tech?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./tech.csv">CSV</a> / <a href="./tech.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TECH search](https://unique.domains/domains/tld/tech?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TECH search](https://unique.domains/domains/tld/tech?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TECH one-word domain catalog.

### Files

- `tech.csv` — public CSV extract (1,000 rows)
- `tech.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tech-oneword-domains/main/tech.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| massproduction.tech | available | $13.99    | $84.99        | 54             | 72     | 15     | name.com                                            |
| Lamborghini.tech    | resell    | —         | —             | 84             | 100    | 11     | Namecheap                                           |
| agricultural.tech   | premium   | $650      | $1,300        | 74             | 84     | 12     | namecheap                                           |
| abaxially.tech      | available | $49.98    | —             | 44             | 72     | 9      | namecheap                                           |
| ignition.tech       | resell    | —         | —             | 70             | 88     | 8      | CHENGDU WEST DIMENSION DIGITAL TECHNOLOGY CO., LTD. |
| accounting.tech     | premium   | $1,625    | $3,250        | 64             | 84     | 10     | namecheap                                           |
| saveit.tech         | available | $13.99    | —             | 74             | 13     | 7      | name.com                                            |
| treasury.tech       | resell    | —         | —             | 68             | 84     | 8      | Namecheap                                           |
| oral.tech           | premium   | $312.50   | $1,250        | 58             | 84     | 4      | name.com                                            |
| howdo.tech          | available | $13.99    | —             | 58             | 13     | 6      | name.com                                            |
| otter.tech          | resell    | —         | —             | 56             | 84     | 5      | HOSTINGER operations, UAB                           |
| coal.tech           | premium   | $312.50   | $1,250        | 50             | 84     | 4      | name.com                                            |
| keepsecret.tech     | available | $13.99    | —             | 48             | 12     | 11     | name.com                                            |
| Minecraft.tech      | resell    | —         | —             | 91             | 81     | 9      | Sav.com, LLC - 25                                   |
| internship.tech     | premium   | $3,125    | $12,500       | 62             | 80     | 10     | name.com                                            |
| MickeyMouse.tech    | available | $58.98    | —             | 86             | 11     | 12     | namecheap                                           |
| agents.tech         | resell    | —         | —             | 56             | 50     | 6      | Spaceship, Inc.                                     |
| cladding.tech       | premium   | $78.12    | $312.50       | 54             | 80     | 8      | name.com                                            |
| bearinmind.tech     | available | $13.99    | —             | 76             | 11     | 12     | name.com                                            |
| quick.tech          | resell    | —         | —             | 72             | 43     | 5      | Spaceship, Inc.                                     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 71,256 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tech?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tech?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TECH One-Word Domains*. Version 2026-05-01. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TECH page](https://unique.domains/domains/tld/tech?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tech_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
