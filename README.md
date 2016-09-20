# Evaluate'em All
Web Application for knowledge evaluations

## Documentation
See the current [available documentation][]

## Issue Tracking
Report issues via the [Evaluate'em All Trello][]

## Building from Source
Evaluate'em All uses a [Maven][]-based build system. In the instructions below, `mvn` is invoked from the root of the source tree and servces as a cross-patform, self-contained bootstrap mechanism for the build.

### Prerequisites
[Git][] and [JDK 8 update 20 or later][JDK8 build]

Be sure that your `JAVA_HOME` environment variable points to the `jdk1.8.0` folder
extracted from the JDK download.

### Check out sources
`git clone git@github.com:evaluatethemall/evaluatethemall.git`

### Import sources into your IDE
In IDE import project as existing Maven project. IDE will load automatically all required dependencies with their sources.

### Compile and test; build all jars, distribution zips, and docs
`mvn clean install`

[available documentation]: https://github.com/evaluatethemall/evaluatethemall/documentation
[Evaluate'em All Trello]: https://trello.com/b/0lytDFVu/evaluate-em-all-public-issues
[Maven]: https://maven.apache.org/
[Git]: http://help.github.com/set-up-git-redirect
[JDK8 build]: http://www.oracle.com/technetwork/java/javase/downloads
