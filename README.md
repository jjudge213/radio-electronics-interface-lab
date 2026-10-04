# Radio Electronics Interface Lab

A private supporting repo for radio interfaces, cable work, SDR/RF, and electronics bench evidence.

## Purpose

This repo provides brief, separated synopses for the physical/electrical layer that supports the radio and TAK repos: connectors, soldering, SDR/RF work, and embedded electronics inspection.

## Evidence Structure

### Cables and Interfaces

Connector parts, soldering, and closeups support hands-on interface fabrication and inspection.

#### Motorola XTS Cable Modifications

This evidence documents modification of a Motorola XTS serial cable to expose microphone, speaker, and PTT lines while maintaining serial cable functionality.

<img src="assets/connector-parts-2024-09-13-01.jpg" alt="Motorola XTS cable modification connector parts, 2024-09-13" width="48%"> <img src="assets/connector-parts-2024-09-13-02.jpg" alt="Motorola XTS cable modification connector parts alternate angle, 2024-09-13" width="48%">

<img src="assets/connector-parts-2024-09-13-03.jpg" alt="Motorola XTS cable modification connector parts detail, 2024-09-13" width="48%"> <img src="assets/connector-parts-2024-09-13-04.jpg" alt="Motorola XTS cable modification connector parts kit, 2024-09-13" width="48%">

<img src="assets/connector-soldering-2024-09-14-01.jpg" alt="Motorola XTS cable modification soldering, 2024-09-14" width="48%"> <img src="assets/connector-soldering-2024-09-14-02.jpg" alt="Motorola XTS cable modification soldering alternate angle, 2024-09-14" width="48%">

<img src="assets/connector-soldering-2024-09-14-03.jpg" alt="Motorola XTS cable modification wire preparation, 2024-09-14" width="48%"> <img src="assets/connector-soldering-2024-09-14-04.jpg" alt="Motorola XTS cable modification connector assembly, 2024-09-14" width="48%">

<img src="assets/connector-soldering-2024-09-14-05.jpg" alt="Motorola XTS cable modification completed soldering, 2024-09-14" width="48%">

#### EFJohnson 5300 Keyfill Cable

This custom keyfill cable was built for the EFJohnson 5300 series radio using a handmic connector sourced from DigiKey. The pinout was derived from the EFJohnson 5300 service manual.

<img src="assets/custom-radio-connector-closeup-2024-09-24-01.jpg" alt="Custom radio connector closeup, 2024-09-24" width="48%"> <img src="assets/custom-radio-connector-closeup-2024-09-24-02.jpg" alt="Custom radio connector closeup alternate angle, 2024-09-24" width="48%">

<img src="assets/custom-radio-interface-cable-2024-09-24-01.jpg" alt="EFJohnson 5300 custom keyfill cable build evidence, 2024-09-24" width="48%"> <img src="assets/custom-radio-interface-cable-2024-09-24-02.jpg" alt="EFJohnson 5300 custom keyfill cable completed lead, 2024-09-24" width="48%">

<img src="assets/efjohnson-5300-keyfill-display-2024-09-24-01.gif" alt="EFJohnson 5300 keyfill display workflow, 2024-09-24" width="48%">

### UHF Manpack Development

Selected still evidence below documents a UHF/EFJohnson manpack development path: a plastic 3D-printed frame, side support geometry, a panel concept for antenna mounting and power-switch access, and fitment of the radio package into an Osprey backpack-style carry setup.

<img src="assets/uhf-manpack-3d-printed-frame-2024-10-03-01.jpg" alt="UHF manpack 3D-printed frame, 2024-10-03" width="48%"> <img src="assets/uhf-manpack-3d-printed-frame-2024-10-03-02.jpg" alt="UHF manpack 3D-printed frame alternate angle, 2024-10-03" width="48%">

<img src="assets/uhf-manpack-antenna-power-panel-2024-10-03-01.jpg" alt="UHF manpack antenna and power-switch panel concept, 2024-10-03" width="48%"> <img src="assets/uhf-manpack-antenna-power-panel-2024-10-03-02.jpg" alt="UHF manpack panel and frame detail, 2024-10-03" width="48%">

