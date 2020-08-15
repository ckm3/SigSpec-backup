# SigSpec-backup
Here is an unofficial backup of SigSpec (abbreviation of `SIGnificance SPECtrum'), which is a program that computes a significance spectrum for a time series, developed by Piet Reegen.

SigSpec is primarily used in asteroseismology to identify variable stars and to classify stellar pulsation. The fact that this method incorporates the properties of the time-domain sampling appropriately makes it a valuable tool for typical astronomical measurements containing data gaps.

## Usage
For Windows build: 

No installation required! Just download the link target above. It is ready to use.

For Linux/Unix:

Recommended compilation via

    gcc -lm -O3 -o SigSpec SigSpec.c

## Online manual
[Online Manual](https://ckm3.github.io/SigSpec-backup/). The PDF version is availble on https://arxiv.org/abs/1006.5081

## Citing
Please cite [Reegen, P., 2007A&A, 467, 1353](https://www.aanda.org/articles/aa/abs/2007/21/aa6597-06/aa6597-06.html), if you find this code useful in your research.
