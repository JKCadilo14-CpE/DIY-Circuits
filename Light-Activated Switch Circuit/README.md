# Light-Activated Switch Circuit

## Overview

This project contains a photodiode-controlled transistor circuit with an LED output.

## Project Information

| Item | Details |
| --- | --- |
| Status | Educational prototype |
| Difficulty | Beginner |
| KiCad project file | [`Light-Activated Switch.kicad_pro`](<Light-Activated Switch.kicad_pro>) |
| Hardware tested | To be verified |
| Manufacturing release | Not yet prepared |

## Project Gallery

Images will be added in Phase 3.

## Repository Navigation

This project is part of the DIY-Circuits collection.

- [Return to the repository overview](../README.md).
- Open the project by opening the `.kicad_pro` file in KiCad.
- The KiCad project, schematic, and PCB files are the authoritative design files.

## Circuit purpose

The photodiode input and BC547 transistor stage are intended to change the LED output in response to light. The exact switching behavior is To be verified.

## Estimated difficulty

Beginner.

## KiCad source files

- `Light-Activated Switch.kicad_pro`
- `Light-Activated Switch.kicad_sch`
- `Light-Activated Switch.kicad_pcb`

## Operating principle

The photodiode provides a light-dependent input to the BC547 transistor. R2 establishes a bias path, while R1 is placed in the LED path.

## Main components

- D1: photodiode; D2: LED.
- Q1: BC547 transistor.
- R1: 420 ohms; R2: 10K ohms.

## Supply voltage

To be verified. The source does not record a numeric supply voltage, LED current target, or connector polarity.

## Files included

The folder includes the KiCad project, schematic, PCB, a B.Cu PDF plot export, and a B.Paste PDF plot export. A BOM is not included.

## Build and test notes

Confirm the photodiode and LED orientations before power-up. The light level that changes the output is To be verified.

## Safety notes

Use a low-voltage supply only and avoid testing the sensor with high-intensity light sources unless their safety is understood.

## Known limitations

No ambient-light threshold, response-time measurement, or supply-current result is documented.

## Future improvements

- Add schematic and PCB screenshots that identify the photodiode and LED paths.
- Add photodiode, LED, and input-polarity silkscreen labels.
- Add test points for checking the sensor bias and LED output.
- Document light-level tests and the expected switching behavior.

## Learning Objectives

After studying this project, readers should understand:

- How a photodiode can provide a light-dependent input signal.
- How transistor bias and LED current limiting appear in a basic light-control circuit.

## Common Beginner Mistakes

- Reversing the photodiode or LED polarity.
- Using an incorrect LED-series resistor.
- Expecting identical behavior under different ambient-light conditions.

## License

MIT - see the repository [LICENSE](../LICENSE).
