# Ether
Networking


Communicating on the Web
Instagram would be pretty terrible if you had to manually copy your photos to your friend's phone when you wanted to share them. Modern applications need to be able to communicate information between devices over the internet.

Gmail doesn't just store your emails in variables on your computer, it stores them on computers in their data centers
You don't lose your Slack messages if you drop your computer in a lake, those messages exist on Slack's servers
How Does Web Communication Work?
When two computers communicate with each other, they need to use the same rules. An English speaker can't communicate verbally with a Japanese speaker, similarly, two computers need to speak the same language to communicate.

This "language" that computers use is called a protocol. The most popular protocol for web communication is HTTP, which stands for Hypertext Transfer Protocol.




> HTTP Requests and Responses
At the heart of HTTP is a simple request-response system. The "requesting" computer, also known as the "client", asks another computer for some information. That computer, "the server" sends back a response with the information that was requested.

HTTP Powers Websites
HTTP, or Hypertext Transfer Protocol, is a protocol designed to transfer information between computers.

There are other protocols for communicating over the internet, but HTTP is the most popular and is particularly great for websites and web applications. Each time you visit a website, your browser is making an HTTP request to that website's server. The server responds with all the text, images, and styling information that your browser needs to render its pretty website!


![image](https://github.com/user-attachments/assets/075027db-ddbe-4e96-b827-684c9204f7cf)


<br />

# HTTP URLS
HTTP URLs
A URL, or Uniform Resource Locator, is the address of another computer, or "server" on the internet. Part of the URL specifies where to reach the server, and part of it tells the server what information we want.


Put simply, a URL represents a piece of information on some computer somewhere. We can get access to it by making a request, and reading the response that the server replies with.

![image](https://github.com/user-attachments/assets/07f80b1c-8c62-442a-ae7f-54796dd1aadd)


<br />

Using URLs in HTTP
The http:// at the beginning of a website URL specifies that the http protocol will be used for communication.

![image](https://github.com/user-attachments/assets/d98fc600-8a72-4961-bae8-53f183e35435)

Other communication protocols use URLs as well, (hence "Uniform Resource Locator"). That's why we need to be specific when we're making HTTP requests by prefixing the URL with http://


<br />
# Request and Responses
  ![image](https://github.com/user-attachments/assets/99166481-b414-4aa3-aa85-479023c3a397)


  
- A "client" is a computer making an HTTP request (whether it's a phone, a laptop, a desktop etc.).
- A "server" is a computer responding to an HTTP request.
- A computer can be a client, a server, both, or neither. "Client" and "server" are just words we use to describe what computers are doing within a communication system.
- Clients send requests and receive responses.
- Servers receive requests and send responses.


<br />
# Web Clients

A client can be any type of device but is often something users physically interact with. For example:

- A desktop computer.
- A mobile phone.
- A tablet.
- In a website or web application, we call the user's device the "front-end".

A front-end client makes requests to a back-end server.

