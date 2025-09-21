# World Wide Web (WWW) -

## Introduction to World Wide Web
The **World Wide Web (WWW)** is a system that allows people to share and access information over the Internet.  
It is not the same as the Internet; rather, it is a **service on the Internet**.  

- Invented by **Tim Berners-Lee** in 1989 at CERN.  
- Uses **HTTP (Hypertext Transfer Protocol)** as the communication protocol.  
- Provides access to documents, multimedia, and applications interconnected through **hyperlinks**.  
- Each resource is identified by a **URL (Uniform Resource Locator)**.  

### Key Components of WWW:
1. **Web Browsers** – Client software to access websites (Chrome, Firefox).  
2. **Web Servers** – Store and serve web pages.  
3. **HTTP/HTTPS Protocols** – Rules for transferring data.  
4. **Hyperlinks** – Connect different documents/resources.  
5. **Search Engines** – Help in discovering websites (Google, Bing).  

---

## Web Page
A **Web Page** is a single document on the web, generally written in **HTML**.  

Types of Web Pages:
- **Static Web Page**: Content remains fixed, only changes if the developer edits it.  
- **Dynamic Web Page**: Content changes based on user interaction, location, time, or database queries.  

### Example:
- Static: A company’s contact page.  
- Dynamic: An online shopping cart page.  

---

## Home Page
- The **home page** is the **default page** of a website.  
- Acts as the **starting point** of navigation.  
- Common file names: `index.html`, `default.html`.  
- Provides menus, links, and site overview.  

---

## Website
A **Website** is a collection of interconnected web pages hosted on a domain/server.  

### Classification of Websites:
1. **Static Websites**
   - Built with HTML & CSS.  
   - No interaction with databases.  
   - Example: Portfolio, blogs.  

2. **Dynamic Websites**
   - Content changes dynamically.  
   - Built using server-side technologies (PHP, Python, Node.js).  
   - Connected with databases (MySQL, MongoDB).  
   - Example: Amazon, Facebook, YouTube.  

---

## Client-Server Computing Concepts
The **client-server model** is the backbone of the WWW.  

- **Client**: A user’s computer, mobile, or browser that requests services.  
- **Server**: A remote computer that provides services like files, databases, or web pages.  

### Process Flow:
1. User types a URL in the browser.  
2. Browser sends a request to the web server.  
3. Server processes the request (possibly fetches from a database).  
4. Response (HTML, CSS, JavaScript, data) is sent back.  
5. Browser renders the page for the user.  

This communication mostly uses the **HTTP/HTTPS protocol**.  

---

## Web Client and Web Server
- **Web Client**: Software or application used to access web resources (e.g., browsers).  
- **Web Server**: Software running on a server computer that handles client requests.  

### Examples of Web Servers:
- Apache HTTP Server  
- Nginx  
- Microsoft IIS  

---

## Web Browser
A **web browser** is an application program that retrieves and displays content from the WWW.  

### Common Browsers:
- Google Chrome  
- Mozilla Firefox  
- Microsoft Edge  
- Safari  

### Functions of a Browser:
- Interpret HTML, CSS, and JavaScript.  
- Provide navigation tools (back, forward, reload).  
- Support plugins and extensions.  
- Handle cookies, cache, and security protocols (HTTPS, SSL).  

---

## Client-Side Scripting Languages
Executed on the **user’s browser**. They make web pages interactive.  

### Examples:
- **HTML** – Structure of a webpage.  
- **CSS** – Styling and design.  
- **JavaScript** – Adds interactivity (form validation, dynamic updates).  

### Advantages:
- Faster response as processing happens in the browser.  
- Reduces server load.  

### Limitations:
- Security risks (code visible to users).  
- Limited access to server resources.  

---

## Server-Side Scripting Languages
Executed on the **web server** before sending the response to the browser.  

### Examples:
- **PHP** – Widely used in WordPress, Drupal.  
- **Node.js** – JavaScript runtime for server-side apps.  
- **Python (Django, Flask)** – Popular in modern web development.  
- **Java (JSP, Servlets)** – Enterprise-level apps.  
- **Ruby on Rails** – Used in startups and rapid prototyping.  

### Advantages:
- Access to server resources and databases.  
- Better security since the code is hidden from the client.  
- Ability to generate dynamic and personalized web content.  

### Limitations:
- Slower compared to client-side since requests go to the server.  
- Requires more server resources.  

---

## Static vs Dynamic Website (Comparison)

| Feature             | Static Website                          | Dynamic Website                          |
|---------------------|------------------------------------------|------------------------------------------|
| Content             | Fixed, same for every visitor           | Changes based on user/data                |
| Technology Used     | HTML, CSS only                          | Server-side scripts + Database            |
| Speed               | Very fast                               | Slower due to processing                  |
| Cost                | Cheaper to host                        | More expensive (needs database, server)   |
| Example             | Portfolio site, Resume site             | E-commerce, Social media sites            |

---
