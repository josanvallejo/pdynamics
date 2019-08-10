# pdynamics
## A Maxima package for computation in Poisson dynamics

A Maxima package called `pdynamics` is described. It is
aimed to study Poisson (and symplectic) systems and, particularly,
the determination of the second-order normal form for perturbed
Hamiltonians H=H<sub>0</sub> +&epsilon; H<sub>1</sub> +&epsilon;<sup>2</sup> H<sub>2</sub>,
relative to the periodic flow of the unperturbed Hamiltonian H<sub>0</sub>.
The formalism presented here is global, it does
not require recursive computations and allows an efficient symbolic implementation.

To use the package, simply copy the file `pdynamics.mac` in the
`contrib` directory of your Maxima installation (in a Unix box
this directory will be something as `/usr/share/maxima/5.42.0/share/contrib`,
 depending on the version number, and you will need root permissions for that,
while in a Windows machine it will be located at
`C:\Program Files\Maxima-5.42.0\share\maxima\5.42.0\share\contrib`).
Another good option is to keep a copy of `pdynamics.mac` in your working directory
(that is, the same directory where you are storing your current Maxima session). In both cases,
it suffices to execute `load("pdynamics.mac")` at the Maxima prompt.

If you place the file somewhere else you can use the Maxima `file_search` command to tell the system where it is,
as in `file_search("/home/johndoe/maxima/pdynamics.mac"`.

The file `pdynamics-doc.pdf` contains a detailed description of the functions in the package, along with many examples of applications. There is also a session file `pdynamics-doc.wxm`, containing all the commands in `pdynamics-doc.pdf` (it can be executed in batch mode).
