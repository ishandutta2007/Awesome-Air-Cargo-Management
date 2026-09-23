# Awesome-Air-Cargo-Management

# Top Air Cargo Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Air Freight Booking, Cargo Airline Systems, AWB/e-AWB, Capacity Management, Messaging & Air Cargo Logistics Platforms*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Air Cargo Management**. These systems support airline and forwarder operations—booking, capacity, air waybills (AWB/e-AWB), messaging (e.g. Cargo-IMP / ONE Record), tracking, and revenue management for air freight.

**Examples** include CHAMP Cargosystems, Awery Aviation Software, CargoAi, Unisys Cargo Portal Services, Descartes Air Messaging, IBS iCargo, WiseTech CargoWise, Wiremind Cargo, SmartKargo, and RapidCargo (the category leaders).

**Open-source emphasis**: Production air cargo airline and GSA systems are almost exclusively commercial. Open activity centers on **IATA ONE Record** reference implementations, general freight/TMS open tools, and educational air-cargo booking prototypes. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[CHAMP Cargosystems](https://www.champ.aero/)**  
  Long-standing air cargo IT provider offering airline cargo systems, community platforms, and related messaging and operations solutions.

- **[IBS iCargo](https://www.ibsplc.com/)**  
  Comprehensive air cargo management suite used by airlines for booking, operations, revenue, and customer-facing cargo processes.

- **[WiseTech CargoWise](https://www.wisetechglobal.com/)**  
  Global logistics platform with strong air freight modules for forwarders—quoting, booking, documentation, and multi-modal operations.

- **[CargoAi, SmartKargo, RapidCargo, Wiremind Cargo](https://cargoai.co/)**  
  Digital booking, capacity, and revenue-management oriented platforms connecting shippers, forwarders, and airlines.

- **[Awery Aviation Software, Unisys Cargo, Descartes Air Messaging](https://awery.aero/)**  
  Aviation and cargo systems covering airline operations, portals, and industry messaging/connectivity.

- **[Other commercial air cargo platforms](https://www.champ.aero/)**  
  Additional solutions for e-AWB, tracking, GSA operations, and air freight community systems.

## Open-Source GitHub Projects

- **[IATA ONE Record / NE:ONE](https://www.one-record-hub.com/)**  
  Open data model and reference server software (NE:ONE) for standardized air freight data exchange—digital twin of shipments, reducing document silos across the air cargo chain (Open Logistics Foundation / industry initiatives).

- **[FreightCMS](https://github.com/freightcms)**  
  Open-source cargo / transportation management oriented software aimed at cloud-native or self-hosted freight management workflows.

- **[Open TMS for freight brokers](https://github.com/loadpartner/tms)**  
  Open-source transportation management system for freight brokers—useful building block for multi-modal logistics that can include air legs.

- **[Air cargo booking & tracking prototypes](https://github.com/search?q=air+cargo+booking+OR+air+freight+open+source)**  
  Production-style educational systems demonstrating route search, booking state machines, timelines, and concurrency-safe cargo booking flows.

- **[Warp Tools & open logistics ops](https://github.com/wearewarp/warp-tools)**  
  Free, self-hosted logistics tools (carrier management, invoices, documents) that replace spreadsheets for operational teams.

- **[General open freight & logistics platforms](https://github.com/search?q=freight+OR+TMS+OR+cargo+management+open+source)**  
  Community TMS, FMS, and cargo tracking projects adaptable to air freight use cases.

- **[e-AWB / messaging open experiments](https://github.com/search?q=e-AWB+OR+Cargo-IMP+OR+ONE+Record)**  
  Tools and schemas related to electronic air waybills and modern air cargo data standards.

- **[Tracking & visibility open components](https://github.com/search?q=shipment+tracking+open+source)**  
  Shipment tracking libraries and dashboards that can surface air cargo status events.

### Additional Strong Open-Source Options

- **Industry data standard**: ONE Record + NE:ONE as the primary open foundation for interoperable air cargo data.
- **Broker / forwarder TMS**: Open TMS projects for organizations that need booking and ops without a full airline cargo system.
- **Prototypes & education**: Air-cargo booking demos for learning state machines and timeline design.
- **Composable stacks**: ONE Record server + open TMS + messaging adapters for limited custom deployments.
- Full airline cargo management (inventory, rating, host systems, regulatory messaging) remains commercial.

**Frameworks for building custom systems**:  
**IATA ONE Record** and the **NE:ONE** reference implementation are the most important open building blocks for modern air cargo data exchange.  
Open TMS and freight tools help forwarders and brokers.  
Commercial platforms (CHAMP, IBS iCargo, CargoWise, CargoAi, Unisys, Descartes, etc.) deliver airline-grade booking, capacity, revenue, e-AWB, and global messaging.  
Airlines and major GSAs run commercial cargo systems; open tools are best for interoperability pilots, forwarder operations, research, and custom visibility layers. Fully open end-to-end airline cargo systems are not available at production scale.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Air cargo systems handle regulated trade, security, and commercial data. Incorrect configuration can affect customs compliance, security screening, and liability. Only validated systems should be used for live airline or regulated freight operations.
- Open-source tools offer transparency for standards and prototypes but generally lack the scale, certification, and 24/7 support of commercial air cargo platforms. Do not use unvalidated open software for production airline cargo inventory or regulatory messaging without thorough engineering and compliance review.

---

**Made for airline cargo teams, freight forwarders, GSAs, and logistics technologists.**  
Let's expand open standards and tools for air freight data exchange while recognizing the operational depth and reliability that leading commercial air cargo management platforms deliver.
