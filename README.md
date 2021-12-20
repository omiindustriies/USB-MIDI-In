# USB-MIDI-In

This code allows for a teensy 3.2 to transmit on/off gate signals from a modular synthesizer and convert them to MIDI note on/off messages. When the teensy receives a high gate signal, it sends a note-on message. Each input transmits on a separate MIDI channel. 
