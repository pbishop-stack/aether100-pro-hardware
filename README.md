# Aether100 Pro Edge AI Workstation Hardware Platform

Open-source Technical Data Package (TDP) for a compact, high-performance edge AI workstation designed for local inference of large language models.

**Status:** Rev A – 2026-07-31  
**License:** CERN-OHL-S

## Design Intent

The Aether100 Pro is an engineering baseline for a desktop-class edge AI system focused on:

- Local execution of 70-billion-parameter class models
- High memory capacity and bandwidth
- Controlled acoustic and thermal performance
- Full open-source hardware documentation

This repository contains the complete controlled document set, not a finished consumer product.

## Key Design Targets (Rev A)

- Custom TSMC 3nm-class ACE-1 SoC architecture
- 256 GB LPDDR5X memory subsystem
- Dual PCIe Gen5 NVMe storage
- Sealed copper vapor chamber thermal solution
- Aggressive low-noise thermal design goals
- Compact CNC aluminum enclosure

## Document Structure

| Document | Location |
|----------|----------|
| Project Charter | [docs/00-project-control/](docs/00-project-control/) |
| Product Requirements Specification | [docs/01-requirements/](docs/01-requirements/) |
| Detailed Design Report | [docs/02-design/](docs/02-design/) |
| Risk Management Plan | [docs/03-risk-management/](docs/03-risk-management/) |
| Bill of Materials | [docs/04-bom/](docs/04-bom/) |
| Manufacturing Drawing Standards | [docs/05-drawing-standards/](docs/05-drawing-standards/) |
| Fabrication Specifications | [docs/06-fabrication/](docs/06-fabrication/) |
| Quality Assurance & FAI Plan | [docs/07-quality/](docs/07-quality/) |
| Assembly Work Instructions | [docs/08-assembly/](docs/08-assembly/) |
| Document Control Procedure | [docs/00-project-control/](docs/00-project-control/) |

## Future Content

- `mechanical/` — CAD models and drawings
- `electrical/` — Schematics, PCB layout, Gerbers
- `firmware/` — Bootloader and thermal management code

## License

This project is released under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S).

See the [LICENSE](LICENSE) file for full terms.
