.. _install-scancode:

Installing ScanCode
===================

.. toctree::
   :maxdepth: 2
   :hidden:

   install-scancode-from-release-archives
   install-scancode-via-docker
   install-scancode-from-source
   install-scancode-via-pip

.. note::

    ScanCode requires a Python version between 3.9 to 3.13 and is tested on Linux, macOS, and Windows


The recommended way to install ScanCode from its release archives:

- :ref:`install-scancode-from-release-archives`

    The recommended method is to download the latest application release as an
    application and then configure and use directly. No knowledge of pip/git or
    other developer tools is necessary. You only need to install Python then
    download and extract the ScanCode application archive to run ScanCode.
    For standard usage that's all you need.


For advanced usage and experienced users, you can also use any of the following methods to install ScanCode:

- :ref:`install-scancode-via-docker`

    An alternative to installing the latest ScanCode-Toolkit release natively is
    to build a Docker image from the included Dockerfile. The only prerequisite
    is a working Docker installation.

- :ref:`install-scancode-from-source`

    You can clone the git source code repository and then run the configure script
    to configure and install ScanCode for local and development usage.

- :ref:`install-scancode-via-pip`

    To use ScanCode as a library in your application, you can install it via
    ``pip``. This is recommended for developers or users familiar with Python
    that want to embed ScanCode as a library.

- Install from Fedora’s repository

    ScanCode is part of main Fedora Linux repository in Fedora 40 and newer. 
    This is recommended for production deployments.


    Install ScanCode from the command line interface using:

    .. code-block:: shell

        dnf install scancode-toolkit

    To uninstall ScanCode, run:

    .. code-block:: shell

        dnf remove scancode-toolkit


.. _installing-scancode-system-requirements:

System requirements
-------------------

- Hardware : ScanCode will run best with a modern X86 64 bits processor and at
  least 8GB of RAM and 2GB of disk space. These are minimum requirements.

- Supported operating systems: ScanCode should run on these 64-bit OSes running
  X86_64 processors:

    #. Linux: on recent 64-bit Linux distributions,
    #. Mac: on recent x86 64-bit macOS (10.15 and up, including 11 and 12),
       Use the X86 emulation mode on Apple ARM M1 CPUs.
       (Note that `pip install` does not work on ARM CPUs)
    #. Windows: on Windows 10 and up,
    #. FreeBSD.
