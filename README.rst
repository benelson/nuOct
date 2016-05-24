GJ876
========

This is a repository for posterior samples of the Gliese 876 planetary system. Methodological and science details can be found at `this arXiv link <http://arxiv.org/abs/1605.06720>`_.


How to read these files
-----------------------

The two files listed above contain posterior samples directly from the RV observations (raw). Each line is a posterior sample containing 54 values. They read as follows.


MCMC information::

    Column 1: Markov chain generation
    Column 2: Markov chain index
    Column 3: Chi squared with jitter penalty term


Orbital Parameter information. Each planet has 9 parameters::

    Columns 4, 13: Orbital period in [days] for planets "d", "c", "b", and "e" respectively.
    Columns 5, 14: RV half amplitude in [m/s] for planets "d", "c", "b", and "e" respectively.
    Columns 6, 15: mass in [solar masses] for planets "d", "c", "b", and "e" respectively.
    Columns 7, 16: semi-major axis in [AU] for planets "d", "c", "b", and "e" respectively.
    Columns 8, 17: eccentricity for planets "d", "c", "b", and "e" respectively.
    Columns 9, 18: inclination in [degrees] for planets "d", "c", "b", and "e" respectively.
    Columns 10, 19: argument of pericenter in [degrees] for planets "d", "c", "b", and "e" respectively.
    Columns 11, 20: longitude of ascending node in [degrees] for planets "d", "c", "b", and "e" respectively.
    Columns 12, 21: mean anomaly at the epoch of the first Lick observation in [degrees] for planets "d", "c", "b", and "e" respectively.


Instrumental parameter information::

    Columns 30: Carnegie HIRES RV offsets


    Column 46: Carnegie HIRES RV jitter


Supplementary information::

    Column 51: Chi squared without jitter
    Column 52: Run length (number of subsequent states in the Markov chain without an Metropolis-Hastings acceptance)
    Column 53: Chi squared with jitter (no penalty term)
    Column 54: Stellar mass in [solar masses]


Attribution
-----------

Please cite `this <http://adsabs.harvard.edu/abs/2015arXiv150407995N>`_ if you use these posterior samples in your research.

The BibTeX entry for the paper is::

    @ARTICLE{2015arXiv150407995N,
	author = {{Nelson}, B.~E. and {Robertson}, P. and {Payne}, M.~J. and {Pritchard}, S.~M. and {Deck}, K.~M. and {Ford}, E.~B. and {Wright}, J.~T. and {Isaacson}, H. },
         title = "{An Empirically Derived Three-Dimensional Laplace Resonance in the Gliese 876 Planetary System}",
       journal = {ArXiv e-prints},
 archivePrefix = "arXiv",
        eprint = {1504.07995},
  primaryClass = "astro-ph.EP",
      keywords = {Astrophysics - Earth and Planetary Astrophysics},
          year = 2015,
         month = apr,
        adsurl = {http://adsabs.harvard.edu/abs/2015arXiv150407995N},
       adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }
