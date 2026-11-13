# Awesome-Data-Center-Infrastructure-Management

## Top Data Center Infrastructure Management (DCIM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Asset Tracking, Capacity Planning & Infrastructure Visualization*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Center Infrastructure Management (DCIM)**. These tools help operations teams document racks, servers, cabling, power, and cooling—providing the "single source of truth" needed for capacity planning, change management, and day-to-day datacenter operations.

**Examples** include Schneider Electric EcoStruxure IT, Sunbird DCIM, Nlyte, Vertiv Trellis, Device42, FNT Command, and open-source alternatives like NetBox, openDCIM, and Ralph (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted DCIM, open-source infrastructure documentation, and community-driven asset management—ideal for organizations seeking data sovereignty and predictable costs over per-rack or per-node enterprise licensing. The open-source DCIM landscape is genuinely functional: NetBox has become the de facto standard for network source-of-truth with 10,000+ organizations [citation:4], openDCIM provides a free GPLv3 DCIM application for physical infrastructure [citation:2], and Ralph offers full-featured asset management with DC visualization [citation:5].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Company Size (Revenue / Valuation) | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-----------------------------------|-------------------|--------------------------|
| **[Schneider Electric EcoStruxure IT](https://www.se.com/)** | Cloud-based DCIM with two tiers: **IT Expert** for real-time monitoring of Schneider and third-party devices; **IT Advisor** for asset management, capacity planning, and digital twin modeling across on-premises, hybrid, and colocation environments. AI-driven predictive maintenance and anomaly detection built in. | €38.2B+ (~$41B) FY24 revenue / ~€140B ($150B+) market cap | $56.00 to $85.00/node/year (IT Expert 1-Year baseline SKU: SWITE1YR-DIGI; 25-node bundle min ~ $1,400/yr) | 30-day free trial (Full-featured access to cloud platform, live dashboards, multi-vendor device monitoring, and smart alarming) |
| **[Vertiv Trellis](https://www.vertiv.com/)** | DCIM platform focused on power, thermal, and capacity management across physical infrastructure. Integrates with Vertiv power systems and Avocent appliances. | $8.01B FY24 ($10.23B FY25) revenue / ~$43B–$63B market cap | $15,000 baseline bundle (Trellis Quick Start Monitoring entry package for ~30 Floor Mounted Devices including appliance gateway) | Formal evaluation license via sales inquiry (Proof of Concept sandbox typically provisioned for 14–30 days upon qualification) |
| **[Panduit SmartZone](https://www.panduit.com/)** | DCIM focused on physical and power infrastructure—cabinets, cabling, and environmental connectivity. Integrates with SmartZone G5 intelligent PDUs. | ~$1.0B–$1.4B annual revenue (Privately held enterprise) | $15.50/IT asset/year (SmartZone Cloud IT Asset SKU: SZC-ITIA1Y; Power/Facility asset SKU: SZC-PEIA1Y at $78/asset/yr) | Guided live sandbox demo & customized 30-day trial license available via Panduit partner sales |
| **[Device42](https://www.device42.com/)** | Comprehensive IT asset management and DCIM with agentless auto-discovery, dependency mapping, and CMDB capabilities. Tracks physical racks, virtual nodes, and cloud workloads. | $230M valuation (Acquired by Freshworks Inc. [NASDAQ: FRSH, ~$1.4B market cap]) | $1,449/year (Core license tier covering up to 100 devices; add-on modules for ADDM, SLM, and power monitoring priced separately) | 14-day free trial (Limited to discovering and tracking up to 100 devices with core DCIM & IPAM features) |
| **[FNT Command](https://www.fntsoftware.com/)** | Enterprise infrastructure management for data centers, telecommunications, and cable networks. Strong in European markets with integrated CAFM/CAD capabilities. | ~$50M–$100M estimated revenue / 200–250 employees (Privately held enterprise) | €99/user/month billed annually (~€1,188/user/year for entry Asset Inventory CORE; rack-based packages available for DCIM) | Tailored Proof-of-Concept (PoC) evaluation license (14 to 30 days sandbox access with sample datacenter data upon sales consultation) |
| **[Sunbird DCIM](https://www.sunbirddcim.com/)** | Enterprise DCIM with robust 3D digital twin visualizations, rack asset tracking, and capacity management (dcTrack & Power IQ). Spun off from Raritan in 2015. | ~$17M–$18.5M estimated revenue (Privately held enterprise) | $13.99/cabinet/month (~$167.88/cabinet/year for dcTrack Operations; Power IQ monitoring starts at $3.99/monitored node/month) | 30-day free trial (Full access to hosted test environment with 3D rack visualization and capacity analytics) |
| **[netTerrain DCIM](https://www.netterrain.com/)** | DCIM with automated rack layout visualization, cable plant documentation, and environmental reporting by Graphical Networks. | ~$2.4M estimated revenue / 20–25 employees (Privately held, bootstrapped) | $4,926/year (Starting base DCIM subscription tier; netTerrain Logical base entry starts at $944/year) | 14-day free trial (Cloud trial environment limited to a test device set; trial extension available on request) |
| **[Hyperview](https://www.hyperviewhq.com/)** | Cloud-native DCIM with agentless discovery from heterogeneous server, power, and cooling hardware. Simplifies infrastructure visibility and carbon tracking. | ~$2.7M ARR / 20 employees / $300K seed funding (Privately held SaaS) | $3.00/asset/year (Billed annually; minimum purchase requirement of 500 assets = $1,500/year base entry) | 30-day free trial (Full-featured access to cloud platform with unlimited test device discovery and no credit card required) |
| **[Cormant-CS](https://www.cormant.com/)** | DCIM with comprehensive physical layer cable management, connectivity, and asset tracking. Acquired by global facility manager BGIS in 2021. | ~$2.5M estimated revenue (Division of BGIS: ~$1B–$5B gross facility management revenue) | $5,000/year (Starter Pack entry tier supporting 25 to 80 racks with bundled instructor-led setup services; includes unlimited user seats) | 7-day hosted cloud trial (Pre-configured sample data environment; customized Proof-of-Concept PoC licenses provisioned upon request) |
| **[Nlyte Software](https://www.nlyte.com/)** | AI-powered DCIM with outage prediction, what-if capacity planning, and intelligent asset placement. Acquired by Carrier Global Corporation in 2021. | Division of Carrier Global Corp. [NYSE: CARR, ~$40B market cap / $22B+ revenue] (Raised $53.5M prior to acquisition) | $20.00/rack/year baseline nominal entry quote (Custom enterprise contracts typically tiered by total power capacity and managed cabinets) | 14-day free trial (Nlyte On-Demand 2-week guided evaluation environment with sample data and tutorials) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[NetBox](https://github.com/netbox-community/netbox)** | [![Stars](https://img.shields.io/github/stars/netbox-community/netbox?style=social&color=white)](https://github.com/netbox-community/netbox/stargazers) | **The world's most widely adopted open-source infrastructure source of truth.** Apache-2.0, Django/Python. Combines IPAM (IP address management) with DCIM (racks, devices, cabling, power) into a unified data model. **Trusted by 10,000+ organizations** including CoreWeave for hyperscale datacenter builds [citation:4]. Plugin architecture enables extensions for floorplan visualization, rack management, and custom workflows [citation:9]. The default choice for network engineers and infrastructure teams needing an API-first, automation-ready platform [citation:11]. |
| **[openDCIM](https://github.com/opendcim/openDCIM)** | [![Stars](https://img.shields.io/github/stars/opendcim/openDCIM?style=social&color=white)](https://github.com/opendcim/openDCIM/stargazers) | **Free, GPLv3 DCIM application for physical infrastructure management.** PHP-based web application (367 GitHub stars). Covers the majority of features needed for datacenter inventory management—rack elevations, device tracking, and space planning—without contending to be a function-by-function replacement for commercial DCIM [citation:2][citation:12]. Provides RESTful API (v4.2+) for integration with asset management platforms like Axonius [citation:6]. Docker and Helm deployment available [citation:2]. |
| **[Ralph](https://github.com/allegro/ralph)** | [![Stars](https://img.shields.io/github/stars/allegro/ralph?style=social&color=white)](https://github.com/allegro/ralph/stargazers) | **Full-featured Asset Management, DCIM, and CMDB for data centers and back offices.** Apache-2.0, Django/Python. Tracks asset purchases and lifecycle, provides flexible flow system for asset management, and includes **built-in DC visualization** [citation:5]. Maintained under a "sources only" model by Allegro—source code published and development continuing, but no guaranteed support for pull requests. Live demo available [citation:5]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[DRACS (Dell Rack & Asset Control System)](https://pypi.org/project/dracs/)** | — | Python-based tool for managing **Dell server fleets** with warranty tracking, BIOS/iDRAC firmware version monitoring, and SNMP-based discovery. Integrates with Dell TechDirect API for warranty data. Web UI with color-coded alerts for expiring warranties and outdated firmware. **Not general-purpose DCIM**—purpose-built for Dell hardware environments [citation:3][citation:10]. |
| **[RackTables](https://github.com/RackTables/racktables)** | — | Long-standing open-source datacenter and server room management tool. Tracks racks, devices, IP addresses, and cabling. Community topic listings show active development around RackTables REST API integrations for modern management [citation:9]. |
| **[Tenqora](https://github.com/topics/rack-management)** | — | "Operations-first DCIM for racks, assets, connectivity, power and lifecycle" listed on GitHub's rack-management topic (October 2026 update). Newer project worth evaluating for teams wanting a modern DCIM interface [citation:9]. |

**Frameworks for building custom systems**: Choose **NetBox** for network-centric infrastructure with IPAM and plugin ecosystem, **openDCIM** for straightforward physical rack/device management on PHP hosting, and **Ralph** for full asset lifecycle tracking with CMDB and visualization—all deployable via Docker without per-rack or per-node licensing. For Dell-specific fleets, **DRACS** provides warranty and firmware tracking that general DCIM tools may not cover natively [citation:3].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- DCIM platforms document critical infrastructure dependencies; inaccurate data can lead to capacity outages, cooling failures, or power overloads. Validate documentation against physical reality before relying on any tool for change planning.
- **Open-source DCIM maturity varies.** NetBox is production-grade with hyperscale adoption [citation:4]. openDCIM is functional but has low community activity (10 contributors, ~1 month since last commit per Open Hub) [citation:12]. Ralph is maintained under a "sources only" model without guaranteed PR support [citation:5]. Commercial DCIM platforms (Schneider, Sunbird, Nlyte, Vertiv) are quote-only enterprise contracts with implementation services typically required. **Pricing transparency is limited**: netTerrain publishes **$4,926/year** [citation:1]; others require sales engagement.

---

**Made for data center managers, infrastructure engineers, network architects, and developers building operations tooling.**  
Let's make data center infrastructure management more open, documented, and reliable.
