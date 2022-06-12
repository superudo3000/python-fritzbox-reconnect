# Restarting your fritzbox with a python script

This is usually realized with tools like Netcat_ or cURL_.  However, when
developing in Python_ anyway, it is more convenient to integrate a native
implementation.  This one requires Python_ 2.5 or higher.

UPnP_ (Universal Plug and Play) control messages are based on SOAP_, which is
itself based on XML_, and transmitted over HTTP_.

Make sure UPnP_ is enabled on the FRITZ!Box.

A reconnect only takes a few second while restarting the box takes about up to
a minute; not counting the time needed to navigate through the web interface.

- Netcat: http://netcat.sourceforge.net/
- cURL:   http://curl.haxx.se/
- Python: http://www.python.org/
- UPnP:   http://www.upnp.org/
- SOAP:   http://www.w3.org/TR/soap/
- XML:    http://www.w3.org/XML/
- HTTP:   http://tools.ietf.org/html/rfc2616

Quick Start:
    python3 fritzbox_restart.py

Or as always for help / arguments:
    python3 fritzbox_restart.py -h

Original post from:
    https://homework.nwsnet.de/releases/ef29/#instruct-an-avm-fritzbox-via-upnp-to-reconnect

Tested with:
    Python 3.8.6 on macOS 12.3.1 and FRITZ!OS: 07.29

Copyright:
	2008-2015 Jochen Kupperschmidt
	Fix by SuperUdo3000 =)

Date:
	12-Jun-2022 (original release: 04-Apr-2008)
	
License:
	MIT