FSBL

This is the First Stage Bootloader for the VCS-1. It's based on Xilinx default FSBL for zynqMP.
It is modified to configure the clock synthesizer, ethernet, USB, VTC, TPG and VDMA when the board is powered up.

The following files have been added:
adv7511.c
adv7511.h
register_map_mod.h
si5338.c
si5338.h
tpg.c
tpg.h
vdma.c
vdma.h
vtc.c
vtc.h

The following files have been modified (searched for "SUN_MOD" in the source code):
xfsbl_board.c
xfsbl_board.h
xfsbl_main.c