# classist

[![Build Status](https://travis-ci.org/andersonlfeitosa/classist.svg?branch=master)](https://travis-ci.org/andersonlfeitosa/classist)

Classist is designed to help you find classes in jars. Classist will recursively walk a filesystem reading in the contents of java archives (ie ears, jars, wars, sars, rars etc). The resulting class files are then searchable using regex. Classist will show you which jars a particular file resides in and will show you all duplicate files within the search directories.

Classist is particularly helpful when attempting to resolve ClassNotFoundExceptions and NoClassDefFoundExceptions as you can search within all your jar/sar/ear/war/rar/par files and add the appropriate entries to you classpath.

Originally developed and maintained on [Google Code](https://code.google.com/archive/p/classist) by luke.biddell.