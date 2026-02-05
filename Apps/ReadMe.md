PCM Hammer supports reading and writing the Operating System (OS) and Calibration of General Motors P01, P04 (early), P04, P08, P11, P12, E54, 98/99 Blackbox and P59 Powertrain Control Modules (PCMs).

PCM Logger supports logging from the same PCMs. 

VPW Explorer is intended for developers rather than for end users. It's basically just a sandbox for testing new ideas.

PcmLibrary contains core logic for the applications. While the applications currently only run on Windows, this probably should work on any operating system that has a .Net Core implementation (Mac, Linux, Android).

PcmLibraryWindowsForms contains Windows-specific functionality like serial ports and J2534 support. 
