.. image:: https://zenodo.org/badge/doi/10.5281/zenodo.11567.png
  :target: http://dx.doi.org/10.5281/zenodo.11567

PDQ2
====

Pretty darn quick interpolating arbitrary waveform generator.


Build
-----

Get Migen: https://github.com/m-labs/migen

$ python3 make.py


Testbenches
-----------

$ python3 -m testbench.escape
$ python3 -m testbench.dac
$ python3 -m testbench.pdq2 -x


References
----------

Arbitrary waveform generator for quantum information processing with trapped
ions; R. Bowler, U. Warring, J. W. Britton, B. C. Sawyer and J. Amini;
Rev. Sci. Instrum. 84, 033108 (2013);
http://dx.doi.org/10.1063/1.4795552
http://tf.boulder.nist.gov/general/pdf/2668.pdf

Coherent Diabatic Ion Transport and Separation in a Multizone Trap Array;
R. Bowler, J. Gaebler, Y. Lin, T. R. Tan, D. Hanneke, J. D. Jost, J. P. Home,
D. Leibfried, and D. J. Wineland; Phys. Rev. Lett. 109, 080502;
http://dx.doi.org/10.1103/PhysRevLett.109.080502
http://tf.boulder.nist.gov/general/pdf/2624.pdf
