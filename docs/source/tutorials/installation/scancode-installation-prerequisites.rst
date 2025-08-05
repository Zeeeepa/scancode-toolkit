.. _scancode-installation-prerequisites

ScanCode installation prerequisites
===================================

ScanCode needs a Python 3.9+ interpreter; We support all Python versions from
3.9 to 3.12. The default version for the application archives is Python 3.9

Linux
-----

    Use your package manager to install ``python3``.

    For Ubuntu, it is ``sudo apt install python3-dev``

    - On Ubuntu 16, 18, 20 ,22 and 24 run::

          sudo apt install python-dev bzip2 xz-utils zlib1g libxml2-dev libxslt1-dev libpopt0

    - On Debian and Debian-based distros run::

          sudo apt-get install python3-dev libbz2-1.0 xz-utils zlib1g libxml2-dev libxslt1-dev libpopt0

    - On RPM-based distros run::

          sudo yum install python3.9-devel zlib bzip2-libs xz-libs libxml2-devel libxslt-devel libpopt0

    - On Fedora 22 and later run::

          sudo dnf install python3.9-devel xz-libs zlib libxml2-devel libxslt-devel bzip2-libs libpopt0


    If these packages are not available from your package manager, you must
    compile them  from sources.


MacOS
-----

    The default Python 3 provided with macOS is 3.9.
    Alternatively you can download and install Python 3.9 from https://www.python.org/


Windows
-------

    Download and install Python 3.9 from https://www.python.org/

    .. Note::

      64-bit Python interpreters (x86-64) are the only interpreters supported by
      ScanCode on all operating systems which means only 64-bit Windows is supported.

    See the :ref:`windows_app_install` section for more installation details.