# M-QAM-Modulation
This GitHub repository hosts the MATLAB source code for obtaining the M-QAM constellation diagram. The project is a coursework assignment for the PDE2103 Digital Signal Processing course at Middlesex University Dubai, Computer Systems Engineering program.

QAM (Quadrature Amplitude Modulation) is a digital modulation technique that conveys information by varying both the amplitude and phase of two carrier signals. QAM can be used for transmitting digital signals over analog communication channels. M-QAM is a variation of QAM where M is the number of points in the constellation diagram.

The repository contains the following MATLAB files:

1. gray_code.m: This file generates the Gray code sequence for a given number of bits. The Gray code is used to map binary data to the constellation points in a way that minimizes the bit error rate.

2. Constellation.m: This file generates the M-QAM constellation diagram for a given value of M. The constellation diagram shows the points in the complex plane that correspond to the different symbol values.

3. get_symbols.m: This file generates random symbol values for a given M-QAM constellation diagram. The symbol values are used to modulate a carrier signal for transmission over a communication channel.

This MATLAB source code can be used to understand the basics of M-QAM modulation and to simulate M-QAM signals in MATLAB. The code can also be extended to implement more complex digital communication systems using QAM modulation.
