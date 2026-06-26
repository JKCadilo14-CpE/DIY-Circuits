# DIY Circuits

A collection of small electronics and PCB-learning projects created in KiCad. Each folder contains the editable KiCad source for a single circuit, making this repository a place to explore schematic capture, footprint assignment, and simple PCB layout.

## 📚 Educational Use Notice

This repository is intended for educational and personal learning purposes. The circuits, schematics, PCB layouts, fabrication files, and documentation are shared to help students understand electronics design, PCB fabrication, and circuit analysis.

Please do not submit these projects as your own academic work. If you use any design or idea from this repository, make sure you understand how it works, adapt it to your own requirements, and follow your institution's academic integrity policies.

The goal of this repository is to encourage learning, experimentation, and skill development—not to replace your own design process.

## Academic Integrity

If you are using this repository for a class, use it as a reference to understand concepts and improve your own designs. Always create and submit work that complies with your instructor's requirements and your institution's academic integrity policies.

## Browse the projects

Open a project's `.kicad_pro` file in KiCad to start. The projects were created across KiCad 9/10-era file formats, so opening an older project in a newer KiCad release may prompt for a format upgrade. Keep a local backup before accepting any conversion.

| Project | Focus |
| --- | --- |
| [9V Battery Status Indicator Circuit](<9V Battery Status Indicator Circuit/README.md>) | Two-LED battery-voltage indication circuit. |
| [Astable multivibrator](<astable miltivibrator Circuit/README.md>) | Two-transistor LED flasher. |
| [Automatic hand sanitizer](<automatic hand sanitizer/README.md>) | Sensor-controlled pump-switching circuit. |
| [Clap switch circuit](<clap switch circuit/clap switch circuit/README.md>) | Sound-responsive switching circuit. |
| [Fire alarm system using photodiode](<fire alarm system using photodiode/README.md>) | Photodiode-triggered alarm circuit. |
| [Hidden Wire Detector](<Hidden Wire Detector/README.md>) | Wire-detection learning circuit. |
| [Laser Alarm Security Circuit](<Laser Alarm Security Circuit/README.md>) | Laser-interruption alarm circuit. |
| [Light-Activated Switch Circuit](<Light-Activated Switch Circuit/README.md>) | Light-sensitive indicator/switch circuit. |
| [Obstacle detector](<obstacle detector/README.md>) | IR emitter and photodiode obstacle detector. |
| [Temperature controlled DC fan - BC547](<temperature controlled dc fan - BC547/README.md>) | Thermistor-controlled fan-driver circuit. |
| [Touch sensor circuit](<touch sensor circuit/README.md>) | Touch-input-controlled load circuit. |
| [Water level indicator](<water level indicator/README.md>) | Multi-level water indication and alarm circuit. |

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
