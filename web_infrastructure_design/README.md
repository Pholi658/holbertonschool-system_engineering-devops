# This is the explanation of the single server infrastructer flow

#1 The user types in www.foobar.com on the browser ->
 
#2 The domain name is sent directly to 8.8.8.8 wich is the ip address for the dns server

#3 The dns sends back the real ip address of the website to the user and a https request is sent to the web server

#3 web server loads the html page onto the browser

#4 The web server can also hit the application based on the needs of the user

#5 and the application server can hit the database server when it needs persisted records that were stored in the database.

#6 The server finally return a http response to the user depending on whether the request was succesful or not