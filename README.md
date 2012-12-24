===========
latex-local
===========

Personal Latex/ Beamer styles.
This is a collection of personal latex bibliographies, shorthands, and styles.

Installation
============

This repo is typically stored in the home directory. Letting the LaTeX engine
know about it can be done several ways.

1. Place the repo in the directory ~/texmf/texmf-local or wherever is pointed
to by the system installation's tex.cnf file.

2. Export the environment variable TEXMFHOME to point to the repo. This method
works well on systems without admin access where one wishes to keep their home
directory uncluttered.
