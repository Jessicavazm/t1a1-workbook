# t1a1-workbook

## Q1
### Identify and explain common and important components and concepts of web development markup languages
	
### HTML

Markup language is an essential tool in the web development world, they are used to define the websibe structure. HTML is the standard markup text language, and most of the websites in today's World are created using HTML.

Every HTML documents starts with the **!DOCTYPE html** to describe document type and it helps the browser to read your document, followed with HTML components **head** and 
**body**. 

In **head** we store information about the website such as title,meta data, CSS link to import design,favicon. Some of these information helps with more visibility in the search engines.
In **body** we place everything that is visible to users using elements such as heading, paragraph, anchor links and images. 

**Semantic tags** are a great tool to use through the process to allocate our content, keep it more clean and give our elements more meaning. It's great for screen-readers and accessibility. Some of the most common semantic elements are header, nav, main, section, footer.

Comments are another way to keep everything organised and explained through the process. In case if there are multiple people working in the project, it's powerful tool that helps to ensure everybody understands the codes being applied.

All elements can have attributes in HTML, they are extra piece of information about elements. Some of the most commons attributes are
- lang: indicates the language, it is placed in the html tag, it also helps for visibility in search engines.
- href: indicates the URL that a link goes to
- src: path to image
- width/height : indicates dimensions of elements
- style: gives style such as colour to an element
- alt: alternative text used for screen-readers or if in case path/link to image is broken

HTML is a powerful tool that allows you to create lists, forms and work together with programmer language to receive users data.

- References: https://www.w3schools.com/ https://www.cloudflare.com/en-gb/

## Q2
### Define the features of the following technologies that are essential in terms of the development of the internet:
 - packets
 - IP addresses (IPv4 and IPv6)
 - routers and routing
 - domains and DNS

### Explain how each technology has contributed to the development of the internet.

- Packets 
Packets are "containers" of data, packets are slipt into small "packages" of data and they are transferred over from one computer to another through computer network. Once the data is slipt in small pieces, it chooses the best route to it's destination and packets have the ability to travel  independently reducing the load on a single route. In case of an issue during the transmission, the route gets changed to ensure the recipient receives the complete data. Once the packets arrived in the destination they are re-organised through a sequence of numbers and they become complete again. Packets has contribute to the development of the internet allowing multiple computers to exchange data simultaneously, allowing computer users to reach each continuously. This technology also allows the reliability of sending and receiving data since routes are changed in case of congestion or failure.

- IP addresses (IPv4 and IPv6)
IP stands for Internet protocol, every computer connected to the internet has an IP, which is an unique identifying number. This number is used to identify where the data goes, it's how devices connects one to another.

IPv4 it's the version 4 of internet protocol also know as 32-bit system, computers switched to IP protocol back in 1983 and this version still in use. IPv4 contains 11 digit numbers separated by dots (decimal structure). It has provided over 4 billions IP, and over the years it ran out of addresses as our usage of devices connected to internet surpassed the four billion addresses provided by IPv4. The solution for the problem arrived in late 90's, IPv6 (version 6).
- 13 header 
- Requires less space for storing address information in the network
- IP addresses are divided by 5 classes A, B, C, D and E
- Checksum
- Manual and DHCP address configuration

IPv6 addresses uses the 128-bit format that means the capacity of unique IP are way more than the previous system and we won't have to worry about running out of IP addresses. Some of the new features in the new version is that the IP addresses contains both numbers and letters separated by colons(Hexadecimal). With the abundance of available addresses provided by IPv6,every device can have their own IP, meaning that data transmission is smoother and faster since the data goes straight from one device to another.
- Larger header = more data each transfer
- Checks for accuracy in data transmission
- IPSEC standard security for data transfer
- Encryption and Authentication
- More efficient data routing 
- Auto-configuration available
- Quality of Service (QoS)

IPv4 has contributed to the development of the internet allowing devices to connect between each other and transfer data efficiently. IPv6 has improved and brought benefits in the updated version offering tons more of IP addresses to keep up with today's world devices, IPSEC was also implemented to add extra layer of security and QoS to prioritise data to ensure quality. Mobile phone, applications and multi-casting were also improved.

