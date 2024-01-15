Ulearn Comunitats Plone 5
=========================

This is the ultimate-uber-maxi-definitive-awesomefull buildout for Comunitats
projects.

Usage
-----

 $ create venv python 2.7.18

 $ cp customizeme.cfg.in customizeme.cfg

 $ /venv/bin/python bootstrap.py --setuptools-version 38.7.0 -c buildout.cfg --buildout-version=2.13.4

 $ bin/buildout -N -c ulearn.cfg


Check out for the available projects in the projects.cfg file.

.. note:: Before that, remember to copy the customizeme.cfg.in file into customizeme.cfg configuring the required parameters.

* Copy versions.cfg, sources.cfg and project.cfg from a prod / pre environment.
