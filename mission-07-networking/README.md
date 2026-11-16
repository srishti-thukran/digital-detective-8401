## TASK-7.1 Explain Network Concepts

| Concept | Explanation | Example |
|---------|-------------|---------|
| LAN | A network covering a small area, such as a home, lab or office | WIFI router |
| MAN | A network covering a city or large campus area. | city wide TV cables |
| WAN | A network covering large geographical areas. | internet connecting computers worldwide |
| DNS | Translates a domain name into an IP address. | Converting google.com into its corresponding IP address |
| Router | Connects networks and forwards data between them. | A home Wi-Fi router connecting phones and laptops to the Internet |
| Protocol | A set of rules devices follow to communicate | HTTP is used for communication between web browsers and websites. |
| Packet switching |Data is divided into packets that travel across a network. | Sending a photo through WhatsApp, where data travels in packets |
| Client server | A client requests a service and a server provides it | A web browser requests a webpage from a web server. |

## TASK-7.2 Observe network information

1. What does a connectivity test help you check?
A connectivity test checks whether my computer can communicate with another computer or server over a network. It helps identify internet connection problems and checks whether the destination is reachable.

2. What information does a DNS lookup display?
A DNS lookup displays the IP address associated with a domain name. It may also show the DNS server used to perform the lookup and other network information.

3. What is the role of DNS when you enter a website name in a browser?
DNS (Domain Name System) translates human-readable website names into IP addresses. When I enter a website name in my browser, DNS helps find the corresponding IP address so that the browser can connect to the correct web server.

## Task 7.3 — What Happens When You Open a Website?

1. Browser (Client): When I enter a website URL in my browser, the browser acts as a client and sends a request to access the website.

2. DNS Lookup: DNS (Domain Name System) converts the website's domain name into its corresponding IP address so the browser can locate the server.

3. Network and Router: The request travels through the network and router, which forwards the data towards the correct destination.

4. Server: The request reaches the web server, which processes it and finds the required webpage.

5. Protocol: The client and server communicate using protocols such as HTTP or HTTPS, which define the rules for exchanging data.

6. Server Response: The server sends the requested webpage data, including HTML, CSS, images and other resources, back to the browser.

7. Displaying the Website: The browser receives the response, processes the data and displays the webpage on the user's screen.

Conclusion: Opening a website involves communication between a client and a server, with DNS, routers and network protocols helping deliver the requested information.

-------------------------------------------------------------------------------------------------------

## 1. Command used

-->ping -c 4 google.com
--> nslookup google.com
