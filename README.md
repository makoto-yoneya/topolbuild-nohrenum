# topolbuild-nohrenum patch

Patch file for [topolbuild][1] ver. 1.3.

## Functions

This patch adds

- "-nohrenum" flag to stop hydrogen atom renumbering

- "-noposresout" flag to stop write out position restraint related files

- environment variable "TOPOLBUILD_DIR" to set absolute directory name of force field data (instead of "-dir" option)

## Prerequisites

Topolbuild1_3 Source: [topolbuld1_3.tar.gz][2]

### Installing

`patch -p1 < topolbuld1_3-nohrenum.patch`

in the top source directory and make.

## Authors

Makoto Yoneya.

[1]: http://www.gromacs.org/Downloads/User_contributions/Other_software
[2]: http://www.gromacs.org/@api/deki/files/93/=topolbuild1_3.tgz
