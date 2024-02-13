### Part One

1. What is HTTP?

HTTP, short for Hypertext Transfer Protocol, is the protocol used to communicate between a client and a server.

2. What is a URL?

URL stands for Unifrom Resource Locator. It's an address that specifies a place on the internet where we are communicating with. A URL consists of a protocol, hostname, Port, Resource and a Query string.

3. What is DNS?

DNS stands for Domain Name Server, it's a computer network that stores all hostnames and their corresponding IP addresses. A DNS translates human-readable domain names into the corresponding IP address.

4. What is a query string?

It is a part of a URL that includes additional information about what you are trying to request. It goes after a '?' on the URL and several arguments can be given, separated by & sign.

5. What are two HTTP verbs and how are they different?

Two HTTP verbs are GET and POST. The main difference is that GET requests don't change server data while POST requests do. GET is used to request data from a server while POST is used to submit data to the server.

6. What is an HTTP request?

It is a message that uses HTTP protocol that the browser sends to the server describing an action to be performed and including additional data.

7. What is an HTTP response?

It is a message using the HTTP protocol that the server sends to the client with requested data in response to the client's request.

8. What is an HTTP header? Give a couple examples of request and response headers you have seen.

A header is a group of additional information sent as part of a response, that includes Content Type, date/time, cookies the server wants to send, and any caching information.

### Part Two
1. setup:  curl -v http://icanhazdadjoke.com
    command: curl -H "Accept: application/json" "https://icanhazdadjoke.com/search?term=pirate
2. using: host -t A url
icanhazdadjoke.com has address 104.21.66.15
    icanhazdadjoke.com has address 172.67.198.173
