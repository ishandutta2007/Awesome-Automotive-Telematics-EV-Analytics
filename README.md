# Awesome-Automotive-Telematics-EV-Analytics

# Awesome-Automotive-Telematics-EV-Analytics

# Awesome Automotive Telematics & EV Analytics 🌟

> **Top Automotive Telematics EV Analytics (Opensource)**  
> A curated list of the best automotive telematics platforms, fleet management systems, and EV analytics tools — with a strong focus on **open-source** and self-hostable alternatives.  
> 🌟 **Star if you like it!** 🌟

Automotive telematics and EV analytics platforms collect real-time vehicle data (GPS, OBD-II, CAN bus, battery metrics, driver behavior, charging sessions) to enable fleet tracking, predictive maintenance, energy optimization, safety monitoring, and operational insights. Commercial leaders such as Geotab, Samsara, and Motive dominate the hosted market, while a growing open-source ecosystem offers full data ownership, hardware flexibility, and no per-vehicle fees.

This list prioritizes **open-source GitHub projects** while keeping SaaS/hosted platforms clearly separated.

## Table of Contents

- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

These are popular commercial automotive telematics, fleet management, and EV analytics platforms (closed-source / hosted):

- **[Geotab](https://www.geotab.com/)** — Leading telematics platform with GO devices, extensive vehicle data, EV-specific insights, and Marketplace integrations.
- **[Samsara](https://www.samsara.com/)** — Cloud-based fleet platform combining GPS tracking, AI cameras, EV charging management, and real-time dashboards.
- **[Verizon Connect](https://www.verizonconnect.com/)** — Comprehensive fleet tracking, routing, compliance, and telematics with strong North American coverage.
- **[Teletrac Navman](https://www.teletracnavman.com/)** — GPS fleet tracking, driver behavior, and asset management solutions.
- **[Fleet Complete](https://www.fleetcomplete.com/)** — End-to-end fleet management with telematics, ELD, and field service tools.
- **[Trimble Transportation](https://www.trimble.com/)** — Enterprise transportation management, fleet telematics, and logistics optimization.
- **[Motive (formerly KeepTruckin)](https://gomotive.com/)** — AI-powered fleet management with ELD, cameras, and vehicle health monitoring.
- **[Webfleet (Bridgestone)](https://www.webfleet.com/)** — European-focused fleet management with real-time tracking and EV optimization.
- **[Cartrack](https://www.cartrack.com/)** — Global vehicle tracking, recovery, and fleet analytics platform.
- **[PowerFleet](https://www.powerfleet.com/)** — Industrial and commercial vehicle telematics with asset tracking and IoT integration.

## Open-Source GitHub Projects

Open-source alternatives and tools you can self-host, run on your own hardware, or extend. These range from full GPS tracking servers and vehicle monitoring systems to EV-specific analytics, OBD/CAN tools, and charging management.

### Full Fleet Tracking & Telematics Platforms

- **[traccar/traccar](https://github.com/traccar/traccar)**  
  The most popular open-source GPS tracking platform. Supports 200+ device protocols and 2000+ tracker models. Real-time tracking, geofencing, reports, driver behavior, and REST API. Fully self-hostable (Java backend + web UI). Excellent for fleets of any size. ~8k+ stars.

- **[fleetbase/fleetbase](https://github.com/fleetbase/fleetbase)**  
  Modular open-source logistics and supply chain operating system (LSOS). Includes fleet management, live tracking, dispatch, order management, and extensible architecture. Self-hostable with REST API and webhooks. ~4.7k stars.

- **[openvehicles/Open-Vehicle-Monitoring-System-3](https://github.com/openvehicles/Open-Vehicle-Monitoring-System-3)** (OVMS)  
  Complete open-source vehicle remote monitoring, diagnosis, and control system. Hardware module + software for live metrics (SoC, temperatures, tyre pressures, faults), alerts, remote control, and fleet monitoring. Excellent EV support and highly scriptable. Hardware + software fully open.

- **[bkbilly/Routario](https://github.com/bkbilly/Routario)**  
  Self-hosted real-time fleet tracking with live maps, smart alerts, trip history, geofences, and sensor analytics. Supports common GPS hardware protocols. No subscriptions and full data ownership.

- **[gx0r/agilegps](https://github.com/gx0r/agilegps)**  
  Real-time fleet tracking software focused on Queclink devices. Multi-tenant, Node.js + RethinkDB, maps, reports, and OBD diagnostics support.

### EV-Specific Analytics & Telemetry

- **[angoikon/byd-trip-stats](https://github.com/angoikon/byd-trip-stats)**  
  Feature-rich Android analytics dashboard for BYD BEV/PHEV vehicles (DiLink 3/5/100). Runs directly on the car’s infotainment screen. Trip recording, real-time range projection based on actual consumption, charging curves, battery health, heatmaps, and offline storage. Source-available and actively maintained.

- **[erc-fhv/open-ev-fleet](https://github.com/erc-fhv/open-ev-fleet)**  
  Research-oriented monorepo for electric vehicle fleet management. Python and Julia packages for optimization algorithms, charging simulation, data processing, and MILP/heuristic solvers.

- **[Mindfactory89/ev-charging-dashboard](https://github.com/Mindfactory89/ev-charging-dashboard)**  
  Self-hosted multi-vehicle EV charging dashboard with analytics, forecasts, session management, and PostgreSQL backend. PWA support and modern UI.

- **[appspace/kwwhat](https://github.com/appspace/kwwhat)**  
  Open-source dbt models that turn raw OCPP logs into structured EV charging analytics (reliability, utilization, charge attempts, visits).

- **[OpenEVSE](https://github.com/OpenEVSE)** (organization)  
  Open-source electric vehicle supply equipment (EVSE) firmware, hardware, and WiFi gateway projects for DIY and commercial charging stations.

### OBD-II, CAN Bus & Vehicle Data Tools

- **[commaai/opendbc](https://github.com/commaai/opendbc)**  
  Python API for reading and writing vehicle CAN data. Supports gas, brake, steering, and many signals across modern cars. Foundation for openpilot and vehicle reverse engineering. ~3.6k+ stars.

- **[iUnreallx/ReDrive](https://github.com/iUnreallx/ReDrive)**  
  Open-source OBD2 dashboard app (Flutter) for real-time sensor data, DTC reading/clearing, and diagnostics via Bluetooth/Wi-Fi/USB ELM327 adapters.

- **[WayBetterSolutions/OCTAVE](https://github.com/WayBetterSolutions/OCTAVE)**  
  Cross-platform open-source telematics and infotainment system. OBD-II data, custom dashboards, phone mirroring, and full theming. Runs on Pi, laptop, or Android.

- **[tzebrowski/ObdGraphs](https://github.com/tzebrowski/ObdGraphs)**  
  Android application for collecting and visualizing vehicle telemetry via ELM327/STN adapters. Real-time gauges and data logging.

- **[speed785/open-mechanic](https://github.com/speed785/open-mechanic)**  
  Open-source AI-powered car diagnostics. Connects OBD-II adapters and uses LLMs for plain-English fault diagnosis and repair guides.

### Additional Notable Projects

- **Eclipse CANought** (Eclipse Foundation / Cummins, Bosch, KPIT) — Open-source standardized CAN access layer for commercial vehicle telematics under the Eclipse Software Defined Vehicle initiative.
- **[sachnaror/fleet-management-system](https://github.com/sachnaror/fleet-management-system)** — Python/FastAPI fleet platform with OBD-II, CAN, GPS, driver behavior, and live dashboard.
- Various OBD databases and signal sets (e.g., community OBDb efforts) that document vehicle-specific parameters and DTCs.

> **Tip**: For pure GPS fleet tracking, start with **Traccar**. For deep EV monitoring and control, **OVMS** is the gold standard. For modern vehicle data access and reverse engineering, **opendbc** is essential. Many projects can be combined (e.g., Traccar + custom OBD collectors + EV analytics dashboards).

## How to Contribute

Contributions are welcome and encouraged!

1. Fork the repository
2. Add a new tool under the appropriate section (keep SaaS and Open-Source strictly separate)
3. Use the same format: **Name** — short description + key features + license/link
4. Prefer actively maintained projects with clear documentation and real vehicle/hardware support
5. Submit a Pull Request

Please keep descriptions neutral and factual. Open-source projects are the primary focus of this list.

## Disclaimer

This is a community-curated list for informational purposes only.  
Inclusion does not constitute an endorsement. Always review licenses, privacy policies, hardware compatibility, safety implications, and legal requirements (especially regarding vehicle data, driver privacy, and regulatory compliance such as ELD or GDPR) before deploying any tool in production.

Some “open-source” projects may include proprietary SDKs, dual licensing, or require paid cloud services for certain features. Check the actual LICENSE file, documentation, and hardware requirements carefully. Vehicle data collection can have significant privacy and safety implications.

---

**Made with ❤️ for the open-source community**  
If this list helped you, please ⭐ the repo!
