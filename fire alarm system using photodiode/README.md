# Fire Alarm System Using Photodiode

## Overview

This project contains a photodiode-input alarm circuit with a buzzer and LED output.

## Project Information

| Item | Details |
| --- | --- |
| Status | Educational prototype |
| Difficulty | Intermediate |
| KiCad project file | [`fire alarm system using photodiode.kicad_pro`](<fire alarm system using photodiode.kicad_pro>) |
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

The schematic uses a photodiode, BC547 transistor, buzzer, and LED for an optical-input alarm concept. The use as a fire alarm is based on the project title and should be verified.

## Estimated difficulty

Intermediate.

## KiCad source files

- `fire alarm system using photodiode.kicad_pro`
- `fire alarm system using photodiode.kicad_sch`
- `fire alarm system using photodiode.kicad_pcb`

## Operating principle

The photodiode input influences a BC547 transistor stage. The stage is connected to the LED and buzzer outputs, providing an optical-condition indication and audible alert path.

## Main components

- D2: photodiode; D1: LED.
- Q1: BC547 transistor; BZ1: buzzer.
- R1: labeled `510 - 1k ohms` in the schematic.

## Supply voltage

To be verified. The schematic does not provide a numeric supply value, input polarity, or buzzer voltage rating.

## Files included

The folder includes the KiCad project, schematic, PCB, and one B.Cu PDF plot export. A BOM is not included.

## Build and test notes

Confirm photodiode orientation, buzzer rating, and the final R1 value before assembly. A tested optical trigger procedure is To be verified.

## Safety notes

This is not documented as a certified fire-safety device. Do not rely on it for life-safety or property-protection functions.

## Known limitations

The sensor response, alarm threshold, illumination conditions, and final resistor selection are not documented.

## Future improvements

- Add schematic and PCB screenshots that identify the photodiode and alarm outputs.
- Add clear silkscreen labels for the photodiode, buzzer, and input connector.
- Add test points for the sensor and transistor output nodes.
- Document the final R1 selection and an optical-trigger test procedure.

## Learning Objectives

After studying this project, readers should understand:

- How a photodiode can provide an input to a transistor alarm stage.
- Why sensor orientation and light conditions matter in optical circuits.

## Common Beginner Mistakes

- Reversing the photodiode or LED polarity.
- Choosing a buzzer without confirming its voltage requirement.
- Treating an educational alarm circuit as a certified safety system.

## License

MIT - see the repository [LICENSE](../LICENSE).
