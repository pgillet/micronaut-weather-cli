# Micronaut Weather CLI application

_This repository is strongly inspired from [micronaut-weather-cli](https://github.com/orevial/micronaut-weather-cli) by [Olivier Revial](https://github.com/orevial). However, I have not forked the original repository and I have fully reimplemented the application from scratch, in particular because I wanted to test by myself the automatic generation of a CLI application template by Micronaut and also because the management of native compilation in the latest version of Micronaut has greatly evolved since the version used in the original repository._

# Original description

The goal of this repository is to demonstrate a real-world use case of Micronaut with Picocli and GraalVM to generate powerful yet simple native images of a command-line application.

This application is built:

* With **Micronaut** as its base:  to show how to use HTTP Clients & other Micronaut such as auto-config
* With **Picocli** to handle all CLI specificities such as options and positional parameters parsing or displaying useful help messages
* With **GraalVM** "native-image" feature enabled in Micronaut so we can easily compile this application down to a native binary.
* With **Weatherbit.io** [weather API](https://www.weatherbit.io/api/) to show interactions with remote services
* With ♥️, but there can still be bugs or problems, contributions are more than welcome !
