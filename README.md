# OMG Vocabularies

[![Build Status](https://travis-ci.org/opencaesar/omg-vocabularies.svg?branch=master)](https://travis-ci.org/opencaesar/omg-vocabularies)

This is a set of OMG vocabularies expressed in [OML](https://github.com/opencaesar/oml)

## Clone
```
  git clone https://github.com/opencaesar/omg-vocabularies.git
  cd omg-vocabularies
```

## Build
Equivalent to owlReason task
```
./gradlew build
```

## Generate Docs
You must first have Bikeshed (the app itself) installed from [here](https://tabatkins.github.io/bikeshed/#install-final)
```
./gradlew generateDocs
```
Note: running the `generateDocs` target assumes you have run the `build` target previously

## Publish to Maven Local
```
./gradlew publishToMavenLocal
```

[ ![Download](https://api.bintray.com/packages/opencaesar/ontologies/jpl-vocabularies/images/download.svg) ](https://bintray.com/opencaesar/ontologies/jpl-vocabularies/_latestVersion)
