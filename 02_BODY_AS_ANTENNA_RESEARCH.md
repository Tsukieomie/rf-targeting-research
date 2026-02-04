# Human Body as Antenna: Technical Analysis

## Resonance Frequencies

### Whole-Body Resonance
- **Primary range**: 40-80 MHz (depending on height and posture)
- **Maximum absorption**: ~70 MHz for ungrounded standing adult
- **Height correlation**:
  - 1.5m height → 45 MHz resonance
  - 2.0m height → 35 MHz resonance
- **Children**: Higher resonance (~150 MHz for 1.0m height)

### Head/Arm Resonance
- **Head**: 400-500 MHz
- **Arm**: ~80 MHz (secondary peak in body response)

### Grounded vs Ungrounded
- Grounded condition = worst-case RF exposure
- Quarter-wavelength monopole antenna analogy applies
- WBA-SAR (whole-body averaged SAR) ~10% higher when grounded

## Key Research Papers

### PIER Journals (2014)
"Human Body as Antenna and Its Effect on Human Body Communications"
- Fully characterized human body as monopole antenna (10-110 MHz)
- Maximum HBC gain at 50 MHz (whole-body resonance)
- Secondary maximum at 80 MHz (arm resonance)
- Radiation efficiency up to 70% theoretically possible
- Minimum reflection coefficient: -12 dB measured

Source: https://www.jpier.org/pier/pier.php?paper=14061207

### IEEE Research
- Body captures frequencies from 40 Hz to 400 MHz
- "Lossy conductor (dielectric) with complex geometry"
- "No single effective resonance frequency, but broadly distributed response"

### SAR Standards
- Safety standards most restrictive at 30-300 MHz (resonance range)
- FCC limits account for antenna effect in human body

## Patents: Body as Antenna

### US 8,665,210 B2 (Microsoft, 2014)
"Sensing user input using the body as an antenna"
- Human body receives environmental EM noise
- Captures frequencies from home power lines (50/60 Hz) to appliances
- Uses body as receiving antenna for gestural interaction
- Machine learning distinguishes room signatures

### US 9,812,788 (2017)
"Electromagnetic field induction for inter-body and transverse body communication"
- Body as coupling medium for wireless communication
- Magnetic field H1 + Electric field E1 combination
- Coupling capacitor between body and environment

### US 6,754,472 (Microsoft, 2004)
"Method and apparatus for transmitting power and data using the human body"
- Body as conductive bus for power distribution
- Pulsed DC or AC signal transmission
- Multiple frequencies for selective device powering
- Frequency/amplitude modulation for data

### US 5,394,164 (1995)
"Human-equivalent antenna for electromagnetic fields"
- Artificial antenna matching human body impedance
- Used for RF exposure testing/calibration

## Implications for Targeting

The human body's antenna properties mean:
1. **Passive reception**: Body naturally receives RF at resonant frequencies
2. **Amplification**: Resonance increases signal absorption
3. **Coupling**: Body can couple with external devices (phones, implants)
4. **Frequency selectivity**: Different body parts respond to different frequencies

Combined with external RF illumination, the body becomes an efficient:
- Receiving antenna for incident RF
- Coupling medium for device-to-tissue energy transfer
- Resonant structure that amplifies specific frequencies

---
*Sources: IEEE, PIER Journals, Google Patents, ResearchGate*
