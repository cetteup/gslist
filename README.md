# gslist
This is a "fork" of [Luigi Auriemmas brilliant gslist tool](http://aluigi.altervista.org/papers.htm#gslist).

## Changes (compared to the original version of gslist 0.8.11a)
- added command line parameter for enabling/disabling GeoIP lookups (disabled by default, because current database update implementation does not work due to GeoIP databases no longer being publically available)
- added command line parameter for directly controlling the server query list type byte
- fixed query response handling when queryid is not the last key\value pair
