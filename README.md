## Daemon Data

Pay-per-result data APIs on [Apify](https://apify.com/data_daemon) for public sources that are hard to use directly: **Dubai Land Department registers**, **job boards** (India, Brazil, the Philippines, Latin America, company career sites), **Indian IPOs and stocks**, **property listings** and **public records**. Every Actor is also an MCP tool for AI assistants.

Website: [datadmon.github.io](https://datadmon.github.io/) · Data studies: [dev.to/datadaemon](https://dev.to/datadaemon) · Code examples: [apify-data-actors-examples](https://github.com/datadmon/apify-data-actors-examples)

### Ready-to-fork templates (GitHub Actions)

| Template | What it does |
|---|---|
| [india-job-alerts](https://github.com/datadmon/india-job-alerts) | New jobs from Indian job boards every morning, to a GitHub issue, Slack, Telegram, Discord or CSV. |
| [uk-insolvency-monitor](https://github.com/datadmon/uk-insolvency-monitor) | Alert when a customer or supplier appears in The Gazette with a winding-up petition, order or administration (matched by Companies House number). |
| [india-ipo-gmp-tracker](https://github.com/datadmon/india-ipo-gmp-tracker) | Today's IPO GMP, estimated listing price and subscription for mainboard and SME IPOs, with a daily GMP history and Telegram alerts. |

### Python scrapers (tested clients with sample output)

| Repository | What it scrapes |
|---|---|
| [naukri-jobs-scraper](https://github.com/datadmon/naukri-jobs-scraper) | Naukri.com jobs with salary in LPA, skills, applicants and full description |
| [iimjobs-jobs-scraper](https://github.com/datadmon/iimjobs-jobs-scraper) | IIMJobs MBA, finance and management jobs |
| [career-site-jobs-scraper](https://github.com/datadmon/career-site-jobs-scraper) | Workday, Greenhouse, Lever, Ashby and SmartRecruiters career-site jobs, or 10,000+ company boards at once |
| [gupy-jobs-scraper](https://github.com/datadmon/gupy-jobs-scraper) | Gupy vagas (Brazil): CLT, estágio, PJ, remoto, PcD |
| [onlinejobs-ph-scraper](https://github.com/datadmon/onlinejobs-ph-scraper) | OnlineJobs.ph virtual-assistant jobs with parsed wages |
| [welcome-to-the-jungle-jobs-scraper](https://github.com/datadmon/welcome-to-the-jungle-jobs-scraper) | Welcome to the Jungle (WTTJ) jobs, France and abroad |

### Data APIs on Apify

**Dubai real estate (Dubai Land Department open data)**

| Data | Actor |
|---|---|
| Property sales, mortgages and gifts with price per sqm | [dubai-property-transactions](https://apify.com/data_daemon/dubai-property-transactions) |
| Ejari registered rent contracts (signed leases, not asking rents) | [dubai-rent-contracts](https://apify.com/data_daemon/dubai-rent-contracts) |
| Real estate projects register (off-plan, escrow, developers) | [dubai-real-estate-projects](https://apify.com/data_daemon/dubai-real-estate-projects) |

**India jobs**

| Source | Actor |
|---|---|
| Naukri.com | [naukri-jobs-scraper](https://apify.com/data_daemon/naukri-jobs-scraper) |
| IIMJobs (MBA, finance, consulting, management) | [iimjobs-jobs-scraper](https://apify.com/data_daemon/iimjobs-jobs-scraper) |
| Hirist.tech (tech jobs) | [hirist-jobs-scraper](https://apify.com/data_daemon/hirist-jobs-scraper) |
| Foundit (formerly Monster India) | [foundit-jobs-scraper](https://apify.com/data_daemon/foundit-jobs-scraper) |
| Instahyre | [instahyre-jobs-scraper](https://apify.com/data_daemon/instahyre-jobs-scraper) |
| Cutshort (startup and tech jobs) | [cutshort-jobs-scraper](https://apify.com/data_daemon/cutshort-jobs-scraper) |
| Shine.com | [shine-jobs-scraper](https://apify.com/data_daemon/shine-jobs-scraper) |
| Apna | [apna-jobs-scraper](https://apify.com/data_daemon/apna-jobs-scraper) |
| WorkIndia | [workindia-jobs-scraper](https://apify.com/data_daemon/workindia-jobs-scraper) |
| Unstop (jobs, internships, hackathons, competitions) | [unstop-scraper](https://apify.com/data_daemon/unstop-scraper) |
| All ten boards in one search, deduplicated | [india-jobs-feed](https://apify.com/data_daemon/india-jobs-feed) |
| The same boards as an MCP server for AI assistants | [india-jobs-mcp](https://apify.com/data_daemon/india-jobs-mcp) |

**Jobs elsewhere**

| Source | Actor |
|---|---|
| Company career sites: Workday, Greenhouse, Lever, Ashby, SmartRecruiters | [career-site-jobs-scraper](https://apify.com/data_daemon/career-site-jobs-scraper) |
| Oracle Recruiting Cloud / Oracle HCM career sites | [oracle-hcm-jobs-scraper](https://apify.com/data_daemon/oracle-hcm-jobs-scraper) |
| Gupy (Brazil) | [gupy-jobs-scraper](https://apify.com/data_daemon/gupy-jobs-scraper) |
| OnlineJobs.ph (Philippines, remote and VA jobs) | [onlinejobs-ph-scraper](https://apify.com/data_daemon/onlinejobs-ph-scraper) |
| Get on Board (Latin America tech jobs) | [getonbrd-jobs-scraper](https://apify.com/data_daemon/getonbrd-jobs-scraper) |
| Welcome to the Jungle (France-focused) | [welcome-to-the-jungle-jobs-scraper](https://apify.com/data_daemon/welcome-to-the-jungle-jobs-scraper) |

**Markets, property and public records**

| Data | Actor |
|---|---|
| India IPO GMP, subscription and calendar | [india-ipo-tracker](https://apify.com/data_daemon/india-ipo-tracker) |
| NSE/BSE stock fundamentals (Tickertape) | [tickertape-stocks-scraper](https://apify.com/data_daemon/tickertape-stocks-scraper) |
| India new company registrations (daily MCA incorporations) | [india-new-company-registrations](https://apify.com/data_daemon/india-new-company-registrations) |
| UK Gazette insolvency notices | [uk-gazette-insolvency-notices](https://apify.com/data_daemon/uk-gazette-insolvency-notices) |
| US import records and bills of lading (ImportYeti) | [importyeti-scraper](https://apify.com/data_daemon/importyeti-scraper) |
| Magicbricks property listings (India) | [magicbricks-property-scraper](https://apify.com/data_daemon/magicbricks-property-scraper) |
| Zap Imóveis and VivaReal property listings (Brazil) | [zap-imoveis-vivareal-scraper](https://apify.com/data_daemon/zap-imoveis-vivareal-scraper) |
| Luma events | [luma-events-scraper](https://apify.com/data_daemon/luma-events-scraper) |

Code examples in Python, Node.js, curl and n8n: [apify-data-actors-examples](https://github.com/datadmon/apify-data-actors-examples). Questions or a missing field: open an issue on the Actor's Issues tab on Apify.
