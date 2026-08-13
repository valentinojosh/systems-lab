# High-End 4K Racing Simulator System Integration

A flagship client system engineered for a premium 4K racing-simulator environment and top-tier general gaming. The project treats the computer as a complete integration problem: workload fit, component compatibility, native high-power GPU delivery, reverse-connector cable presentation, thermal headroom, coordinated white aesthetics, staged commissioning, and final evidence capture.

## Objective

Design and commission a visually cohesive all-white system that can anchor a dedicated racing-simulator setup while delivering flagship-class gaming performance. The client also wanted room to decide between a future matching liquid cooler and a full CPU/GPU custom loop without delaying initial use of the system.

## Requirements

- gaming-first CPU performance for a 4K simulator workload;
- RTX 5090-class graphics capability in a premium white build;
- modern native power delivery for the flagship GPU tier;
- clean internal presentation and reduced visible cabling;
- substantial airflow and future liquid-cooling capacity;
- Windows 11 Pro deployment and post-build validation;
- a staged path from initial commissioning to the client's final cooling decision.

## Architecture and component strategy

### Gaming-focused compute platform

The AMD Ryzen 7 9800X3D supplies eight Zen 5 cores, sixteen threads, and second-generation 3D V-Cache in a processor positioned by AMD for enthusiast gaming. That makes it a workload-aligned choice for a simulator-first system rather than a workstation specification selected by core count alone.

The confirmed graphics requirement is RTX 5090 class. The exact board-partner SKU is withheld until it is reconciled against the physical card, packaging, or receipt.

### Rear-connector presentation

The B850 AORUS STEALTH ICE provides an AM5, Ryzen 9000-compatible white motherboard platform. Its STEALTH rear-connector layout moves supported power and front-panel connections behind the motherboard tray, improving the presentation and cable-management strategy. CORSAIR explicitly lists the 9000D as compatible with GIGABYTE Project Stealth reverse-connection motherboards.

### Storage

A 2 TB Samsung 990 PRO PCIe 4.0 NVMe SSD serves as the boot and game drive. Samsung rates the 2 TB model for sequential transfers up to 7,450 MB/s read and 6,900 MB/s write; those are manufacturer capabilities, not claimed measurements from this build.

### Power delivery

The white Super Flower LEADEX VIII Platinum PRO 1200 W provides a fully modular ATX 3.1 / PCIe 5.1 platform with a native 12V-2x6 cable. Native delivery avoids an adapter-dependent GPU connection and the 1200 W capacity preserves headroom for a flagship graphics card, transient demand, fans, pumps, and future cooling hardware. Super Flower lists the 1200 W unit at 125 mm long with Cybenetics Platinum certification.

### Chassis, airflow, and cooling

The white CORSAIR 9000D was selected for presentation, reverse-connector compatibility, and extensive fan/radiator flexibility. CORSAIR documents front and top support for eight 120 mm fans and up to 480 mm radiators, plus side and rear mounting options.

The planned front intake bank uses eight reverse-blade CORSAIR LX120-R fans so the clean side of the fan remains visible inside the case while air enters through the front. Final exhaust placement will be recorded from the installed configuration rather than inferred from the chassis maximum.

A white Montech NX400 air cooler supports the initial commissioning phase. It is a deliberate temporary component that lets the system be assembled and validated while the client evaluates the final cooling architecture. A future matching AIO or full CPU-and-GPU custom loop remains a client decision, not a completed feature.

## Implementation and commissioning

The project is being delivered in stages:

1. reconcile the physical components against the build record;
2. assemble the rear-connector platform and route power without stressing the native GPU cable;
3. establish safe initial cooling with the NX400;
4. install Windows 11 Pro from Rufus-created media;
5. install current platform, graphics, and peripheral drivers;
6. configure firmware and memory settings supported by the actual installed kit;
7. validate stability, temperatures, and gaming behavior under controlled loads;
8. integrate the PC with the client's racing-simulator environment;
9. finalize the long-term cooling and fan configuration with the client.

Third-party Windows provisioning tools may support deployment, but they are not authored as part of this project and no uninspected script behavior is presented as an optimization.

## Engineering decisions

### Staged delivery reduces decision pressure

The temporary cooler decouples a functional system build from a significant aesthetic and cost decision. It enables early firmware, driver, and component validation while preserving the client's choice of final cooling approach.

### Compatibility is a system property

