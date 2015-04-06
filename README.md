# The Infinite Web Server Honeypot

This is a quick honeypot web server that delivers an infinite web page to anyone asking for it. It sends a never ending web page that may fill up the hard disk of the attacker if the download is automatic.

The new version uses twisted and curses to show the info. You can see the connected clients, the duration of the client connection and the bytes transfered.

## Usage
Just start the python script and then try to download it with wget or something.

In a local network is able to send data at ~2.5Mbps
