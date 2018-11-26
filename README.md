# Web-Request-Logger
This Simple PHP will sending you a telegram with the exact request

1. Upload this php to any php server 
2. Add your Telegram Keys from here https://my.telegram.org/apps

Every time this PHP is call a telegram alert will be send to you with the requested information. Useful to derect Server Side Request.

Extras:
```
GET and POST request
File Log Link
ISP Details
Threatcrowd IP Details
Censys IP Details
Robtex IP Details
Threatminer IP Detail
```

## Telegram Message send:

New Request to Request Log
```
The IP: 172.217.0.110
The URL request was made to: /index.php
The request REFERER was: https://google.com/
The User Agent was: Mozilla/5.0 
```

All Headers:
```
POST /index.php HTTP/1.1
HOST: Logserver.com 
Connection: Keep-Alive 
Proxy-Connection: Keep-Alive 
X-Forwarded-Proto: https 
X-Real-IP: 172.217.0.110 
X-Forwarded-For: 172.217.0.110
Content-Length: 9 
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.14; rv:63.0) Gecko/20100101 Firefox/63.0 
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8 
Accept-Language: en-US,en;q=0.5 
Accept-Encoding: gzip, deflate 
DNT: 1 
Upgrade-Insecure-Requests: 1 

TEST=TEST
```

File Log Link
ISP Details Link
Threatcrowd IP Details
Censys IP Details
Robtex IP Details
Threatminer IP Details
