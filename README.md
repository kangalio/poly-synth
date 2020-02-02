# poly-synth
A little polyphonic (dual-voice) pulse wave synthesizer for the Z80 microprocessor, more precisely for use on the TI-83 calculator

It's controlled using the 8 keys from "0" key up to "X,T,O,n" key, currently it's set to a minor scale. The key frequencies are freely configurable though (see CYCLE_SPEEDS label in the code).

This program accesses both the keyboard and the link port (where the audio is output to) via raw input/output instructions. That means that you don't need any OS headers or anything.
