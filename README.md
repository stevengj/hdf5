# HDF5

This repository is a fork of https://bitbucket.hdfgroup.org/scm/hdffv/hdf5.git
with the goal of making a cross-compilable version of [HDF5](https://support.hdfgroup.org/HDF5/).

In particular, it modifies the HDF5 `configure` script to take
advantage of the `autoconf` cross-compilation features, in order to
rewrite feature tests to no longer rely on running executables on
the build machine.

This is a work in progress, with the eventual goal of submitting
a patch to the official HDF5 repository.  See the `cross` branch
for the cross-compiling version.
