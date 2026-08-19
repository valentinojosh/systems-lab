# Systems Lab & Technical Projects

Hands-on systems engineering across segmented networking, self-hosted infrastructure, high-performance system integration, storage recovery, Windows deployment, diagnostics, repair, and recoverability. This repository documents systems I have designed, built, configured, operated, repaired, recovered, validated, or improved—with the engineering decisions, validation methods, and supporting evidence behind the result.

## Engineering scope

| Discipline | Applied experience |
| --- | --- |
| Infrastructure & networking | Segmented home networking, managed wired distribution, IoT isolation, DNS-layer filtering, and reliability-conscious traffic management |
| Systems administration | Native Windows services, account separation, maintenance planning, remote-administration design, and application-state protection |
| Hardware & integration | Requirements-driven PC architecture, compatibility and power planning, thermal strategy, staged commissioning, repair, and upgrades |
| Diagnostics & recovery | Cross-platform disk triage, source-preserving imaging, hardware telemetry, controlled load testing, driver remediation, and OS integrity checks |
| Deployment & reliability | Reproducible Windows installation media, post-install validation, storage migration, cold/off-site backup, and recovery planning |

## Featured case studies

### [Segmented Home Network & Security Architecture](projects/segmented-home-network/README.md)

A home network evolved from a flat consumer topology into a policy-conscious environment that separates trusted endpoints from less-trusted IoT devices while preserving low latency, compatibility, and day-to-day reliability.

- GL.iNet Flint 2 gateway with NETGEAR GS305E managed office distribution
- Intentional isolation of less-trusted IoT devices from trusted endpoints and household services
- Conservative network-wide DNS filtering without invasive browsing-history retention
- Evidence-based roadmap for validating segmentation, QoS, firewall policy, and congestion management

### [Self-Hosted Media Server & Home Theater PC](projects/self-hosted-media-server/README.md)

A spare-hardware platform repurposed into a dual-role Windows Jellyfin server and directly connected home-theater PC, balancing local service delivery, simple living-room operation, and recoverability.

- Ryzen 5 5500, RTX 2060 Super, and 32 GB DDR4 right-sized for the combined role
- 8 TB active library with NVIDIA hardware-accelerated transcoding
- LAN-only service exposure and separation between administration and viewing accounts
- Storage growth from 2 TB to 4 TB to 8 TB, backed by reviewed Robocopy operations, representative-file checks, tested cold/off-site media, and successful Jellyfin-state restoration

### [High-End 4K Racing Simulator System Integration](projects/racing-simulator-pc/README.md)

A flagship client gaming system commissioned for a 4K racing-simulator environment and premium all-white presentation. Phase 1 is operational; custom water cooling and the complete simulator expansion remain later stages.

- Operational Ryzen 7 9800X3D and AORUS GeForce RTX 5090 STEALTH ICE 32G platform
- B850 AORUS STEALTH ICE rear-connector integration inside a white CORSAIR 9000D
- Full 18-fan iCUE LINK deployment across two System Hubs, with hub-controlled case/front-I/O lighting and separate FPANEL adapter integration
- BIOS, EXPO, Windows 11 Pro, driver, iCUE LINK, and full-platform stability commissioning
- Intentional air-cooled Phase 1 complete; custom water cooling and the planned three-display simulator remain future phases

### [Storage Recovery & Cross-Platform Diagnostics](projects/storage-recovery/README.md)

A repeatable Windows/macOS recovery practice centered on protecting unstable source media before destructive action, collecting disk-health evidence, recovering from an image or clone, and validating restored data.

- Bootable Linux recovery environments for offline storage access and diagnostics
- SMART inspection, disk imaging/cloning, and mountable recovery images
- Windows filesystem, OS-integrity, memory, indexing, and multi-disk conflict remediation
- Source-first workflow that separates evidence preservation from repair

## Additional Systems Lab work

| Project | Focus |
| --- | --- |
| [Residential Security System](projects/residential-security-system/README.md) | Coverage planning, mixed power sources, local recording, detection-zone tuning, false-positive reduction, and IoT network placement |
| [Personal Performance Workstation](projects/personal-workstation/README.md) | Self-designed Windows 11 Pro gaming and development platform used for ongoing integration and validation work |
| [Windows Deployment & Provisioning](docs/windows-deployment.md) | Reproducible installation media, local-account setup, driver remediation, and post-install health validation |
| [Technician Bench & Diagnostic Toolkit](docs/technician-toolkit.md) | Purpose-driven telemetry, load testing, storage health, driver cleanup, and OS repair workflows |
| [Hardware Repair & Upgrades](docs/hardware-repair.md) | Mobile-device, MacBook, laptop, and desktop disassembly, component replacement, migration, and functional verification |
| [Backup & Recovery Practices](docs/backup-and-recovery.md) | Cross-project data protection, application-state backup and restoration, cold/off-site media validation, imaging, and recovery testing |
| [Historical Projects](docs/historical-projects.md) | Administration and organic growth of a 100+ member remote-study community during COVID-era university instruction |

## Operating approach

The projects follow a consistent engineering loop: establish requirements, design within real constraints, implement deliberately, validate with appropriate evidence, document recovery paths, and evolve the system when measurements justify a change. Implemented configurations are clearly separated from future capabilities, third-party tools remain attributed to their authors, and sensitive operational details are intentionally sanitized.

This repository is a curated technical portfolio, not a software distribution or tutorial archive. Executables, private configurations, credentials, and raw infrastructure exports are intentionally excluded.
