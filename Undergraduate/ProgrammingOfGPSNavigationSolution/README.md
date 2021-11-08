# Programming of GPS Navigation Solution

## Project Abstract
This report outlines the procedure taken to determine a GPS navigation solution from
satellite observation and navigation files.
Matlab code was created to conduct the data reading of most (given) observation and
navigation files, apply clock corrections and ionospheric corrections to the transmitted
psuedoranges, determine the positions of the satellites transmitting messages (based on their sent
C1 code), and use such positions to calculate the receiver coordinates through non-linear
parametric least squares adjustment. In addition, the Geometric Dilution of Precision (GDOP),
Position Dilution of Precision (PDOP), and Time Dilution of Precision (TDOP) factors were
computed and plotted to aid in assess the quality of results (or, more specifically, the effects of
satellite positioning/geometry on results). Such code was created around the ALGO112008
dataset.

The position of the receiver was computed to be [9.1818x10^5m, -4.3461x10^6m, 4.5620x10^6m] in the XYZ direction, respectively. This differed from the given approximate
coordinates in the observation file by [-51.6341m, -2.9873m, -6.8225m]. It is believed
that, given addition tropospheric corrections, such differences (mainly in the X component)
could be reduced in magnitude. Peaks were seen in the DOP plots where satellite number for
each epoch was low (only 5-7 satellites). This supported the fact that receiver position is better
estimated with greater number of healthy satellites (and good transmitted messages). The
minimum computed deviations for the GDOP, PDOP, and TDOP factors were 1.4151m, 1.2797m, and 2.015x10^-9m, respectively. The maximum computed deviations for the GDOP,
PDOP, and TDOP factors were 7.9796m, 6.3342m, and 1.6188x10^-8, respectively.

## Uploaded File Details
- *ESSE4610_Project3_AgataSzeremeta_WithoutCode.pdf*: Final submitted report modified to remove code originally included in the Appendix
