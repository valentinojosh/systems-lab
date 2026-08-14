# Hardware Repair & Upgrades

Hands-on repair and upgrade work across mobile devices, Mac hardware, laptops, and desktop PCs. The common discipline is controlled disassembly, correct part identification, compatibility planning, data protection, careful reassembly, and functional validation—not unsupported board-level repair claims.

## Repair workflow

1. Confirm the reported symptom and reproduce it when safe.
2. Identify the exact device, model/revision, installed components, and data risk.
3. Determine whether the likely remedy is a replaceable assembly, storage migration, firmware/driver change, or specialist escalation.
4. Back up or preserve accessible data before invasive work.
5. Verify part compatibility and prepare model-appropriate tools, adhesives, and replacement materials.
6. Disassemble methodically, tracking fasteners, cable routing, shields, and connector orientation.
7. Inspect for related damage before installing the replacement.
8. Reassemble carefully, restoring routing, shields, fasteners, and enclosure fit.
9. Test the repaired subsystem and adjacent functions that may have been disturbed during disassembly.
10. Validate charging/power, thermals, storage, networking, audio, cameras, display, input, sleep/restart, or workload behavior as relevant.

## Mobile-device repair

Experience spans multiple iPhone generations from approximately the iPhone 6 era through current devices, including:

- battery replacement;
- screen/display replacement;
- camera-lens repair;
- model-specific disassembly and reassembly;
- post-repair checks for display/touch, cameras, charging, buttons, audio, and enclosure fit.

Modern mobile repair is sensitive to fragile flex cables, adhesive sealing, battery handling, paired components, and model-specific calibration behavior. Successful physical replacement is followed by subsystem and adjacent-function verification rather than assumed from power-on.

## 2015 MacBook Pro repair and platform extension

Work on a 2015 MacBook Pro included:

- speaker repair/replacement;
- battery replacement;
- SSD upgrade;
- third-party SSD compatibility work;
- Boot Camp dual-boot Windows/macOS operation before a dedicated Windows PC was available.

The storage upgrade required attention to Apple platform firmware and third-party SSD compatibility. The detailed historical mechanism is withheld until it can be verified against the exact Mac model, OS version, and storage hardware; the confirmed work remains a successful storage upgrade and compatibility-focused migration.

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

Storage replacement crosses hardware and data-recovery concerns. The process distinguishes:

- a healthy source suitable for cloning;
- an unstable source that should be imaged with recovery-focused tooling;
- a new system that benefits from fresh OS installation;
- a capacity migration that must preserve a working data set;
- a boot conflict that requires separating disks before repair.

See [Storage Recovery & Cross-Platform Diagnostics](../projects/storage-recovery/README.md) for the source-preserving recovery model and [Windows Deployment & Provisioning](windows-deployment.md) for the current fresh-install preference.

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
