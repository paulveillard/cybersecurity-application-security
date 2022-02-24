# Application Security
> An ongoing & curated collection of awesome  software practices and remediation, libraries and frameworks,payloads and techniques, best guidelines and technical resources about Application Security.


## Introduction

> A Web application (Web app) is an application program that is stored on a remote server and delivered over the Internet through a browser interface. […] Web applications do not need to be downloaded since they are accessed through a network. Users can access a Web application through a web browser such as Google Chrome, Mozilla Firefox or Safari. For a web app to operate, it needs a Web server, application server, and a database. Web servers manage the requests that come from a client, while the application server completes the requested task. A database can be used to store any needed information.

![image](https://github.com/paulveillard/cybersecurity-application-security/blob/main/img/Anatomy_WEB_APPLICATION.png)


## Benefits of a Web Application
#### A. EASIER INSTALLATION AND MAINTENANCE 
It’s much easier to install, upgrade or maintain a web-based application than a standalone desktop application. Web applications are upgraded in the host servers, and every user can access the updated version as soon as the deployment had finished, without needing to update the application on their PCs. 

#### B. NO DOWNLOAD HASSLES
From an end-user perspective, this is probably the greatest advantage – with web applications, you don’t have to download anything in order to use the service. A compatible browser with Internet access is usually all you need. 

#### C. USE OF LESS STORAGE SPACE 
When using a web application, you don’t have to worry about how much space and memory it needs on your device. Moreover, they can be accessed from any place in the world where there is an active Internet connection. 

#### D. ACCESSIBLE ON VARIOUS PLATFORMS  
It’s safe to say that nowadays mobility is a great asset and it sure helps a lot not to depend on a certain device in order to complete your tasks. Web applications can be used on any platform (desktop, laptop, phone, tablet), wherever you are. 


## Web Application Types
#### A. STATIC WEB APPLICATIONS 
These are the most basic type of web application, created using HTML and CSS. If you need to make any serious changes to it, it’s highly certain that you need to contact the ones who planned and designed it. 

#### B. DYNAMIC WEB APPLICATIONS 
Dynamic web applications can include databases or forums and have the constant ability to update or change the available information. 

#### C. E-COMMERCE APPLICATIONS
E-commerce apps are more complex than the other two mentioned before, since they need a way to collect electronic payment. 

#### D. PORTAL WEB APPLICATIONS 
Portal web applications include forums, chats, emails etc. and are characterized by many different sections or categories which are accessible by way of a home page. 

#### E. ANIMATED WEB APPLICATIONS 
It’s mandatory for this kind of applications to use FLASH technology. Animated web applications do not work with SEO optimization or positioning, because search engines cannot read their information properly. 

#### F. CONTENT MANAGEMENT SYSTEMS 
Content management systems offer interfaces that can be accessed and updated and are used for personal or corporate blogs, media sites and so on.  If we want to talk about web application security, though, we must first specify that web applications are related to the supply chain topic, which we covered here. Unfortunately but not surprisingly, as third-parties in your business workflow, web applications can be attacked in various ways, from database manipulation to large-scale network disruption.  According to DARKReading, 


## What is web application security?
- Web application security is the process of protecting websites and online services against different security threats that exploit vulnerabilities in an application’s code. Common targets for web application attacks are content management systems (e.g., WordPress), database administration tools (e.g., phpMyAdmin) and SaaS applications.

![image](https://github.com/paulveillard/cybersecurity-application-security/blob/main/img/web-application-firewall.png)


## Here are the main web application security threats that you need to be aware of: 


![image](https://github.com/paulveillard/cybersecurity-application-security/blob/main/img/threats.png)

#### 1. CROSS-SITE SCRIPTING ( XSS)
In a cross-site scripting attack, hackers inject client-side scripts into webpages to get direct access to important information, to impersonate the user or to trick the user into disclosing sensitive data. If a visitor loads the compromised page, his/her browser may execute the malicious code. This kind of attack is not really the most sophisticated, but it is the most common. 

#### 2. CROSS-SITE REQUEST FORGERY 
This type of attack is a serious web application security vulnerability, involving tricking a user into making a request utilizing their authentication or authorization. By leveraging account privileges, attackers are able to send false requests. The common targets for cross-site request forgeries are the highly privileged accounts, like administrator or executive, which results in the exfiltration, destruction or modification of important information. 

#### 3. DENIAL-OF-SERVICE (DOS) & DISTRIBUTED DENIAL-OF-SERVICE (DDOS) ATTACKS 
During a DoS or DDoS attack, hackers try to overload a targeted server or its surrounding infrastructure. When the server is no longer able to effectively process incoming requests, it will start to behave in an irregular manner, denying service to incoming requests from legitimate users. 

#### 4. DATA BREACHES 
Data breaches may occur through malicious actions or by mistake, but the consequence is the same: sensitive or confidential information gets leaked. Depending on the company who is unfortunate enough to experience a data breach, millions of user accounts can get exposed. 

#### 5. BUFFER OVERFLOW
The term buffer refers to memory storage regions that temporarily hold data during its transfer from one location to another. A buffer overflow/overrun happens when the data volume is bigger than the storage capacity of the memory buffer, which results in adjacent memory locations being overwritten with data. By overwriting the memory of an application, the execution path of the program is changed, which triggers a response that compromises files or exposes sensitive information. Moreover, extra codes that send new instructions to the application may be introduced to get access to the IT systems. 

#### 6. SQL INJECTION (SQI) 
Structured Query Language (SQL) represents a programming language typically used in relational databases or data stream management systems, being very effective in querying, manipulating, aggregating data and performing an impressive number of other functions. In a SQL Injection attack,  the malicious players exploit vulnerabilities in the way a database executes search queries. 

#### 7. MEMORY CORRUPTION 
Memory corruptions refer to that process in which a location in memory is unintentionally modified, possibly leading into unexpected behaviour. Hackers will try to exploit this by attempting code injections or buffer overflow attacks. 

#### 8. PATH TRAVERSAL
Path traversal attacks refer to the injection of “../” patterns in order to move up in the server directory hierarchy, for the purpose of accessing unauthorized files or directories outside the webroot folder. Successful path traversal attack might allow hackers access to user credentials, configuration files or even databases.  All these sound pretty alarming, but, fortunately, there are many options you can choose when it comes to web application security and protecting your company by detecting, preventing and responding to attacks. 




## Table of Contents
