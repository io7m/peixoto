peixoto
===

[![Maven Central](https://img.shields.io/maven-central/v/com.io7m.peixoto/com.io7m.peixoto.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.io7m.peixoto%22)
[![Maven Central (snapshot)](https://img.shields.io/nexus/s/com.io7m.peixoto/com.io7m.peixoto?server=https%3A%2F%2Fs01.oss.sonatype.org&style=flat-square)](https://s01.oss.sonatype.org/content/repositories/snapshots/com/io7m/peixoto/)
[![Codecov](https://img.shields.io/codecov/c/github/io7m-com/peixoto.svg?style=flat-square)](https://codecov.io/gh/io7m-com/peixoto)
![Java Version](https://img.shields.io/badge/21-java?label=java&color=e6c35c)

![com.io7m.peixoto](./src/site/resources/peixoto.jpg?raw=true)

| JVM | Platform | Status |
|-----|----------|--------|
| OpenJDK (Temurin) Current | Linux | [![Build (OpenJDK (Temurin) Current, Linux)](https://img.shields.io/github/actions/workflow/status/io7m-com/peixoto/main.linux.temurin.current.yml)](https://www.github.com/io7m-com/peixoto/actions?query=workflow%3Amain.linux.temurin.current)|
| OpenJDK (Temurin) LTS | Linux | [![Build (OpenJDK (Temurin) LTS, Linux)](https://img.shields.io/github/actions/workflow/status/io7m-com/peixoto/main.linux.temurin.lts.yml)](https://www.github.com/io7m-com/peixoto/actions?query=workflow%3Amain.linux.temurin.lts)|
| OpenJDK (Temurin) Current | Windows | [![Build (OpenJDK (Temurin) Current, Windows)](https://img.shields.io/github/actions/workflow/status/io7m-com/peixoto/main.windows.temurin.current.yml)](https://www.github.com/io7m-com/peixoto/actions?query=workflow%3Amain.windows.temurin.current)|
| OpenJDK (Temurin) LTS | Windows | [![Build (OpenJDK (Temurin) LTS, Windows)](https://img.shields.io/github/actions/workflow/status/io7m-com/peixoto/main.windows.temurin.lts.yml)](https://www.github.com/io7m-com/peixoto/actions?query=workflow%3Amain.windows.temurin.lts)|

## peixoto

A shaded distribution of the S3 client from the
[AWS v2 SDK](https://github.com/aws/aws-sdk-java-v2).
All packages and dependencies of the packages are relocated to a
`com.io7m.peixoto.sdk.*` namespace for isolation from the rest of the
dependency tree.

This package exists to solve some specific dependency issues with other
projects. If you don't know why you need this, then you probably don't. Use the
AWS SDK directly.

## Features

* S3 access but isolated from the rest of the dependency tree.
* Apache 2.0 license.

## Usage

Usage is identical to the [AWS v2 SDK](https://github.com/aws/aws-sdk-java-v2)
except that packages start with `com.io7m.peixoto.sdk.software.amazon.*`.

