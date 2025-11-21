Client:which request resource.

Server: which respond to the resource.

Devices can be either client or server.

1-Tier Architecture:
--------------------
Client and server are in single layer.

2-Tier Architecture: 
---------------------
Client and server are in different layers.
server has application server and database  server.  

3-Tier Architecture:
-------------------
Client,application layer,database  layer are in different layers.
    
Application server:
------------------
The server which has application is hosted/deployed.

Database server:
-------------
The server which is stored database.

Internet protocol:
-----------------
It is a unique identifer for a device in the network.

Hostname:
---------
Name of the server.

DNS: Domain Name Server
----------------------
It track the IP address and Host Name.

RNS: Root Name Server
--------------------
It checks the root names like .com,.in this are also known as top level domain.
 
SOA: Start of Authority
-----------------------
It has the IP Address.

Firewall:
---------
It stops the unauthorized access to the network.

http: 80 /not secure connection to the application.

https: 443 /secure connection.

sh: 22 /connect to Linux.

RDP: 3389 /connect to windows.

Request travels in the form of packets. It stores the information of request.

Load Balancer:
-------------
It distribute the traffic  to multiple the serviers. It uses round robin method.

Protocols:
----------
HTTP: Hyper Text Transfer Protocol
----------------------------------
It transfer the data to and fro from browser to server.

HTTP Status code:
----------------
404-page not found.

500-Internal service error.

503-service unavailable.

200-success, page found.


TCP: Transmition control Protocol
---------------------------------
Tcp acts as connection between two hosts/ servers.
It acts like a bridge.

OSI layers:
----------
There are 7 layers
1. physical layer
2. Data Link layer
3. Network layer(using IP)
4.Transport layer( using TCP)
5.session layer
6.presentation layer(SSH, RDP etc...)
7.Application layer (HTTP,HTTPS)




AWS has global Infrastructure.
AWS is providing Infrastructure as a service.
Cloud is present in the Remote Location.
Remote location Contains Datacenters.
Datacenters contains Infrastructure.
Infrastructure contains storage,DB's, Servers,Networks,VM,etc..
We need internet to connect to the cloud.
AWS has 33 places his Infrastructures.

AWs: Amazon web services
------------------------------
AWS is a cloud provider, who provides Infrastructure as a services.
we can access services through Amazon Management Console.

Physical Datacenter ------> virtualization------>Cloud ------> AWS (Remotelocation--->Datacenters) 
 
 Types of Clouds/ Deployment Models in Clouds:
 ---------------------------------------------
 Public cloud: The providers services which are accessed by everyone like Azure, AWS, GCP etc...
 Private cloud: The providers services which are accessed with in the organization like oracle, IBM
 Hybrid cloud: The combination of public and private cloud.

 Service Models:
 ---------------
 Infrastructure as a Service(IAAS) :  provider responsible for virtualization, Network, Datacenters and customer is responsible for OS, data, Application. Ex: AWS
 Platform as a Service(PAAS): provider responsible for virtualization, Network, Datacenters, OS and customer is responsible for data, Application. Ex: Azure
 Software as a Service(SAAS):all responsible for provider. EX: Gmail, zoom .....


EC2: Elastic compute Cloud 
--------------------------
EC2 is a AWS service where we can launch EC2 instance.

ElasticBean stalk:
------------------
Easy and quick way of deploying application in aws.



Regions and Availability Zones:
--------------------------------
Region: It is a place where AWS has its infrastructure. ex: AWS-Region in mumbai.
A Region has multiple availability zones(data centers).
servers=Instances


scalability:
------------
Increasing the capacity of servers.

High Availability:
------------------
The period of time available for customer is the high availability. these is measured in %.
Three rules of high availability:
1.Redundency: Keeping the same application in different servers.
2.Monitoring: loadbalancer is doing the monitoring using(Status code 200)
3.failover: If one server goes down another server will take care with the help of load balancer.

Down Time:
----------
The period of time not available for customer is the down time.

zero down time:
--------------
falltolarence is achieved by auto scaling this is called Zero downtime.

Low Latency: High speed (good)
High Latency: low speed (bad)