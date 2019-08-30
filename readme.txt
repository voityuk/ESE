Executables for WINDOWS (ese.exe) and LINUX (ese.x) are provided.

Input file for the ESE program contains two section 

(1) atomic coordinates of the system and

(2) atomic charges. 

Also any comments may be included. 

(1) The atomic coordinate section begins with a line containing 'Atomic coordinates' 
followed by N lines (one line per atom) with an atomic number  (or the corresponding element symbol)
and XYZ coordinates in Angstroms. The section ends with a blank line.


(2) The section of atomic charges begins with a line containing 'Ground state charges'.
the following lines should contain N atomic charges  separated by a one or several spaces.
The section ends with a blank line.

An example of the input file is given below.
----------------------------
 0217wat ESP charges

 Atomic coordinates
   8        0.0000      0.0000      0.1164
   1        0.0000      0.7614     -0.4656
   1        0.0000     -0.7614     -0.4656

 Ground state charges
 -0.7573  0.3787  0.3787

------------------------------
