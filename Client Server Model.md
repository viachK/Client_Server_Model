### 1. Client-server model

In client/server architecture, clients—programs that represent users who need services—and servers—programs that provide services—are separate logical objects that communicate over a network to perform tasks together. A client makes a request for a service and receives a reply to that request. A server receives and processes a request, and sends back the required response.

###### Most client-server applications have three components.
- __Presentation.__ This is essentially a user interface. The presentation component is responsible for displaying information and sending user’s requests to the business logic component.
- __Business Logic.__ This is the software processing client’s requests. It coordinates the application and makes decisions.
- __Data Storage.__ The component responsible for storing and retrieving the data as requested by business logic. This is typically a database.

***

#### Types of Client Server Architecture

###### 1-tier architecture

In this category of client-server setting, the user interface, marketing logic and data logic are present in the same system. This kind of service is reasonable but it is hard to manage due to data variance that allots replication of work. One-tier architecture consists of layers.

For example, Presentation, Business, Data Access layers within a single software package. The data is usually stored in the local system or a shared drive. Applications which handle all the three tiers such as MP3 player, MS Office come under one-tier application.

###### 2-tier architecture

In this type of client-server environment, the user interface is stored at client machine and the database is stored on the server. Database logic and business logic are filed at either client or server but it needs to be maintained. If Business Logic and Data Logic are collected at a client side, it is named as fat client thin server architecture. If Business Logic and Data Logic are handled on the server, it is called thin client fat server architecture. This is considered as affordable.

In two-tier architecture, client and server have to come in direct incorporation. If a client is giving an input to the server there shouldn’t be any intermediate. This is done for rapid results and to avoid confusion between different clients. For instance, online ticket reservations software use this two-tier architecture.

###### 3-tier architecture

In this variety of client-server context, an extra middleware is used that means client request goes to the server through that middle layer and the response of server is received by middleware first and then to the client. This architecture protects 2-tier architecture and gives the best performance. This system comes expensive but it is simple to use. The middleware stores all the business logic and data passage logic. The idea of middleware is to database staging, queuing, application execution, scheduling etc. A Middleware improves flexibility and gives the best performance.

The Three-tier architecture is split into 3 parts, namely, The presentation layer (Client Tier), Application layer (Business Tier) and Database layer (Data Tier). The Client system manages Presentation layer; the Application server takes care of the Application layer, and the Server system supervises Database layer.

In the present scenario of online business, there has been growing demands for the quick responses and quality services. Therefore, the complex client architecture is crucial for the business activities. Companies usually explore possibilities to keep service and quality meet to maintain its marketplace with the help of client-server architecture. The architecture increases productivity through the practice of cost-efficient user interfaces, improved data storage, expanded connectivity and secure services.

***

Depending how much logic is built into the client, the clients can be further classified into thick and thin clients.
- __Thick client.__ It runs on a user’s computer and does most of computing using local resources. It can often work without network connection at all, or with limited connection. An example would be a game that runs on a computer and uses it resources heavily but also needs internet connection to interact with other people.
- __Thin client.__ It relies on a server to do all computing and does not work offline. A typical example would be a web browser. They do not do anything on its own; however, by connecting to various web servers, they can provide a wide range of functionality.