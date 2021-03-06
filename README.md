roboptim-core-plugin-ipopt
==========================

[![Build Status](https://travis-ci.org/roboptim/roboptim-core-plugin-ipopt.png?branch=master)](https://travis-ci.org/roboptim/roboptim-core-plugin-ipopt)
[![Coverage Status](https://coveralls.io/repos/roboptim/roboptim-core-plugin-ipopt/badge.png)](https://coveralls.io/r/roboptim/roboptim-core-plugin-ipopt)

![LGPL-3](https://www.gnu.org/graphics/lgplv3-88x31.png)


[![Zenodo](https://zenodo.org/badge/doi/10.5281/zenodo.10332.png)](http://zenodo.org/record/10332)

This package is the IPOPT plug-in of the RobOptim framework. It is
released under the [LGPL-3](COPYING.LESSER) license.

**Warning:** this repository contains [Git
submodules][git-submodules]. Please clone this repository using the
`git clone --recursive` command. If you already have cloned the
repository, you can run `git submodule init && git submodule update`
to retrieve the submodules.


For general information about the project, please refer to its
homepage: http://www.roboptim.net/


Documentation
-------------

To get started with this library, please read the [online Doxygen
documentation][doxygen-documentation].

It can also be generated locally by running the `make doc`
command. After the package is installed, the documentation will be
located in the `$prefix/share/doc/roboptim-core` directory where
`$prefix` is your installation prefix (`/usr/local` by default).


Getting Help
------------

Support is provided through:
 * the RobOptim mailing-list: roboptim@googlegroups.com
 * the following HipChat room: http://www.hipchat.com/gh4wQrZeV


Contributing
------------

If you want to contribute, please refer to the
[CONTRIBUTING.md](CONTRIBUTING.md) file.


Credits
-------

This package authors are credited in the [AUTHORS](AUTHORS) file.


Available packages
------------------

 * Arch Linux (Git master branch):
   https://aur.archlinux.org/packages/roboptim-core-plugin-ipopt-git/
 * Mac OS X Homebrew Formula (Git HEAD):
   https://www.github.com/roboptim/homebrew-roboptim

[doxygen-documentation]: http://www.roboptim.net/roboptim-core-plugin-ipopt/doxygen/HEAD/

[git-submodules]: http://git-scm.com/book/en/Git-Tools-Submodules

[Boost]: http://www.boost.org/
[CMake]: htttp://www.cmake.org/
[Doxygen]: http://www.stack.nl/~dimitri/doxygen/
[Eigen]: http://eigen.tuxfamily.org/
[Git]: http://git-scm.com/
[Libtool]: https://www.gnu.org/software/libtool/
[log4cxx]: https://logging.apache.org/log4cxx/
[pkg-config]: http://www.freedesktop.org/wiki/Software/pkg-config/
[RobotPkg]: http://robotpkg.openrobots.org/
