# P-T-conversion
Finding of conversion coefficient for recalculation of probability (P) into the temperature (T). More detailed, this is dTdP(T) coefficient that depends also on the temperature.

As an input, there is set of measured s-type curves for different temperatures (e.g. 350mK - 800K each 5mK)

![FIG1](https://github.com/andr-nau/s-curves-coef/blob/master/Fig1_init_data.gif "Input data")

After two intermediate steps:

Slope of linearly fitted middle part (probability from 0.3 to 0.7) of each S curve.

![FIG2](https://github.com/andr-nau/s-curves-coef/blob/master/Fig2_Step1_medium.gif "Step1")

Calibration curve – temperature dependence of the switching current at P = 0.5 extracted from set of S curves.

![FIG3](https://github.com/andr-nau/s-curves-coef/blob/master/Fig3_Step2_medium.gif "Step2")

As an output, we have conversion curve – ratio between changes in probability and temperature for different base temperature. Open squares - discrete values of conversion coefficient for different temperatures; red dashed line - approximation - polynome of 3rd order A+B*x+C*x^2+D*x^3:

![FIG4](https://github.com/andr-nau/s-curves-coef/blob/master/Fig4_output_data.gif "Output data")
