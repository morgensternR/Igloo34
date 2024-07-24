# Project/path setup
- Open amcc-template.kicad_pro, save as new project name

# Adding footprint+symbols
- Any footprint files added to /project-footprints/ will be added automatically to the "project-footprints" library
- Add any kicad_sym files to /project-symbols/ and add their path directly to Symbol Libraries:  Menu->Preferences->Manage Symbol Libraries
    - Suggested name:  "project-symbols2", "project-symbols3", etc
    - Whenever searching for symbols/footprints, just type "project" in the search bar

# To insert your new symbol + footprint
- Click Add Symbol button on right
- Navigate to e.g. "project-symbols2" and select the symbol
- Place the device, and double-click it to open properties
- Edit the "Footprint" field and navigate to e.g. "project-footprints" to select the footprint

# Before starting
- PCBNew->Menu->File->Board Setup
    - Physical Stackup -> 2 or 4 layers
    - Net Classes:
        - JLCPCB Stripline 50 Ohm trace width = 0.35mm wide
        - Via size/hole = 0.6mm/0.4mm
