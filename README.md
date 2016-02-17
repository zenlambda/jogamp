# JOGAMP

## Deprecation notice

JOGL builds are now pushed to maven repository so it is no longer necessary to install the JARs yourself or 
do any fancy build as we do where. For more info [read here](https://jogamp.org/wiki/index.php/Maven).

This project mainly now serves as an example of one way to import 3rdparty libraries into maven.

## About

A maven project that installs the JOGAMP libraries as JARs in maven from a distribution archive.

## Dependencies and Prerequisites

This build needs a 7z unpacking plugin which isn't in maven central. The un7z-maven-plugin plugin therefore
needs to be [installed from source](https://github.com/zenlambda/un7z-maven-plugin) before this build can be run.
