# Device-Wipers
Shell scripts to wipe HDDs, SSDs and USB storage devices.

Usage:

"sudo ./SATAWiper" - to use the SECURITY ERASE command on SATA devices. Very quick on SSDs.

or

"sudo ./USBWiper" - to use a dd command to wipe the device using 0x00s on every sector.

Requires 'dc3dd', 'pv' and 'hdparm' commands are installed.
