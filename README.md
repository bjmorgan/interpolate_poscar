# interpolate_poscar

Interpolates two VASP POSCAR files using the command

    interpolate_poscar <POSCAR1> <POSCAR2>

writing the interpolated POSCAR file to STDOUT.

Issues:

* No checking for the existence of files, or that POSCAR1 and POSCAR2 are compatible.
* Ignores periodic boundary conditions and the minimum image convention.
