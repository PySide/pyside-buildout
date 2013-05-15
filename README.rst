Setting up Your Development Environment
=======================================

To set up a PySide development environment:

    ::

        git clone https://github.com/PySide/pyside.buildout ./PySideDevel
        virtualenv --no-site-packages PySideEnv
        cd PySideDevel
        ../PySideEnv/bin/python bootstrap.py
        bin/buildout
