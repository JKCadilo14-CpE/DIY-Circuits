# DIY Circuits

A collection of small electronics and PCB-learning projects created in KiCad. Each folder contains the editable KiCad source for a single circuit, making this repository a place to explore schematic capture, footprint assignment, and simple PCB layout.

## Browse the projects

Open a project's `.kicad_pro` file in KiCad to start. The projects were created across KiCad 9/10-era file formats, so opening an older project in a newer KiCad release may prompt for a format upgrade. Keep a local backup before accepting any conversion.

| Project | Focus |
| --- | --- |
| [9V Battery Status Indicator Circuit](<9V Battery Status Indicator Circuit/>) | Two-LED battery-voltage indication circuit. |
| [Astable multivibrator](<astable miltivibrator Circuit/>) | Two-transistor LED flasher. |
| [Automatic hand sanitizer](<automatic hand sanitizer/>) | Sensor-controlled pump-switching circuit. |
| [Clap switch circuit](<clap switch circuit/clap switch circuit/>) | Sound-responsive switching circuit. |
| [Fire alarm system using photodiode](<fire alarm system using photodiode/>) | Photodiode-triggered alarm circuit. |
| [Hidden Wire Detector](<Hidden Wire Detector/>) | Wire-detection learning circuit. |
| [Laser Alarm Security Circuit](<Laser Alarm Security Circuit/>) | Laser-interruption alarm circuit. |
| [Light-Activated Switch Circuit](<Light-Activated Switch Circuit/>) | Light-sensitive indicator/switch circuit. |
| [Obstacle detector](<obstacle detector/>) | IR emitter and photodiode obstacle detector. |
| [Temperature controlled DC fan - BC547](<temperature controlled dc fan - BC547/>) | Thermistor-controlled fan-driver circuit. |
| [Touch sensor circuit](<touch sensor circuit/>) | Touch-input-controlled load circuit. |
| [Water level indicator](<water level indicator/>) | Multi-level water indication and alarm circuit. |

## Canonical source files

For every project, the authoritative design files are:

- `*.kicad_pro` - KiCad project settings and entry point.
- `*.kicad_sch` - Schematic source.
- `*.kicad_pcb` - PCB layout source.

Local KiCad session files, footprint caches, automatic backups, and local-history folders are intentionally ignored. They are useful on an individual computer, but they are not part of the portable project source.

## Project status

This repository currently shares editable learning-project sources. Manufacturing release packages, formal design-review records, and verified hardware test results are not yet included. Treat each design as an educational starting point and review it for your own requirements before building.

## Safety

These projects are intended for low-voltage electronics learning. Do not connect a design to mains electricity or use it in safety-critical, medical, or life-support applications without a qualified engineering review and appropriate protection measures.

## License

This repository is available under the [MIT License](LICENSE).
