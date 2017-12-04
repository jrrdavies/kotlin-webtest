# About this project #
Do not use this software. It is not finished, subject to change and bug-ridden. However, if you really need this stuff and are the brave soul who likes to ride the depths of Hades' SOAP-service underworld on his/her flaming JVM chariot wielding the almighty sword named 'Kotlin', I very much welcome you.
I might even fix some bugs if you ask nicely (be sure to supply logs, steps to reproduce, and beer). 

# Features #

## SOAP 1.1 & 1.2 ##
This implementation is not intended to be feature-complete but one which is just enough to test a spec-compliant SOAP-service, but nothing more.
This means it might fail to detect an in theory malformed/invalid SOAP-response which parses OK.

Validators: HTTP responses, SOAP faults, XPath, XSD

## REST ##

Validators: HTTP responses

# TODO #
The following stuff (and much more) needs to be done:
- Sending MTOM (receiving works)
- SwA support (only MTOM/XOP is supported right now)
- General cleanup
- Improve logging (human-friendly v.s. technical log?)
- More test coverage. This stuff slowly becomes something a poor soul actually would be using, so some additional unit tests would be nice.
- Everything where your find // TODO in the code
- Push to Maven Central (when all of the above has been fixed)
- Getting the default namespace in XPath validators to work
- JDBC support
- Parsing WSDLs