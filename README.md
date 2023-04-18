
HTTP/HTTPS forward proxy with content adaptive optimizer capabilities.
One use case is to reduce bandwidth usage when browsing on limited mobile broadband connection.

Usage
------

    python3 main.py (-p 8080) (-m HTTPS) (-i 127.0.0.1)
    
    -p: Default: 8080
        The port this proxy is listening on.
    
    -m: Default: HTTPS
        The mode, HTTPS or HTTP. If not set, the proxy will try HTTPS, and fall back to HTTP should required.
    
    -i: Default: ''
        The IP address this proxy is listening on.


Requirement
------

- Python 3.7.9+
- ```ssl``` package, as in openssl




