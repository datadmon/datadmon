## Daemon Data

Pay-per-result data APIs on [Apify](https://apify.com/data_daemon) for sources that have no official API: **Indian job boards**, **Oracle Recruiting Cloud career sites**, **Indian IPOs and stocks**, **Dubai Land Department transactions**, **UK Gazette insolvency notices** and **Luma events**. Website: [datadmon.github.io](https://datadmon.github.io/).

### Ready-to-fork templates (GitHub Actions)

| Template | What it does |
|---|---|
| [india-job-alerts](https://github.com/datadmon/india-job-alerts) | New jobs from IIMJobs, Hirist, Foundit and Instahyre every morning, to a GitHub issue, Slack, Telegram, Discord or CSV. |
| [uk-insolvency-monitor](https://github.com/datadmon/uk-insolvency-monitor) | Alert when a customer or supplier appears in The Gazette with a winding-up petition, order or administration (matched by Companies House number). |
| [india-ipo-gmp-tracker](https://github.com/datadmon/india-ipo-gmp-tracker) | Today's IPO GMP, estimated listing price and subscription for mainboard and SME IPOs, with a daily GMP history and Telegram alerts. |

### Python scrapers (tested clients with sample output)

| Repository | What it scrapes |
|---|---|
| [naukri-jobs-scraper](https://github.com/datadmon/naukri-jobs-scraper) | Naukri.com jobs with salary in LPA, skills, applicants and full description |
| [iimjobs-jobs-scraper](https://github.com/datadmon/iimjobs-jobs-scraper) | IIMJobs MBA, finance and management jobs |
| [welcome-to-the-jungle-jobs-scraper](https://github.com/datadmon/welcome-to-the-jungle-jobs-scraper) | Welcome to the Jungle (WTTJ) jobs, France and abroad |
| [gupy-jobs-scraper](https://github.com/datadmon/gupy-jobs-scraper) | Gupy vagas (Brazil): CLT, estágio, PJ, remoto, PcD |
| [onlinejobs-ph-scraper](https://github.com/datadmon/onlinejobs-ph-scraper) | OnlineJobs.ph virtual-assistant jobs with parsed wages |

### Data APIs

| Source | Apify Actor |
|---|---|
| IIMJobs (MBA, finance, consulting, management jobs) | [iimjobs-jobs-scraper](https://apify.com/data_daemon/iimjobs-jobs-scraper) |
| Hirist.tech (India tech jobs) | [hirist-jobs-scraper](https://apify.com/data_daemon/hirist-jobs-scraper) |
| Foundit (formerly Monster India) | [foundit-jobs-scraper](https://apify.com/data_daemon/foundit-jobs-scraper) |
| Instahyre (startup and product-company jobs) | [instahyre-jobs-scraper](https://apify.com/data_daemon/instahyre-jobs-scraper) |
| Welcome to the Jungle (France-focused jobs) | [welcome-to-the-jungle-jobs-scraper](https://apify.com/data_daemon/welcome-to-the-jungle-jobs-scraper) |
| Oracle Recruiting Cloud / Oracle HCM career sites | [oracle-hcm-jobs-scraper](https://apify.com/data_daemon/oracle-hcm-jobs-scraper) |
| India IPO GMP, subscription, calendar | [india-ipo-tracker](https://apify.com/data_daemon/india-ipo-tracker) |
| NSE/BSE fundamentals (Tickertape) | [tickertape-stocks-scraper](https://apify.com/data_daemon/tickertape-stocks-scraper) |
| Dubai Land Department transactions | [dubai-property-transactions](https://apify.com/data_daemon/dubai-property-transactions) |
| UK Gazette insolvency notices | [uk-gazette-insolvency-notices](https://apify.com/data_daemon/uk-gazette-insolvency-notices) |
| Luma events | [luma-events-scraper](https://apify.com/data_daemon/luma-events-scraper) |

Code examples in Python, Node.js, curl and n8n for all of them: [apify-data-actors-examples](https://github.com/datadmon/apify-data-actors-examples). Each Actor is also an MCP tool for AI assistants through Apify's MCP server.
