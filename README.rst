nu Octantis
========

This is a repository for posterior samples of the nu Octantis system. Methodological and science details can be found at `this arXiv link <http://arxiv.org/abs/1605.06720>`_.


How to read these files
-----------------------

The two files listed above contain posterior samples directly from the RV observations (raw). Each line is a posterior sample containing 54 values. They read as follows.


MCMC information::

    Column 1: Markov chain generation
    Column 2: Markov chain index
    Column 3: Chi squared with jitter penalty term


Orbital Parameter information. Each companion has 9 parameters::

    Columns 4, 13: Orbital period in [days] for companions "b" and "B" respectively.
    Columns 5, 14: RV half amplitude in [m/s] for companions "b" and "B" respectively.
    Columns 6, 15: mass in [solar masses] for companions "b" and "B" respectively.
    Columns 7, 16: semi-major axis in [AU] for companions "b" and "B" respectively.
    Columns 8, 17: eccentricity for companions "b" and "B" respectively.
    Columns 9, 18: inclination in [degrees] for companions "b" and "B" respectively.
    Columns 10, 19: argument of pericenter in [degrees] for companions "b" and "B" respectively.
    Columns 11, 20: longitude of ascending node in [degrees] for companions "b" and "B" respectively.
    Columns 12, 21: mean anomaly at the epoch of the first HERCULES observation in [degrees] for companions "b" and "B" respectively.


Instrumental parameter information::

    Column 30: 4kx4k CCF RVs offset
    Column 31: 4kx4k iodine RVs offset
    Column 32: 1kx1k CCF RVs offset

    Column 33: 4kx4k CCF RVs jitter
    Column 34: 4kx4k iodine RVs jitter
    Column 35: 1kx1k CCF RVs jitter


Supplementary information::

    Column 36: Chi squared without jitter
    Column 37: Run length (number of subsequent states in the Markov chain without an Metropolis-Hastings acceptance)
    Column 38: Chi squared with jitter (no penalty term)
    Column 39: Stellar mass in [solar masses]
    Column 40: Mutual inclination [degrees]


Attribution
-----------

Please cite `this <http://adsabs.harvard.edu/abs/2015arXiv150407995N>`_ if you use these posterior samples in your research.

The BibTeX entry for the paper is::

    @ARTICLE{2015arXiv150407995N,
	author = {{Ramm}, D.~J. and {Nelson}, B.~E. and {Endl}, M. and {Wittenmyer}, R.~A. and {Gunn}, F. and {Bergmann}, C. and {Kilmartin}, P. and {Erogt}, E. },
         title = "{The conjectured S-type retrograde planet in nu Octantis: more evidence including four years of iodine-cell radial velocities}",
       journal = {ArXiv e-prints},
 archivePrefix = "arXiv",
        eprint = {1605.06720},
  primaryClass = "astro-ph.EP",
      keywords = {Astrophysics - Earth and Planetary Astrophysics},
          year = 2016,
        adsurl = {http://adsabs.harvard.edu/abs/2016arXiv160506720R},
       adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }
