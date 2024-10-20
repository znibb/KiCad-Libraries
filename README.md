# KiCad-Libraries <!-- omit from toc -->
 Personal KiCad libraries

## Table of Contents <!-- omit from toc -->
- [1. Installation](#1-installation)
- [2. Library Guidelines](#2-library-guidelines)
  - [2.1. Sources](#21-sources)
  - [2.2. Symbols](#22-symbols)
    - [2.2.1. R/C/L](#221-rcl)
  - [2.3. Footprints](#23-footprints)
    - [2.3.1. R/C/L](#231-rcl)


## 1. Installation
1. Clone this repo to somewhere on your PC
1. Open KiCAD and from the main window go to `Preferences->Configure Paths...`
1. Add the following environment variables and point them to the respective repository sub directory:
    - DATASHEETS
    - FOOTPRINTS
    - MODELS
    - SYMBOLS
    - TEMPLATES
1. Click `OK`
1. Go to `Preferences->Manage Symbol Libraries...`
1. Click `Add existing library to table` (folder icon) and add all the .kicad_sym files from the SYMBOLS directory (be aware of duplicate names between the imported and default libraries)
1. Go to `Preferences->Manage Footprint Libraries...`
1. Click `Add Existing` (folder icon) and add all the .pretty files from the FOOTPRINTS directory (be aware of duplicate names between the imported and default libraries)
1. Click `OK`

## 2. Library Guidelines
### 2.1. Sources
snapeda.com

### 2.2. Symbols
Checklist for symbol creation/import
#### 2.2.1. R/C/L
H Align - Left on all text
Double check footprint filters

### 2.3. Footprints
Checklist for footprint creation/import

Pads: Rounded rectangle 25%

#### 2.3.1. R/C/L
Hide Value
Check Description
Fix 3D-model
Check >1.27mm clearance between silkscreen and exposed copper
Check 0.1mm line width for silkscreen
Add 0.4x0.6mm filled rectangle to silkscreen