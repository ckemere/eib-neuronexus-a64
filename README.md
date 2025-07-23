# EIB for Neuronexus A64 probes

- 64 electrodes
- Power ground (GND) and amplifier reference (REF) exposed via 2.54mm header
- Compatible with
  [headstage-64](https://github.com/open-ephys/onix-headstage-64) Rev. 1.3 and 1.3B, [headstage-64s](https://github.com/open-ephys/onix-headstage-64s), and the [low-profile headstage](https://open-ephys.org/acquisition-system/low-profile-spi-headstage-64ch). 

# Notes about this fork:
This repository is a fork of https://github.com/open-ephys/eib-neuronexus-a64. 
I've replaced the through-hole connector from
that design with a SMD connector (i.e., FOLC-110-02-S-Q-P). While this makes
alignment of the two connectors much more challenging, it allows for
fabrication with a standard 2-layer PCB process with 6 mil trace/space.
