[![Documentation Status](https://readthedocs.org/projects/py12box/badge/?version=latest)](https://py12box.readthedocs.io/en/latest/?badge=latest)

# AGAGE 12-box model with ocean 4-box model

This is a modified version of the AGAGE 12-box model (https://github.com/mrghg/py12box, see details here for AGAGE 12-box model) to  include the 4-box ocean model of Wang et al. (2021) https://doi.org/10.1073/pnas.2021528118 with modified transport timescales.
This makes a 16-box ocean-atmosphere model.

## Installation

I haven't tried this, but you may be able to install it using:

```pip install git+https://github.com/lukewestern/py12box_ocean.git#egg=py12box_ocean```

## Getting started

The usage is the same as the 12-box model. The exception is that the piston velcoty (air-sea exchange velocity) and ocean degradation half-life must be set in species_ocean_ info.csv

Please read the documentation [here](https://py12box.readthedocs.io/en/latest/index.html).

Also see examples of usage in [this repository](https://github.com/mrghg/py12box) under the "notebooks" folder.

## References

Cunnold, D. M., Prinn, R. G., Rasmussen, R. A., Simmonds, P. G., Alyea, F. N., Cardelino, C. A., Crawford, A. J., Fraser, P. J. and Rosen, R. D.: The Atmospheric Lifetime Experiment 3. Lifetime Methodology and Application to Three Years of CFCl3 Data, Journal of Geophysical Research, 88(C13), 8379–8400, 1983.

Cunnold, D. M., Fraser, P. J., Weiss, R. F., Prinn, R. G., Simmonds, P. G., Miller, B. R., Alyea, F. N. and Crawford, A. J.: Global trends and annual releases of CCI3F and CCI2F2 estimated from ALE/GAGE and other measurements from July 1978 to June 1991, Journal of Geophysical Research, 99(D1), 1107–1126, [doi:10.1029/93JD02715](https://doi.org/10.1029/93JD02715), 1994.

Rigby, M., Prinn, R. G., O’Doherty, S., Montzka, S. a., McCulloch, A., Harth, C. M., Mühle, J., Salameh, P. K., Weiss, R. F., Young, D., Simmonds, P. G., Hall, B. D., Dutton, G. S., Nance, D., Mondeel, D. J., Elkins, J. W., Krummel, P. B., Steele, L. P. and Fraser, P. J.: Re-evaluation of the lifetimes of the major CFCs and CH3CCl3 using atmospheric trends, Atmospheric Chemistry and Physics, 13(5), 2691–2702, [doi:10.5194/acp-13-2691-2013](https://doi.org/10.5194/acp-13-2691-2013), 2013.

Wang, P., Scott, J.R., Solomon, S., Marshall, J., Babbin, A.R., Lickley, M., Thompson, D.W., DeVries, T., Liang, Q. and Prinn, R.G., 2021. On the effects of the ocean on atmospheric CFC-11 lifetimes and emissions. Proceedings of the National Academy of Sciences, 118(12), p.e2021528118.