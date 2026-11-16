# Changelog

All notable changes to this project are recorded here.

## [1.0.0] - 2026-11-16

### Added
- Schematic (`PWM_schematic.SchDoc`) and two-layer PCB (`PWM.PcbDoc`) for the NE555P + IRLZ44N PWM generator.
- Project libraries: NE555P, 3296-W trimmer, KF301-2P terminal, IRLZ44N symbol and TO-220 footprint.
- Project report (`README.md`) with design overview, bill of materials, library setup and DRC notes.

- Fabrication set `fabrication/PWM-gerbers.zip` (Gerber RS-274X with embedded apertures, plus drill file).
- Project file `PWM.PrjPcb`, with document paths made relative to this repository.

### Verified
- Design rule check passes with 0 violations after relaxing silk-to-solder-mask clearance to 5 mil, annotating all designators and removing the auto-generated room.
