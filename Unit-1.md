# UNIT 1 
>**Overview of Computing Paradigm: Recent Trends in Computing: [Distributed Computing](#distributed-computing), [Cluster Computing](#cluster-computing), [Grid-computing](#grid-computing), [Utility Computing](#utility-computing), [Cloud Computing](#cloud-computing)**

>**Evolution of Cloud Computing: Migrating into a Cloud.**

>**Cloud Computing Basics: Cloud Computing Overview; [Characteristics](#characteristics) [Applications](#applications),[Benefits](#benefits), [Limitations](#limitations), [Challenges](#challenges).**

>**Cloud Computing Service Models: [Infrastructure as a Service](#iaas), [Platform as a Service](#paas), [Software as a Service](#saas), Cloud Computing Deployment Models: Private Cloud; Public Cloud; Community Cloud; Hybrid Cloud.**


## **Distributed Computing:**
![Distributed Computing](https://www.ridge.co/wp-content/uploads/2021/10/distributed-computing-diagram.gif)

Distributed computing is the method of making multiple computers work together to solve a common problem. It makes a computer network appear as a powerful single computer that provides large-scale resources to deal with complex challenges.

### Advantages:
1. **Scalability:** Distributed computing can scale up or down to meet the demands of the system. Adding more nodes to the network can increase its capacity to handle more data and users.

2. **Fault tolerance:** A distributed system can continue to function even if some of its nodes fail. The system can replicate data and computations across multiple nodes, reducing the impact of any single failure.

3. **Flexibility:** Distributed computing allows for a variety of hardware and software configurations, making it easier to adapt to changing needs or requirements.

4. **Increased performance:** By distributing computations across multiple nodes, distributed computing can achieve higher processing speeds than a single computer or server.

5. **Cost-effectiveness:** Distributing computations across a network of low-cost nodes can be more cost-effective than purchasing a single high-performance computer or server.

6. **Reduced data transfer time:** By distributing computations closer to the data, distributed computing can reduce data transfer time and network congestion.

7. **Improved security:** By distributing data across multiple nodes, a distributed system can reduce the risk of data loss or theft. Encryption and other security measures can also be implemented on each node to increase security.



### Architecture:
1. **Client-Server:** A type of architecture where a central server provides services or resources to multiple clients over a network.

2. **Peer-to-Peer (P2P):** A type of architecture where nodes (peers) communicate and share resources directly with each other, without the need for a central server.

3. **Clustered:** A type of architecture where multiple servers or nodes are connected to work together as a single system to provide high availability and scalability.

4. **Grid:** A type of architecture where multiple geographically dispersed computers work together to solve a single problem, typically used for large-scale scientific or engineering computations.

5. **Cloud:** A type of architecture where services and resources are provided over the internet on-demand, typically through a third-party provider.

6. **Service-Oriented:** A type of architecture where components of a system are designed to provide services that can be accessed by other components over a network, allowing for modular and scalable systems.

7. **Microservices:** A type of architecture where a system is composed of small, independent services that communicate with each other over a network. This allows for greater flexibility, scalability, and ease of development and maintenance.

## **Cluster Computing:**

![](https://media.geeksforgeeks.org/wp-content/uploads/20210313225739/UntitledDiagram4.png)

Cluster computing is a type of distributed computing architecture where multiple computers or servers are connected together to work as a single system. In a cluster, each node typically runs its own operating system and application software, and the nodes are connected through a high-speed local area network (LAN).
### Advantages
- High availability and scalability
- Fault tolerance
- Better performance and faster processing of large datasets
- Cost-effective compared to supercomputers
- Modular and flexible architecture
- Improved resource utilization and energy efficiency
- Easy to expand or upgrade as needed
- Increased reliability and reduced downtime

### Types:
- High-Performance Computing (HPC) Clusters
- Load Balancing Clusters
- High-Availability Clusters
- Database Clusters
- Web Clusters
- Compute Clusters
- Storage Clusters
- Virtual Clusters

## **Grid Computing:**
![](https://i.ytimg.com/vi/LO97PDNUrTg/sddefault.jpg)

Grid computing is a computing infrastructure that combines computer resources spread over different geographical locations to achieve a common goal. All unused resources on multiple computers are pooled together and made available for a single task. 

### Advantages:
- High computing power and scalability
- Efficient resource utilization
- Cost-effective compared to building a physical supercomputer
- Ability to handle complex and large-scale tasks
- Distributed computing model ensures fault tolerance and reliability
- Ability to share resources among multiple organizations

### Disadvantages:
- Complexity in managing and maintaining the grid infrastructure
- Security concerns in sharing resources and data over a network
- Potential for data privacy breaches and unauthorized access
- Challenges in ensuring compatibility and interoperability of different systems
- Lack of standardization and uniformity in grid computing protocols and technologies
- Dependence on network connectivity and bandwidth

## **Utility Computing:**
![](https://1.bp.blogspot.com/-hhWr0MEOswc/Uqz6DEPAKOI/AAAAAAAAD4Y/8fRD7qDQNIs/s400/utility.jpg)

Utility computing is a computing service that provides computing resources on a pay-per-use basis, similar to utility services like water and electricity. Users can quickly and easily provision resources for their applications, reducing the time and cost required to set up and maintain their own computing infrastructure.

### Advantages:
- Cost-effective, as users only pay for the resources they consume
- Scalable, allowing users to easily scale up or down their resource usage based on changing demands
- Flexible, allowing users to access resources from anywhere with an internet connection
- Reduces the need for users to invest in and manage their own computing infrastructure

### Disadvantages:
- Dependence on network connectivity and internet bandwidth
- Security risks associated with accessing resources over the internet
- Cost management can be challenging, as the pay-per-use model can lead to unpredictable expenses if usage levels are not closely monitored
- Potential for vendor lock-in, as users may become dependent on a single provider for their computing needs.


## **Cloud Computing:**
![](https://www.tutorialride.com/images/cloud-computing/view-of-cloud-computing-architecture.jpeg)
![](https://www.click2cloud.com/blogs/Cloud-Architecture.jpg)

Cloud computing is a service that provides computing resources over the internet, allowing users to easily access and scale resources from anywhere. It offers flexibility and a range of tools, but can also present challenges with security, cost management, and data control.

>## characteristics 

- **On-demand self-service:** Users can provision computing resources as needed, without interaction with the service provider.
- **Broad network access:** Cloud computing resources are accessible over a network such as the internet, from any device.
- **Resource pooling:** Cloud computing providers use virtualization technology to dynamically allocate resources across multiple users, allowing for efficient resource utilization and scalability.
- **Rapid elasticity:** Cloud computing resources can be quickly scaled up or down in response to changing user demands.
- **Measured service:** Cloud computing providers use metering and monitoring to track resource usage and bill users accordingly.

>## Applications:

- Data storage and backup
- Software development and testing
- Website hosting and e-commerce
- Big data analytics and processing
- Machine learning and AI
- Collaboration and communication tools
- Virtual desktops and remote workspaces
- Content delivery networks (CDNs)
- Internet of Things (IoT) data processing and storage
- Gaming and media streaming services

>## Benefits:

- Cost savings from not having to maintain on-premises infrastructure
- Increased flexibility and scalability of computing resources
- Improved accessibility and mobility of applications and data
- Enhanced data security and disaster recovery capabilities
- Reduced environmental impact through shared resources and           energy-efficient infrastructure
- Improved agility and speed of innovation and deployment

>## Limitations:
- Dependence on reliable and fast internet connectivity
- Potential security concerns with storing sensitive or confidential data in the cloud
- Vendor lock-in and lack of flexibility in switching to another platform or provider
- Limited control over infrastructure in a public cloud environment
- Downtime and service availability issues
- Compliance and regulatory challenges with data privacy and governance.

>## Challenges:
- Managing and optimizing cloud costs
- Integrating with existing on-premises systems and applications
- Ensuring data security and compliance with regulations
- Avoiding vendor lock-in and maintaining flexibility
- Managing multi-cloud and hybrid cloud environments
- Providing reliable and consistent performance and availability
- Addressing skills gaps and training employees on cloud technologies.


![](https://hazelcast.com/wp-content/uploads/2021/12/infrastructure-as-a-service-iaas-800x435-1.png)

## ***IaaS:***
`Infrastructure as a Service` (IaaS) is a cloud computing model that provides virtualized computing resources over the internet. With IaaS, users can rent servers, storage, and networking components on a pay-per-use basis, rather than purchasing and managing their own physical infrastructure.

> Advantages:
1. Scalability: Resources can be easily scaled up or down as needed.
2. Flexibility: Users have access to a wide range of resources and can customize their infrastructure to meet their specific needs.
3. Cost savings: IaaS eliminates the need for businesses to purchase and maintain their own physical infrastructure, reducing capital expenditures.
4. High availability: IaaS providers typically offer high levels of availability and uptime.
5. Disaster recovery: IaaS providers can help businesses implement disaster recovery plans to ensure business continuity.

> Disadvantages:
1. Security: Users need to take responsibility for securing their applications and data in the cloud.
2. Dependence on provider: Users are dependent on the IaaS provider for infrastructure maintenance and support.
3. Potential downtime: If the IaaS provider experiences downtime or service disruption, users may experience interruptions to their business operations.
4. Data transfer costs: Moving large amounts of data in and out of the cloud can result in additional costs.
5. Technical expertise: Users need to have the technical expertise to manage their infrastructure in the cloud.


## ***PaaS:***
![]()
PaaS, or `Platform-as-a-Service`, is a cloud computing model that provides customers a complete cloud platform—hardware, software, and infrastructure—for developing, running, and managing applications without the cost, complexity, and inflexibility that often comes with building and maintaining that platform on-premises.

> Benifits:
1. Cost-effectiveness
2. Scalability
3. Faster time-to-market
4. Easy maintenance and upgrades
5. High availability and reliability
6. Improved security

> Use cases:
1. Building and deploying web applications
2. Developing and deploying mobile applications
3. Creating and managing databases
4. Integrating with third-party services and APIs
5. Hosting websites and e-commerce platforms
6. Analyzing and processing data
7. Creating and managing virtual machines and containers

## ***SaaS:***

SaaS stands for `Software as a Service`, which is a software delivery model in which a third-party provider hosts applications and makes them available to customers over the internet. Rather than purchasing software licenses and installing them on their own computers, users access the software through a web browser or mobile app and pay a subscription fee to use the service.

 >Advantages:
1. Lower upfront costs
2. Scalability
3. Accessibility
4. Automatic updates and maintenance
5. Integration
6. Subscription pricing
7. Improved security
8. Support and training
9. Fast deployment
10. Easy customization

> Use Cases:
1. Customer Relationship Management (CRM) software
2. Enterprise Resource Planning (ERP) software
3. Human Resources Management (HRM) software
4. Project management software
5. Email marketing software
6. Document management software
7. Accounting software
8. Video conferencing software
9. E-commerce software
10. Business intelligence and analytics software

## ***Private Cloud:***
A private cloud is a type of cloud computing infrastructure that is owned and 
operated by a single organisation and provides dedicated 
resources for that organisation's users or tenants. 
It is deployed within the organisation's own data centre or on-premises 
infrastructure and offers greater control over the environment, security,
and compliance compared to public cloud solutions.
Private Cloud:

### Advantages:
1. Greater control over the infrastructure and data security
2. High level of customisation and flexibility to meet specific needs
3. Better performance and reliability due to dedicated resources
4. Ability to meet compliance and regulatory requirements
5. Cost-effective for large organisations with high resource demands
### Disadvantages:
1. Higher upfront costs due to the need for dedicated infrastructure
2. Increased maintenance and management responsibilities
3. Limited scalability compared to public cloud options
4. Limited access to the latest technology advancements
5. Potentially slower adoption of new services and features


## ***Public Cloud***
	>