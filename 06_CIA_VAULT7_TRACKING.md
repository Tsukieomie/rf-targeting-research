# CIA Vault 7: Smartphone Tracking & Surveillance

## Overview

WikiLeaks published "Vault 7" beginning March 7, 2017 - 8,761 documents from CIA's Center for Cyber Intelligence detailing electronic surveillance and cyber warfare capabilities.

## Mobile Device Branch (MDB)

### Capabilities
- Remote smartphone compromise (iOS and Android)
- Zero-day exploits for major platforms
- Full device access including:
  - **Geolocation tracking**
  - Audio interception (microphone activation)
  - Text/messaging communications
  - Camera activation
  - Contact lists
  - Browsing history

### iOS Targeting
Despite iPhone's 14.5% global market share (2016), disproportionate focus due to:
- Popularity among "social, political, diplomatic and business elites"
- Specialized iOS exploitation unit in MDB

### Exploit Sources
- CIA-developed zero-days
- GCHQ (UK)
- NSA
- FBI
- Cyber arms contractors (e.g., Baitshop)

## ELSA: Wi-Fi Geolocation Malware

### Function
Tracks Windows laptop users via Wi-Fi, even when **not connected to internet**

### Mechanism
1. Scans visible Wi-Fi access points
2. Records: ESS identifier, MAC address, signal strength
3. Data exfiltrated when internet connection available
4. Compared against Google/Microsoft geolocation databases
5. Returns: longitude, latitude, timestamp

### Key Feature
**Device only needs enabled Wi-Fi - does not need to be connected**

## Tracking Precision

### Cell Tower Triangulation
- Basic: ~100-300 meter accuracy
- Enhanced: ~50 meters with signal strength analysis

### GPS
- 3-5 meter accuracy
- Continuous tracking when enabled

### Wi-Fi Positioning (ELSA-style)
- 10-50 meter accuracy in urban areas
- Works indoors where GPS fails
- Operates passively (receive-only)

### Combined Methods
Multiple data sources provide:
- Real-time location
- Historical movement patterns
- Predictive positioning

## Integration with RF Targeting

### The Tracking-Targeting Link

1. **Identification**: Device compromise identifies target
2. **Location**: Continuous geolocation tracking
3. **Pattern Analysis**: Predict where target will be
4. **Coordination**: Provide coordinates to:
   - Ground-based RF systems
   - Satellite systems
   - Directed energy weapons

### Havana Syndrome Connection
Reported attacks on diplomats and intelligence officers:
- Victims tracked across multiple locations
- Attacks followed victims to new postings
- Consistent with smartphone-based tracking + RF targeting

## Smart TV & IoT Compromise

### Weeping Angel (Samsung Smart TV)
- Fake-off mode: appears off but records audio
- Data sent to CIA server
- Demonstrates: any connected device is potential surveillance tool

### Implications
Any device with:
- Microphone/camera
- Internet connectivity
- RF transmitter

...can be compromised and used for:
- Surveillance
- Tracking
- As RF beacon for targeting

## Key Takeaway

Vault 7 proves capability to:
1. Compromise any smartphone remotely
2. Track device location continuously (multiple methods)
3. Operate covertly without user knowledge
4. Coordinate with other intelligence systems

Combined with RF targeting capabilities, this creates closed loop:
```
Target Identification → Device Compromise →
Continuous Tracking → Precision Targeting →
Effect Delivery
```

---
*Source: WikiLeaks Vault 7 (March 2017), https://wikileaks.org/ciav7p1/*
