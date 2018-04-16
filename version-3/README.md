## Instructions

Using the information in the `web-diagram` files, make a sequence diagram that describes the interactions between clients, servers, DNS, and databases for this scenario:

## Scenario

A browser makes an HTTP request to the website `mysite.com`, which returns its `index.html` page. It has a linked JavaScript file, `app.js`. On load, the script makes an AJAX request to `mysite.com/users/1`, which retrieves a user from a Postgres database at `mydatabase.com` and sends it back to the browser as JSON.

## Notes

* The IP address of `mysite.com` is `172.217.0.78`
* The IP address of the DNS server is `8.8.8.8`
* The IP address of database server is `192.0.23.17`
