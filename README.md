# Example of calling C++ library from Go using SWIG

## Build Environment

* [Go 1.7.3](https://golang.org/)
* [SWIG 3.0.10](http://www.swig.org)
* [g++ 5.3.1](http://www.cprogramming.com/g++.html)
* [Ubuntu 16.04 LTS](https://www.ubuntu.com/)

Note: This build environment is for reference only. Other versions of build tools and OS may work as well.

## Build & Run

Terminal:
```
$ cd $GOPATH/src/github.com/samherrmann/go-to-cpp
$ go build
$ ./go-to-cpp
```
You should see `Hello World!` being printed to the console.



## Resources
* [https://github.com/draffensperger/go-interlang](https://github.com/draffensperger/go-interlang)