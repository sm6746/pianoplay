Piano Simulation Program
Description
This C program simulates a piano, allowing users to play piano notes using their computer keyboard. It utilizes X11 for keyboard input and PortAudio for audio playback. The piano keys are mapped to specific keys on the keyboard, and pressing a key triggers the corresponding piano note.

Features
Plays piano notes based on keyboard input.
Supports multiple octaves.
Provides two output options:
Display the currently pressed piano keys in text format (-onotes argument).
Display the piano keyboard with currently pressed keys highlighted (-osheet argument).
Uses WAV audio files for each piano note.
Usage
Compile the program using a C compiler.
Copy code
gcc -o piano piano.c -lX11 -lportaudio
Run the compiled program.
bash
Copy code
./piano [-onotes | -osheet]
Use the -onotes argument to display currently pressed piano keys in text format.
Use the -osheet argument to display the piano keyboard with currently pressed keys highlighted.
Press the corresponding keys on your keyboard to play piano notes.
Press Shift or Ctrl to change the octave.
Dependencies
X11 library for keyboard input handling.
PortAudio library for audio playback.
Compilation
The program can be compiled using GCC with the following command:

Copy code
gcc -o piano piano.c -lX11 -lportaudio
Keyboard Mapping
The piano keys are mapped to specific keys on the keyboard. The default mapping starts from the A key and spans several rows. Octave shifting can be achieved using Shift and Ctrl keys.