The motherboard, chassis, power supply, graphics tier, cooling hardware, fans, storage, and simulator connections were evaluated as an interacting system. The 9000D's reverse-connector support and the PSU's native 12V-2x6 connection directly reinforce the visual and electrical requirements.

### Theoretical capacity is not the installed design

The 9000D can accommodate extreme fan and radiator configurations, but the finished portfolio record will describe the physical build. Chassis maximums are useful for design headroom; they are not evidence of installed radiators, pumps, or fans.

## Validation plan

Final validation will record:

- firmware revision, driver state, and recognized component inventory;
- memory profile and stability checks appropriate to the installed kit;
- HWiNFO64 sensor data at idle and under sustained gaming/load conditions;
- CPU and GPU temperatures, clock behavior, and power observations;
- CPU and GPU benchmark runs used comparatively rather than as isolated marketing numbers;
- frame-time and 4K performance evidence from the racing-simulator workload;
- post-integration checks for controls, display behavior, audio, networking, and sleep/restart reliability.

No benchmark or thermal result is published until retained evidence is available.

## Current result

The confirmed architecture pairs a gaming-specialized AMD platform, RTX 5090-class graphics, native modern power delivery, high-performance NVMe storage, a reverse-connector white presentation, and a chassis with enough thermal flexibility to support the client's eventual cooling decision. The case study will be completed after final configuration, simulator integration, and evidence capture.

## Evolution

- Confirm the exact GPU, memory kit, display, and simulator hardware from physical evidence.
- Record the installed fan map and airflow direction after assembly.
- Complete thermal and stability validation before selecting final cooling.
- Evaluate a matching AIO against the cost, maintenance, acoustic, and presentation goals of a full custom CPU/GPU loop.
- If a custom loop is approved, design radiator and pump/reservoir placement from measured clearances rather than maximum chassis specifications.

<!-- MEDIA TODO:
Add a full-system hero photo after final commissioning.
Recommended framing: three-quarter view with neutral lighting, clean background, and no client-identifying surroundings.
-->

<!-- MEDIA TODO:
Add a straight-on interior photo showing the rear-connector presentation and fan layout.
Recommended framing: system powered down or safely lit; exclude serial-number labels and identifying reflections.
-->

<!-- MEDIA TODO:
Add a wide photo of the PC integrated with the racing-simulator environment.
Recommended framing: show the relationship between computer, display, and cockpit without implying responsibility for unselected peripherals or exposing client information.
-->

<!-- MEDIA TODO:
Add a sanitized thermal and benchmark evidence panel.
Recommended framing: show tool version, test name, duration, and relevant sensors; remove usernames, device serials, and unsupported comparison claims.
-->

<!-- MEDIA TODO:
If implemented, add a later custom-loop update with build photos and final validation.
Recommended framing: document actual routing, components, leak testing, and thermal evidence; do not present the concept as completed before installation.
-->

## Confirmed technologies and hardware

- AMD Ryzen 7 9800X3D
- GIGABYTE B850 AORUS STEALTH ICE
- RTX 5090-class premium white graphics card
- Samsung 990 PRO 2 TB
- Super Flower LEADEX VIII Platinum PRO 1200 W, white
- CORSAIR 9000D RGB AIRFLOW, white
- CORSAIR LX / LX-R fan ecosystem
- Montech NX400 temporary commissioning cooler, white
- Windows 11 Pro deployment target
- Rufus installation media

## Selected references

- [AMD Ryzen 7 9800X3D specifications](https://www.amd.com/en/products/processors/desktops/ryzen/9000-series/amd-ryzen-7-9800x3d.html)
- [GIGABYTE B850 AORUS STEALTH ICE specifications](https://www.gigabyte.com/us/Motherboard/B850-AORUS-STEALTH-ICE-rev-10/sp)
- [Samsung 990 PRO 2 TB](https://www.samsung.com/us/memory-storage/nvme-ssd/990-pro-pcie-4-0-nvme-ssd-1tb-sku-mz-v9p2t0b-am/)
- [Super Flower LEADEX VIII Platinum PRO](https://www.super-flower.com.tw/products-detail/LVIII-P-PRO/)
- [CORSAIR 9000D specifications](https://www.corsair.com/us/en/p/pc-cases/cc-9011273-ww/9000d-rgb-airflow-super-full-tower-pc-case-cc-9011273-ww)
- [CORSAIR 9000D fan and radiator compatibility](https://www.corsair.com/us/en/explorer/diy-builder/cases/9000d-fan-and-radiator-compatibility/)
- [Rufus bootable USB documentation](https://rufus.ie/en/)
