# Network Programming

## intro/
- echocli.py
- echoserv.py

## echo/
### echo/clients/
- client_wrong.py: incorrect version
- client_shutdown.py: receive more data after shutdown
- client_makefile.py: converting socket to file-like object
- client_thread.py: multi-threading
- client_class.py: class implementation
- clients.py: running multiple clients for testing servers<br>
    Usage:
    ```bash
    python clients.py [<n>]   # run n(=3, default) clients
    ```

### echo/servers/
- server_select.py: I/O multiplexing
- server_thread.py: multi-threading
- server.py: OO approach with multi-threading
- server_socketserver: using socketserver module

## iot/
- iotclient.py: an IoT client example
- iotserver.py: an IoT server example

## http/
- httpcli.py: http client using socket
- httpserver.py: writing HTTPHandler using socketserver.TCPServer
- headers.py: parse HTTP headers
