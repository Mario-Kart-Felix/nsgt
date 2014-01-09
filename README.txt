Python implementation of Non-Stationary Gabor Transform (NSGT)
derived from MATLAB code by NUHAG, University of Vienna, Austria

Thomas Grill, 2011-2012
http://grrrr.org/nsgt

Austrian Research Institute for Artificial Intelligence (OFAI)
AudioMiner project, supported by Vienna Science and Technology Fund (WWTF)


covered by Creative Commons Attribution-NonCommercial-ShareAlike license (CC BY-NC-SA)
http://creativecommons.org/licenses/by-nc-sa/3.0/at/deed.en

-----


Mandatory dependencies:
-----------------------
Numerical Python (http://numpy.scipy.org)

Optional dependencies:
-----------------------
PyFFTW3 (https://launchpad.net/pyfftw)
will greatly speed up the NSGT transformation is fftw3 is installed on your system

scikits.audiolab (http://pypi.python.org/pypi/scikits.audiolab)
is needed for using the built-in audio import/streaming functionality


Installation:
-------------

In the console (terminal application) change to the folder containing this readme.txt file.

To build the package run the following command:
python setup.py build

To install the package (with administrator rights):
sudo python setup.py install


Todo:
-----

- Quality measurement for coefficients of sliced transform
- Unify nsgfwin sliced/non-sliced


--
Original matlab code copyright follows:

AUTHOR(s) : Monika D�rfler, Gino Angelo Velasco, Nicki Holighaus, 2010-2011

COPYRIGHT : (c) NUHAG, Dept.Math., University of Vienna, AUSTRIA
http://nuhag.eu/
Permission is granted to modify and re-distribute this
code in any manner as long as this notice is preserved.
All standard disclaimers apply.
