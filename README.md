[![Build Status](https://github.com/scijava/scijava-links/actions/workflows/build.yml/badge.svg)](https://github.com/scijava/scijava-links/actions/workflows/build.yml)

This package provides a subsystem for SciJava applications
that enables handling of URI-based links via plugins.

It is kept separate from the SciJava Common core classes
because it requires Java 11 as a minimum, due to its use
of java.awt.Desktop features not present in Java 8.
