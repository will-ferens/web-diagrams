Passing requires all values

## Functional

In this order:

* [ ] Makes DNS query with mysite.com from browser to the DNS server at 8.8.8.8
* [ ] DNS server replies back to browser with 172.217.0.78
* [ ] Browser makes request to web server
* [ ] Browser makes HTTP GET request to 172.217.0.78:80
* [ ] Server responds with HTTP 200 OK and an HTML payload
* [ ] Browser renders the HTML into the DOM
* [ ] Browser looks up the IP address for the site in its DNS cache
* [ ] Browser makes an HTTP GET request to web server 172.217.0.78:80/app.js
* [ ] Server responds with HTTP 200 OK and a JS payload
* [ ] Browser looks up the IP address for the site in its DNS cache
* [ ] Browser makes an HTTP GET request to 172.217.0.78:80/users/1
* [ ] Server makes a DNS query for the database at mydatabase.com
* [ ] DNS server replies back to browser with 191.0.23.17
* [ ] Server makes a postgres request to 191.0.0.23.17:5432
* [ ] Database server replies to web server with data
* [ ] Web server replies to browser with data formatted as JSON

## Style

* [ ] Has actors for browser, DNS, and server
* [ ] Life-lines descend down from actors
* [ ] Use arrows to indicate direction
