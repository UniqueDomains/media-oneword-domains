# Media One-Word Domains (20,204)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C204%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of media one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,204 domains** on the canonical page below.

**Public extract:** 10,000 rows · **Live catalog:** 20,204 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/sector/media`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/sector/media?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./media.csv">CSV</a> / <a href="./media.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this exact search](https://unique.domains/domains/sector/media?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this exact search](https://unique.domains/domains/sector/media?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for the exact Unique Domains search represented by `https://unique.domains/domains/sector/media`.

### Files

- `media.csv` — public CSV extract (10,000 rows)
- `media.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/media-oneword-domains/main/media.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar                 |
| ------------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------------------- |
| communication.ninja | available | $42.98     | —             | 54             | 80     | 13     | namecheap                 |
| entertainment.xyz   | resell    | $57,494.25 | $20.99        | 56             | 88     | 13     | Go Australia Domains, LLC |
| internet.tech       | premium   | $3,250     | $13,000       | 64             | 88     | 8      | namecheap                 |
| news.desi           | available | $22.98     | —             | 82             | 64     | 4      | namecheap                 |
| marketing.me        | resell    | $28,750    | $27.99        | 74             | 49     | 9      | RegistryGate GmbH         |
| internet.store      | premium   | $1,562.50  | $6,250        | 64             | 88     | 8      | name.com                  |
| industry.new        | available | $549.99    | —             | 72             | 61     | 8      | name.com                  |
| video.net           | resell    | $115,000   | $23.99        | 106            | 47     | 5      | Spaceship, Inc.           |
| internet.space      | premium   | $3,250     | $13,000       | 64             | 88     | 8      | namecheap                 |
| industry.moi        | available | $39.99     | —             | 72             | 61     | 8      | name.com                  |
| content.xyz         | resell    | $57,500    | $20.99        | 138            | 39     | 7      | Unstoppable Domains, Inc. |
| internet.site       | premium   | $3,125     | $12,500       | 64             | 88     | 8      | name.com                  |
| industry.kiwi       | available | $35.68     | —             | 72             | 61     | 8      | namecheap                 |
| streaming.homes     | resell    | $19.98     | —             | 88             | 35     | 9      | Spaceship, Inc.           |
| internet.online     | premium   | $3,125     | $12,500       | 64             | 88     | 8      | name.com                  |
| industry.desi       | available | $22.98     | —             | 72             | 61     | 8      | namecheap                 |
| technology.army     | resell    | $48.98     | —             | 88             | 35     | 10     | GoDaddy.com, LLC          |
| entertainment.zone  | premium   | $1,040     | $1,040        | 56             | 88     | 13     | namecheap                 |
| storytelling.zone   | available | $51.98     | —             | —              | 60     | 12     | namecheap                 |
| press.paris         | resell    | $51.98     | —             | 66             | 29     | 5      | GoDaddy.com LLC           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract           | Unique Domains                                   |
| ------------------------ | ------------------------------------------------ |
| 10,000-row public sample | 20,204 live domains                              |
| Static CSV / JSON        | live search and daily refresh                    |
| Basic exported fields    | deeper price, demand, risk, and workflow context |
| No persistence           | Radar, saved search, and alerts                  |
| No founder workflow      | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/sector/media?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/sector/media?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Media One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live search](https://unique.domains/domains/sector/media?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_media_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
