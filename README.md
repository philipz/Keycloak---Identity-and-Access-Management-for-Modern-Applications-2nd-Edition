# Keycloak - Identity and Access Management for Modern Applications, Second Edition
This is the code repository for [Keycloak - Identity and Access Management for Modern Applications, Second Edition](https://www.packtpub.com/product/keycloak-identity-and-access-management-for-modern-applications-second-edition/9781804616444), published by Packt.

**Harness the power of Keycloak, OpenID Connect, and OAuth 2.0 to secure applications**

The authors of this book are -[Stian Thorgersen](https://www.linkedin.com/in/stian-thorgersen-4714983), [Pedro Igor Silva](https://www.linkedin.com/in/pigorcraveiro)
## About the book

The 2nd Edition of Keycloak - Identity and Access Management for Modern Applications is an updated, comprehensive introduction to Keycloak and its updates.

In this new edition, you will learn how to use the latest distribution of Keycloak. The recent versions of Keycloak are now based on Quarkus, which brings a new and improved user experience and a new admin console with a higher focus on usability. You will see how to leverage Spring Security, instead of the Keycloak Spring adapter, while using the latest distribution of Keycloak. As you progress, you will understand the new Keycloak distribution and explore best practices in using OAuth. Finally, you'll cover general best practices and other information on how to protect your applications.

By the end of this new edition, you will have learned how to install and manage the latest version of Keycloak to secure new and existing applications using the newest features.

## Key Takeaways
- Understand how to install, configure and manage the latest version of Keycloak
- Leverage additional features and capabilities of Keycloak in this new version
- Discover new updates to installing and running Keycloak
- Secure new and existing applications with Keycloak
- Safely manage Keycloak in a production environment
- Discover available frameworks and third-party libraries that can be used with Keycloak

## New Edition v/s Previous Edition: 
- Based on, and fully updated for, the newest Keycloak version 
- Spring Security replaces the older Spring Adapter 
- More in-depth coverage of OAuth best practices 
- More content on Keycloak authorization services 

## What's New 

In the previous edition - '[Keycloak - Identity and Access Management for Modern Applications](https://www.packtpub.com/product/keycloak-identity-and-access-management-for-modern-applications/9781800562493)' Keycloak was deployed on top of WildFly, a JavaEE Application Server, while more recent versions of Keycloak are now built with Quarkus, a cloud native Java framework. Being based on Quarkus brings a number of improvements, reducing startup time significantly, reducing memory footprint, and most importantly a much simpler and consistent approach to configuring Keycloak. 

Another big change that came to Keycloak was a new admin console with a bigger focus on usability than the previous console. The new admin console underwent a complete re-design to make it easier and more intuitive. 

## Table of contents
### Chapters
1. Getting Started with Keycloak
2. Securing Your First Application
3. Brief Introduction to Standards
4. Authenticating Users with OpenID Connect
5. Authorizing Access with OAuth 2.0
6. Securing Different Application Types
7. Integrating Applications with Keycloak
8. Authorization Strategies
9. Configuring Keycloak for Production
10. Managing Users
11. Authenticating Users
12. Managing Tokens and Sessions
13. Extending Keycloak
14. Securing Keycloak and Applications

## Chapter Summary
### Chapter 1, Getting Started with Keycloak
This chapter gives you a brief introduction to Keycloak and steps on how to get quickly up to speed by installing and running Keycloak yourself. It also provides an introduction to the Keycloak admin and account consoles.

We’re going to cover the following main topics:
- Introducing Keycloak
- Installing and running Keycloak
- Discovering the Keycloak admin and account consoles

### Chapter 2, Securing Your First Application 
This chapter explains how to secure your first application with Keycloak through a sample application consisting of a single-page application and a REST API.

We’re going to cover the following main topics:
- Understanding the sample application
- Running the application
- Understanding how to log in to the application
- Securely invoking the backend REST API

### Chapter 3, Brief Introduction to Standards 
This chapter provides a brief introduction and comparison of the standards Keycloak supports to enable you to integrate your applications securely and easily with Keycloak.

We’re going to cover the following main topics:
- Authorizing application access with OAuth 2.0
- Authenticating users with OpenID Connect
- Leveraging JWT for tokens
- Understanding why SAML 2.0 is still relevant

### Chapter 4, Authenticating Users with OpenID Connect 
This chapter teaches how to authenticate users by leveraging the OpenID Connect standard. This chapter leverages a sample application that allows you to see and understand how an application authenticates to Keycloak through Open ID Connect.

We’re going to cover the following main topics:
- Running the OpenID Connect playground
- Understanding the Discovery endpoint
- Authenticating a user
- Understanding the ID token
- Invoking the UserInfo endpoint
- Dealing with users logging out

### Chapter 5, Authorizing Access with OAuth 2.0
This chapter teaches how to authorize access to REST APIs and other services by leveraging the OAuth 2.0 standard. Through a sample application, you will see firsthand how an application obtains an access token through OAuth 2.0, which the application uses to invoke a protected REST API.

We’re going to cover the following main topics:
- Running the OAuth 2.0 playground
- Obtaining an access token
- Requiring user consent
- Limiting the access granted to access tokens
- Validating access tokens
 
### Chapter 6, Securing Different Application Types
This chapter covers best practices on how to secure different types of applications, including web, mobile, and native applications, as well as REST APIs and other backend services.

We’re going to cover the following main topics:
- Understanding internal and external applications
- Securing web applications
- Securing native and mobile applications
- Securing REST APIs and services

### Chapter 7, Integrating Applications with Keycloak
This chapter provides steps on how to integrate your applications with Keycloak, covering a range of different programming languages, including Go, Java, client-side JavaScript, Node.js, and Python. It also covers how you can utilize a reverse proxy to secure an application implemented in any programming language or framework.

We are going to cover the following topics and integrations:
- Choosing an integration architecture
- Choosing an integration option
- Integrating with Golang applications
- Integrating with Java applications
- Integrating with JavaScript applications
- Integrating with Node.js applications
- Using a reverse proxy
- Try not to implement your own integration

### Chapter 8, Authorization Strategies
This chapter covers how your application can use information about the user from Keycloak for access management, covering roles and groups, as well as custom information about users.

We will be covering the following topics in this chapter:
- Understanding authorization
- Using RBAC
- Using GBAC
- Using OAuth2 scopes
- Using ABAC
- Using Keycloak as a centralized authorization server

### Chapter 9, Configuring Keycloak for Production
This chapter teaches how to configure Keycloak for production, including how to enable TLS, configuring a relational database, and enabling clustering for additional scale and availability.

We will be covering the following topics:
- Setting the hostname for Keycloak
- Enabling TLS
- Configuring a database
- Enabling clustering
- Configuring a reverse proxy
- Evaluating your environment

### Chapter 10, Managing Users
This chapter takes a closer look at the capabilities provided by Keycloak related to user management. It also explains how to federate users from external sources such as LDAP, social networks, and external identity providers.

We will cover the following topics:
- Managing local users
- Integrating with LDAP and Active Directory
- Integrating with social identity providers
- Integrating with third-party identity providers
- Allowing users to manage their data

### Chapter 11, Authenticating Users
This chapter covers the various authentication capabilities provided by Keycloak, including how to enable second-factor authentication, as well as security keys.

We will cover the following topics:
- Understanding authentication flows
- Using passwords
- Using one-time passwords (OTPs)
- Using Web Authentication (WebAuthn)
- Using strong authentication

### Chapter 12, Managing Tokens and Sessions
This chapter helps understand how Keycloak leverages server-side sessions to keep track of authenticated users, as well as best practices for managing tokens issued to your applications.

We are going to cover the following topics:
- Managing sessions
- Managing tokens

### Chapter 13, Extending Keycloak
This chapter explains how you can extend Keycloak, covering how you can modify the look and feel of user-facing pages such as the login pages and account console. It also provides a brief introduction to one of the more powerful capabilities of Keycloak that allows you to provide custom extensions for a large number of extension points.

We are going to cover the following topics in this chapter:
- Understanding service provider interfaces
- Changing the look and feel
- Customizing authentication flows
- Looking at other customization points

### Chapter 14, Securing Keycloak and Applications
This chapter provides best practices on how to secure Keycloak for production. It also provides a brief introduction to some best practices to follow when securing your own applications.

We’re going to cover the following main topics:
- Securing Keycloak
- Securing the database
- Securing cluster communication
- Securing applications

### Assessments
In this check your answers to the questions at the end of each chapter here.

> If you feel this book is for you, get your [copy](https://www.amazon.com/Keycloak-Identity-Management-Applications-applications/dp/1804616443) today! <img alt="Coding" height="15" width="35"  src="https://media.tenor.com/ex_HDD_k5P8AAAAi/habbo-habbohotel.gif">


With the following software and hardware list you can run all code files present in the book (Chapter number mention here).

## Software and hardware list

| Chapter | Software required    | Link to the software    | Hardware specifications    | OS required    |
|:---:  |:---:  |:---:  |:---:  |:---:  |
| All chapters  | Keycloak 22  | [https://www.keycloak.org/downloads/](https://www.keycloak.org/downloads) | Should work on any recent computer | Windows, MacOS, Linux  |
| All chapters  | Docker  | [https://www.docker.com/](https://www.docker.com/) | Should work on any recent computer | Windows, MacOS, Linux  |
| All chapters  | JDK 17+  | [https://openjdk.java.net/](https://openjdk.java.net/) | Should work on any recent computer  | Windows, MacOS, Linux |
| Chapter 5-14  | Node.js 18+  | [https://nodejs.org/ ](https://nodejs.org/) | Should work on any recent computer  | Windows, MacOS, Linux |


## Know more on the Discord server <img alt="Coding" height="25" width="32"  src="https://cliply.co/wp-content/uploads/2021/08/372108630_DISCORD_LOGO_400.gif">
You can get more engaged on the discord server for more latest updates and discussions in the community at [Discord](https://packt.link/SecNet)

## Download a free PDF <img alt="Coding" height="25" width="40" src="https://emergency.com.au/wp-content/uploads/2021/03/free.gif">

_If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost. Simply click on the link to claim your free PDF._
[Free-Ebook](https://download.packt.com/free-ebook/9781804616444) <img alt="Coding" height="15" width="35"  src="https://media.tenor.com/ex_HDD_k5P8AAAAi/habbo-habbohotel.gif">

We also provide a PDF file that has color images of the screenshots/diagrams used in this book at [GraphicBundle](https://packt.link/6BLPp) <img alt="Coding" height="15" width="35"  src="https://media.tenor.com/ex_HDD_k5P8AAAAi/habbo-habbohotel.gif">


## Get to know the Authors
_Stian Thorgersen_ started his career at Arjuna Technologies building a cloud federation platform, years before most companies were even ready for a single-vendor public cloud. He later joined Red Hat, looking for ways to make developers’ lives easier, which is where the idea of Keycloak started. In 2013, Stian co-founded the Keycloak project with another developer at Red Hat. Today, Stian is the Keycloak project lead and is also the top contributor to the project. He is still employed by Red Hat as a senior principal software engineer focusing on identity and access management, both for Red Hat and for Red Hat’s customers. In his spare time, there is nothing Stian likes more than throwing his bike down the mountains of Norway.

_Pedro Igor Silva_ started his career back in 2000 at an ISP, where he had his first experiences with open source projects such as FreeBSD and Linux. In this time he worked as a Java and J2EE software engineer. Since then, he has worked in different IT companies as a system engineer, system architect, and consultant. Today, Pedro Igor is a principal software engineer at Red Hat and one of the core developers of Keycloak. His main area of interest and study is now IT security, specifically in the application security and identity and access management spaces. In his non-working hours, he takes care of his planted aquariums.

## Other Related Books
- [Cybersecurity Threats, Malware Trends, and Strategies - Second Edition](https://www.packtpub.com/product/cybersecurity-threats-malware-trends-and-strategies-second-edition/9781804613672)
- [Cybersecurity Blue Team Strategies](https://www.packtpub.com/product/cybersecurity-blue-team-strategies/9781801072472)
