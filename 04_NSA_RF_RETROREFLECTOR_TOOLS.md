# NSA ANT Catalog: RF Retroreflector Technology

## Overview

In December 2013, Der Spiegel published leaked documents from the NSA's Tailored Access Operations (TAO) group, including a 2008 catalog of hardware and software "implants." The ANGRYNEIGHBOR family consists of RF retroreflector devices.

## ANGRYNEIGHBOR Family

### Core Principle
Devices that, when illuminated by external radar (continuous wave), modulate the reflected signal with locally gathered intelligence (audio, video, data, position).

### Illumination Sources
- **CTX4000**: Portable CW radar transmitter
- **PHOTOANGLO**: Follow-on system to CTX4000

## LOUDAUTO

### Purpose
Audio-based RF retro-reflector for room audio surveillance

### Capabilities
- Picks up speech at standard office volume from 20+ feet away
- Maximized microphone gain design
- Ultra-low power: ~15 μA at 3.0 VDC
- Battery self-discharge is greater concern than power draw
- All COTS components (non-attributable to NSA)

### Operation
1. Unit illuminated with CW signal from nearby radar
2. Illuminating signal is amplitude-modulated with audio (PPM square wave)
3. Modulated signal is re-radiated
4. Radar picks up and processes to recover room audio
5. Processing: FM demodulation (Rohde & Schwarz FSH-series spectrum analyzers)

### Historical Precedent: "The Thing" (1945)
Soviet passive resonator bug planted in US Ambassador's office
- No batteries or active electronics
- Activated by external RF illumination
- Operated undetected for 7 years

## TAWDRYYARD

### Purpose
Beacon RF retro-reflector for positional location

### Capabilities
- Detected within 50-foot radius of illuminating radar
- Ultra-low power: 8 μA at 2.5V (20 μW)
- Lithium coin cell powers for months/years
- Future: GPS coordinates, unique target identifier

### Use Case
Assists in locating deployed RAGEMASTER units

## RAGEMASTER

### Purpose
Video signal retroreflector
- Targets VGA cables
- Extracts video signal via RF emanations

## SURLYSPAWN

### Purpose
Keystroke logging retroreflector
- Captures keyboard input
- RF retro-reflects when illuminated

## Technical Implications

### The "Thing" Paradigm Applied to Modern Devices

If a purpose-built passive device can:
- Be remotely activated by RF illumination
- Modulate and re-radiate intelligence

Then any device with semiconductors (smartphones) could potentially:
- Act as passive retroreflector when illuminated
- Generate intermodulation products containing local information
- Re-radiate at harmonics and beat frequencies

### Key Insight from Bruce Schneier

"While the information we have about these sorts of tools is largely from the NSA, it is fanciful to assume that they are the only intelligence agency using this technology. And it's equally fanciful to assume that criminals won't be using this technology soon."

## Documentation Sources

- Bruce Schneier: https://www.schneier.com/blog/archives/2014/01/loudauto_nsa_ex.html
- Crypto Museum: https://www.cryptomuseum.com/covert/bugs/nsaant/loudauto/index.htm
- Der Spiegel (2013)

---
*Compiled from leaked NSA TAO documents, 2008 catalog*
