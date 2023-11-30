# REST

## Contents

- ### What is API?
- ### Few Approaches To Create APIs
- ### REST And It's Architecture
- ### REST Advantages

## What is API

- An API (**Application Programming Interface**) is a software interface where we can make interaction/communication between software.
- Before the use of APIs it is not easy to make two or more software interactions.
- By using **API** we can make communication easy irrespective of the language/environment in which the application was built.
- API helps in concentrating on the functionality rather than making **interface**, this is the reason nowadays **MICROSERVICES** are popular.

## Few Approaches To Create APIs

- Initially **MICROSOFT** created **SOAP**(**Simple Object Access protocol**) which uses communication between softwares using **XML**. However, it uses only **XML** type data to transfer and XML has more structure(syntax) it requires more bandwidth and if we use SOAP protocol no cache is created.
- **RPC(Remote Procedure Call)** is also an action-oriented protocol that provides high performance. It is used for client-server communication however it is not a standardized protocol. And it only supports GET and POST methods.

## REST And It's Structure

- REST(**Representational State Transfer**) is an API that contains a set of rules that need to be followed to create an interface among software. It is **simple and flexible** and it uses the HTTP Request. It can use the methods PUT, GET, DELETE, and POST.
- ![Architecture](/restArchitecture.png)

- ### Architecture
- It contains a client and server where the server connects to the database if required. It is possible that different kinds of clients can use the same REST API as per the requirements. This API makes things easy as it hides all information and we can use directly APIs without their implementation.
- REST APIs are mostly used in modern web development.

  ## REST Advantages

  - **Client-Server**
    - REST separates client and server and due to this, it increases the concentration on the client side and server side independently.
  - **Stateless**
    - Each request from the client can be treated individually as the server design does not store any information about previous client requests.
  - **Cache**
    - Cache at the client increases the performance of the application, REST makes use of this storing of cache at the client side.
  - **Uniform Interface**
    - There will be a clear understanding of how client and server communicate through URLs.
  - **Layered System**
    - Due to this layered system, the security of the application increases. As only one layer depends on its adjacent layers.
  - **Code on Demand**
    - This feature enables a server to send the code to client if needed.
    ## References
    * [REST API geeks for geeks](https://www.geeksforgeeks.org/rest-api-introduction/)
