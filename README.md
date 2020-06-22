# P-T-conversion
Finding of conversion coefficient for recalculation of probability (P) into the temperature (T). More detailed, this is dTdP(T) coefficient that depends also on the temperature.

As an input, there is set of measured s-type curves for different temperatures (e.g. 350mK - 800K each 5mK)

![Input data](https://github.com/andr-nau/s-curves-coef/blob/master/Fig1_init_data.gif "Input data")

After two intermediate steps:

![Step1](https://github.com/andr-nau/s-curves-coef/blob/master/Fig2_Step1_medium.gif "Step1")
![Step2](https://github.com/andr-nau/s-curves-coef/blob/master/Fig3_Step2_medium.gif "Step2")

As an output, we have conversion coefficient vs temperature dependence (dots) and conversion formula - polynome of 3rd order A+B*x+C*x^2+D*x^3 (red line):

![Output data](https://github.com/andr-nau/s-curves-coef/blob/master/Fig4_output_data.gif "Output data")
