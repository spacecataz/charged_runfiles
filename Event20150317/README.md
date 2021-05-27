Everyone wants to simulate the "St. Patrick's Day" storm of March 17, 2015.

Input Value Description
-----------------------
IMF values were obtained via ACE MFI from CDAWeb.
Solar wind plasma parameters were obtained from ACE SWEPAM via CDAWeb.
Values were propagated via Aaron Ridley's IDL cdf_to_mhd routine.
Significant gaps exist in SWEPAM density.  These values were suplemented
via OMNI database values.  The OMNI propagation matches very well with
the Ridley ballistic method.

F10.7 value (115 SFU) was obtained from this website:
http://www.spaceweather.gc.ca/solarflux/sx-5-flux-en.php?year=2015

Model Combination Folders
-------------------------
UA - this folder contains input files for stand-alone UA/GITM.  It has params for both creating
preconditioning restarts for the coupled runs that begin on 2015/03/16 20:00UT and for performing
the full storm in GITM stand-alone.

The GMIMIE combination has two sets of PARAMS:
PARAM.in contains the input files 

Satellites & Magnetometers
--------------------------
`mags.dat` contains a comprehensive list of magnetometers from the SuperMAG website & IMAGE array.
The `virtsats` and `sats.include` file have all virtual satellite information for the event.
Place all of these files/directories into the run directory before starting.

THINGS TO DO:
-------------
IE must use variable F10.7.  How to do this?
Need restart params to pick up runs after crash/stall/timeout.
