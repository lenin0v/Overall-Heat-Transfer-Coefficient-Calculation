# Overall-Heat-Transfer-Coefficient-Calculation
Intro to Thermal Sciences Schmidt Problem 7-6

#7_6 overall heat transfer coefficient 
import numpy as np

h1 = 10000 
F1 = 0.0001 
d1 = 0.03
d2 = 0.034
Kw = 52
F2 = 0.00009
h2 = 50000

U = (1)/((1/h1)+ F1 + ((d1*(np.log(d2/d1)))/(2*Kw)) + ((d1/d2)*F2) + (d1/(d2*h2)))

print( f"U = {U} W/m^2*˚C")
