# Hey, I'm Justin

Full-stack developer in New Hampshire building software for the fuel and energy industry. I specialize in connecting legacy industrial systems to modern cloud infrastructure — the kind of work where you're reading protocol specs from 2003 and deploying to AWS in the same afternoon.

## What I Build

### Fuel Operations Platform

My main project is a comprehensive backoffice platform for a propane fuel company — pricing intelligence, delivery forecasting, route optimization, and real-time tank monitoring all in one system. It handles the full operational lifecycle:

- **Propane pricing engine** — Cost modeling, margin analysis, competitor tracking, what-if scenarios, and automated price review queues
- **Delivery forecasting** — K-factor projections, degree-day trends, usage analysis, and smart delivery scheduling
- **Tank monitoring** — Real-time liquid level data from field sensors via SFTP and Dropbox integrations
- **Route optimization** — Delivery route planning using AWS Location and Google Maps APIs
- **Customer intelligence** — Prospect estimation, quote generation, and customer profitability analysis

Built with Node.js, Express, MS SQL Server, and deployed on AWS EC2. Modular architecture with 18 feature modules and 10+ internal service libraries.

### Industrial IoT

OPW/Dover fuel management controllers (FSC3000, SiteSentinel, Petro Vend) have embedded email alerting — but their Windows CE SMTP client can't speak TLS. I built a relay that bridges these devices to AWS SES, handling all the protocol quirks along the way.

### Financial Data Tools

Parsers and integrations for market data — S&P 500 company listings, Intrinio financial APIs, and Google Finance data. Building tools to make financial analysis more accessible.

### OpenYard

E-commerce marketplace platform built on Symfony/PHP.

## Open Source Projects

| Project | What it does |
|---|---|
| [opw-mail-relay](https://github.com/justinpfister/opw-mail-relay) | SMTP relay bridging OPW fuel site controllers to AWS SES — solves the "no TLS on Windows CE" problem |
| [fitness-apps-unite](https://github.com/justinpfister/fitness-apps-unite) | Unifies Peloton, Strava, and Garmin activity data into a single view |
| [sp500-companies-data](https://github.com/justinpfister/sp500-companies-data) | S&P 500 company data parser with current listings and financials |

## Tech

Node.js, TypeScript, Express, MS SQL Server, PHP, Python, AWS (EC2, SES, SSM, Location), Nginx, PM2, Google OAuth, Linux

## Find Me

[LinkedIn](https://www.linkedin.com/in/justinpfister)
