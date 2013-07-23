PCP client library
===================

PCP client library implements client side of PCP stack 
([RFC 6887](http://datatracker.ietf.org/doc/rfc6887/)). It enables any network
application to manage network edge device using PCP (e.g. to create NAT mapping 
or ask router for specific flow treatment).  
There are also other PCP command line tools included.

### Components ###

  - libpcp     - PCP client library
  - pcp_app    - PCP client CLI app
  - pcp_server - mock PCP server
  - scapy      - PCP layer for Scapy

Build instructions are located in INSTALL.md file. More information about
components are in each subdirectory's README.md file.
