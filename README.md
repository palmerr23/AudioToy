# AudioToy
8x8 channel modular hardware for Teensy 4.0 Audio with balanced inputs and outputs at pro-audio levels.

A CS42448 8x8 channel audio board, with headers for off-board input and output amplifiers. The board includes a 14-pin stacking header for the 16x16 TDM hardware under development by Paul Stoffregen.

The board is hardware compatible with Paul's 8x8 revised audio board and software compatible with the CS42448 object in the Audio Library. (see https://hackaday.io/project/2984/logs)

2 input preamplifier module designs: one with mic/line capabilities (Combo XLR socket), the other for line/instrument inputs (TRS). All pre-amps can handle balanced or unbalanced inputs.
All input module controls (gains and pads) are controlled by I2C, and insertion of a TRS plug into the Combo socket is remotely readable.

An output module capable of driving 600  ohm outputs at +8dBm.

Two small subsidiary PCBs complete the set: An I2C to GPIO expander to drive some functions on the input boards and provide level shifting for a WS2812B LED string, to indicate each channel's level. 

This repo has production Gerber files, a BoM, placement file and schematic for each of the boards.

Permission is hereby granted to use this material under the terms of the CERN Open Hardware Licence Version 2 (Weakly Reciprocal) https://ohwr.org/cern_ohl_w_v2.txt  

In brief, this licence grants full, non-exclusive rights to the intellectual property requiring that the modified designs are made available if a product is being Made or Conveyed.
