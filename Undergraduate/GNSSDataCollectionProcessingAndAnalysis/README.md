# GNSS Data Collection Processing And Analysis

## Project Abstract
The purpose of this report is to explore the factors that influence GNSS positional accuracy.
Utilizing both an in-field method and a research approach, factors contributing to accuracy
degradation will be discussed.

The first approach was to conduct field observations to investigate environmental effects on
signal quality. Using the location of a known point as a base station, differential GNSS positioning
was applied to acquire the location of three surrounding points. One point was underneath a canopy of
tree branches, another was adjacent to a wall of a building, and the final point was in an open field.
GNSS observations were collected 3 times for each point at different times.
The second approach was to inspect data from two base-stations available through the
SOPAC database. Data over a 7 day period was collected and analyzed to reveal accuracy parameters.
In particular, the receiver’s signal frequency and elevation cutoff was altered to produce various
observation scenarios.

Utilizing Leica Infinity software we were able to process the information to reveal coordinates
in the WGS84 and NAD83 CSRS UTM Zone 17 coordinate systems. In order to infer the effects on
positional accuracy, the following parameters were studied:

- 1D, 2D and 3D measurement rms errors (“CQs”)
- GDOP, PDOP, HDOP and VDOP
- The number of satellites tracked vs. the number of satellites available

From the results we see multipath error as a large contributor of positional accuracy
degradation. In addition to this, the duration of time, signals received and the geometry of the
satellites observed, all play a role in the accuracy of the acquired position.

## Uploaded File Details
- *ESSE4610_FinalReport_AgataColinDawidMitch.pdf*: Final submitted report
