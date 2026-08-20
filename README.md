# Available .HAUS One-Word Domains (16,745)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C745%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .haus one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,745 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,745 domains · **Median ask:** $21.37 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/haus`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/haus?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./haus.csv">CSV</a> / <a href="./haus.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .HAUS search](https://unique.domains/domains/tld/haus?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .HAUS search](https://unique.domains/domains/tld/haus?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .HAUS one-word domain catalog.

### Files

- `haus.csv`, public CSV extract (1,000 rows)
- `haus.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/haus-oneword-domains/main/haus.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar           |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------- |
| ain.haus   | available | $11.98    | $37.98        | low            | low    | 3      | namecheap           |
| car.haus   | resell    | —         | —             | high           | medium | 3      | Dynadot Inc         |
| tea.haus   | premium   | $854      | $854          | medium         | medium | 3      | namesilo            |
| all.haus   | available | $19.99    | —             | high           | medium | 3      | name.com            |
| sea.haus   | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC    |
| web.haus   | premium   | $854      | $854          | high           | medium | 3      | namesilo            |
| are.haus   | available | $19.99    | —             | high           | low    | 3      | name.com            |
| sip.haus   | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC    |
| bake.haus  | premium   | $242      | $242          | high           | low    | 4      | namesilo            |
| ash.haus   | available | $19.99    | —             | medium         | low    | 3      | name.com            |
| live.haus  | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 11   |
| bern.haus  | premium   | $854      | $854          | high           | low    | 4      | namesilo            |
| era.haus   | available | $19.99    | —             | high           | medium | 3      | name.com            |
| sexy.haus  | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC    |
| jail.haus  | premium   | $242      | $242          | high           | low    | 4      | namesilo            |
| fin.haus   | available | $11.98    | $37.98        | low            | low    | 3      | namecheap           |
| motor.haus | resell    | —         | —             | high           | low    | 5      | NameCheap, Inc.     |
| block.haus | premium   | $1,040    | $1,040        | medium         | low    | 5      | namecheap           |
| icu.haus   | available | $19.99    | —             | high           | low    | 3      | name.com            |
| pizza.haus | resell    | —         | —             | high           | low    | 5      | united-domains GmbH |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,745 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/haus?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/haus?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=related_pricing)

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

This list of one-word .HAUS domains covers short, single-token names built for creative, home, design, and lifestyle brands — the kind of category .HAUS is known for. Pricing sits low relative to major TLDs, with a median ask near $28, making it easy to test brand fit before committing to a longer-term renewal cost. Compare each name for spelling clarity, length, and category fit before shortlisting.

- 11,838 one-word .HAUS domains available for evaluation
- Median asking price near $28 across the selection
- Short, brandable names suited to design and lifestyle brands
- Updated daily as new .HAUS domains enter the selection

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HAUS One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HAUS page](https://unique.domains/domains/tld/haus?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
