# Personal Performance Workstation

A self-designed Windows 11 Pro workstation that serves as the primary gaming, development, AI-assisted development, recording, and editing platform. The system also functions as an ongoing integration and validation environment for firmware, drivers, hardware telemetry, and performance-sensitive workflows.

## Objective

Build a responsive, upgradeable daily system that balances high-refresh gaming with software-development and media workloads. The platform needed strong general CPU performance, capable discrete graphics, fast primary storage, accessible project storage, and a recoverability plan outside the active machine.

## Platform

| Component | Current configuration |
| --- | --- |
| Operating system | Windows 11 Pro |
| CPU | AMD Ryzen 9 9900X |
| Motherboard | MSI MAG X670E Tomahawk |
| Memory | G.SKILL Flare X 32 GB |
| Graphics | NVIDIA GeForce RTX 3070 |
| CPU cooler | DeepCool AK620 DIGITAL |
| Chassis | SAMA case |
| Primary storage | Samsung 990 PRO 1 TB NVMe SSD |
| Secondary storage | 1 TB WD Blue SATA drive |

## Workloads

- primary gaming environment;
- software and AI-assisted development;
- performance-sensitive desktop workflows;
- game capture and editing projects;
- hardware and driver validation;
- technician-bench support for testing components and utilities.

## Architecture and implementation

The AM5/X670E platform provides an upgradeable base around an AMD Ryzen 9 9900X processor and G.SKILL Flare X 32 GB memory. The RTX 3070 supports the system's gaming and GPU-accelerated desktop workloads, while the Samsung 990 PRO NVMe SSD carries the operating system and latency-sensitive applications.

Secondary WD Blue SATA storage separates active recordings, editing material, and working copies from the primary volume. Separate cold/off-site backup protects selected data beyond the disks installed in the workstation; the secondary internal disk is treated as accessible working storage, not as the entire recovery strategy.

Windows 11 Pro was provisioned with current platform and device drivers, then maintained as the daily validation environment. Firmware, graphics drivers, storage health, thermals, and operating-system integrity are reviewed with the same bench tools documented elsewhere in this repository.

## Engineering decisions

### General-purpose performance over a single benchmark target

The workstation supports mixed daily use rather than one synthetic workload. CPU, memory, GPU, storage, cooling, and chassis choices are evaluated together for responsive development work, high-frame-rate gaming, recording, and sustained reliability.

### Separate active storage from recovery copies

The secondary disk improves workspace organization and provides convenient additional copies for selected projects, while a separate cold/off-site process addresses risks that affect the whole PC. This distinction avoids presenting a second internal disk as an off-host backup.

### Reproducible performance baselines

Future benchmark baselines will retain the test version, settings, sensor context, and result capture so performance can be compared meaningfully over time.

## Validation approach

- confirm firmware and driver state after significant hardware changes;
- inspect CPU/GPU/storage telemetry with HWiNFO64, GPU-Z, and CrystalDiskInfo;
- use CPU/GPU loads appropriate to the changed subsystem;
- review thermals, clocks, errors, and stability rather than score alone;
- evaluate frame-time behavior with CapFrameX or LatencyMon when investigating responsiveness;
- run OS integrity and memory diagnostics when symptoms indicate them;
- recheck backup coverage after changing storage layout or project locations.

## Results

The workstation provides a unified high-performance platform for gaming, development, recording, editing, and technical validation. Its value in the lab extends beyond its component list: it is the daily environment in which deployment, driver, telemetry, backup, and troubleshooting practices are exercised.

## Evolution

- Capture a fresh, reproducible baseline for CPU, GPU, storage, thermals, and representative gaming frame times.
- Record benchmark tool versions, settings, ambient context where practical, and retained screenshots.
- Review project-data backup coverage and extend periodic restore sampling to critical workstation projects.
- Revalidate cooling and power behavior after future GPU or CPU changes.

<!-- MEDIA TODO:
Add a clean system photo and one reproducible telemetry/benchmark capture.
Recommended framing: neutral background and readable test context; remove usernames, device serial numbers, local paths, and unrelated applications.
-->

## Related documentation

- [Technician Bench & Diagnostic Toolkit](../../docs/technician-toolkit.md)
- [Windows Deployment & Provisioning](../../docs/windows-deployment.md)
- [Backup & Recovery Practices](../../docs/backup-and-recovery.md)
