# uml-vocabulary

[![Build Status](https://travis-ci.org/opencaesar/uml-vocabulary.svg?branch=master)](https://travis-ci.org/opencaesar/uml-vocabulary)
[ ![Download](https://api.bintray.com/packages/opencaesar/uml-vocabulary/uml-vocabulary/images/download.svg) ](https://bintray.com/opencaesar/uml-vocabulary/uml-vocabulary/_latestVersion)

The [UML](https://www.omg.org/spec/UML/) vocabulary expressed in [OML](https://opencaesar.github.io/oml/)

## Pre-requisite
The ecore2oml process is required to build this repository. Until a publc release of this process is available on Bintrary, you can clone it, build it, and publish it to your local maven repo as follows:

On Linux/MacOS
```
git clone https://github.com/opencaesar/ecore-adapter.git
cd ecore-adapter/ecore-adapter
./gradlew build
./gradlew publishToMavenLocal
```
On Windows
```
git clone https://github.com/opencaesar/ecore-adapter.git
cd ecore-adapter/ecore-adapter
gradlew.bat build
gradlew.bat publishToMavenLocal
```

## Clone
```
  git clone https://github.com/opencaesar/uml-vocabulary.git
  cd uml-vocabulary
```

## Build
On Linux/MacOS
```
./gradlew build
```
On Windows
```
gradlew.bat build
```
The UML vocabulary should be in the `build/oml/www.eclipse.org/uml2` folder`
