# Changelog

This is a simple changelog for a Classist. Classist is designed to help you find classes in jars. Classist will recursively walk a filesystem reading in the contents of java archives (ie ears, jars, wars, sars, rars etc). The resulting class files are then searchable using regex. Classist will show you which jars a particular file resides in and will show you all duplicate files within the search directories.

Classist is particularly helpful when attempting to resolve ClassNotFoundExceptions and NoClassDefFoundExceptions as you can search within all your jar/sar/ear/war/rar/par files and add the appropriate entries to you classpath.

Originally developed and maintained on [Google Code](https://code.google.com/archive/p/classist) by luke.biddell.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.0.0]
### Added
- Brew tap on andersonlfeitosa/homebrew-classist
- Readme
- License
- Using Maven to generate dist
- gitignore