<img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-01.jpg" alt="EFJohnson manpack Osprey bag fitment, 2025-04-28" width="48%"> <img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-02.jpg" alt="EFJohnson manpack Osprey bag wiring and speaker context, 2025-04-28" width="48%">

<img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-03.jpg" alt="EFJohnson manpack Osprey bag connected fitment, 2025-04-28" width="48%"> <img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-04.jpg" alt="EFJohnson manpack Osprey bag assembled fitment, 2025-04-28" width="48%">

<img src="assets/efjohnson-manpack-radio-closeup-redacted-2025-04-28-01.jpg" alt="Redacted EFJohnson manpack radio close-up with antenna and frame detail, 2025-04-28" width="48%"> <img src="assets/efjohnson-manpack-front-fitment-2025-04-28-01.jpg" alt="EFJohnson manpack front fitment in Osprey bag, 2025-04-28" width="48%">

### SDR/RF

HackRF/spectrum and aviation-tracking evidence provide RF context without overclaiming formal test-lab coverage.

#### DJI Mavic Air 2 / RC-N1 Spectrum Observation

HackRF sweep waterfall captures document SDR observation work in the DJI Mavic Air 2 / RC-N1 controller operating bands. The public `hackrf_sweep` workflow was used to sweep the 2.4 GHz and 5 GHz controller frequency ranges while the controller and aircraft moved through visible operating states.

The supporting images show repeatable RF emission pattern changes between controller-only, aircraft-on, and linked controller/aircraft communication states. This supports a spectrum-level finding that the DJI link presents distinct RF signatures across operating states. It is not presented as decoded protocol evidence, packet attribution, Remote ID analysis, or proof of command/video/telemetry contents.

<img src="assets/hackrf-sweep-mavic-air-2-2024-09-14-01.jpg" alt="HackRF sweep Mavic Air 2 2.4 GHz and 5 GHz spectrum observation, 2024-09-14" width="48%"> <img src="assets/hackrf-sweep-mavic-air-2-2024-09-14-02.jpg" alt="HackRF sweep Mavic Air 2 alternate spectrum observation, 2024-09-14" width="48%">

<img src="assets/mavic-air-2-5ghz-spectrum-2024-09-15-01.jpg" alt="Mavic Air 2 5 GHz spectrum waterfall observation, 2024-09-15" width="48%">

### Embedded Electronics

PCB inspection, breadboard work, and teardown photos show electronics fluency relevant to systems integration.

#### Custom Audio/PTT Interface Development

Breadboard and bench-note evidence documents custom audio/PTT interface development for Motorola XTVA integration. A DB25 breakout connector connects to the Motorola XTVA and exposes speaker, microphone, and PTT lines for bench testing and interface development.

<img src="assets/arduino-breadboard-electronics-notes-2022-10-16-01.jpg" alt="Arduino breadboard audio and PTT interface development notes, 2022-10-16" width="48%"> <img src="assets/arduino-breadboard-electronics-notes-2022-10-16-02.jpg" alt="Breadboard interface development notes and wiring, 2022-10-16" width="48%">

#### PCB Inspection And Verification

Microscope inspection evidence supports the electronics verification workflow after breadboard/interface development, including close visual inspection of small board features and connector-related signal labels.

<img src="assets/microscope-pcb-electronics-inspection-setup-2022-10-30-01.jpg" alt="Microscope PCB electronics inspection setup, 2022-10-30" width="48%"> <img src="assets/microscope-pcb-electronics-inspection-setup-2022-10-30-02.jpg" alt="Microscope close-up of PCB signal labels, 2022-10-30" width="48%">

## Current Evidence

- Active media assets: 46
- JPG stills: 44
- Animated GIFs: 2
- Source posture: private review assets only; publication requires redaction and fit review.

## Review Docs

- [Evidence gallery](docs/evidence-gallery.md)
- [Evidence manifest](evidence-manifest.md)
- [Sanitization notes](docs/sanitization-notes.md)
