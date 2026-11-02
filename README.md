# LinkedIn Jobs Scraper Pro

LinkedIn job postings with full description, applicant count, seniority and salary at $1 per 1,000 jobs. Remote, job type, experience, Easy Apply and posted-within filters, plus company, title and applicant filters applied before billing.

> [Run LinkedIn Jobs Scraper Pro on the Apify Store](https://apify.com/red.cars/linkedin-jobs-scraper-pro)
> [ScraperFleet data page](https://scraperfleet.com/actors/linkedin-jobs-scraper-pro/)

## Why this actor

- Purpose-built: LinkedIn job postings with full description, applicant count, seniority and salary at $1 per 1,000 jobs.
- Categories: JOBS, LEAD_GENERATION, AI
- Runs on Apify's managed platform with results delivered to the actor dataset, ready via API, webhook, or download.

## Comparison

If you're comparing LinkedIn Easy Apply jobs scrapers on the Apify Store, the dedicated Easy Apply listings at the top of that search have nine users or fewer, and most general LinkedIn jobs scrapers don't expose applicant counts at all. This actor filters on Easy Apply before billing and returns full description, applicant count, seniority and salary on every row, so you never pay for jobs your filters rejected.

## Pricing

| Item | Price |
| --- | --- |
| Run start | $0.005 per run |
| Job saved | $1.00 per 1,000 jobs (pay per event) |

## FAQ

**Do I need a LinkedIn account or cookies?**
No. It reads LinkedIn's public job pages only. No login, no session cookies, no setup.

**What exactly do I get per job?**
Title, company, location, posted date, applicant count, salary band when the employer posted one, and the full job description (plus criteria and the apply link). Every row is a complete job record, not a truncated snippet.

**How does pricing work exactly?**
Pay per event: $0.005 per run start plus $0.001 per job saved ($1.00 per 1,000). Filters run before billing, so a job removed by your company, title, or applicant filters is never charged. 10,000 fresh jobs with descriptions and applicant counts cost about $10.

**How many jobs can one search return?**
LinkedIn's public search returns up to about 1,000 jobs per query. Split big searches by location or keyword to go further. Duplicates across searches are removed automatically.

**Do I pay for filtered jobs?**
No. Company, title and applicant filters run before anything is saved or charged.

**What makes it different?**
Full job details in every row, applicant counts on every job, filters applied before billing, and one flat price on every Apify plan, free plan included.

**Is salary always included?**
Only when the employer posts it on LinkedIn. Use `minSalary` to restrict to jobs with a posted salary band (US).

**Which output format should I use?**
JSON, CSV and Excel land in the run dataset, or pull rows through the API, n8n, Make, Zapier or an MCP client. JSON for pipelines, Excel for spreadsheets, API for live feeds.

**Can I run it on a schedule?**
Yes. Set an Apify schedule for a daily or hourly pull of the same searches. Pair it with `postedWithin: 24h` to feed a job board or alert feed with fresh listings only.

**Is scraping LinkedIn jobs legal?**
The actor collects publicly visible job postings without logging in. Check with your counsel for your use case.

## Send your leads straight to your pipeline

Every run lands as clean JSON/CSV in the run dataset, ready to push into HubSpot, Pipedrive, HighLevel, Instantly, Smartlead, or Lemlist through Apify's built-in Zapier, Make, and n8n integrations, or straight into Google Sheets. Scrape in the morning, sequence outreach the same day.