Router is a hardware device responsible for directing data packets through networks and controlling the data traffic between networks. Routers are also used to connect devices in the same network. Some different types of routers are Wired routers, Wireless routers, Core routers, etc. 

Routing is the process that a data packet takes to reach their final destination. Once the router receives a data packet, it uses a router table to find out the best path to send the data, and the router table uses the content in the header of each packet to decide it's destination. Routing tables can be static, they don't change and they are set by the network administrator, and dynamic tables that get updated automatically to find the fastest/ shortest way to deliver the data, it's a more efficient way.

Routers has contributed immensely to the development of the internet allowing multiple devices from the same network to share internet in both home and business environments, exchange data and manage data traffic control allowing data to be transferred quickly and efficiently.

Domains and DNS

Domains are names that we use to access data, when you open a browser you don't need to remember the long number/letter address, instead you search for domain name. Domain is part of DNS (Domain Name system), this system converts domains names e.g www.google.com to IP addresses. 

## Q3
### Define the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)

### Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

- TCP stands for transmission control protocol, it's bridge between the sender and the final destination. TCP is responsible for putting all packets back together, making sure the transmission occurs smoothly free of delays and errors. TCP uses a process called "Three way shake hand" that initialise the connection between the sender and the receiver, making sure there's a stable connection before data exchange. Three Way Handshake consist in tree steps *SYN* (this packet requests initialisation of transmission process, this is sent from source to target server), *SYN-ACK* (target server sends a packet back with agreement to source) and the last packet *ACK* (source sends target server a packet to confirm the connection is established). Another feature is Segment Number system, TCP packets are identified with numbers, in case any problem occurs to a packet in the transmission process, TCP can identify efficiently what packet has failed and retransmit that pack again.

- TCP has contributed to the development client-server making sure data transmission is secure and reliable, free of errors, control the flow of how much data server sends to client, allowing a reliable connection and less probability of corrupted files or congestion. 

- HTTP stands for Hypertext Transfer Protocol, it's a transfer protocol that establish the connection between server and client. It's the bridge 

-HTTPS is an considered more secure than HTTP. It uses encryption protocol (TLS) to ensure security of data. It's very useful when dealing with private information such as addresses, bank details, anything that contains your private information. Some web browsers such as Google Chrome are able to tell what web page doesn't use HTTPS, and are not secure.
- HTTPS has contributed to client and server to ensure security of data exchanges, it has an extra layer of protection and if it's leaked it won't be able to be understood.

- Web browsers are softwares that enables users access, find webpages and see it's content such as text, videos and images. We can use Web browsers in our computer, laptops, phones. Some of the most used web browsers are: Google Chrome, Safari, Microsoft Edge and plenty more. 
Web browsers translate HTML documents in web pages, web browser is the bridge between hyper text documents and what the user sees on the screen. Http, TCP and IP all work together.
- Request is the process of requesting a specific path from the client, request uses some import information such as URL.TCP is also established here.
- Rendering this is the process from translating HTML, CSS into webpages we see on the browser.
- Developer tools are tools built into the browsers to help developers fix any errors and optimise the webpages.
Some of the developer tools include: elements panel (here you can see html, and css elements applied to webpage).

References: https://www.cloudflare.com/ https://www.geeksforgeeks.org/ https://tecnoblog.net/

## Q4
### Describe the features of interpreters and compilers and how they are different.

```
- Codes are translated one by one as the program runs.
- Interpreters language examples: Python, Ruby, JavaScript.
- Slower processing when compared to compiler languages
- More flexible, program display errors as you go.
- Independent platform
```

```
- Compiler languages translate the whole code in one go.
- Compilers languages examples:C, C++, Pascal.
- Processing is faster and more efficiently 
- Harder to debug since the error will only be displayed after reading the whole code
```
- Interpreters languages are considered less secure, it requires less memory since no object is generated opposite to Compiler languages. Compiler are harder to debug since you need execute the whole code first, while Interpreter once the error occurs, you can see straight away.

Reference: https://www.freecodecamp.org https://www.geeksforgeeks.org/language-processors-assembler-compiler-and-interpreter/

## Q5	
### Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.

