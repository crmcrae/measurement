## Qi/Qc Test:

This test shows the accuracy of the fits as a function of changing Qc values for three different values of Qi.

## Data:

![alt text](https://raw.githubusercontent.com/Boulder-Cryogenic-Resonator-Testbed/measurement/master/BCRTresfit/circuit_simulation_results/QiQc/DCM.png)

This data illustrates that there appears to be a range of Qi/Qc where the accuracy of Qi is high for the DCM fit. This range appears to be between 10^-2 and 10 for Qi
on the order of 10^2, between 10^-2 and 10^2 for Qi on the order of 10^4, and between 10^-2 and 10^3 for Qi on the order of 10^6. In short, it appears that as long as
Qc and Qi are within two orders of magnitude from each other, the result will be quite accurate for determining Qi.

![alt text](https://raw.githubusercontent.com/Boulder-Cryogenic-Resonator-Testbed/measurement/master/BCRTresfit/circuit_simulation_results/QiQc/INV.png)

Similary for INV.png, there appears to be another range of Qi/Qc where the accuracy of Qi is high. This range appears to be the same as the DCM fitting image for Qi
on the order of 10^2 and clear limits where the percent error goes above 2% are not shown in this graph for the other two Qi values.

These graphs demonstrate that the INV fitting method appears to be more robust across high and low Qi/Qc ratios and that each Qi appears to have an ideal Qi/Qc ratio
range that gives accurate fitting results.