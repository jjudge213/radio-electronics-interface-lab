# Radio Electronics Interface Lab

Public-safe project collection for radio interfaces, cable work, SDR/RF, and electronics bench projects.

## Purpose

This repo collects the physical and electrical layer work that supports the radio and TAK projects: connectors, soldering, SDR/RF work, embedded electronics, and bench-level interface development.

## Key Results

- Modified a Motorola XTS serial cable to expose speaker, microphone, and PTT lines while preserving serial-cable functionality.
- Built a custom EFJohnson 5300 interface cable from a handmic connector using reference documentation, connector inspection, and bench verification.
- Developed a Motorola XTVA audio/PTT breakout path using DB25 breakout wiring, breadboard work, and PCB-side inspection.
- Captured HackRF waterfall/sweep observations of DJI Mavic Air 2 / RC-N1 link-state changes at the spectrum level.
- Built and fit early UHF/EFJohnson manpack hardware concepts, including frame, antenna/power panel, and carry-system fitment.

## Resume Bullets

- Fabricated and modified radio interface cabling for Motorola, EFJohnson, and related P25 radio workflows, including audio/PTT and accessory-interface paths.
- Modified a Motorola XTS serial cable to expose microphone, speaker, and PTT lines while preserving original serial-cable functionality.
- Built an EFJohnson 5300 interface cable using reference documentation, connector inspection, and bench-level fabrication practices.
- Developed Motorola XTVA audio/PTT interface concepts using DB25 breakout wiring, breadboard validation, and microscope inspection of the PCB-side interface.
- Used HackRF spectrum/waterfall observation to document DJI Mavic Air 2 / RC-N1 RF link-state changes while clearly limiting claims to spectrum-level behavior.

## Interface / RF / Bench Map

```mermaid
flowchart TD
    radio[Radio platforms] --> cable[Cable and connector work]
    cable --> audio[Audio / PTT / accessory interfaces]
    audio --> bench[Breadboard and microscope bench work]
    radio --> manpack[Manpack frame and panel development]
    rf[SDR/RF tools] --> sweep[HackRF spectrum observation]
    sweep --> notes[Bounded RF findings<br/>no decoded protocol claims]
```

## Project Sections

### Cables and Interfaces

Connector parts, soldering, and closeups show the hands-on interface fabrication work behind the radio projects.

#### Motorola XTS Cable Modifications

This section documents modification of a Motorola XTS serial cable to expose microphone, speaker, and PTT lines while maintaining serial cable functionality.

<img src="assets/connector-parts-2024-09-13-01.jpg" alt="Motorola XTS cable modification connector parts, 2024-09-13" width="48%"> <img src="assets/connector-parts-2024-09-13-02.jpg" alt="Motorola XTS cable modification connector parts alternate angle, 2024-09-13" width="48%">

<img src="assets/connector-parts-2024-09-13-03.jpg" alt="Motorola XTS cable modification connector parts detail, 2024-09-13" width="48%"> <img src="assets/connector-parts-2024-09-13-04.jpg" alt="Motorola XTS cable modification connector parts kit, 2024-09-13" width="48%">

<img src="assets/connector-soldering-2024-09-14-01.jpg" alt="Motorola XTS cable modification soldering, 2024-09-14" width="48%"> <img src="assets/connector-soldering-2024-09-14-02.jpg" alt="Motorola XTS cable modification soldering alternate angle, 2024-09-14" width="48%">

<img src="assets/connector-soldering-2024-09-14-03.jpg" alt="Motorola XTS cable modification wire preparation, 2024-09-14" width="48%"> <img src="assets/connector-soldering-2024-09-14-04.jpg" alt="Motorola XTS cable modification connector assembly, 2024-09-14" width="48%">

<img src="assets/connector-soldering-2024-09-14-05.jpg" alt="Motorola XTS cable modification completed soldering, 2024-09-14" width="48%">

#### EFJohnson 5300 Interface Cable

This custom interface cable was built for the EFJohnson 5300 series radio using a handmic connector sourced from DigiKey. The public write-up is limited to fabrication, connector inspection, and bench-verification workflow; manufacturer manual pages, proprietary pinout tables, key material, and programming details are not reproduced.

<img src="assets/custom-radio-connector-closeup-2024-09-24-01.jpg" alt="Custom radio connector closeup, 2024-09-24" width="48%"> <img src="assets/custom-radio-connector-closeup-2024-09-24-02.jpg" alt="Custom radio connector closeup alternate angle, 2024-09-24" width="48%">

<img src="assets/custom-radio-interface-cable-2024-09-24-01.jpg" alt="EFJohnson 5300 custom interface cable build, 2024-09-24" width="48%"> <img src="assets/custom-radio-interface-cable-2024-09-24-02.jpg" alt="EFJohnson 5300 custom interface cable completed lead, 2024-09-24" width="48%">

<img src="assets/efjohnson-5300-interface-display-2024-09-24-01.gif" alt="EFJohnson 5300 interface display workflow, 2024-09-24" width="48%">

