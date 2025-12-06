# analog-boost-converter-ltspice
Fully analog boost converter designed and simulated in LTspice using discrete components only. Achieves stable regulated output across varying input voltages with ~15 mV ripple and fast settling time.
# Analog Boost Converter (LTspice)

This repository contains the design and LTspice simulation of a fully analog DC–DC boost converter implemented without using any controller IC.

## Design Objectives
- Use only fundamental discrete components (transistors, resistors, capacitors, diodes)
- Maintain a stable regulated output voltage under varying input voltages
- Achieve low output voltage ripple
- Fast transient response and settling time

## Design Details
- Control and switching behavior implemented using discrete transistor-based circuitry
- Feedback mechanism ensures output voltage regulation without a dedicated controller IC
- The design was tested with several input voltage levels while maintaining a stable output

## Performance (Simulation Results)
- Output voltage ripple: ~15 mV peak-to-peak  
- Settling time: ~550 µs to reach steady-state  
- Stable operation across multiple input voltage conditions

## Verification
All performance characteristics were verified using LTspice simulation.

## Tools Used
- LTspice

## Author
Milan Galahitiyawa
