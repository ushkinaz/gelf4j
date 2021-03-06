## 1.6:

* Enhance  : Add support for a -f option that will take the message from a file.

## 1.5:

* Enhance  : Improve the mechanism for deriving the message id so that even when a message
             is sent in the same nano-second, the message will have a unique identifier.

## 1.4:

* Enhance  : Specify the Main-Class attribute in the manifest for the all jar so it can be
             directly executed from the command line.

## 1.3:

* Enhance  : If looking up the canonical hostname results in an exception attempt to guess the host name by iterating
             over the network interfaces.
## 1.2:

* Fix      : Fix data encoding for non-latin symbols.

## 1.1:

* Fix      : Handle the scenario where the logging frameworks supply a null message.

## 1.0:

* Fix      : Ensure that the MDC data in the log4j appender works with 
             the AsyncAppender. Thanks to Christoph Neuroth.

## 0.9:

* Enhance  : Use Java NIO when sending the packets.
* Enhance  : Improve the testing to ensure delivery across a socket occurs.
* Enhance  : Package the artifacts as OSGi bundles.

## 0.8:

* Enhance  : Improve the documentation.
* Change   : Remove the uncompleted remnants of the log forwarding application.
* Change   : Update to use getop4j CLI argument parser.

## 0.7:

* Initial release