### UHF Manpack Development

This section follows a UHF/EFJohnson manpack development path: a plastic 3D-printed frame, side support geometry, a panel concept for antenna mounting and power-switch access, and fitment of the radio package into an Osprey backpack-style carry setup.

<img src="assets/uhf-manpack-3d-printed-frame-2024-10-03-01.jpg" alt="UHF manpack 3D-printed frame, 2024-10-03" width="48%"> <img src="assets/uhf-manpack-3d-printed-frame-2024-10-03-02.jpg" alt="UHF manpack 3D-printed frame alternate angle, 2024-10-03" width="48%">

<img src="assets/uhf-manpack-antenna-power-panel-2024-10-03-01.jpg" alt="UHF manpack antenna and power-switch panel concept, 2024-10-03" width="48%"> <img src="assets/uhf-manpack-antenna-power-panel-2024-10-03-02.jpg" alt="UHF manpack panel and frame detail, 2024-10-03" width="48%">

<img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-01.jpg" alt="EFJohnson manpack Osprey bag fitment, 2025-04-28" width="48%"> <img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-02.jpg" alt="EFJohnson manpack Osprey bag wiring and speaker context, 2025-04-28" width="48%">

<img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-03.jpg" alt="EFJohnson manpack Osprey bag connected fitment, 2025-04-28" width="48%"> <img src="assets/efjohnson-manpack-osprey-fitment-2025-04-28-04.jpg" alt="EFJohnson manpack Osprey bag assembled fitment, 2025-04-28" width="48%">

<img src="assets/efjohnson-manpack-radio-closeup-redacted-2025-04-28-01.jpg" alt="Redacted EFJohnson manpack radio close-up with antenna and frame detail, 2025-04-28" width="48%"> <img src="assets/efjohnson-manpack-front-fitment-2025-04-28-01.jpg" alt="EFJohnson manpack front fitment in Osprey bag, 2025-04-28" width="48%">

### SDR/RF

HackRF spectrum captures and aviation-tracking work provide RF context without presenting this as formal test-lab coverage.

#### DJI Mavic Air 2 / RC-N1 Spectrum Observation

HackRF sweep waterfall captures document SDR observation work in the DJI Mavic Air 2 / RC-N1 controller operating bands. The public `hackrf_sweep` workflow was used to sweep the 2.4 GHz and 5 GHz controller frequency ranges while the controller and aircraft moved through visible operating states.

The supporting images show repeatable RF emission pattern changes between controller-only, aircraft-on, and linked controller/aircraft communication states. The takeaway is intentionally narrow: the DJI link presents distinct RF signatures across operating states at the spectrum/waterfall level. This is not decoded protocol traffic, packet attribution, Remote ID analysis, or proof of command/video/telemetry contents.

<img src="assets/hackrf-sweep-mavic-air-2-2024-09-14-01.jpg" alt="HackRF sweep Mavic Air 2 2.4 GHz and 5 GHz spectrum observation, 2024-09-14" width="48%"> <img src="assets/hackrf-sweep-mavic-air-2-2024-09-14-02.jpg" alt="HackRF sweep Mavic Air 2 alternate spectrum observation, 2024-09-14" width="48%">

<img src="assets/mavic-air-2-5ghz-spectrum-2024-09-15-01.jpg" alt="Mavic Air 2 5 GHz spectrum waterfall observation, 2024-09-15" width="48%">

### Embedded Electronics

PCB inspection, breadboard work, and teardown photos cover the electronics bench work behind the interface projects.

#### Custom Audio/PTT Interface Development

Breadboard, bench-note, and microscope images document custom audio/PTT interface development for Motorola XTVA integration. A DB25 breakout connector connects to the Motorola XTVA and exposes speaker, microphone, and PTT lines for bench testing and interface development. The microscope images show the PCB side of the same audio/PTT interface, including close inspection of signal labels and small board features.

<img src="assets/arduino-breadboard-electronics-notes-2022-10-16-01.jpg" alt="Arduino breadboard audio and PTT interface development notes, 2022-10-16" width="48%"> <img src="assets/arduino-breadboard-electronics-notes-2022-10-16-02.jpg" alt="Breadboard interface development notes and wiring, 2022-10-16" width="48%">

<img src="assets/microscope-pcb-electronics-inspection-setup-2022-10-30-01.jpg" alt="Microscope view of the PCB side of the audio/PTT interface, 2022-10-30" width="48%"> <img src="assets/microscope-pcb-electronics-inspection-setup-2022-10-30-02.jpg" alt="Microscope close-up of audio/PTT interface PCB signal labels, 2022-10-30" width="48%">

## Current Media

- Active media assets: 46
- JPG stills: 44
- Animated GIFs: 2
- Source posture: public-safe derivatives only; source material and sensitive details remain out of scope.

## Review Docs

- [Evidence gallery](docs/evidence-gallery.md)
- [Evidence manifest](evidence-manifest.md)
- [Sanitization notes](docs/sanitization-notes.md)
