# Correlade Package

Pearson correlation only really detects linear relationships. Distance Correlation is a better measure, detecting more varied dependency relationships between variables. 

This package aims to give a one-liner that'll be super useful for preliminary data analysis **in Pandas**, producing a matrix of pairwise distance correlations and also a heatmap of these reults.

Because this correlation measure is more computationally expensive, if you feed it more than 2000 observations it will randomly select 2000 rows on which to base the calculation.  

To install:

```
pip3 install cython <br>
pip3 install git+https://github.com/hoihui/distcorr <br>
pip3 install correlade <br>
```

To use: <br>
```
from correlade import correlade <br>
correlade.dcorr(df) <br>
```