### Python
Python is a high programming language and interpreter language. Some of the benefits of being a high language is the code is easy to understand and code since the language is more similar to human language. Another benefit is being an interpreter language which translate the code line by line so when an error occurs you can see it straight away and fix it. Python also has an inbuilt " Standard Library " which offers plenty of functions and modules. Pythons offers REPL - Read, Eval, Print, Loop which allows 
us to test our code instantly. Another nice feature of Python is Object Oriented Language, you can create classes and objects. Python is a great option for people interested in learning programming language because of it's simple syntax. Some of the cons of Python include, slower than Compilers languages since the processing is done line by line. When it comes to mobile development Python doesn't rank high, it's not the preferred language for mobile, however is highly desirable for desktop. Consumes more memory than other programming languages.

### JavaScript
Java Script is the most popular programming language, most of the websites currently use JavaScript.
JavaScript works together with HTML and Css, syntax of JS can be implemented in HTML. It's responsible for creating dynamic content in web pages resulting in a better user experience. Another benefit is the syntax is considered easy and thus the popularity of the language, there are plenty of resources to learn about JS. Different than Python, JS has more compatibility towards mobile and games. With JS you are able to create pop up windows, validate forms, autocomplete sentences, create animations, interactive forms, menus. 
JS can be used for front-end and back-end purposes, making the language very versatile. 
Some of the drawbacks is that since JS is a Client-Side it's security is more exposed.



References: https://www.geeksforgeeks.org/
https://www.geeksforgeeks.org/disadvantages-of-python/
https://www.w3schools.com/js/


## Q6	
### A hypothetical client has sent you an email (shown in the Q6 Email section), asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself.	

##Q7	
### Think back to a scenario or situation in your own software development projects or work.
Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique.


##Q8	
### A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops. 

Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan.

   
## Q9	
### Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects.	

Language-learning can be used to generate content, using keys points you give it can deliver the document and adjust it in any you want, it can be moral formal, casual or technical. It's able to proofread documents and correct any spelling mistakes. 
For software development it can be used to generate codes, provides suggestions to make the code more efficient, it's also able to spot bugs and gives the solution making the debugging process faster. ChapGPT adds comments when spilling out the code so it's easier for the developer to understand the process. These languages are able to respond to very technical questions.



## Q10	
### Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects.	

## Q11	
### Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace.

- Soft skills:
    - Effective communication: Ability to communicate with team to solve issues, come up with ideas, understand the requirements to deliver common goal.
    - Team work: Be able to work together with the team to deliver the project, always helping each other and supporting.
    - Problem-solving: Be able to solve issues, trace back to the root of the problem and come up with an alternative path to solve the issue. 
    - Time management: Be able to prioritise more import tasks. Be aware of the time to deliver project in time, never late.
    - Willingness to learn and help: Be open to help a coworker when needed and be open to ask for help when needed.


- Hard skills
    - Skills/ knowledge gained through education, previous jobs or any experience such as placement.
    - Programming language: You need to understand how they work, what language will be better for each project, be able to code efficiently.
    - Software Dev Tools: Understanding of version control systems. 
     

I believe the balance is to have a good mix of both Soft and Hard Skills. For software development I believe all skills above are equally important, soft skills such as team-work, problem solving and willing to help will make sure the team works together towards one goal. Hard skills will make the work achievable, since the team has the knowledge needed to develop and deliver the application. 

References: https://au.indeed.com/

## Q12	
### Explain multiple roles or job positions that would be found in a medium-sized software development company.

Some of the jobs in a development company are:

- Front-End Developer: Developers that work on the user interface side, their work-stack include HTML, CSS and JavaScript. 

- Back-End Developer: Developers that work on the server-side, their work-stack include programming language such as Python, Ruby or Java.

- Fullstack Developer: Developers that work on both sides, front and back end. 

- UI/UX Designers: They design the user interface. 

- Graphic designer: Creates logos, icons and any other visual content for the application.

- Project Manager: Manages the team, ensure delivery, oversees the project.

- Product Manager: Defines the roadwork to achieve result, and prioritise what needs to be done first.

- QA Engineer: Test the application to make sure everything runs smoothly, report bugs and makes application meets it's standards. 

- DevOps Engineer: Automates deployment process and ensure system reliability.

- System Administrator: Administrate servers, networks and systems.

- Data Scientist/ Data Analyst: Analyses the data to provide feedback.

