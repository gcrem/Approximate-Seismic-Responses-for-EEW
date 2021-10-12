Mat files are interpreted as follows: 

Coefficients_PFA_2021.mat: 101 x 15 x 3 x 8 double containing model coefficients for peak floor acceleration (m/s^2). The first dimension refers to equally spaced values of increasing relative building height, the second dimension refers to building period (s) ([0.1 0.2 0.3 0.4 0.5 0.75 1 1.5 2 2.5 3 3.5 4 4.5 5]), the third dimension refers to alpha ([0.1, 8, 30]), and the fourth dimension contains the 8 different model coefficients.
 

Coefficients_IDR_2021.mat: 15 x 100 3 x 8 double containing model coefficients for interstory drift ratio (%). The first dimension refers to building period (s) ([0.1 0.2 0.3 0.4 0.5 0.75 1 1.5 2 2.5 3 3.5 4 4.5 5]), the second dimension refers to equally spaced values of increasing relative building height, the third dimension refers to alpha ([0.1, 8, 30]), and the fourth dimension contains the 8 different model coefficients.


Coefficients_MIDR_2021.mat: 15 x 3 x 8 double containing model coefficients for maximum interstory drift ratio (%). The first dimension refers to building period (s) ([0.1 0.2 0.3 0.4 0.5 0.75 1 1.5 2 2.5 3 3.5 4 4.5 5]), the second dimension refers to alpha ([0.1, 8, 30]), and the third dimension contains the 8 different model coefficients.