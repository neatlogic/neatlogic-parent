[中文](README.md) / English

neatlogic-parent is used to manage the reference versions of each package in the entire neatlogic project.

In order to be compatible with references in both the production environment and the development environment,
neatlogic-parent will always only have the release version. Every time you modify the pom file, you need to increase the
minor version number and refresh the maven cache.

The pom file comes with two profiles, develop and release, which can be adjusted as needed during debugging.