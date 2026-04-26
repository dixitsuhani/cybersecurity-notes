# HTTP

## What is HyperText Transfer Protocol?
HTTP is a protocol used for communication between a client (browser) and a server to request and transfer web data.

## What is HyperText Transfer Protocol Secure?
HTTPS is a secure version of HTTP that encrypts data between the client and server, preventing attackers from reading or modifying it.

## HTTP Methods
Tells the server what action is to be performed.
#### (a) GET: Retrieve data; Data sent in URL; Visible in browser
#### (b) POST: Send data to server; Data sent in body; Used in forms, login, signup; Not secure without HTTPS
#### (c) PUT: Update or replace data
#### (d) DELETE: Delete data; Should require authentication

## HTTP Status Codes
Server tells the client the result of a request.
#### 100-199: Information Response (Request received, continuing process.)
#### 200-299: Success (Request was successful.)
#### 300-399: Redirection (This will be available on another resource.)
#### 400-499: Client Errors (You did something wrong.)
#### 500-599: Server Errors (Something is broken down on my side.)

## Commonly Used HTTP Status Codes
#### 200-OK: Request was completed successfully.
#### 201-Created: Resource has been created.
#### 301-Permanent Redirect: Redirects the client's browser to different webpage or lets the search engine know that requested information is on another webpage.
#### 302-Temporary Redirect: The resource is moved temporarily and may change again in future.
#### 400-Bad Request: Something is wrong or missing in the request.
#### 401-Not Authorized: Login to view this resource.
#### 403-Forbidden: You are not allowed to view this resource logged in or not.
#### 405-Method Not Allowed: Resource does not allow a certain method for a particular request.
#### 404-Page Not Found: Page does not exist.
#### 500-Internal Server Error: Server has encountered some error and doesn't know how to handle it.
#### 503-Service Unavailable: This server is overloaded or down for maintenance therefore cannot handle your request.

## Headers
These are additional bit of data you can send to web servers while making request.
Important headers:
#### (a) Host: Website that we are requesting
#### (b) User-Agent: Information about browser or device
#### (c) Content-Type: Type of data
#### (d) Content-Length: How much data is there
#### (e) Set-Cookie: Server sends cookie to browser.
#### (f) Cookie: Stores session information sent by the browser.

## Cookie
Cookie is a piece of data stored on computer that helps server identify a user and maintain sessions. It is mainly used for website authentication.
