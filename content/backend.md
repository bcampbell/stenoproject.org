## Back end tools


### Scrapeomat

The main back end tool is `scrapeomat`.

It collects articles from configured sites, storing them in a (postgresql) database.
It's designed to be run as a server on a unix-style box.

Code on github: https://github.com/bcampbell/scrapeomat

### Slurpserver

Provides an HTTP API which front end clients can connect to and retrieve
collected articles for analysis.

Clients can then access the collected articles via an HTTP API.

(source code is under `cmd/slurpserver` at https://github.com/bcampbell/scrapeomat)

