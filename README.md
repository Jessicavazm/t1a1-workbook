# t1a1-workbook

# T1A2 Workbook

## Question number 01
	
### HTML

Markup language is an essential tool in the web development world, they are used to define the websibe structure. HTML is the standard markup text language, and most of the websites in today's World are created using HTML.

Every HTML documents starts with the **!DOCTYPE html** to describe document type and it helps the browser to read your document, followed with HTML components **head** and 
**body**. 

In **head** we store information about the website such as title,meta data, CSS link to import design,favicon. Some of these information helps with more visibiliaty in the search engines.
In **body** we place everything that is visible to users using elements such as heading, paragraph, archor links and images. 

**Semantic tags** are a great tool to use through the process to allocate our content, keep it more clean and give our elements more meaning. It's great for screenreaders and accessibility. Some of the most common semantic elements are header, nav, main, section, footer.

Comments are another way to keep everything organised and explained through the process. In case if there are multiple people working in the project, it's powerful tool that helps to ensure everybody understands the codes being applied.

All elements can have attributes in HTML, they are extra piece of information about elements. Some of the most commons attributes are
- lang: indicates the language, it is placed in the html tag, it also helps for visibiliaty in search engines.
- href: indicates the URL that a link goes to
- src: path to image
- width/height : indicates dimensions of elements
- style: gives style such as colour to an element
- alt: alternative text used for screenreaders or if in case path/link to image is broken

HTML is a powerful tool that allows you to create lists, forms and work together with programmer language to receive users data.

## Q2
Define the features of the following technologies that are essential in terms of the development of the internet:
 
- Packets 
Packets are "containers" of data, packets are slipt into small "packages" of data and they are transferred over from one computer to another through computer network. Once the data is slipt in small pieces, it chooses the best route to it's destination and packets have the ability to travel  independently reducing the load on a single route. In case of an issue during the transmition, the route gets changed to ensure the recipient receives the complete data. Once the packets arrived in the destination they are re-organised through a sequence of numbers and they become complete again. Packets has contribute to the development of the internet allowing multiple computers to exchange data simultaneously, allowing computer users to reach each continuosly. This technology also allows the reliability of sending and receving data since routes are changed in case of congestion or failure.

- IP addresses (IPv4 and IPv6)
IP stands for Internet protocol, every computer connected to the internet has an IP, which is an unique identifying number. This number is used to identify where the data goes, it's how devices connects one to another.

IPv4 it's the version 4 of internet protocol also know as 32-bit system, computers switched to IP protocol back in 1983 and this version still in use. IPv4 contains 11 digit numbers separeted by dots (decimal structure). It has provided over 4 billions IP, and over the years it ran out of addresses as our usage of devices connected to internet surpassed the four billion addresses provided by IPv4. The solution for the problem arrived in late 90's, IPv6 (version 6).
- 13 header 
- Requires less space for storing address information in the network
- IP addresses are diveded by 5 classes A, B, C, D and E
- Checksum
- Manual and DHCP address configuration

IPv6 addresses uses the 128-bit format that means the capacity of unique IP are way more than the previous system and we won't have to worry about running out of IP addresses. Some of the new features in the new version is that the IP addresses contains both numbers and letters separated by colons(hexa-decimal). With the abundancy of available addresses provided by IPv6,every device can have their own IP, meaning that data transmition is smoother and faster since the data goes straight from one device to another.
- Larger header = more data each transfer
- Checks for accurancy in data transmition
- IPSEC standard security for data transfer
- Encryption and Authentication
- More efficient data routing 
- Auto-configuration available
- Quality of Service (QoS)

IPv4 has contributed to the development of the internet allowing devices to connect between each other and transfer data efficiently. IPv6 has improved and brought benefits in the updated version offering tons more of IP addresses to keep up with today's world devices, IPSEC was also implemented to add extra layer of security and QoS to prioritise data to ensure quality. Mobile phone, applications and multi-casting were also improved.

Router is a hardware device responsible for directing data packets through networks and controlling the data traffic bewteen networks. Routers are also used to connect devices in the same network. Some different types of routers are Wired routers, Wireless routers, Core routers, etc. 

Routing is the process that a data packet takes to reach their final destination. Once the router receives a data packet, it uses a router table to find out the best path to send the data, and the router table uses the content in the header of each packet to decide it's destination. Routing tables can be static, they don't change and they are set by the network adminstrator, and dynamic tables that get updated automatically to find the fastest/ shortest way to deliver the data, it's a more efficient way.

Routers has contributed immensilly to the development of the internet allowing multipe devices from the same network to share internet in both home and business environments, exchange data and manage data traffic control allowing data to be transferred quickly and efficiently.

Domains and DNS

Domains are names that we use to access data, when you open a browser you don't need to remember the long number/letter address, instead you search for domain name. Domain is part of DNS (Domain Name system), this system converts domains names e.g www.google.com to IP addresses. 



Question 03.
Define the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)

Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

