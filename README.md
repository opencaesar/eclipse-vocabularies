# Eclipse Vocabularies

[![Build Status](https://travis-ci.org/opencaesar/eclipse-vocabularies.svg?branch=master)](https://travis-ci.org/opencaesar/eclipse-vocabularies)
[![Download](https://api.bintray.com/packages/opencaesar/ontologies/eclipse-vocabularies/images/download.svg)](https://bintray.com/opencaesar/ontologies/eclipse-vocabularies/_latestVersion)

This is a set of vocabularies from the Eclipse [MDT](https://www.eclipse.org/modeling/mdt) Project expressed in [OML](https://github.com/opencaesar/oml)

The provided vocabularies include [UML2](https://www.eclipse.org/modeling/mdt/?project=uml2) and [BPMN2](https://www.eclipse.org/modeling/mdt/?project=bpmn2).

## Clone
```
  git clone https://github.com/opencaesar/eclipse-vocabularies.git
  cd eclipse-vocabularies
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