# Tsung README (WG version)

##  Introduction

This document gives pointers for information on this package which is
distributed under the GNU General Public License version 2 (see file
COPYING).

##  What This Package Is

- forked from process-one tsung
- rolled back to latest stable release 1.5.1
- applied WG specific workarounds: 
	* make passwords to be static=Prefix
	*  It was RG workaround for _This is expected to instruct the TCP-driver to reuse source ports when connecting to 
different interfaces
	* add_to_online issue, details are there - 
http://lists.process-one.net/pipermail/tsung-users/2013-November/002765.html



WANTED:
- fix for BOSH: Tsung will add " xmlns='jabber:client'" to its iq requests; otherway JD server throws 
"unsupported-stanza-type". Current workaround is to use raw xml and adding missed part manually but it's not great one. Need 
fix on Tsung side ... 
