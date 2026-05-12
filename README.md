# Available .DESI One-Word Domains (10,409)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C409%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .desi one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,409 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,409 domains · **Median ask:** $22.98 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/desi`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/desi?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./desi.csv">CSV</a> / <a href="./desi.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DESI search](https://unique.domains/domains/tld/desi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DESI search](https://unique.domains/domains/tld/desi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DESI one-word domain catalog.

### Files

- `desi.csv` — public CSV extract (1,000 rows)
- `desi.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/desi-oneword-domains/main/desi.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Sony.desi          | premium   | —         | —             | 86             | 67     | 4      | —         |
| homes.desi         | available | $22.98    | —             | 86             | 34     | 5      | namecheap |
| Fanta.desi         | premium   | —         | —             | 88             | 17     | 5      | —         |
| movies.desi        | available | $22.98    | —             | 80             | 28     | 6      | namecheap |
| winners.desi       | available | $22.98    | —             | 60             | 81     | 7      | namecheap |
| RedCross.desi      | premium   | —         | —             | 71             | 95     | 9      | —         |
| insight.desi       | available | $22.98    | —             | 76             | 69     | 8      | namecheap |
| NewZealand.desi    | premium   | —         | —             | 78             | 94     | 11     | —         |
| online.desi        | available | $22.98    | —             | 70             | 62     | 7      | namecheap |
| Siri.desi          | premium   | —         | —             | 76             | 68     | 4      | —         |
| keepthechange.desi | available | $22.98    | —             | 46             | 59     | 15     | namecheap |
| everything.desi    | available | $22.98    | —             | 68             | 47     | 10     | namecheap |
| WhiteSox.desi      | premium   | —         | —             | 70             | 58     | 9      | —         |
| whynot.desi        | available | $22.98    | —             | 74             | 39     | 7      | namecheap |
| Ava.desi           | premium   | —         | —             | 76             | 41     | 3      | —         |
| Flowers.desi       | premium   | —         | —             | 72             | 39     | 7      | —         |
| ing.desi           | available | $22.98    | —             | 68             | 34     | 3      | namecheap |
| Jim.desi           | premium   | —         | —             | 78             | 28     | 3      | —         |
| etc.desi           | available | $22.98    | —             | 58             | 34     | 3      | namecheap |
| CNN.desi           | premium   | —         | —             | 78             | 27     | 3      | —         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,409 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/desi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/desi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of one-word .desi domains, which creates a very specific buying profile. The extension signals a South Asian or diaspora angle, so the best fits are names that stay clear, memorable, and contextually appropriate with that identity. The sample includes generic terms such as tips.desi and when.desi, geo and personal-name options like NYC.desi and Liam.desi, and also terms that raise obvious trademark concerns such as Audi.desi, Sony.desi, and Uber.desi. With a median ask of $22.98, price is accessible, but selection quality matters more than entry cost. Compare these domains on semantic fit, pronunciation, renewal comfort, and legal exposure.

- Generic words usually offer broader use than surname or given-name picks
- Geo terms like NYC.desi can suit community or local audience angles
- Trademarked terms carry clear legal and resale risk in this set
- Low ask price helps, but extension fit still drives long-term value

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DESI One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DESI page](https://unique.domains/domains/tld/desi?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_desi_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
