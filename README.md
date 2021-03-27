# serverless-for-peopleops
# Serverless Architecture
Serverless is called serverless architecture in Turkish because we are not dealing with tasks such as setting up a server or a virtual machine in any way, configuring (Provision, Configuration). In other words, we can say that it is an evolved version of PaaS (Platform as a Service). Serverless Architecture, also referred to as BaaS (Back-end as a Service) or FaaS (Function as a Service), is essentially about Functions, as it can be understood from FaaS. So you write your functions, the provider you use runs these functions according to certain events. You do not have to worry about issues such as infrastructure or network structure.
 
As we move to the left of the chart, we need a team with more control and managing the infrastructure. When we go to the right, we are abstracted from the infrastructure and infrastructure services are provided by the Cloud providers. <br/>
**(On-Premise)** In the past years, companies were making serious hardware investments for physical servers (On-Premise). Hardware, operating system, network, security issues are under the responsibility of the infrastructure team. With the development of cloud technologies, virtual servers were created with virtualization technologies and a hardware service rental model started to be taken. <br/>
**IaaS (Infrastructure-as-a-Service)** The entire infrastructure is moved to the Cloud, but teams are still setting up servers, etc. has to deal with things. With the changing needs and the development of Container technologies, Cloud providers provide services for the management of containers. <br/>
**CaaS (Container as a Service)** With this service, our containers are hosted and managed. Guest operating system is not needed and unnecessary cost items are reduced. Cloud providers manage containers for you. <br/>
**Paas (Platform as a Service)** In the ongoing process, Paas emerged, which saves some of the server operations. Responsibilities such as operating system, database and network are under the responsibility of Cloud providers. You can only choose the language you will develop and upload your application. <br/>
**Faas (Function as a Service)** In 2014, Serverless or Faas was announced. A structure where developers are completely isolated from the server and focused only on business has entered our lives. In the serverless approach, functions work as event driven. Therefore, they need a kickback. <br/>

Serverless is not an approach like servers are no longer needed or applications won't run on servers. In terms of software development and management, we can call it an approach or an architectural pattern that makes us think less about the server concept. Scaling is based on the basis that you don't worry about load distribution, server configurations, error management, deployment and even run-time. <br/>

*Servers are definitely used in serverless architectures. The important point here is that the management of these servers, and therefore many operational works that occur, are no longer ours but the service provider's problem.*

Serverless architecture allows developers to focus more on business. Usually a function works in an event driven approach. This trigger can be an http call or it can be triggered by a timer, bus, queue or file upload to the service. <br/>

**Microsoft Azure, Amazon Web Services (AWS) Lambda, Google Cloud Functions, IBM OpenWhisk** are some of the most well-known providers of serverless solutions.
 
In order to meet intense demands in serverless architecture, developers do not need to worry about scaling. This process is done automatically upon request. On the cost side, it is based on Pay as you go. **To give a real-life example, we buy monthly packages from GSM operators, such as talk, sms internet. If we cannot reach these limits or even send SMS, we pay the package fee in advance.** However, the more we consume in the serverless approach, the more invoices are incurred. In this way, we will not be charged for the service we do not use.
 
In the meantime, application should be developed with a different perspective in the serverless architecture approach. It may not be the right choice for every problem. As developers, we have to decide. Switching to serverless architecture may not be right for every project. Serverless may make sense if you have a small number of business transactions that you need to be hosted. If you want to develop a complex application in serverless architecture, you should design the architecture in accordance with serverless. Sometimes faulty designs can incur high costs. If you already have an application, moving the application in Lift and shift logic and moving the small parts to serveless step by step will be more effective in carrying the project.
<br/>
**In what situations do we need it most?**
<br/>
Application management stages are extremely complex and involve many operational studies. Therefore, it is used to make MVPs fast, to pay as much as you actually use and to scale according to the requests sent to the server.

