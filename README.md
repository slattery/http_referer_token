# HTTP Referer Token
Places a whole and parsed HTTP referer in a token

## v001
You can use the following tokens

* [http_referer:raw] gives you the whole string
* [http_referer:path] gives you the path, plus scheme and host if external
* [http_referer:query:*] gives you the value of the key you type in
* [http_referer:ext] gives you a boolean telling if external or not

## Dependencies
Needs the Token Module to work