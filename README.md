# Synthetic-seismogram
The python script generates synthetic seismogram, from a real-world well log data. 
Steps involved in making synthetic seismograms:
i) Pre-processing the well-log data - This involves removing any NULL values, smoothing the data for spikes and filling the gaps in the data.
ii) Conversion from depth domain to time domain.
iii) Impedance estimation - Impedance Z = density* velocity
iv) Reflection coefficient calculation:- RC = (Z2-Z1)/(Z2+Z1)
v) Designing a zero-phase wavelet
vi) Convolution of RC and the wavelet
