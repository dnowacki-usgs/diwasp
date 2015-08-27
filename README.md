# diwasp

Fork of DIWASP 1.4, available at http://www.metocean.co.nz/support/resources/

This repo has modifications I found necessary in order to run without issue

In particular:

* Limit the number of iterations in wavenumber.m (imax = 20) to prevent endless loops that won't converge
* Capitalization on call to hsig in infospec.m
