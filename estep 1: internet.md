# Internet

## How does the internet work?

**Internet** ⇒ The physical thing that do every work

**World Wide Web (WWW)** ⇒ The internet protocol

**Backbones** ⇒ They are the mangment request networks, they receive or send requests. 

**TCP/IP** ⇒ Tecnology that makes connection between two locals networks.

**Is it possible to tear down the internet?** In the theory, yes! But in the real, no. Because, if someone destroyed some equipments, the signal can bypass this place. And in attack software programs cases, the architecture can be protecting and isolate the attack.

**Overview (steps):** 

- The starting point is the backbones, which distribute information across the network using TCP/IP technology to determine where the data should go.
- Then, the internet reaches the access providers, who contract the connection with the backbones and distribute it to the service providers.
- Service providers, in turn, distribute the connection to end users, for example, via fiber optics.
- Finally, the internet connection reaches end users' devices.

## What is the Hypertext Transfer Protocol (HTTP)?

The HTTP is the foundation of the World Wide Web, and is used to load webpages using hypertext links. 

**HTTP request include**: HTTP version type, a headers, an URL, an optional body, method (POST, GET etc.) 

**Extra**: The HTTP protocol is not very security, so we use HTTPS protocol.
That is the form of obtain more security, because is the join between HTTP protocol and SSL security protocol.
## Browser and how they work?

Is the application that can insert URL pages address and access this one.

**Example**: Google Chrome, Safari, Opera, Firefox e Edge

**How is it work?**: The browser sends request on the internet with HTTP protocol and get data page, commonly the request pages return HTML data of the page or site. Each application have a unique URL (Unique Recourse Localization).

**The browser's high level structure:**

- The user interface ⇒ The UI interface.
- The browser engine ⇒ The engineer interactions among user and rendering engineer.
- The rendering engine ⇒ The presenter of content requested response.
- Networking ⇒ The networker and it’s platform-independent interface.
- UI backend ⇒ used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath, it uses operating system user interface methods.
- JavaScript interpreter ⇒ Used to parse and execute JavaScript code.
- Data storage ⇒ The Persistence layer. Such as local storage and cookies, Browser needs to them.

## What is the DNS and how they work?

The DNS is as book that users search an application (IP) starting the domain name.

**Overview (steps):**

- request URL exempe.com
- resolver DNS received and redirect request to root name server DNS
- resolver receive response with address of the DNS server TLD as the ".com"
- send request to TLD
- The TDL server response, the IP server with domain "[anything.com](http://anything.com/)"
- The recursive resolver sends a request to names server
- The resolver response web user request with the IP address the initial domain
