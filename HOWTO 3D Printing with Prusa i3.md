
# Prusa i3 Printer Usage Notes

Some general notes and tips about using the Prusa i3 printers.

## Filaments

Prusa printers use 1.75mm diameter filament.
It should be kept tightly wound on the spool. 
It should be stored in a dry location.

### Main Filament Types

  - PLA - easy to print, hard, lower-temperature, corn-starch based
  - PETG - good for mechanical parts, less brittle, can be a little stringy
  - TPU - flexible, sticks too well to beds so **use glue stick** 
  - Phosphorescent - abrasive on brass nozzle
  - ABS/ASA - strong, higher temperature, but needs ventilation and slower cooling
  - Wood-filled: use only Hatchbox brand on 0.4mm nozzles (others clog it)
  - Carbon Fiber-filled: very abrasive on nozzle, see monitor about swapping to harder nozzle.
  - Nylon: not on Prusa steel sheet beds at this time

For further info, consult [Prusa Materials Guides](https://help.prusa3d.com/category/material-guide_220)

Some brands we've liked:
  - Hatchbox, eSun, Prusa, tty3D, 3DSoluTech, ZyTech, Matterhackers, Protopasta, AmazonBasics (sometimes)

## Current Printer Logistics

  - Come in during Open Studio time
  - Select an available printer
  - Remove and stow any completed job on that printer
    - Printed object, filament, and SD Card
  - Job submission is by SD-Card - BYO or use ours
    - TBD: or via OctoPrint if installed on the available printer.
  - Stay around for 1st layer adhesion
    - Or convince someone to watch it for you
  - Leave a card with your name and contact info

### Caveats

  - Start with a clean prepared bed for your material
  - Do not swap the steel sheet with another printer 
     - Each printer is calibrated for its sheet and that is saved in a profile
       It can be recalibrated for a different sheet and the settings stored 
  - Do not adjust Z-height settings w/o recording it in the log
     - But really ask why you need to do this in the first place?
     - (see Troubleshooting tips below)

## Printer Bed Sheets 

### Bed Sheet Usage Tips

  - Smooth - good for PLA, sometimes too sticky for PETG
  - Textured - good for PETG, okay for PLA
  - Both - TPU but use glue stick for ease of removal

### Cleaning Tips

  - Avoid fingerprints and other greases
  - Clean while cool
     - Isopropyl alcohol if printing with PLA
     - Windex™ if printing with PETG 
        - Especially on smooth sheets!
     - Can use dish soap and water but must immediately dry
       - Sparingly on textured sheets

## Troubleshooting

  - If a job fails - change something before trying it again.
    - Most commonly it’s first layer adhesion.
    - Try cleaning the bed first
    - Check first layer thickness, is it at least 0.2mm? 
    - Temperature, filament, speed, or supports can also contribute.
      - reduce speed for 1st layer to 85%
      - increase bed temperature by 5°C
      - is it old filament?
      - is the filament coming off the spool correctly?
  - Sometimes it’s just a fluke.
