# Korg Volca Mixer

## Features

### Must have

- 4x stereo 3.5mm TRS inputs
- Stereo 3.5mm TRS main output
- Fader pots on each channel
- External power supply

### Should have

- Main output on 2x balanced 6mm TRS

### Could have

- Aux bus/output
- Output fader
- Battery power

### Won't have

- Pan/balance controls
- Input meters
- Output meter
- EQ

## Power supply

9V, center positive via EIAJ-03 (4.75mm OD, 1.7mm ID plug)

Each Volca draws at most 100mA (<https://myvolts.com/blog/power-korg-volca/>) leaving 600mA free on the 1A power supply

## Inputs

The Volca Bass has a measured max output of approx. 1Vrms or +2dBu and an output impedance of 1k.

On the Soundcraft EPM, mono line input impedance is >11k and stereo is >>36k. Mic input impedance is ~2k. Max line input level is +30dBu.

Target input impedance between 10k and 100k and max level at least +10dBu.

## Output

Soundcraft EPM specifies line output impedance of 75R and max level of +20dBu.

Target output impedance 100R and max level at least +10dBu.

## Frequency response

Soundcraft EPM is specified as 20Hz to 20kHz +/-0.5dB but that's excessive for this application.

Target 40Hz to 8kHz +/-1dB and 20Hz to 20kHz +/-10dB seems sufficient.

## Reference

0dBu ~ 0.7746 Vrms (pro level = +4dBu = 1.228 Vrms)

0dBV = 1 Vrms (consumer level = -10dBV = 0.316 Vrms)

Voltage decibel scales use a factor of 20, not 10.
