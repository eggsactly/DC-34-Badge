# About
DC-34 Badge contains the KiCad 6 design files for the Cyber Professionals 
Enthusiast Club (CPEC) DEFCON 34 Badge. 

## Board Features
- 2.2" 320x240 display
- Wifi and Bluetooth LE equiped
- 3 Shitty Add On (SAO) 1.69bis ports equiped with I2C
- Gameboy equivalent buttons
- Rumble pack

## Project Structure
The structure of this repo is organized as such:

| Directory               | About                                                   |
|:------------------------|:--------------------------------------------------------|
| DC-34-Badge             | KiCad 6 Design files                                    |
| digikey-kicad-libraries | Symbol libraries and footprints downloaded from digikey |
| kicad-libraries         | git subtree containing expressif design files           |

## Running
To view schematics, please run KiCad 6.0.11 or later. Change directory into 
DC-34-Badge and run
```
kicad DC-34-Badge.kicad_pro
```

Please note: please run kicad from the same directory as the .kicad_pro file 
is stored because the fp-lib-table and sym-lib-table use relative paths 
so that this project is portable between computers.

# Associated Repos
Board firmware is developed in this repo: 
[https://github.com/wildcat86/DC34-Mech-Badge](https://github.com/wildcat86/DC34-Mech-Badge)

