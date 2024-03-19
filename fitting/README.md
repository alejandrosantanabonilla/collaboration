# Fitting the torsional angle

In this repository, we can find 2 files. The **angle_fitting.py**, where the program fitting is stored. The file
**d_10_5_2_1.dat**, where the angles vs relaxed energies obtained by ORCA has been stored. This is for the molecule
*poly_t_cispt*.

## Remarks

The script runs with the python library symfit, this needs to be installed by typing:

```
pip install symfit
```

Similarly, there are two functions for fitting the data. The first one is **fourier_series**, that contains sine terms and the second
one is **fourier_series_cosine** that only contains the cosine terms. This last one is the default. One can change it by changing the
following part of the code:


