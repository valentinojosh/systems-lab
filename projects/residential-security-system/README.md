# Residential Security System Deployment

A self-deployed residential surveillance system combining a video doorbell and two exterior cameras with location-appropriate power, Wi-Fi integration, local recording, detection-zone configuration, and alert tuning. The project focuses on useful event capture and maintainable operation without publishing details that could weaken household security.

## Objective

Provide practical exterior awareness with local event retention while minimizing irrelevant clips and notifications. The deployment needed to adapt to different mounting locations, available power, Wi-Fi connectivity, weather exposure, and the trust boundary created by Internet-connected cameras.

## Environment and requirements

- one video doorbell and two additional exterior cameras;
- Wi-Fi connectivity across the camera deployment;
- a mix of solar and wired power selected by site constraints;
- local SD-card recording;
- configurable motion/object detection and detection regions;
- reduced false positives and unnecessary storage consumption;
- separation from trusted household computing devices.

## Implementation

### Placement and power planning

Each device was placed to serve a distinct exterior monitoring purpose. Power was selected per location: solar where cable routing and exposure supported it, and wired power where continuous supply was practical. This avoided forcing one installation method across three different physical contexts.

### Network integration

The camera setup uses Wi-Fi connectivity, and its devices are treated as less-trusted IoT endpoints. Their placement in the restricted side of the home network supports the broader goal that camera-class devices should not freely initiate communication with trusted workstations or the local media service.

### Local recording

Event footage is stored on device-local SD media. Local recording provides an on-premises retention path and reduces dependence on a continuously reachable remote service. Capacity and retention behavior are reviewed as operational settings rather than assumed from product marketing.

### Detection tuning

Detection regions, tolerance, sensitivity, and available object/motion classifications were adjusted to focus recording on useful events. Iterative tuning reduced irrelevant triggers—including unwanted animal activity—so storage and attention are directed toward meaningful captures.

## Engineering decisions

### Match power to the physical site

Mixed power sources trade a uniform bill of materials for better installation fit. Solar operation is useful where charging exposure and placement support it; wired power provides continuity where cabling is readily available.

### Tune for signal, not notification volume

Default sensitivity can produce excessive event noise. Region and classification tuning turns motion detection into an operationally useful system by reducing repeated low-value clips and preserving attention for relevant activity.

### Treat cameras as untrusted endpoints

Security devices can themselves expand a network's attack surface. Restricting their reach toward trusted clients applies a defense-in-depth boundary without interfering with their intended recording and alert functions.

## Security, privacy, and reliability

- Camera credentials, endpoints, serial numbers, and live network identifiers are excluded.
- Exact views, blind spots, detection regions, and retention settings are not published.
- Local recording reduces reliance on a remote storage path.
- IoT placement limits unnecessary reachability toward trusted systems.
- Firmware/update state should be reviewed periodically after the device models are confirmed.
- SD media health and successful event playback require recurring checks because the presence of a card does not prove recoverable recordings.

## Validation

The system was validated by triggering representative events, reviewing captured clips, and iterating on zones and sensitivity to reduce irrelevant recordings. Ongoing checks should confirm Wi-Fi stability, power/charging state, correct timestamps, available storage, event playback, and update status.

## Results

The deployment provides three coordinated residential security viewpoints with site-appropriate power and local recording. Detection tuning improved the usefulness of retained events while the network design keeps the camera class separated from trusted computing.

## Evolution

- Reconcile the exact models and supported update lifecycle from the physical devices.
- Document a private maintenance checklist for firmware, SD-card health, power, timestamps, and test events.
- Confirm that each device's required Internet access is no broader than necessary.
- Review retention capacity after real event volume is measured.
- Keep any future topology or coverage diagram private unless it can be generalized without exposing security-relevant detail.

<!-- MEDIA TODO:
Add one sanitized exterior hardware photo if it materially improves the case study.
Recommended framing: close view of a single installed device with house numbers, neighboring property, reflections, landmarks, camera view, and location metadata removed.
-->

## Technologies

- Wi-Fi-connected camera system
- Video doorbell and two exterior cameras
- Solar and wired power
- Local SD-card recording
- Motion/object detection
- Detection regions and sensitivity tuning
- Restricted IoT network placement
