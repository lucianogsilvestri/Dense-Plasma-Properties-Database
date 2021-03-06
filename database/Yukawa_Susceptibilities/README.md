The suceptibilities of Yukawa potential
Calculated using the molecular dynamics via Sarkas.
Yukawa reduced unit is used (time is normalized by the ion plasma frequency, 
length is normalized by the ion sphere radius)

Simulation parameter:
dt = 0.01
Number of timesteps = 80000
Number of particles = 10000

plasma parameters:
kappa = 0; Gamma = [10, 50, 150]
kappa = 1; Gamma = [14, 72, 217]
kappa = 2; Gamma = [31, 158, 476]
kappa = 3; Gamma = [100, 503, 1510]


The data contains the susceptibilities for only 0.0 < w < 3. If you need 
higher frequency data, please contact Prof. Murillo murillom@msu.edu. 

The data is written in Python numpy format.
The data size is (166x764) and covers  0.18< q < 30, and 0 < w < 3.
The 1st row is the frequency.
The 1st column is the wavenumber.

"chi_fig.py" draws the DSF for a given kappa, Gamma, and q. Please see the file
for more information.

For citation:
Yongjun Choi, Gautham Dharuman, and Michael S. Murillo, High-Frequency Response 
of Classical Strongly Coupled Plasmas,
Physical Review E, currently under review.
