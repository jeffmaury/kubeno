# `kubeno`: kubens for OpenShift

![Latest GitHub release](https://img.shields.io/github/release/jeffmaury/kubeno.svg)
[![Build](https://github.com/jeffmaury/kubeno/workflows/Build/badge.svg)](https://github.com/jeffmaury/kubeno/actions?query=workflow%3A"Build")
![Proudly written in Java](https://img.shields.io/badge/written%20in-Java-ff69b4.svg)

This repository provides both `kubeno` tool.
[Install &rarr;](#installation)


# kubeno(1)

kubeno is a utility to switch between Kubernetes/OpenShift namespaces.

```
USAGE:
  kubeno                    : list the namespaces
  kubeno <NAME>             : change the active namespace
```


### Usage

```sh
$ kubeno kube-system
Active namespace is "kube-system".
```


## Installation

There are several installation options:

- Using jbang (https://github.com/jbangdev/jbang)
- Using Java command line

### jbang

Once you have jbang installed (see https://www.jbang.dev/download), just run:

```sh
jbang https://github.com/jeffmaury/kubeno/tree/main/src/main/java/kubeno.java
```

You can also use jbang to install it locally:

```sh
jbang app install https://github.com/jeffmaury/kubeno/tree/main/src/main/java/kubeno.java
```

and then use:

```sh
kubeno
```

### Java command line

Download the latest `kubeno` jar from here: https://github.com/jeffmaury/kubeno/releases/latest

Then, run `kubeno` using the Java command line:

```sh
java -jar kubeno.jar
```

