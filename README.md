# PreConconant 2021

![Assembled PreConsonant PCB](hero.jpg)

### Basic information

This repository contains all the information necessary to build the PreConsonant 2021 phono preamplifier.

The original circuit was first published in the Elektor magazine in 1978. In the 1980s it was one of the most popular DIY phono preamplifiers in Europe because of its low parts count and good performance.

My version of the PreConsonant features the following improvements compared to the original:

 - a more efficient PCB layout with full ground plane;
 - the PCB has enough space for audiophile grade components, namely input and output coupling capacitors;
 - increased gain (39dB at 1kHz vs 34dB at 1kHz for the original);
 - the level adjustment pots at the output have been removed; they probably made a lot of sense when the average integrated amplifier had input sensitivity of ~250mV and typical analogue sources, such as tuners, had output levels between 80 and 300mV. Today we live in a different world: most digital sources have output voltage of 2V RMS, and most amplifiers have much lower sensitivity than in the 1970s, making trimpots at the outputs completely unnecessary.
 
### Technical specifications (based on actual measurements)

 - RIAA frequency response deviation, 100Hz-20kHz: within 0.2dB.
 - RIAA frequency response deviation, 20Hz-20kHz: within 0.4dB.
 - Input overload level at 1 kHz: 112 mV (when powered from a 24V DC supply).
 - Signal to noise ratio: greater than 72dB (ref. 5mV input at 1kHz).
 - Total harmonic distortion: less than 0.008% (ref. 20mV input at 1kHz).
 - Recommended power supply: 24V DC, e.g. [this one](https://github.com/SpinningVinyl/PreConsonantPSU).

### Documentation

The documentation (bill of materials, full schematic and build notes) is located in the `docs` folder.

### Status of the project

The PCB is now on its third major revision, it has been successfully built and tested multiple times. The current version (R3.1f) does not have any known defects and is considered to be the final revision.

### License

See the `LICENSE` file for details.

