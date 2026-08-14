# Hardware Repair & Upgrades

Hands-on repair and upgrade work across mobile devices, Mac hardware, laptops, and desktop PCs. The method combines controlled disassembly, part identification, compatibility planning, data protection, reassembly, and functional validation—not unsupported board-level claims.

## Repair workflow

1. Confirm the symptom, device revision, installed components, and data risk.
2. Decide whether the remedy is assembly replacement, migration, firmware/driver work, or specialist escalation.
3. Preserve accessible data, verify part compatibility, and prepare model-appropriate tools.
4. Disassemble methodically, tracking fasteners, routing, shields, and connector orientation.
5. Inspect for related damage, install the replacement, and reassemble.
6. Test the affected and adjacent functions under the device's normal workload.

## Mobile-device repair

Experience spans multiple iPhone generations from approximately the iPhone 6 era through current devices, including:

- battery replacement;
- screen/display replacement;
- camera-lens repair;
- model-specific disassembly and reassembly;
- post-repair checks for display/touch, cameras, charging, buttons, audio, and enclosure fit.

This work accounts for fragile flex cables, adhesive sealing, battery handling, paired components, and model-specific calibration. A successful replacement is verified functionally rather than inferred from power-on.

## 2015 MacBook Pro repair and platform extension

Work on a 2015 MacBook Pro included:

- speaker repair/replacement;
- battery replacement;
- SSD upgrade;
- third-party SSD compatibility work;
- Boot Camp dual-boot Windows/macOS operation before a dedicated Windows PC was available.

The storage upgrade required Apple firmware and third-party SSD compatibility work. The detailed mechanism is withheld until reconciled with the exact Mac model, OS version, and storage hardware; the confirmed result is a successful compatibility-focused migration.

## Laptop and desktop work

- laptop component repair and upgrades;
- HDD/SSD replacement and capacity upgrades;
- disk cloning and data migration;
- desktop GPU swaps;
- graphics-driver cleanup and reinstall with DDU when warranted;
- BIOS/UEFI and firmware troubleshooting;
- Windows recovery after hardware change;
- cable, seating, power, thermal, and peripheral checks;
- post-change stability and workload validation.

## Storage upgrades and migration

For storage replacement, I distinguish:

- a healthy source suitable for cloning;
- an unstable source that should be imaged with recovery-focused tooling;
- a new system that benefits from fresh OS installation;
- a capacity migration that must preserve a working data set;
- a boot conflict that requires separating disks before repair.

See [Storage Recovery & Cross-Platform Diagnostics](../projects/storage-recovery/README.md) for source preservation and [Windows Deployment & Provisioning](windows-deployment.md) for the current fresh-install preference.

## Validation by repair class

| Repair class | Representative validation |
| --- | --- |
| Battery/power | Charge detection, discharge behavior, sleep/wake, restart, thermal observation, enclosure fit |
| Display/touch | Uniform image, brightness, touch across the panel, camera/sensor behavior, connector stability |
| Camera/lens | Focus, image clarity, switching modes/cameras, flash where applicable, physical seal/fit |
| Storage | Device identity, health data, capacity, filesystem, boot, representative file checks, sustained copy |
| GPU/driver | Device detection, clean driver state, display outputs, controlled load, thermals, target applications |
| Firmware/BIOS | Settings retention, device enumeration, boot order, restart/cold boot, workload behavior |
| Laptop/desktop assembly | Fans, ports, audio, network, input, sleep, restart, temperatures, and system-specific workload |

## Scope boundaries

This portfolio documents component and assembly-level repair, upgrades, configuration, migration, and validation. It does not claim microsoldering, board-level electronics repair, mechanical-drive hardware repair, Apple-certified service, or authorship of third-party tools.

## Evolution

- Maintain model-specific intake and validation checklists for recurring repair types.
- Record part source, compatibility evidence, and pre/post condition without retaining client identifiers.
- Add battery and storage health evidence when the platform exposes reliable metrics.
- Define clear escalation criteria for swollen batteries, liquid damage, board faults, physically failing disks, and irreplaceable data.
- Capture new repair evidence prospectively rather than recreating unavailable historical photos.
