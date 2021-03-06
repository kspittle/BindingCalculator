Version 2.0.1.2
- Changed polymerase ratio from 2 to 3 for large-scale magbead when P4 binding kit selected (issue 23482)

Version 2.0.1.1 
 (released with PacBio RS version 2.0.2 Software)
- Remove warning with standard/diffusion protocol when P4 binding kit selected (issue 23427)
- Correct binding buffer calculations when P4 binding kit selected (issue 23428)
- Change low binding volume error message and avoid showing erroneous calculations (issue 23450)
- Show DNA Control dilution in print view when P4 binding kit selected (issue 23455)
- Added nM units to the titration input concentrations (issue 23478)

Version 2.0.1.0
- Update coefficients for the P4 binding kit
- Correct polymerase tube label for samples using P4 (issue 23382)
- Correct the diluted polymerase label in the print view (issue 23382)
- Only display extra dilution step in "using binding complex" section with large preparations (issue 23382)

Version 2.0.0.2
- Switching a sample to non-standard will now recompute concentrations immediately (issue 23123)
- The polymerase dilution is now displayed in the print view for standard samples (issue 23127)
- Print view sample concentration is now labeled as ng/uL instead of nM (issue 23144)
- Print view checkbox options now persist between both stand-alone and on-instrument (issue 23126)
- Resolve issue where sorting the list of samples could result in only 20 displayed (issue 23168)

Version 2.0.0.1
- Prevents renaming a sample to have a blank name (issue 23060)
- Improves display of errors when renaming
- Only rounds volumes to two digits of precision when less than 1 uL

Version 2.0.0
- First release of stand-alone Sample Prep Calculator
