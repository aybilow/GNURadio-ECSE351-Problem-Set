# GNURadio Problem Set for ECSE 351 Spring 2025
This is a problem set assigned to the ECSE 351 Class at CWRU for Spring 2025.

## Acknowledgements
Credit to Dr. Kristina Collins KD8OXT and Dr. David Kazdan AD8Y (Case Western Reserve University) for the original assignment as well as guidance throughout the course. The code found in this codebase is based on the GNURadio flow found [here](https://github.com/Jtearwicker/AGISETI/tree/main/Week4_Radio_Astronomy_II/grc_files). Changes to this code have been made as documented below.

## Changes / Revisions Made to the Original Codebase
The assignment outlined that for this particular problem one is to add additional antennas to the 'array' which is already set out. This revised flow includes three more antennas that receive a new signal (in this case a sawtooth, but it is easily editable). A component was also added into the signal flow which in addition to the original interferometry displays a waterfall to show the signal to noise ratio (SNR) of the received signal. 

## Usage
This program requires GNURadio Companion to function. Please reference the [official GNURadio Website](https://www.gnuradio.org) for information on how to install and use GNURadio Companion. This project is built with GNURadio Companion. To use, simply launch GNURadio Companion, open the .grc file included in this repo, and the flow chart shall appear. Any parameter may be edited by double-clicking on the corresponding block, and the program can be executed by clicking the 'play' button at the top. For any issues regarding GNURadio Companion, please reference the afforementioned recources from GNURadio for documentation and the like. 

## Contributing
All contributions are welcome, please make sure to document as needed. Prior approval or discussion is not required or necesssary. 

## License
This work is hereby entered into the Public Domain. Any and all relevant licenses either for the original AGISeti codebase or GNURadio is pursuant to the licnesure of those works.


