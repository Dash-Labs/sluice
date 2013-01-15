Sluice
======

A configuration of [jetty](http://jetty.codehaus.org/jetty/) to act simply as a static content server.  This project is configured to be used as a [ply](https://github.com/blangel/ply) script.


Compilation 
-----------

Sluice uses [ply](http://github.com/blangel/ply) as its build tool, ensure you have it installed.  To compile:

    $ ply clean compile package

One can then copy the generated `target/sluice-1.0.jar` into a scripts directory for `ply` to execute.


