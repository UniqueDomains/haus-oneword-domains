# Available .HAUS One-Word Domains (11,836)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C836%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .haus one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,836 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,836 domains · **Median ask:** $25.46 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-15  
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

- `haus.csv` — public CSV extract (1,000 rows)
- `haus.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/haus-oneword-domains/main/haus.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| shortcuts.haus     | available | $19.99    | —             | 48             | 41     | 10     | name.com    |
| Your.haus          | resell    | —         | —             | 68             | 59     | 4      | Dynadot Inc |
| slots.haus         | premium   | $242      | $242          | 49             | 31     | 5      | namesilo    |
| neuroscience.haus  | available | $19.99    | —             | 80             | 37     | 12     | name.com    |
| cars.haus          | resell    | —         | —             | 66             | 47     | 4      | Porkbun LLC |
| hightech.haus      | premium   | $250      | —             | 83             | 16     | 9      | name.com    |
| payments.haus      | available | $19.99    | —             | 58             | 33     | 8      | name.com    |
| homes.haus         | resell    | —         | —             | 86             | 34     | 5      | Porkbun LLC |
| VirginiaBeach.haus | premium   | $1,120    | $1,120        | 58             | 9      | 14     | namecheap   |
| teams.haus         | available | $19.99    | —             | 62             | 32     | 5      | name.com    |
| nana.haus          | premium   | —         | —             | 76             | 28     | 4      | —           |
| trends.haus        | available | $19.99    | —             | 60             | 32     | 6      | name.com    |
| cams.haus          | available | $19.99    | —             | 52             | 29     | 4      | name.com    |
| Elias.haus         | available | $37.98    | —             | 72             | 28     | 5      | namecheap   |
| KFC.haus           | available | $37.98    | —             | 74             | 27     | 3      | namecheap   |
| drops.haus         | available | $19.99    | —             | 52             | 25     | 5      | name.com    |
| Trex.haus          | available | $37.98    | —             | 80             | 24     | 5      | namecheap   |
| whats.haus         | available | $19.99    | —             | 58             | 24     | 5      | name.com    |
| loans.haus         | available | $19.99    | —             | 58             | 24     | 5      | name.com    |
| reports.haus       | available | $19.99    | —             | 58             | 24     | 7      | name.com    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,836 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/haus?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/haus?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .haus domains. The set spans dictionary words, abstract terms, and sharper brand words such as medicine.haus, right.haus, ink.haus, and raise.haus. For founders, the main question is whether the word is memorable and credible enough to carry a brand on a niche extension. For investors, the key issue is whether the word has enough commercial clarity to offset narrower buyer demand outside mainstream TLDs. With a median ask of 25.46, price may look accessible, but the stronger names are still the ones with broad meaning, clean spelling, and obvious end-user relevance.

- Prefer clear words that stay strong on a niche extension
- Check whether the word matches housing, design, or studio use
- Shorter, cleaner words tend to be easier to recall
- Avoid words that add trademark or interpretation risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HAUS One-Word Domains*. Version 2026-05-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HAUS page](https://unique.domains/domains/tld/haus?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_haus_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
