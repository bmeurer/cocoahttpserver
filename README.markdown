## About

This is my fork of the [CocoaHTTPServer](http://code.google.com/p/cocoahttpserver/) project, which adds a Xcode project file with targets suitable for embedding into other Xcode projects, and fixes several known bugs.


## CocoaHTTPServer

[CocoaHTTPServer](http://code.google.com/p/cocoahttpserver/) is a small, lightweight, embeddable HTTP server for Mac OS X or iOS applications.

Sometimes developers need an embedded HTTP server in their app. Perhaps it's a server application with remote monitoring. Or perhaps it's a desktop application using HTTP for the communication backend. Or perhaps it's an iOS app providing over-the-air access to documents. Whatever your reason, CocoaHTTPServer can get the job done. It provides:

- Built in support for bonjour broadcasting
- IPv4 and IPv6 support
- Asynchronous networking using GCD and standard sockets
- Password protection support
- SSL/TLS encryption support
- Extremely FAST and memory efficient
- Extremely scalable (built entirely upon GCD)
- Heavily commented code
- Very easily extensible
- WebDAV is supported too!


## License

CocoaHTTPServer is licensed under the [Simplified BSD License](http://en.wikipedia.org/wiki/BSD_license). See the [LICENSE.txt](http://github.com/bmeurer/cocoahttpserver/raw/master/LICENSE.txt) file for details.


