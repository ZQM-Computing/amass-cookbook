# Amass Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Amass cookbook** for passive subdomain enumeration and graph output. Patterns are drawn from the ZQM fleet's Amass v5.1.1 installs (size-exact tarball) and its passive demo against zqmlabs.com only, whose FQDN list contained only the apex. Note: a keyless passive enum took about 14 minutes on the fleet — output lands at the end, climbing CPU means it is progressing. It is intended for OSINT practitioners who map subdomains and infrastructure passively. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Amass patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (POI, weather, satellite imagery, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

OSINT practitioners who map subdomains and infrastructure passively.

## Prerequisites

- Amass v5.1.1
- An in-scope domain you own or are authorized to research
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-passive-enum` | Passive enumeration with no active probing |
| 02 | `02-config` | Configuration files and data-source selection |
| 03 | `03-output-parsing` | Reading FQDN lists and graph outputs |

## Repository layout

```text
amass-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
- [shodan-cookbook](https://github.com/ZQM-Computing/shodan-cookbook) — Internet-device search from the command line
