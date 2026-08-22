---
layout: post
permalink: /my-career-at-fortnine/
title:  "My career at FortNine"
categories: [technology, software, development]
tags: [fortnine, career, history]
comments: true
---

July 21, 2014, was my first day at [Canada’s Motorcycle](https://canadasmotorcycle.ca), the company that would later become [FortNine](https://fortnine.ca). That morning, [Amin](https://www.linkedin.com/in/aminmarcsawaf/), its founder and CEO, handed me a USB drive. It contained a ZIP archive of the codebase that powered the storefront side of the business. Various third-party contractors had worked on it over the preceding few years, and the result was a single large monolith with no meaningful separation between the underlying platform, custom functionality, and theme. It also performed terribly.

**That USB drive told me almost everything I needed to know about the work ahead.**

The codebase needed to be brought under proper Git version control, divided into maintainable modules and themes, supported by reproducible development environments, and deployed through automated processes rather than passed between people as a collection of files. The challenge was not simply to clean up the code. The company needed an internal software development capability, an engineering culture, a modern architecture, and a technology platform capable of growing with the business. Building those foundations became my responsibility.

That first handoff marked the beginning of a twelve-year progression in confidence, trust, and ownership. I joined as a Senior Full-Stack Web Developer, initially responsible for taking control of the codebase and establishing the Web Development department. In January 2017, I was promoted to Director of Technology and entrusted with the entire Technology platform. My responsibilities expanded to include software development, architecture, infrastructure, cybersecurity, internal systems, warehouse technology, data, and technical personnel. In January 2024, I became Vice President of Technology, with enterprise-wide accountability across FortNine and its growing group of commerce properties.

Each transition represented more than a change in title. It reflected the confidence Amin and the company placed in me to take responsibility for increasingly consequential parts of the business and exercise independent judgment. I was trusted to build the teams and systems required for each new stage of growth while remaining accountable for the results. Throughout that progression, I remained directly involved in architecture, system design, engineering practices, production operations, technical risk, and the development of the people around me.

Most career summaries are exercises in compression. A resume or [LinkedIn profile](https://www.linkedin.com/in/danemacmillan/) reduces years of work to a handful of titles, responsibilities, and outcomes, but too much of the story disappears in that format. This post is intentionally long. It is a chronological record of the significant systems I built, transformations I led, responsibilities I assumed, problems I helped solve, and organizational changes I helped bring about between July 2014 and May 2026.

None of this is intended to suggest that these outcomes were mine alone. FortNine’s growth was the work of many people across the company, including the developers and technical leaders I worked alongside and had the opportunity to lead. This is my attempt to document the part I played in that growth with enough detail to preserve the scope, progression, and continuity of the work rather than reducing nearly twelve years to another highlight reel.

<br/>

![FortNine logo]({{site.url}}/assets/img/fortnine-logo-red-2299w512h.png)

<br/>

---

<br/>



## Senior Full-Stack Web Developer

**July 2014–December 2016**

Joined FortNine as its senior technical builder and established the Web Development department from the ground up. Worked hands-on across frontend development, backend systems, databases, integrations, infrastructure, security, performance, deployment, and production operations.

### 2014 — Building the development foundation

- Built and led the Web Development function from scratch.
- Established the initial software architecture, engineering standards, development tooling, deployment practices, and technical direction required to support the company’s growth.
- Assumed hands-on responsibility for the performance, reliability, security, and maintainability of the customer-facing commerce platform.
- Began developing the technical and engineering culture that would later expand into formal coding standards, automated testing, DevOps, documentation, architectural review, and developer mentorship.
- Helped establish a model in which developers retained direct ownership of systems from implementation through production operation.
- Received the first company-issued MacBook, beginning a broader transition toward Apple hardware that eventually expanded across most of the office.

### 2015 — Security, performance, localization, and conversion

- Implemented full-site HTTPS across the commerce experience, rather than limiting encryption to account and checkout pages.
- Strengthened customer trust, search-engine readiness, and the company’s long-term security posture through early full-site encryption.
- Designed and implemented storefront caching strategies that eliminated frequent timeouts and reduced page loads from approximately 10–30 seconds to sub-second response times.
- Established performance engineering as an ongoing platform discipline rather than a one-time optimization project.
- Built the company’s French-localization capabilities.
- Expanded the platform through Moreyat to support four locales and multiple currencies.
- Began the redesign of the shopping cart and checkout experience.
- Improved frontend and backend architecture to support increasing traffic, catalog complexity, and transaction volume.
- Contributed to the early conversion improvements that would continue throughout the remainder of the tenure.

### 2016 — Mobile commerce, checkout, and FortNine rebrand

- Designed the UI/UX of the cart and checkout, then built it. Every customer dollar into FortNine goes through this experience, and that continues to this day. Internal codename: "MoneyMaker." 
- Simplified customer flows and significantly improved usability and conversion.
- Designed and built a dedicated mobile-first commerce experience. To this day it is the experience all customers receive.
- Improved mobile usability and conversion at a time when many competitors still treated mobile commerce as secondary.
- Led the technical execution of the rebrand from CanadasMotorcycle.ca to FortNine.ca.
- Coordinated the application, infrastructure, analytics, domain, redirect, and search-engine aspects of the rebrand.
- Completed the FortNine rebrand without a loss of SEO performance.
- Continued evolving the platform’s multilingual, multicurrency, mobile, performance, security, and commerce foundations.
- Established the technical credibility and organizational trust that led to promotion into complete Technology ownership in January 2017.

<br/>

---

<br/>

## Director of Technology

**January 2017–December 2023**

Promoted to Director of Technology in January 2017 and assumed responsibility for the complete Technology platform. Continued to work hands-on in software architecture, system design, development practices, infrastructure, security, and critical technical delivery while expanding into organizational leadership, enterprise risk, investor diligence, M&A, and post-acquisition integration.

### 2017 — Full Technology ownership and initial cloud transformation

- Assumed responsibility for Software Development, systems architecture, cloud infrastructure, cybersecurity, internal systems, warehouse technology, data integrity, and technical personnel.
- Continued reporting directly to the Founder/CEO.
- Architected and led the company’s initial migration to Google Cloud Platform.
- Established a scalable cloud foundation capable of supporting continued traffic, catalog, transaction, and organizational growth.
- Improved infrastructure elasticity, isolation, deployment capability, observability, and operational resilience.
- Began the full System API transformation.
- Started consolidating business logic that had previously been distributed across legacy applications and systems.
- Established the basis of an API-first architecture that could support storefronts, internal systems, warehouse operations, and future commerce properties.
- Began assuming broader responsibility for technical roadmapping, sequencing, risk identification, and long-term platform investment.
- Continued remaining directly involved in architectural design, implementation reviews, production troubleshooting, and developer mentorship.

### 2018 — API architecture, automation, data, security, and modernization

- Completed the 2017–2018 System API transformation.
- Centralized shared business logic and reduced duplication across applications.
- Improved consistency, reuse, maintainability, and the ability to introduce new systems and properties.
- Led a major database-refactoring initiative.
- Centralized transactional business logic and removed important performance bottlenecks.
- Began the long-running transition from legacy Windows systems to Linux, cloud-hosted infrastructure, APIs, command-line automation, and more modern deployment practices.
- Migrated from GCP Cloud Armor to Cloudflare WAF for richer security tooling and improved operational responsiveness.
- Strengthened DDoS protection and application-layer security.
- Built and launched the proprietary Scrape Task framework for intelligent, high-volume, near-real-time data processing.
- Built and launched the proprietary Transport Task framework to address data-processing reliability and operational issues.
- Migrated the Warehouse API to Google Cloud Platform.
- Expanded infrastructure monitoring, security review, access control, and production observability.
- Continued formalizing engineering standards, code quality, automated testing, DevOps, documentation, and reusable developer tooling.

### 2019 — Magento 2 and zero-downtime infrastructure transformation

- Completed and launched a 26-month Magento 2 replatforming program.
- Directed the architecture, application, integration, data, deployment, testing, and operational work required to replace the company’s core commerce platform.
- Delivered the Magento 2 launch without interrupting the business.
- Achieved major improvements in stability, scalability, maintainability, and platform capability.
- Led the migration of production infrastructure and data-centre operations to Canadian infrastructure.
- Completed the Canadian infrastructure cutover with zero downtime.
- Replaced legacy Windows synchronization services with Linux-based command-line automation.
- Reduced operational fragility and eliminated important sources of synchronization and downtime risk.
- Continued modernizing deployment processes so that complex production changes could be released frequently and rolled back rapidly when required.

### 2020 — Operational systems, data isolation, and investor diligence

- Built and launched the Order Portal.
- Expanded bespoke operational tooling supporting ordering, fulfilment, customer service, and internal business workflows.
- Moved Business Intelligence workloads toward BigQuery.
- Isolated analytical queries from customer-facing transactional databases.
- Prevented reporting and BI activity from degrading production commerce performance.
- Led FortNine’s Technology and Cybersecurity participation in Novacap’s pre-investment due diligence.
- Presented the company’s architecture, infrastructure, systems, security posture, engineering practices, technical risks, and future requirements.
- Was identified by Novacap as a key person in FortNine’s success.
- Received external recognition from Novacap’s technology leadership for FortNine’s strong security posture.
- Helped demonstrate that the Technology organization and platform were capable of supporting the company’s next stage of growth.

### 2021 — Board exposure, payments, and Defender diligence

- Advocated for and launched Apple Pay.
- Expanded payment options and reduced friction in the transaction experience.
- Began participating as a guest contributor at every quarterly FortNine board meeting with Novacap.
- Presented the state of the technology platform, strategic priorities, upcoming initiatives, progress, operational risks, cybersecurity concerns, and investment requirements.
- Participated in board-level discussions concerning M&A opportunities and the technical implications of acquisitions.
- Led the Technology and Cybersecurity due-diligence workstream for FortNine’s acquisition of Defender US.
- Directed a broad, multi-stakeholder technical interview and evaluation process.
- Assessed Defender’s storefront, applications, infrastructure, integrations, security, internal systems, personnel dependencies, and operational risks.
- Identified technical and cybersecurity issues that informed valuation and transaction terms.
- Developed the initial technical integration and risk-remediation strategy.
- Assumed technical leadership responsibility for Defender following the acquisition at the end of 2021.

### 2022 — Complete Defender US replatforming

- Owned the full post-acquisition technology integration of Defender US.
- Directed the complete replatforming of Defender’s business onto FortNine’s technology estate.
- Replaced Defender’s existing storefront, infrastructure, integrations, internal systems, and technical operating model with FortNine’s shared systems and architecture.
- Consolidated the acquired business onto the existing FortNine platform rather than maintaining a separate and duplicative technology stack.
- Extended technical leadership, architecture, security, release practices, and operational standards across Defender.
- Coordinated the technical, operational, organizational, and stakeholder changes required to prepare for the production transition.
- Developed cutover plans, validation procedures, rollback options, contingency planning, operational-readiness checks, and post-launch stabilization processes.
- Gained significant change-management experience across a business-critical acquisition integration.
- Converted that experience into a repeatable approach for later major releases and platform transformations.
- Created substantial operating leverage by allowing the acquired business to function on FortNine’s existing technology foundation.

### January 2023 — Defender US production cutover

- Shut down Defender US’s legacy platform.
- Completed the production cutover to FortNine’s storefront, infrastructure, and internal systems in January 2023.
- Absorbed Defender’s traffic, sales, transaction volume, and technical operations onto FortNine’s platform.
- Completed the transition without downtime.
- Maintained customer and business continuity throughout the cutover.
- Stabilized the acquired business on the common platform following launch.
- Established Defender as another FortNine-operated technology property rather than a separately maintained technical organization.
- Applied the lessons from the Defender transition to later change-management, release-readiness, communication, and risk-management practices.

### Late 2023 — Business context for OEM expansion

- FortNine’s acquisition of Moto Illimitées provided the dealership access required to sell a broader range of OEM parts in Canada.
- The acquisition itself was not a major area of personal involvement.
- The resulting catalog and dealership capabilities created the business context for the OEM Portal work launched under the VP role in 2024.

<br/>

---

<br/>

## Vice President of Technology

**January 2024–May 2026**

Promoted to Vice President of Technology in January 2024 with enterprise-wide accountability for Technology across FortNine and Defender. Led Software Development, Architecture, Cloud Infrastructure, Cybersecurity, IT, Warehouse Technology, internal systems, data integrity, storefront performance, platform reliability, and technical personnel while remaining directly engaged in system design, engineering standards, mentorship, and major technical decisions.

### 2024 — Enterprise scope, OEM platform, data architecture, and Defender Canada

- Assumed VP-level accountability for the complete Technology estate across FortNine, Defender, and 6Routes.
- Continued reporting directly to the Founder/CEO.
- Operated as a member of the executive leadership team while remaining hands-on in software architecture, system design, engineering practices, and critical delivery.
- Built and launched the OEM Portal.
- Used the group’s dealership capability to enable the sale of a substantially broader OEM-parts catalog.
- Established the architectural and integration foundation that would later scale to 19 OEM vendors.
- Led another major database-refactoring and transactional-centralization initiative.
- Improved database isolation, modularity, platform stability, and separation of workloads.
- Reduced the risk that one system or workload could degrade unrelated transactional operations.
- Launched a storefront SEO refresh.
- Continued strengthening organic-search architecture and platform discoverability.
- Launched Defender Canada in May 2024.
- Extended the shared FortNine commerce architecture into another national property.
- Continued evolving the platform toward reusable multi-property, multi-brand, multilingual, and multicurrency commerce.
- Maintained near-perfect availability while expanding platform scope and business complexity.

### 2025 — Infrastructure reliability and operational resilience

- Retained full accountability for all Technology functions across FortNine and Defender.
- Maintained near-perfect uptime across commerce and internal-system properties for a second consecutive year.
- Recorded zero downtime incidents attributable to internal architecture, deployment processes, or operational oversight.
- Absorbed only one availability event during 2025, caused by a major external Google Cloud Platform outage.
- Preserved platform stability while onboarding multiple developers and launching major features and new commerce properties.
- Maintained mature production-release practices without regression in reliability.
- Continued deploying multiple systems several times per week, depending on release scope and risk.
- Preserved rollback and recovery capabilities measured in minutes.

### 2025 — Security, compliance, and governance

- Completed the migration from LastPass to 1Password.
- Strengthened credential governance, access visibility, auditability, and administrative control.
- Expanded GitHub adoption to nearly all office employees.
- Enrolled the company in Novacap’s cybersecurity program.
- Led a detailed IT infrastructure and risk audit with Novacap and Crosslake.
- Participated directly in structured reviews of architecture, access management, infrastructure practices, security controls, and risk posture.
- Identified security, compliance, and operational-control gaps requiring remediation.
- Formalized the IT organization in part to improve ownership of those controls and remediation efforts.
- Identified frontend-integrity and analytics issues introduced by third-party scripts and contractor integrations through Google Tag Manager and AB Tasty.
- Isolated the injected scripts that were degrading customer-facing performance and analytics accuracy.
- Restored frontend performance and data integrity.
- Authored and published the company’s first formal frontend-governance policy: the Platform Integrity and Operational Excellence Charter.
- Established clearer accountability for third-party scripts, frontend performance, observability, security, and release integrity.
- Continued enforcing secure infrastructure standards, constrained access, centralized controls, active monitoring, and proactive risk review.

### 2025 — Organizational scaling and technical leadership

- Doubled the Technology organization.
- Managed the hiring, onboarding, integration, and development of five new team members.
- Protected long-term quality and cohesion while accepting the expected short-term velocity cost of rapid organizational growth.
- Established a formal IT department under a dedicated IT Manager.
- Separated day-to-day IT operations from Software Development while retaining unified executive accountability.
- Promoted an experienced engineer to Lead Software Developer following structured grooming and increasing responsibility.
- Expanded the Lead Software Developer’s mandate across both System and Warehouse technology stacks.
- Introduced a more scalable leadership structure through technical leads reporting directly to the VP role.
- Built onboarding processes capable of absorbing multiple developers.
- Reduced Storefront development-environment setup from hours or days to minutes.
- Delegated increased release authority while retaining architectural, security, and risk oversight.
- Continued mentoring engineers and technical leads in software architecture, system design, code quality, testing, deployment safety, operational ownership, and technical decision-making.
- Maintained exceptional retention and long employee tenures while scaling the organization.

### 2025 — Multi-property commerce architecture

- Launched 6Routes on the Storefront architecture originally founded and continuously evolved at FortNine.
- Demonstrated that the shared platform could support new commerce properties without creating independent technology stacks.
- Removed a longstanding Magento architectural constraint involving reuse of identical Store View Codes across multiple websites.
- Established a more scalable foundation for multi-brand and multi-property commerce.
- Implemented multi-website inventory functionality.
- Enabled merchandising teams to share catalog and inventory information across commerce properties.
- Expanded the OEM Portal to 19 vendor integrations.
- Scaled Scrape Task infrastructure to support more than a dozen additional OEM data integrations.
- Addressed increased scrape volume, memory use, throughput, scheduling, and reliability requirements.
- Expanded the reusable widget suite to improve the speed and consistency of marketing and merchandising execution.
- Released Curated Recommendations widgets for Defender.
- Delivered new promotional-rules widgets.
- Implemented an expanded coupon-management system capable of supporting increasingly complex promotional events.
- Continued developing the shared architecture required for FortNine, Defender US, Defender Canada, 6Routes, and future properties.

### 2025 — AI enablement and organizational knowledge

- Led the rollout of AI tooling to all front-office employees.
- Extended adoption across Software Development, Customer Service, Business Intelligence, Marketing, and other office functions.
- Guided the development and deployment of Custom GPT initiatives.
- Used AI-based knowledge systems to reduce customer-service knowledge gaps.
- Built organizational experience applying AI outside the Software Development team.
- Measured estimated developer productivity gains of approximately six hours per developer per week.
- Helped normalize responsible AI use as part of everyday knowledge work and software development.

### 2025 — Internal systems, automation, and bespoke software

- Continued evolving a substantial estate of bespoke ERP, CRM, warehouse, purchasing, returns, merchandising, billing, ordering, and operational systems.
- Oversaw the rewrite of Fitment Verifier from a legacy C# application into a modern web-based system.
- Guided a multi-month fitment-automation initiative.
- Significantly increased the speed at which vehicles could be associated with products.
- Reduced manual merchandising work through automation and system-level improvements.
- Continued iterative improvements across internal tools including:
  - Helix Web
  - Returns Manager
  - Scrape Tasks
  - Purchaser
  - Transport Tasks
  - Multi Order Processor
  - PO Manager
  - Partial Order Creator
  - Billing Verifier
- Supported a scraping refactor that reduced memory consumption and improved reliability.
- Expanded internal command-line tooling to standardize developer workflows and improve productivity.
- Continued improving high-volume ordering, fulfilment, warehouse, purchasing, billing, returns, and post-purchase systems without publishing sensitive transaction counts.

### 2025 — Warehouse and operational technology

- Guided the evolution of mobile warehouse scanners through direct collaboration with operational stakeholders.
- Oversaw frontend performance optimization for warehouse devices.
- Improved scanning speed, responsiveness, and usability.
- Continued aligning warehouse technology with the broader architecture, reliability, security, and deployment standards of the Technology organization.

### 2025 — Executive leadership and risk communication

- Continued presenting at quarterly FortNine board meetings with Novacap.
- Presented platform health, technology strategy, roadmap progress, upcoming initiatives, investment needs, operational risks, cybersecurity posture, and delivery status.
- Participated in board discussions concerning M&A opportunities and post-acquisition integration.
- Provided candid, technically grounded, and business-aligned feedback to the Founder/CEO and other executive leaders.
- Raised strategic, architectural, security, operational, and platform-integrity risks directly, including when the feedback was difficult.
- Treated long-term platform integrity and risk exposure as executive responsibilities rather than purely technical concerns.
- Balanced delivery pressure with the need to protect security, maintainability, reliability, and organizational cohesion.

### 2026 — Cloud Run and next-generation GCP architecture

- Rebuilt the Google Cloud architecture to address rapidly increasing traffic and performance requirements.
- Migrated core production workloads to Cloud Run.
- Modernized the production runtime, deployment model, development environment, and broader developer stack.
- Completed the May 2026 production cutover without downtime.
- Reduced average backend response time from approximately 914 ms to 555 ms.
- Delivered a measured 39.3% improvement in average backend latency.
- Produced sustained improvements in p95 and p99 latency following the migration.
- Reduced long-tail latency across catalog browsing, cart, checkout, and other customer pathways.
- Reduced the number of required infrastructure instances by using fewer, more capable resources.
- Applied committed-use discounts and architectural efficiencies to reduce infrastructure costs by approximately one-third.
- Delivered the modernization at a scale exceeding 1 billion raw edge requests per month across all commerce properties.
- Completed the final major infrastructure transformation before the conclusion of the tenure in May 2026.

<br/>

---

<br/>

## Cross-Role and Ongoing Achievements

**Applicable across multiple FortNine positions or throughout the full tenure**

### Executive scope and reporting

- Reported directly to the Founder/CEO throughout the tenure.
- Led Software Development, Architecture, Cloud Infrastructure, Cybersecurity, IT, Warehouse Technology, and Data.
- Held responsibility across FortNine, Defender US, Defender Canada, and 6Routes.
- Initially managed all employees directly and later introduced Team Lead positions that continued reporting directly to the VP role.
- Remained accountable for platform architecture, security, reliability, development practices, operational systems, and technical personnel as the organization expanded.
- Operated across both strategic and hands-on levels rather than transitioning into a purely administrative executive role.

### Company transformation and commercial scale

- Played a central role in transforming FortNine from a smaller Canadian retailer into a leading multi-property North American e-commerce group.
- Built and scaled the technology platform and organization underpinning more than 30-fold growth in annual revenue.
- Supported more than 30-fold growth in annual revenue from 2014 to 2026 across FortNine, Defender US, Defender Canada, and 6Routes.
- Scaled raw edge traffic from several million requests per month to more than 1 billion monthly requests across all properties.
- Supported a catalog of more than 2.5 million active SKUs.
- Built the architecture needed to handle major increases in products, vendor feeds, search and indexing activity, inventory data, fitment information, storefront traffic, and transactional complexity.
- Helped lift sitewide conversion to roughly 2.5 times its original level.
- Contributed to conversion improvements through performance, mobile commerce, cart, checkout, payments, customer experience, localization, experimentation, and platform reliability.

### Reliability, deployment, and operational maturity

- Designed and operated a high-availability platform averaging approximately 99.98% uptime over the tenure.
- Maintained recovery and rollback times measured in minutes after problems were identified. MTTR.
- Established deployment practices that supported multiple production releases per week across multiple systems.
- Favoured smaller, frequent, lower-risk releases over infrequent high-risk deployments.
- Designed systems and release processes around observability, rollback, containment, and rapid recovery.
- Completed multiple major production transformations without downtime.
- Maintained strong reliability while scaling traffic, product data, transaction volume, property count, team size, and architectural complexity.
- Ensured that the platform could continue operating during infrastructure changes, application migrations, acquisition integrations, and organizational growth.

### Cybersecurity and risk governance

- Maintained a record without a successful cybersecurity breach throughout the tenure.
- Developed a security-first culture based on constrained access, centralized systems, controlled attack surface, active monitoring, and practical risk reduction.
- Continuously reviewed database access, production permissions, credentials, infrastructure controls, vendor access, and third-party integrations.
- Led or participated in recurring security reviews, investor diligence, external audits, and compliance assessments.
- Modernized application-layer protection, credential management, access governance, monitoring, and infrastructure security over time.
- Treated security as an architectural and operational discipline rather than a collection of isolated products.
- Balanced usability and delivery speed against the need to limit unnecessary exposure and system proliferation.
- Regularly surfaced security and operational risks to the Founder/CEO, executive team, board, and investor stakeholders.

### Software-development culture and engineering practices

- Established and continuously evolved the Software Development culture.
- Defined and refined coding standards, architectural principles, code-review practices, automated testing, deployment standards, and release procedures.
- Introduced and matured DevOps practices throughout the tenure.
- Built reusable development tooling, command-line utilities (Linus CLI framework), onboarding automation, and local-environment standards.
- Improved documentation and reduced dependence on tribal knowledge.
- Discouraged cargo-cult implementations by requiring engineers to understand the systems and abstractions they used.
- Promoted direct technical ownership, engineering judgment, maintainability, and long-term system stewardship.
- Continued modernizing languages, frameworks, dependencies, hosting platforms, and infrastructure rather than allowing the platform to stagnate.
- Preserved hands-on software-development and architectural credibility throughout the progression into executive leadership.

### Architecture and systems modernization

- Continuously moved the organization away from legacy Windows-based processes toward Linux, cloud-native infrastructure, APIs, automation, containers, and managed services.
- Began the major Windows-to-Linux and cloud modernization program in 2018 and continued it through the end of the tenure.
- Centralized shared business logic through APIs and common systems.
- Isolated transactional, analytical, warehouse, scraping, and operational workloads to improve stability.
- Built a reusable platform capable of supporting multiple websites, brands, countries, currencies, locales, catalogs, and internal operations.
- Repeatedly rebuilt or refactored systems before increasing scale made the existing architecture an operational constraint.
- Developed a broad proprietary software estate rather than relying exclusively on packaged ERP, CRM, warehouse, purchasing, returns, or merchandising products.

### Internal business systems and automation

- Built and evolved bespoke systems spanning:
  - ERP workflows
  - CRM and customer-service operations
  - Warehouse technology
  - Purchasing and purchase orders
  - Returns and post-purchase operations
  - Product fitment
  - Merchandising
  - Billing verification
  - Order processing
  - Inventory sharing
  - Vendor integrations
  - Scraping and data ingestion
  - Promotions and coupons
  - Developer tooling
- Used automation to reduce manual work, improve consistency, increase throughput, and lower operational risk.
- Designed internal systems as part of the same broader architecture and engineering discipline as the customer-facing storefront.
- Maintained high availability and rapid release capability across both storefront and operational systems.

### Team building, retention, and mentorship

- Built a small, highly leveraged Technology team capable of supporting exceptional business and platform growth.
- Maintained no meaningful voluntary churn across the core engineering team.
- Retained core hires with tenures spanning five to ten years.
- Developed engineers into broader architectural, operational, release, and leadership responsibilities.
- Promoted internal technical leadership rather than relying solely on external management hires.
- Mentored engineers and technical leads in software architecture, system design, SDLC practices, code quality, testing, deployment safety, production ownership, and technical judgment.
- Created an environment in which long employee tenures coexisted with high standards and direct accountability.
- Balanced individual autonomy with architectural consistency and risk oversight.

### Board, investor, and M&A exposure

- Participated as a guest contributor at quarterly FortNine board meetings with Novacap from 2021 through 2026.
- Presented technology strategy, platform health, roadmap progress, upcoming initiatives, delivery status, investment requirements, security posture, and risks.
- Participated in M&A discussions before and after acquisitions.
- Led major technology and cybersecurity diligence workstreams.
- Identified technical risks that informed transaction terms.
- Assumed responsibility for post-acquisition technical leadership and integration.
- Built practical change-management experience through the Defender transition and applied it to later releases and transformations.
- Was formally recognized by Novacap during pre-investment due diligence as a key person in FortNine’s success.

### Roadmapping and strategic planning

- Defined long-term technology direction and translated it into sequenced, multi-year roadmaps.
- Balanced customer-facing initiatives, internal-system needs, infrastructure modernization, cybersecurity, operational risk, and organizational capacity.
- Identified when existing architecture was approaching its limits and initiated modernization before it became a crisis.
- Regularly communicated priorities, dependencies, progress, trade-offs, and risks to executives and the board.
- Maintained continuity between business strategy, technical architecture, team development, and delivery execution.

### Workplace technology and broader enablement

- Championed Apple adoption beginning with the first company MacBook in 2014.
- Helped expand Apple hardware until most office employees were using MacBooks by the end of the tenure.
- Expanded GitHub and modern development tooling beyond the original software team.
- Led AI enablement across the front office.
- Treated employee tooling, onboarding, credentials, knowledge systems, and internal productivity as part of the broader Technology mandate.

<br />

![FortNine's F9 emblem]({{site.url}}/assets/img/f9-emblem-red-bold-transparent.png)

