# MayUpgrade

In May/June 2017, during a chilled water shutdown, the Transmission, R30, and R45_1 cRIOs were upgraded to 9067s.  This project simply ports the old Kubley-era (LV2010) code to the new cRIO controllers (in LV2016).  Later on, the cRIO code will be updated with that in PRIMELab-2017 project.

The significant change is to the R30 FPGA code and module layout to consolidate Analog output modules to 1 (there had been two, with the 2nd only using one output).
