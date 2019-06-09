# PorschePCMStuff
Porsche PCM4 (MIB2) and QNX Related Scripts
Just some random stuff for Porsche PCM analysis.

# extract_efs.py
Unpacks QNX EFS filesystem with output from dumpefs tool
Usage example: dumpefs -t ./efs-persist.efs > output.txt && python extract_efs.py output.txt ./extracted_efs

-> Source: https://www.defcon.org/images/defcon-22/dc-22-presentations/Such/DEFCON-22-Paul-Such-0x222-Playing-with-Car-Firmware.pdf
