# PDC
Potential Derived Charges for molecular mechanics
        Alexei Nikitin and Vladimir Chekhov

A program for extracting partial charges on atoms from the electrostatic 
potential calculated by the quantum chemical program ORCA 
https://orcaforum.kofo.mpg.de


Features

* Extracting the PDC from the MyMol.vpot electrostatic potential file 
  generated by ORCA.
* Fixing the charge of the molecule.
* Per component fixation of the dipole moment of a molecule.


Usage

Put the PDC.exe, MyMol.vpot and MyMol.out files in one folder.
Put the model of the molecule in the model.xyz file.
Run the calculation by 
  PDC.exe MyMol.vpot MyMol.out >PDC_result.txt 
or 
  PDC.bat

The output of the program is in the PDC_result.txt file.
Models of molecules with partial charges on atoms are in the files:
PDC_result.xyz in .xyz format,
PDC_p.mlm      in .mlm format http://www.biomolecular-modeling.com/Abalone/index.html


