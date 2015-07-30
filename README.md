GNU Datamash Galaxy Tools
=========================

This repository contains Galaxy tools for GNU Datamash.

**WARNING**: This repository uses the development branch
of GNU Datamash, with new features which are not yet
in the stable version.

License
-------
Copyright (C) 2015 Assaf Gordon (assafgordon@gmail.com).

The files in this repository are licensed under
BSD-3-Clause license.

More information
----------------

GNU Datamash : http://www.gnu.org/software/datamash 

Galaxy: https://usegalaxy.org/


Testing
-------

First clone a galaxy repository:

    git clone https://github.com/galaxyproject/galaxy

Then clone this repository:

    git clone https://github.com/agordon/tools-datamash-next

Install [Planemo](https://github.com/galaxyproject/planemo/)
(see [Planemo Quick-Start](https://planemo.readthedocs.org/en/latest/readme.html))

    brew tap galaxyproject/tap
    brew install planemo

And test the tools with:

    cd tools-datamash
    planemo test --galaxy_root=../galaxy tools
