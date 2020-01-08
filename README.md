# match_filtering_simulation
Simulation of Matched Filter performance in cranial ultrasound done using FIELD-II toolkit on Matlab.
clone link: https://github.com/DING-raja/match_filtering_simulation.git


An annular transducer will be used with an outer diameter of 8mm and an inner diameter of 3mm (hole).

A medium similar to the cranium-ventricle environment will be modeled and field-ii will be used to insonify the same.

The raw echo is obtained (in pulse-echo mode) at different angles (tranducer directivity), it's envelope is filtered using hilbert transform (I/Q demodulation). 

The echo envelope is sent to match filter to boost signal's SNR.
