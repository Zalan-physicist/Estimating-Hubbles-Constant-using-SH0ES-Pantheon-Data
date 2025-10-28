# Estimating-Hubbles-Constant-using-SH0ES-Pantheon-Data
Hubble's Constant is a fundamental constant that appears in Cosmology. 
There are two traditional ways to estiamte Hubble's constant, type 1A Supernovae and the other uses fluctuations in the Cosmic Microwave background.
This code aims at using Supernovae data from the SH0ES+Pantheon dataset, which can be found online at https://github.com/PantheonPlusSH0ES/DataRelease.
The absolute magnitude of Type 1A Supernovae is constant with a value of approximately -19. 
Therefore, by observing the apparent magnitude, and using the relation, mu= m - M = 5 log(d_l / 10 parsec).
Here, mu is distance modulus,  m is the apparent magnitude, M is the absolute magnitude and d_l is the luminosity distance.
We plot m against redshift, z.
Using the definiton of luminosity distance from cosmology, we obtain a theoretical model, on which we run regression using scipy.optimize's subpackage curve_fit to estimate Hubble's constant. 
 
