# OpenCV: Open Source Computer Vision Library
# Minimal Source Package

This repository is intended to provide a working source tree for the
[OpenCV](http://opencv.org) Library with a much smaller download size
than the official package.

The main use case for this repository is build and deployment systems,
where the documentation, sample programs, and extra language bindings
generally serve no puprpose.  If you want to learn OpenCV, it is
highly recommended that you use the official repository and packages.

## Status

I've just started working on this and it's not tested very thoroughly yet.

## Comparison with the official package

This is a manifest of the changes made to this repository vs. the repository at http://github.com/itseez/opencv.

### Removed from the official package
* The entirety of the samples/ directory.
* The entirety of the doc/ directory.
* The entirety of the 3rdparty/ directory.
* The entirety of the data/ directory.

### Changed in this package
* This README.md file

### Size difference

The official OpenCV 2.4.7 source tarball is 81.6 MB compressed and 184 MB decompressed. This repository is 42 MB uncompressed and about 20 MB compressed.
