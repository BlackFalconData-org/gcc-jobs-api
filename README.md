# GCC Jobs API

Get current job listings in the UAE, Saudi Arabia, Qatar, Kuwait, Bahrain and Oman from Bayt, Naukrigulf and GulfTalent with one HTTP call or MCP tool. Filter by city, salary and posting date, flag likely cross-board duplicates and follow new and expired jobs.

**[GCC Jobs API on Apify →](https://apify.com/blackfalcondata/gcc-jobs-api?fpr=1h3gvi)**

---

## 🚀 How to use this actor

> ### 💚 $5 free Apify credits — every month
> No credit card required. No commitment. Cancel anytime.

### 👉 [Sign up free on Apify →](https://console.apify.com/sign-up?fpr=1h3gvi)

1. **Click sign up** — pick GitHub, Google, or email; takes ~30 seconds
2. **Open this actor** — input is pre-filled with a working example
3. **Click Start** — export results as JSON, CSV, or Excel

Your **$5 monthly platform credit** is enough to run this actor right away — and again every month — scraping typically several hundred to several thousand results per run, depending on your input.

## Key features

**Export anywhere** — Download as JSON, CSV, or Excel. Stream via Apify API, webhooks, or integrations with Make, Zapier, Airbyte, Keboola.

**Structured data** — Every job returns the same schema with consistent field naming. All fields always present — `null` when unavailable, never omitted.

---

## Use cases

**Data pipeline automation**
Integrate with your ETL pipeline to collect structured jobs from the source on a schedule. Export to CSV, JSON, or directly to your database.

**Market research**
Monitor jobs, track trends, and analyze market dynamics with structured, deduplicated data from the source.

**Compensation benchmarking**
Aggregate salary ranges across roles, industries, and locations on the source to inform pricing decisions, hiring plans, or candidate negotiations.

**AI / LLM training data**
Structured JSON per job is ready for RAG pipelines, embeddings, and agent workflows.

---

## Quick start

```json
{
  "maxResults": 50
}
```

---

## Input parameters

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|

---

## Output fields

Every job returns the same 14-field schema. Missing values are `null` — never omitted.

- `id`
- `board`
- `country`
- `title`
- `company`
- `location`
- `category`
- `industry`
- `postedAt`
- `url`
- `city`
- `salary`
- `su`
- `summary`

---

## Sample output

One object per job. Here is a real example from a production run:

```json
{
  "id": "naukrigulf-271026000350",
  "board": "naukrigulf",
  "country": "AE",
  "title": "environmental engineer / environmental consultant",
  "company": "Confidential Company",
  "location": "Dubai - United Arab Emirates (UAE)",
  "category": "Engineering",
  "industry": "Water Treatment / De-Salination / Waste Management",
  "postedAt": "2026-10-27T17:17:49.000Z",
  "url": "https://www.naukrigulf.com/environmental-engineer-environmental-consultant-jobs-in-dubai-uae-in-confidential-2-to-8-years-n-jid-271026000350",
  "city": "Dubai",
  "salary": null
}
```

*Truncated — full records contain 14 fields. See Output fields for the complete schema.*

**[Try GCC Jobs API now — $5 free credit, no credit card →](https://apify.com/blackfalcondata/gcc-jobs-api?fpr=1h3gvi)**

---

## Pricing

Pay only for what you extract. No subscription required — Apify's free $5 credit covers thousands of results.

| Event | Price (USD) |
| --- | --- |
| Job record | $0.0011 |

See the [actor on Apify](https://apify.com/blackfalcondata/gcc-jobs-api?fpr=1h3gvi) for current pricing.

---

## FAQ

**How much does it cost?**
Pay-per-event pricing — you only pay for ${NOUNS} extracted. Apify's free $5 credit is enough to run thousands of results before you pay anything.

**Do I need an API key or credentials?**
No. Just sign up for Apify, paste your input, and click Start. No credit card required.

---

## Related products by Black Falcon Data

[Browse all Black Falcon Data actors →](https://apify.com/blackfalcondata?fpr=1h3gvi)

---

## Getting started with Apify

New to Apify? [Create a free account with $5 credit](https://console.apify.com/sign-up?fpr=1h3gvi) — no credit card required.

1. Sign up — $5 platform credit included
2. Open [GCC Jobs API](https://apify.com/blackfalcondata/gcc-jobs-api?fpr=1h3gvi) and configure your input
3. Click **Start** — export results as JSON, CSV, or Excel

Need more later? [See Apify pricing](https://apify.com/pricing?fpr=1h3gvi).

---

## About Black Falcon Data

Black Falcon Data builds production-grade web scrapers for job boards and marketplace data. Browse our full actor catalog at [www.blackfalcondata.com](https://www.blackfalcondata.com).

---

*Last updated: 2026 10*
