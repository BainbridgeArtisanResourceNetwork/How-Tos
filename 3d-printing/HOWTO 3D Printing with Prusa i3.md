---
marp: true
paginate: true
---
<!-- header: Prusa Printer Usage Notes-->

# Prusa Printer Usage Notes
Some general notes and tips about using the Prusa printers.

---
## Filaments

Things to remember about printer filaments:
 - Prusa printers use 1.75mm diameter filament.
 - It should be kept tightly wound on the spool. 
 - It should be stored in a dry location.

---
### Main Filament Types
  - PLA - easy to print, hard, lower-temperature, corn-starch based
  - PETG - good for mechanical parts, less brittle, can be a little stringy
  - TPU - flexible, sticks too well to beds so **use glue stick** 

### Secondary Filament Types
  - Phosphorescent - abrasive on brass nozzle, use on hardened-nozzle printer
  - ABS/ASA - strong, higher temperature, but needs ventilation and slower cooling
  - Wood-filled: use only Hatchbox brand on 0.4mm nozzles, prefer hardened-nozzle.
  - Carbon Fiber-filled: very abrasive on nozzle, use on hardened-nozzle printer.
  - Nylon: use satin sheet beds at this time with glue interface

---
### Further Information

For further info, consult [Prusa Materials Guides](https://help.prusa3d.com/category/material-guide_220)

Some brands we've liked:
  - Hatchbox, eSun, Prusa, tty3D, 3DSoluTech, Polymaker, Matterhackers, Protopasta, AmazonBasics (sometimes)


---
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


---
### Caveats

  - Start with a clean prepared bed for your material
  - Do not arbitrarily swap the steel sheet with another printer
     - each printer has a named profile for the sheets its calibrated for
     - any change means switching to a different profile too
  - Do not adjust Z-height settings w/o recording it in the log
     - But really ask why you need to do this in the first place?
     - (see Troubleshooting tips below)

---
<!-- header: Printer Bed Sheets -->
## Printer Bed Sheets 

Care and maintenance of print bed sheets

---
### Bed Sheet Usage Tips

  - Smooth - good for PLA, usually too sticky for PETG
    - use Windex to clean it, or use glue stick interface layer
  - Textured - good for PETG, okay for PLA (but more sensitive)
  - Satin - good for all (use glue stick with PC or PA)
  - All - for TPU use glue stick for ease of removal

---
### Cleaning Tips

  - Avoid fingerprints and other greases
  - Clean sheet while cool
     - Isopropyl alcohol if printing with PLA
     - Windex™ if printing with PETG 
        - Especially on smooth sheets!
     - Can use dish soap and water but must immediately dry
       - Sparingly on textured sheets
  - never use acetone on non-smooth sheets
     - and even then only sparingly

---
## Troubleshooting

  - If a job fails - change something before trying it again.
    - Most commonly it’s first layer adhesion.
    - Try cleaning the sheet first
    - Check first layer thickness, is it at least 0.2mm? 
    - Temperature, filament, speed, or supports can also contribute.
      - reduce speed for 1st layer to 85%
      - increase bed temperature by 5°C
      - is it old filament?
      - is the filament coming off the spool correctly?

---
<!-- header: Printer Use Checklists --> 
# Checklists

Things to remember when using the printers

---
## Removing a print job

  -  remove printed parts carefully when bed has cooled, set aside.
  -  preheat for the type of filament currently loaded, and unload it when hot.
  -  thread end of filament through holes in spool to keep it wound
  -  place part, filament, and user's card (if any) on the shelf by the window
 
---
## Starting a print job

  - ensure printer sheet is clean, and ready for printing
  - visually inspect printer: is the hot end clear, any other issues?
  - preheat for selected filament, load into extruder when it's ready
  - keep letting it extrude more until your filament is extruding cleanly
  - load part to be printed via SD-Card, USB stick, or OctoPrint (depending on printer)
  - select part and start it printing
  - observe and wait for print to start, be prepared to catch stray threads at start
  - do not leave until the first layer has been successfully printed
