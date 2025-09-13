# nafion-thinfilm-md

Simulation input files for Nafion thin films on Au and cysteamine-modified Au surfaces.

## Contents
- `nafion_on_gold/` – Input and data files for Nafion on pristine Au.
  - `nafion_gold.data` – LAMMPS data file
  - `nafion_gold.in` – Main input script
  - `nafion_gold.in.init` – Initialization settings
  - `nafion_gold.in.settings` – Force field settings
- `nafion_on_cysteamine_gold/` – Input and data files for Nafion on cysteamine-modified Au.
  - `nafion_cys_gold.data`
  - `nafion_cys_gold.in`
  - `nafion_cys_gold.in.init`
  - `nafion_cys_gold.in.settings`

## Usage

$lammps_binary -in nafion_gold.in