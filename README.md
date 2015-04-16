fabric-scripts
======================

[![Build Status](https://travis-ci.org/paulocheque/fabric-scripts.png?branch=master)](https://travis-ci.org/paulocheque/fabric-scripts)
[![Docs Status](https://readthedocs.org/projects/fabric-scripts/badge/?version=latest)](http://fabric-scripts.readthedocs.org/en/latest/index.html)
[![Coverage Status](https://coveralls.io/repos/paulocheque/fabric-scripts/badge.png?branch=master)](https://coveralls.io/r/paulocheque/fabric-scripts?branch=master)
[![Code Status](https://landscape.io/github/paulocheque/fabric-scripts/master/landscape.png)](https://landscape.io/github/paulocheque/fabric-scripts/)
[![PyPi version](https://pypip.in/v/fabric-scripts/badge.png)](https://crate.io/packages/fabric-scripts/)
[![PyPi downloads](https://pypip.in/d/fabric-scripts/badge.png)](https://crate.io/packages/fabric-scripts/)

**Latest version: 0.0.16 (2014/09)**

Small description.

Install
-------------

    sudo pip install fabric
    sudo pip install fabric-scripts

Upgrade
-------------

    sudo pip install fabric-scripts --upgrade

Documentation
-------------

http://fabric-scripts.readthedocs.org/en/latest/index.html


Troubleshooting
----------------

Fixing upgrade issue caused by Pip bug:

    sudo rm -rf /private/tmp/pip-build-root/fabric-scripts/
    sudo pip install fabric-scripts --upgrade
    python -c "import fab_scripts ; print(fab_scripts.VERSION)"
