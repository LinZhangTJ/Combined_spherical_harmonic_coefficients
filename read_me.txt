The datasets include the period from January 1993 to December 2024:

cs: Combined spherical harmonic coefficients (without GIA correction, no C20 and C30 replacement, no degree-1 coefficients added back)

cs_sig: Uncertainty of cs

TWSA: Grids converted from cs with the following corrections:
(1) The degree-1 coefficients are restored using Technical Note 13
(2) The C20 and C30 coefficients are replaced with those from Technical Note 14
(3) For the pre-GRACE and GRACE-gap periods, the degree-1 coefficients are derived from Locher et al. (2025), whereas the C20 and C30 coefficients remain unmodified
(4) Throughout the entire period, the GIA effect is removed using the ICE6G-D model (Peltier et al., 2018), and the same mean field spanning January 2004 to December 2009 is removed