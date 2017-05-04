Program to see the contribution of each orbital of each atom for an specific k-point, from VASP results. Version 1.0 MAR 2017

This program sum the contribution of each orbital for each atom for an specific k-point. The results are given in percentage. The PROCAR and OUTCAR files of VASP are necessary.

Compile using:

g++ -o vbmcharacter vbmcharacter1.0c

Run given as argument the number of the band you want to analize and the number of k-point. Ex: vbmcharacter 20 1
