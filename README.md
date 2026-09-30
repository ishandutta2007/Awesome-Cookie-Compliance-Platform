# Awesome-Cookie-Compliance-Platform

## Top Cookie Compliance Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cookie Consent, GDPR/CCPA Compliance, Google Consent Mode & Privacy Compliance*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cookie Compliance**. These tools help websites collect, manage, and document user consent for cookies and tracking technologies in compliance with GDPR, CCPA/CPRA, ePrivacy, and other privacy regulations.



**Examples** include Cookiebot, CookieYes, Usercentrics, OneTrust, TrustArc, Termly, Complianz, Didomi, Consentmanager, and Osano (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom consent workflows, and transparent privacy compliance — ideal for organizations that need full control over consent data without per-pageview SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cookiebot](https://www.cookiebot.com/)**

  Popular CMP known for automated cookie scanning and user-friendly banner. Provides GDPR, CCPA, and Google Consent Mode compliance with a free tier for small websites. Currently used by 138,234 origins with 57% mobile performance score .



- **[CookieYes](https://www.cookieyes.com/)**

  Affordable CMP with automated cookie scanning and banner customization. Provides GDPR, CCPA, and Google Consent Mode compliance. The most widely deployed CMP in the HTTP Archive dataset with 222,809 origins, 46% mobile performance, and 92% best practices score .



- **[Usercentrics](https://usercentrics.com/)**

  German CMP platform with strong European market presence. Provides consent management, preference centers, and compliance across multiple regulations. Used by 43,324 origins with 61% mobile performance score .



- **[OneTrust](https://www.onetrust.com/)**

  The dominant enterprise CMP and privacy management platform. **Fall 2026 release** introduces a redesigned CMP experience with website-centric workflows, unified management of websites/publishing/tracking technologies, and bulk script publishing . New permissions include bulk exports for CMP receipts and download permissions for export files .



- **[TrustArc](https://trustarc.com/)**

  Privacy compliance platform with CMP, assessments, and certification services. **Q2 2026 updates** include Unified Consent across domains/brands for CCPA compliance, **Global Privacy Control (GPC) recognition enabled by default**, flexible manual/scheduled scanning, and smarter DSR form administration with activity logging .



- **[Termly](https://termly.io/)**

  CMP and legal compliance platform. Provides cookie consent, privacy policy generation, and terms of service tools. Users praise the friendly UI for creating and managing policies, though customization options are considered limited .



- **[Complianz](https://complianz.io/)**

  WordPress-focused cookie banner plugin with **1 million+ active users** and 4.8/5 WordPress rating . Features plug-and-play setup, automated scans, consent management with automatic third-party script blocking, and coverage for GDPR, CCPA, LGPD, and more. **Google CMP certified**, **IAB TCF v2.3 validated** (CMP ID 332) .



- **[Didomi](https://www.didomi.io/)**

  French CMP and consent management platform. Provides cookie consent, preference management, and compliance tools. **Performance focus**: new performance flag delivered 60-70% improvement in average INP scores for CMP-related actions (developed with Google) . Supports cross-device consent sharing and server-side tracking .



- **[Consentmanager](https://www.consentmanager.net/)**

  German CMP provider with cookie consent and compliance tools. **Features**: 3M+ cookies categorized, 2,500+ vendors recognized, **ML-powered A/B testing** (15%+ higher acceptance rates on average), automatic cookie blocking, and **Compatibility Mode** for switching without rebuilding tag manager setup . **Google-certified CMP Partner**, **IAB TCF v2.3 validated**, **EU-only data storage** .



- **[Osano](https://www.osano.com/)**

  Privacy platform with CMP, data mapping, and consent management. Focuses on simplifying privacy compliance for businesses. **Fender case study**: replaced manual processes and spreadsheets with centralized platform, enabling privacy-by-design guardrails and proactive legal partnership .



## Open-Source GitHub Projects



- **[ConsentOS](https://github.com/consentos/consentos)**

  **The most complete source-available consent management platform, positioned as a self-hosted alternative to OneTrust, Cookiebot, and CookieYes.** **Elastic Licence 2.0** (source-available, self-host indefinitely). **Key features**: Single `<script>` tag embed; **auto-blocking** (intercepts script creation, cookie writes, and storage API calls until consent); **Playwright-driven cookie scanner** with auto-categorization against Open Cookie Database (2,200+ patterns); **dark pattern detection** (pre-ticked boxes, missing reject buttons, button asymmetry, scroll-based dismissal); compliance engine for **GDPR, CNIL, CCPA/CPRA, ePrivacy, and LGPD** with severity scoring; **tamper-evident consent record audit trail**. **Standards-complete**: IAB TCF v2.3, GPP v1 (six US state sections), Google Consent Mode v2, GPC, Shopify Customer Privacy API . **Multi-tenant from day one** with configuration cascade (System → Org → Site Group → Site → Region). Banner is ~2KB loader + ~26KB bundle gzipped, rendered in Shadow DOM for style isolation . Docker Compose deployment with PostgreSQL 17 .



- **[Klaro](https://github.com/kirotus/klaro)**

  **The most established open-source consent manager.** **1,210 GitHub stars, 256 forks**, JavaScript-based . **Open-source version is completely free** for personal and commercial use, with all client-side features of the commercial editions . **Key features**: Automatic UI display in website languages with GUI text customization; growing third-party database with technical and legal details; unlimited configurations for subpages, landing pages, subdomains, testing; **complete traceability of all configuration changes for audit logs**; **full REST API** for programmatic and automated use; **anonymous real-time statistics** on consent types, views, browser properties, and acceptance rates; **open-source client libraries and UIs** that you can freely use, adapt, and host; **unlimited and complete export** of all data and configuration settings . **Unique positioning**: "the only consent management platform that uses a completely free open-source code base in the frontend" .



- **[Orejime](https://github.com/boscop-fr/orejime)**

  **Easy-to-use consent manager focusing on accessibility.** **189 GitHub stars, 37 forks** . Open-source, designed to be simple to use and accessible. Suitable for organizations prioritizing accessibility in their consent workflows.



- **[Haven](https://github.com/chiiya/haven)**

  **Fully-featured, GDPR-ready cookie consent manager.** **77 GitHub stars, 4 forks**, TypeScript-based . Open-source, designed for GDPR compliance.



### Additional Strong Open-Source Options



- **Full Platforms**: **ConsentOS** (source-available, multi-tenant, comprehensive compliance engine) .

- **Lightweight Banners**: **Klaro** (1,210 stars, free, REST API, audit logs) , **Orejime** (189 stars, accessibility-focused) , **Haven** (77 stars, GDPR-ready) .

- **CMS Integrations**: **TYPO3 dp_cookieconsent** (TYPO3 extension, 33 stars) , **Grav ePrivacy Plugin** (Grav CMS) , **October CMS GDPR Plugin** (36 stars) .

- **Libraries**: **cookies-consent-js** (TypeScript library for GDPR/ePrivacy) , **cookiesconsentjs** (JavaScript library) .



**Frameworks for building custom systems**: Combine **ConsentOS** for a complete self-hosted CMP with auto-blocking and compliance auditing, **Klaro** for lightweight client-side consent management with REST API, and **Orejime** for accessibility-focused consent flows. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cookie compliance platforms handle sensitive consent data; ensure compliance with GDPR, CCPA/CPRA, ePrivacy, and relevant regional privacy regulations.

- **Open-source reality**: The open-source ecosystem for cookie compliance is **mature and production-ready**. **ConsentOS** provides a comprehensive source-available CMP with auto-blocking, cookie scanning, dark pattern detection, and multi-tenant support . **Klaro** is the most established open-source consent manager with 1,210 stars, free client-side functionality, REST API, and audit logs . **Orejime** and **Haven** provide accessibility-focused and GDPR-ready alternatives . However, **commercial platforms** (Cookiebot, CookieYes, Usercentrics, OneTrust, TrustArc) provide **managed cookie databases, automated scanner updates, enterprise integrations, and dedicated support** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with engineering capacity seeking full data sovereignty and zero license fees.



---



**Made for privacy engineers, web developers, compliance officers, and legal teams.**

Let's make cookie compliance more open, transparent, and privacy-respecting.
