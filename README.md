# HP Officejet Pro X476dw

Stuff related to the HP Officejet Pro X476dw printer.

* Improved PPD

## Improved PPD

The stock PPD that came with Ubuntu 14.04 and 14.10 has a few flaws: 
* It prints in 300dpi instead of 600dpi which the printer actually supports.
* It creates huge print jobs with extra empty pages when printing multiple copies.

This version includes the following enhancements:
* Set printing resolution to 600dpi
* Use printer for multiple copies, not CUPS
* Default to duplex printing
