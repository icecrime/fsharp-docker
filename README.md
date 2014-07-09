fsharp-docker
=============

This repository contains the sources for the following [docker](http://www.docker.io) base images:

* [`icecrime/fsharp`](http://github.com/icecrime/fsharp-docker/blob/master/base)
* [`icecrime/fsharp-runtime`](http://github.com/icecrime/fsharp-docker/blob/master/runtime)
* [`icecrime/fsharp-hello`](http://github.com/icecrime/fsharp-docker/blob/master/hello)

The repository layout is shamelessly inspired from [`GoogleCloudPlatform/python-docker`](https://github.com/GoogleCloudPlatform/python-docker) by [**@proppy**](https://github.com/proppy).

Usage
----

    $> docker build -t icecrime/fsharp base/
    $> docker build -t icecrime/fsharp-runtime runtime/
    $> docker build -t icecrime/fsharp-hello hello/
    $> docker run --rm icecrime/fsharp-hello
    Hello world from F#!

