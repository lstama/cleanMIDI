# cleanMIDI
Simple programs to "clean" MIDI file

These programs (replacecomma & simplify) were created to parsing MIDI file into simple form for my future neural network project. The output will be MIDI file without percussion, one track, one channel (channel 1), and discard all configuration except note and pitch.

DEFAULT:

Tempo: 387096

Key_signature: "major"

Time_signature: 4, 2, 24, 8 

USAGE:

Midicsv < (input).mid | replacecomma | simplify | Csvmidi > (output),mid

(You can get Midicsv and Csvmidi documentation on http://www.fourmilab.ch/webtools/midicsv/)

TODO:

+source code

+set tempo, key_signature, and time_signature to same as input

+command line argument for channel options (single/multiple)

+command line argument for volume options (single/multiple)