# py_check_ssl_certificate
Nagios Plugin to check the expiration of ssl certificates

## Dependencies
[PyOpenSSl](https://github.com/pyca/pyopenssl)

## Parameter
```
-h Help
-H Host (IP or domain name to connect to) like: -H www.example.com 
-p Optional port number (default 443) like: -p 443
-w Warning value to alert on (days until expiration) like: -w 21 
-c Critical value to alert on (days until expiration) like: -c 14
```
