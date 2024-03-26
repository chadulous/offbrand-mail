# offbrand-mail

Email over HTTPS

Connections happen between servers via SSE.

Sending Server -> Recieving server GET /.well-known/web-msg/hi; Recieving server responds with 202, any other code assumes this server is not using the protocol, and is not supported, and the entire thing is off, the user is notified.

Sending Server -> Recieving server POST /.well-known/web-msg/handshake; 