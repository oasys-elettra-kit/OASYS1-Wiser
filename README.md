# Links and Contacts

OasysWiser has not an offical page yet :-/

Please, check this session for updates. :-)

Main contact: michele.manfredda@elettra.eu

# Wiser for OASYS
----------

OasysWiser is the GUI part of Wiser in Oasys. 

Hierarchy:
* LibWiser - Python implementation of WISE (numerical integration using Huygens integral)
* WofryWiser - intermediate layer, taking care of compatibility with the rest of Oasys packages
* OasysWiser - GUI part, calling WofryWiser intermediate routines

Installation
----------

1) Install the latest version of OASYS. This can be found here:

https://github.com/oasys-kit/oasys-installation-scripts/wiki/Install-Oasys-in-Windows-10

2) Update OasysWiser through Oasys add-on manager. That is:

    a) In Oasys: Menu Options -> Add-ons...", then in the window click "Add more..."
    
    b) Type "OASYS1-OasysWiser" and install it
   
3) Restart OASYS.

    a) If it complains about WofryWiser, then install WofryWiser and LibWiser manually through add-on manager [advanced users]. Restart OASYS again.
    
    b) If you are experiencing other issues, please report them
    
    
3. There is a problem with engineering_notation package, as it seems that it can't be installed automatically (I don't know why, yet), so install manually using pip install engineering_notation


[old... forget this]
----------
OasysWiser will be pip installable (https://pip.pypa.io/) by:

    pip install oasyswiser

to install it.

