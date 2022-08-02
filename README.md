# Asyncronous Client Server Interaction

## Polling

## WebSocket

Bidirecional communication.

Best use cases: Google Wave, Chat Applications, anything that needs bidirecional communication.

## Server-Sent Events

Unidirecional communication, from Server to Client. If you want Client to Server communication, you need do make a separated POST request.

Best use cases: Stock prices updates, notifications, anything that needs unidirecional communication.

## HTTP2 Push :skull:	

Developers from Chromium removed the support of this feature. As Chrome has 70% of market share (2022), they are effectively killing HTTP2 Push. As HTTP2 Push is not mandatory, Chromium keeps HTTP2 compliant.

Chromium Team announcement (2021): https://groups.google.com/a/chromium.org/g/blink-dev/c/K3rYLvmQUBY/m/0o4J1GEjAgAJ
