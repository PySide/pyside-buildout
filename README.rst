===========================
PySide development buildout
===========================

.. contents:: **Table of Contents** 

Setting up Your Development Environment
=======================================

To set up a PySide development environment:

    ::

        git clone https://github.com/PySide/pyside-buildout.git PySideDevel
        virtualenv --no-site-packages PySideEnv
        cd PySideDevel
        mkdir downloads
        ../PySideEnv/bin/python bootstrap.py
        bin/buildout
