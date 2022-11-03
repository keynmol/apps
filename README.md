# Coursier Apps
[![Build status](https://github.com/coursier/apps/workflows/build/badge.svg)](https://github.com/coursier/apps/actions?query=workflow%3Abuild)
[![Release status](https://github.com/coursier/apps/workflows/publish/badge.svg)](https://github.com/coursier/apps/actions?query=workflow%3Apublish)
[![Maven Central](https://img.shields.io/maven-central/v/io.get-coursier/apps.svg)](https://maven-badges.herokuapp.com/maven-central/io.get-coursier/apps)

This repository holds the apps in the Main and Contrib channels for Coursier.
You can find information about creating your own application to be installed
with `cs` [here on the
website](https://get-coursier.io/docs/cli-install.html#creating-your-own-applications).

## Main
These are the apps in the default main JAR-based channel, `io.get-coursier:app`
which is used with `cs install`

 - almond
 - ammonite
 - bloop-jvm
 - bloop
 - coursier
 - cs
 - csbt
 - dotty-repl
 - echo-graalvm
 - echo-java
 - echo-native
 - giter8
 - mdoc
 - metac
 - metals-emacs
 - metals
 - metap-native
 - metap
 - mill-interactive
 - mill
 - sbt-launcher
 - sbt
 - sbtn
 - scala-cli
 - scala
 - scala3-compiler
 - scala3-decompiler
 - scala3-doc
 - scala3-repl
 - scala3
 - scalac
 - scaladoc
 - scalafix
 - scalafmt
 - scalap
 - scalapbc
 - stc

## Contrib
These apps are available by passing `--contrib` to the `cs install` command.
Feel free to send in a PR to add your application here!

 - amm-runner
 - asm-textifier
 - asmifier
 - authors
 - avro-tools
 - bfg
 - cache-migration
 - catscript
 - clojure
 - fastpass-jvm
 - fastpass
 - firstbird-emergence
 - flyway
 - frege
 - git-changelog
 - google-java-format
 - groovy-shell
 - groovy
 - guardrail
 - ivy
 - jansi
 - jfiglet
 - jruby
 - jython
 - kafka-console-consumer
 - kafka-console-producer
 - kafka-consumer-groups
 - kafka-server
 - kafka-topics
 - ktfmt
 - lsif-java
 - make-it-g8
 - openapi-generator
 - plantuml
 - proguard-7
 - proguard-retrace
 - proguard
 - protoc-jar
 - rhino
 - rsc
 - rscj
 - scala-cli
 - scala-debugger
 - scala-steward
 - scala-update
 - scalaxb
 - scip-java
 - sclin
 - spark-repl
 - sqlline
 - swagger-codegen
 - wiremock
 - zookeeper

### Updating the README
This README is auto-generated by the `scripts/generate-readme.sc` Ammonite
script Please don't update the README directly, but rather update the
`README.template.md`. Note that you don't need to manually add your app to it,
it will be automatically added in CI.

### Testing a change
If you'd like to test a change locally to ensure what you're adding or changing
works correctly, you can do the following while in the workspace.

```
cs launch --default-channels=false --channel ./(apps|apps-contrib)/resources <app name>
```
