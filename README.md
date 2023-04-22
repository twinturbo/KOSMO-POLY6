# KOSMO-POLY6
KOSMO Format 6 Channel Polyphonic Synthesiser Master Repository 

This repository acts as the master repository for information and documentation for my Poly6 Synthersiser based on an initial idea for a Raspbery Pi Pico DCO ( Digitaly Controlled Oscilator ) by "Polykit" AKA Jan Knipper [DCO](https://github.com/polykit/pico-dco). The PICO-DCO is largely a lift and shift of his work.

The designs are in the format for modular synth created by "Look Mum No Computer" called the Kosmo format, these are 20CM High and multiples of 2.5CM wide depending on the design. 

Modules will be released as and when they are designed, built and tested. Modules on the list below will build towoard a fully fleged 6 voice MIDI Synth.

The minimum for a working synth is the DCO, ADSR , MIX and VCA. 

A revised DCO based on the Electric Druid DCO chip will also be in the works.

Each repository includes the schematics, PCB design and gerbers for production. Some repositiories have more than one schematic/pcb where the build requires a main and sub board. 

Each repositiory also contanis a front panel design.

- KOSMO-POLY6-PICO-DCO 
  - STATUS - Complete 
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-PICO-DCO)
  - [Forum](https://https://lookmumnocomputer.discourse.group/t/kosmoing-the-polykit-dco/5878)
- KOSMO-POLY6-DRUID-DCO 
  - STATUS - To be designed
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-DRUID-DCO) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group)
- KOSMO-POLY6-JACKS 
  - STATUS Complete
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-JACKS)
  - [Forum](https://lookmumnocomputer.discourse.group/t/kosmoing-the-polykit-dco/5878)
- KOSMO-POLY6-MIX 
  - STAUS - Building , trouble shooting and revising.
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-MIX) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group/t/kosmo-poly6-mix-voltage-controlled-x-fade-crossfade/5979)
- KOSMO-POLY6-ADSR
  - STATUS - Tested , Final build required. 
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-ADSR) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group/t/reworked-version-of-the-polykit-adsr/5892)
- KOSMO-POLY6-VCA - 
  - STATUS - BUILDING, trouble shooting, revising.
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-ADSR) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group/t/kosmo-poly6-vca/6066)
- KOSMO-POLY6-CONTROLS
  - STATUS - To be designed
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-CONTROLS) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group)
- KOSMO-POLY6 Filter
  - STATUS - To be designed
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-FILTER) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group)
- KOSMO-POLY6-PG Programmer
  - STATUS - To be designed
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-PG) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group)
- KOSMO-POLY6-MetricST-Front-Panel
  - STATUS - To be designed
  - [GIT](https://github.com/twinturbo/KOSMO-POLY6-MSTFP) PRIVATE
  - [Forum](https://lookmumnocomputer.discourse.group)

## Key features

- 6 Channel MIDI Polyphonic Oscilators
- Modular Design 
- Ribbon Cable Interconncet
- Expandability

## Special Requirements
 - Raspbery Pi Pico [PICO DCO] 
 - 3360 x3 VCA Chips from either Alfa or Curtis
 - Electric Druid ENVGEN8 x6 [ADSR] or blank PICS and programmer.
 - Electric Druid VCDO x 6 [DRUID DCO] or blank PICS and a programmer.

## Version Numbering
  Vx.y.z
  
  - x major version numbers starting 0, denotes a significant design version
  - y reworks within a design version. Odd numbers should be considered WiP, Even are Releases. 
  - z minor fixes.

## Pictures



## References
- The Original DCO Project [ Original ](https://github.com/polykit/pico-dco)
- 
- The LMNC project thread [ Thread ](https://lookmumnocomputer.discourse.group/t/kosmoing-the-polykit-dco/5878)
- The Publishing Thread of my POLY6 Modules [ Publish thread ](https://lookmumnocomputer.discourse.group/t/kosmo-poly6-releases/5962)
- Kosmo/LMNC forum [ Frorum Home ](https://lookmumnocomputer.discourse.group/)
- LMNC Webpage [ LMNC website](https://www.lookmumnocomputer.com/)
- LMNC Youtube [ LMNC Youetube](https://www.youtube.com/c/LOOKMUMNOCOMPUTER/videos)
