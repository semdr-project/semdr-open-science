# SEMDR Open Science

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19615334.svg)](https://doi.org/10.5281/zenodo.19615334)

**Central landing page for all open science outputs from the SEMDR project
(Smart Energy Management & Demand Response Capabilities for Sustainable
Industry).**

This repository serves as a single entry point to the project's open-source
software, datasets, publications, and related resources.

**Project website:** [semdrcy.replit.app](https://semdrcy.replit.app)

---

## Open-Source Repositories

| ID | Repository | Type | Licence | Description |
| --- | --- | --- | --- | --- |
| OS-1 | [cyprus-energy-market-prices-forecaster](https://github.com/semdr-project/cyprus-energy-market-prices-forecaster) | Software | MIT | Cyprus day-ahead electricity price forecasting tools. Includes data acquisition scripts and forecasting models for research and analytical use. |
| OS-2 | [cyprus-weather-electricity-prices](https://github.com/semdr-project/cyprus-weather-electricity-prices) | Software + Dataset | MIT (code) / CC BY 4.0 (data) | Combined weather and day-ahead electricity price dataset for Cyprus, with acquisition and preparation scripts. Public market and weather data restructured for research use. |
| OS-3 | [limassol-hotel-hvac-energyplus-dataset](https://github.com/semdr-project/limassol-hotel-hvac-energyplus-dataset) | Dataset | CC BY 4.0 | Five fixed-setpoint EnergyPlus simulation baselines (12, 14, 16, 18, 20°C chilled water supply) for a Mediterranean large hotel building, based on the publicly available US Department of Energy reference building model. Intended as a benchmark for researchers developing their own HVAC control strategies. |

Each repository has been integrated with Zenodo to provide persistent
DOI-based citation and long-term preservation.

---

## Publications

| ID | Title | Type | Status | Venue |
| --- | --- | --- | --- | --- |
| P-01 | Real-World Demonstration of Optimized Pool Pump Control for Demand Response in the Hospitality Sector | Conference paper | Published (Dec 2025) | 32nd EU CIGRE, Athens |
| P-02 | Validated Energy Savings Through Smart Demand Response in the Hospitality Sector: A Pilot Study in Cyprus | Journal article | In preparation | Applied Energy / Energy and Buildings (Elsevier) |

---

## Planned Open Data Releases

| ID | Description | Licence | Timeline |
| --- | --- | --- | --- |
| OS-5 | Anonymised pool pump energy and water quality time-series from the live pilot deployment | CC BY 4.0 | By September 2026 |
| OS-7 | Anonymised HVAC energy consumption time-series from the live deployment | CC BY 4.0 | Post-project (following cooling season validation) |

---

## Full Open Science Outputs Inventory

| ID | Type | Status |
| --- | --- | --- |
| OS-1 | Cyprus electricity price forecaster | Completed |
| OS-2 | Cyprus weather and electricity prices dataset | Completed |
| OS-3 | Mediterranean hotel HVAC EnergyPlus baselines | Completed |
| OS-4 | CIGRE 2025 conference paper | Published; Zenodo planned |
| OS-5 | Anonymised pool pump production dataset | Committed — Sep 2026 |
| OS-6 | Methods journal paper | Planned — Q2 2026 |
| OS-7 | Anonymised HVAC production dataset | Planned — post-project |
| OS-8 | Project website | Operational |
| OS-9 | Public deliverables on website | Completed |

---

## FAIR Data Compliance

All published outputs follow the FAIR principles:

* **Findable** — persistent Zenodo DOIs, Dublin Core metadata, SEMDR community on Zenodo
* **Accessible** — open access via GitHub HTTPS and Zenodo download, no authentication required
* **Interoperable** — CSV for time-series, JSON for structured data, IDF for EnergyPlus models, ISO 8601 timestamps, SI units
* **Reusable** — comprehensive READMEs with data dictionaries, clear provenance, permissive licences (MIT / CC BY 4.0)

---

## Acknowledgement

This work was carried out as part of the SEMDR project (Smart Energy Management & Demand Response Capabilities for Sustainable Industry, COM-CONCEPT-ENERGY/0624/0160), implemented within the framework of the Cyprus Recovery and Resilience Plan "Cyprus tomorrow" with funding from the European Union — NextGenerationEU, through the Research and Innovation Foundation.
