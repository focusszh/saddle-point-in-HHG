# saddle-point-in-HHG
Here we show an example of how to solve the saddle point method equations in python in certain condition and the comparison with the semi-classical three steps model.

##Condition 

```python
wl = 800
c = 2.99792458e8
epl = 8.85e-12
I = 4e18#4e18
m = 9.1e-31#-31
q = 1.6e-19#-19
E0 = np.sqrt(2 * I / c / epl)  # electric field (SI)
omc = 2 * np.pi * c / wl * 1e-6  # PHz
hbar = 1.05e-34
Ip = 21.5 #21.5  # eV
E00 = 1.545#1.545  # eV
Up=E0**2 *q**2 /4 /m/omc**2 *1e-30 / q #ev```

##22

