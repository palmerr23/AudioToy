# AudioToy
8x8 channel hardware for Teensy 4.0 Audio

A CS42448 8x8 channel audio board, with headers for off-board input and output amplifiers.

2 input preamplifier module designs: one with mic/line capabilities (Combo XLR socket), the other for line/instrument inputs (TRS). All pre-amps can handle balanced or unbalanced inputs.
All input module controls (gains and pads) are controlled by I2C, and insertion of a TRS plug into the Combo socket is remotely readable.

An output module capable of driving 600  ohm outputs at +8dBm.

Two small subsidiary PCBs complete the set: An I2C to GPIO expander to drive some functions on the input boards and provide level shifting for a WS2812B LED string, to indicate each channel's level. 

This repo has production Gerber files, a BoM and schematic for each of the boards, along with brief design notes.
