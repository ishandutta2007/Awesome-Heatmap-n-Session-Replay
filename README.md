# Awesome-Heatmap-n-Session-Replay

## Top Heatmap & Session Replay Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on User Behavior Visualization, Click/Scroll Heatmaps, Session Recordings, Frustration Detection & Product Experience Insights*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Heatmaps and Session Replay**. These tools capture how users interact with websites and applications, replaying sessions and generating heatmaps to reveal friction, usability issues, and opportunities for improvement.



**Examples** include Hotjar, Microsoft Clarity, FullStory, Smartlook, Lucky Orange, Crazy Egg, Mouseflow, Contentsquare, Inspectlet, and Glassbox (the category leaders).



**Open-source emphasis**: Session replay and heatmap capabilities are well-supported in the open-source world. Mature projects such as **PostHog**, **OpenReplay**, and the foundational **rrweb** library provide powerful self-hosted alternatives with full data ownership. This section is heavily expanded with every major active project.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Hotjar (Contentsquare)](https://www.hotjar.com/)** | Popular behavior analytics platform offering heatmaps, session recordings, surveys, and feedback tools; now part of the broader Contentsquare ecosystem. | Starts at **$39/mo** (Growth plan, billed annually) / **$49/mo** (monthly) | **Free forever plan**: up to 200,000 monthly sessions, 1 project, heatmaps, and basic surveys (up to 100 responses/mo) |
| **[Microsoft Clarity](https://clarity.microsoft.com/)** | Free heatmap and session recording tool from Microsoft with unlimited sessions, rage-click detection, and strong privacy-focused design. | **$0 / Free** (100% free tool, no paid tiers) | **Free forever plan**: unlimited sessions, unlimited heatmaps, unlimited domains, 90-day recording retention |
| **[FullStory](https://www.fullstory.com/)** | Enterprise digital experience analytics platform with high-fidelity session replay, powerful search, and AI-assisted insights. | Starts at **~$10,000/yr** (~$833/mo) for Business tier / annual contract quote | **Free forever plan (FullstoryFree)**: 30,000 sessions/month, 10 seats, 1-year data retention *(or 14-day free trial on premium features)* |
| **[Smartlook](https://www.smartlook.com/)** | Session recording and heatmap solution supporting both web and mobile apps, with event tracking and funnel analysis. | Starts at **$55/mo** (Business tier, billed monthly) | **Free forever plan**: up to 3,000 sessions/month, 10 heatmaps, 10 events, 2 funnels, 1-month data history |
| **[Lucky Orange](https://www.luckyorange.com/)** | All-in-one visitor insight platform combining heatmaps, session recordings, live chat, and form analytics, popular with SMBs and ecommerce. | Starts at **$32/mo** (Build plan, billed annually) / **$39/mo** (monthly) | **Free forever plan**: 100 sessions/month, heatmaps, and surveys *(plus 7-day free trial on higher tiers)* |
| **[Crazy Egg](https://www.crazyegg.com/)** | Classic heatmap tool offering click, scroll, and confetti maps along with simple A/B testing capabilities. | Starts at **$29/mo** (Starter plan, billed annually at $348/yr) | **30-day free trial** on Starter plan: 5,000 tracked pageviews/mo, 5 heatmap reports, 50 session recordings/mo *(plus separate Free Web Analytics tier)* |
| **[Mouseflow](https://mouseflow.com/)** | Session replay and heatmap platform known for form analytics, friction scoring, and multiple heatmap types. | Starts at **$25/mo** (Essential plan, billed annually) / **$31/mo** (monthly) | **Free forever plan**: 500 recordings/sessions per month, 1 website, all heatmap types |
| **[Contentsquare](https://contentsquare.com/)** | Enterprise experience analytics platform with advanced zone-based heatmaps, journey analysis, and deep behavioral insights. | Starts at **$39/mo** (Growth plan, billed annually) / **$49/mo** (monthly) | **Free forever plan**: up to 200,000 monthly sessions, 1 project, basic heatmaps and funnels *(plus 15-day free trial for Growth tier)* |
| **[Inspectlet](https://www.inspectlet.com/)** | Session recording and heatmap tool focused on visualizing user interactions and identifying usability issues. | Starts at **$39/mo** (Micro plan, 10,000 recorded sessions/mo) | **Free forever plan**: 2,500 recorded sessions/month, 3 websites, 1-month data retention |
| **[Glassbox](https://www.glassbox.com/)** | Enterprise digital experience and session replay platform often used in regulated industries, with strong struggle detection and analytics. | Starts at **$50,000/yr** (~$4,167/mo AWS Marketplace / annual enterprise contract for up to 50K sessions/mo) | **30-day free trial**: evaluation tier with full struggle detection, heatmap, and session replay access |



## Open-Source GitHub Projects



- **[PostHog](https://github.com/PostHog/posthog)**  

  Leading open-source product analytics platform that includes session replay, heatmaps, feature flags, experiments, and more. Fully self-hostable with a generous free cloud tier; MIT-licensed core.



- **[OpenReplay](https://github.com/openreplay/openreplay)**  

  Dedicated open-source session replay suite you can self-host. Captures user interactions plus network activity, console logs, errors, and performance metrics for debugging and product improvement.



- **[rrweb](https://github.com/rrweb-io/rrweb)**  

  Foundational open-source library for recording and replaying web sessions. Used as the capture engine by many analytics and replay products (including PostHog and others).



- **[rrHog and related stacks](https://github.com/rrHog/rrHog)**  

  Open-source, self-hosted web analytics and session replay solutions built on rrweb, often paired with high-performance storage such as ClickHouse.



- **[Highlight](https://github.com/highlight/highlight)**  

  Open-source platform combining session replay with error monitoring, giving developers sessions and stack traces in one place.



- **[Other rrweb-based projects](https://github.com/search?q=rrweb+session+replay)**  

  Community tools and platforms that leverage rrweb for custom session recording, support tooling, or internal analytics.



### Additional Strong Open-Source Options



- **Self-hosted analytics suites**: Platforms that bundle session replay with product analytics, feature flags, and event tracking.

- **Privacy & masking tooling**: Libraries and configurations for sanitizing sensitive data (PII, form fields, etc.) before storage.

- **Developer-focused replay**: Tools optimized for reproducing bugs with console, network, and state capture.

- **Heatmap generation libraries**: Open-source components for rendering click, scroll, and attention heatmaps from recorded data.

- **Mobile session capture**: Emerging open-source approaches for recording mobile app sessions (where available).

- Integration examples with error trackers (Sentry, etc.) and observability stacks.



**Frameworks for building custom systems**:  

For most teams, start with **PostHog** (analytics + replay + flags in one platform) or **OpenReplay** (replay-first with strong developer tooling).  

Both can be self-hosted for complete data control.  

For embedding replay inside your own product or support tooling, use the **rrweb** library directly.  

Add privacy controls, retention policies, and access governance appropriate to your compliance needs.  

This stack can fully replace many commercial heatmap and session-replay tools while keeping user data under your control.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Session replay and heatmap tools capture detailed user behavior and can include sensitive information. Proper consent, privacy notices, data masking, retention policies, and compliance with regulations (GDPR, CCPA, etc.) are essential.

- Self-hosted open-source solutions require secure infrastructure, access controls, and ongoing maintenance. Teams remain responsible for the lawful and ethical use of recorded data.



---



**Made for product managers, UX researchers, growth teams, and engineers who want to understand real user behavior.**  

Let's make insightful, privacy-respecting session analysis accessible through powerful open-source tools.
