# Changelog

## [0.17] - 2022-09-25
### Updated
- Support for encrypted (TLS) connections with PostgreSQL
- Native support for PBKDF2 algorithm to allow SCRAM-SHA-256 authentication without the external
  nettle-pbkdf2 application
- Implement multibyte encoding and decoding for pg-exec requests
- Send application_name to PostgreSQL backend to improve observability
- Fix handling of NotificationResponse messages 
- Improve test coverage


## [0.16] - 2022-09-18
### Updated
- Fix MD5 authentication
- Use client-encoding to decode PostgreSQL error messages
- Improve GitHub Actions continuous integration workflow


## [0.15] - 2022-09-06
### Updated
- Moved from cl library to cl-lib
- pg: prefix for symbol names changed to pg- (Emacs Lisp coding conventions)
- Implemented version 3.0 of the PostgreSQL wire protocol
- Implemented SCRAM-SHA-256 authentication
- Implemented MD5 authentication
- Distributed via github repository



## [0.11] - 2001

This version was distributed from http://purl.org/net/emarsden/home/downloads/
and via the EmacsWiki. 
