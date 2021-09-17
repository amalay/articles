# Frequent Terms used in Cloud world

Before going to the cloud world, lets first understand the <b>Environment</b>.

## Environment:
Combination of Infrastructure/Hardwares, Softwares and Networking is collectively called as environment. Environment can be setup in two way On-Premises environment and Cloud environment.

### 1. On-Premises Environment:
When all the required resources (Hardwares, Softwares, Tools, Applications etc.) are deployed in-house and within an enterprise’s IT infrastructure then it is called on-premises environment.

An enterprise is responsible for maintaining the solution and all its related processes like Infrastructure Setup, Software, Licenses, Hosting, Backup, Recovery, Security etc. On-Premises environment is fully controlled by enterprise and enterprise can do each on everything on it.

On-Premises environment is good in terms of security & compliance, regulatory control(e.g. GDPR, HIPAA, FERPA etc.) for sensitive data (e.g. Government, Banking & Financial etc.).

### 2. Cloud Environment:
Cloud is nothing but a kind of on-premises environment only but the difference is, it is exist in Cloud Service provider's premises. And an enterprise are able to access those resources and use as much as they want at any given time. Cloud environment is not in fully controlled by an enterprise.

Although Cloud service provider promise to provide good level for security but despite of their promise, enterprise don't prefer to go to cloud because security is the first priority for them sometime.

## Frequent Terms used in Cloud world
### Cloud Computing:
On-demand availability of the required computing resources like Hardwares, Softwares (e.g. Operating Systems, Frameworks, Tools), Servers, Networking, Storage, Databases, Applications, Analytics, Intelligence etc.) over the internet within no time is called Cloud Computing.

In Cloud Computing, we only pay for the cloud services which we use. Also we can reduce the operating cost by running the infrastructure more efficiently (e.g. scale-up/scale-down the resources based on business need).
Cloud Service Providers:

The companies which provide all those cloud computing services are called cloud service providers. There are various cloud service provider available in the market like Microsoft Cloud (Azure), Amazon Web Services (AWS), Google Cloud Platform (GCP), Oracle Cloud World Infrastructure (OCI), IBM Cloud etc. You can choose any of the cloud service provider based on there offer price, availability in your region and your business requirement.

### Cloud Type:
There are various type of clouds and your can choose/setup based on your business need.

### Public Cloud:
In public cloud, all the services are offered over public internet and available to anyone who want to buy it.

### Private Cloud:
In private cloud, all the services are offered over the Internet or over a private internal network to only selected users or group of users. General public users can access it.

### Hybrid Cloud:
Combination of both public and private cloud model is called Hybrid cloud. In hybrid cloud model, public and private clouds are bounded together by technology in such a way that data and applications can be shared between them. A hybrid cloud gives businesses greater flexibility to scale-up/scale-down the resources and offers more deployment options.

### Multi Cloud:
Sometimes some enterprises take some cloud services from one cloud service provider and some cloud services from other cloud service provider depending on the availability in their region. So this kind of model is called as Multi cloud.

### Cloud Bursting:
Cloud bursting is a configuration that’s set up between a private and a public cloud in such a way that if private cloud's resources are utilized by 100 percent of their capacity, then overflow traffic will be directed to the public cloud.

### Virtualization:
Virtualization is the process of creating a computing environment (e.g. including hardware, operating system, storage devices, networking equipments etc.) virtually rather than a creating it physically.

### Infrastructure as a service (IaaS):
Providing Infrastructure (e.g. including hardwares, servers, networking equipments and software) as a service over the internet in a virtualized form is called as IaaS. Sometimes it is also called as Hardware as a Service (HaaS).

### Platform as a service(PaaS):
Providing a computing platform (e.g. Operating system, Frameworks, Analytics or Business intelligence and other services which you can subscribe and use immediately to develop your application) as a service over the Internet is called as PaaS. Using PaaS you can cut your coding time, increase development capabilities without adding more staff, efficiently manage your application life cycle and son. Azure offers PaaS feature.

### Software as a service (SaaS):
Providing an application (e.g. Office 365, Gmail,  Web App, API App, Microservices etc.) over the Internet is called as SaaS. In this case user don't need to purchase, install and run the application at their machine.

SaaS application is also know an hosted application. Earlier SaaS was referred as Application Server Providers (ASPs).

### Infrastructure as code (IaC):
Infrastructure as a code means create your required infrastructure through the code written using PowerShell or Azure CLI or Terraform. This code can be stored and versioned in version control systems, where people can review and re-utilize. The purpose of infrastructure as code is to enable developers or operations teams to automatically manage, monitor and provision resources, rather than manually configure discrete hardware devices and operating systems. It very helpful to reduce the risk of human error especially for complex and large environments.

### Serverless Computing:
It is quite confusing word and it doesn't mean that server is not needed at all to run the application. Of course servers are needed. The purpose of this naming convention is to remove the burden of provisioning, scaling and managing the infrastructure from developer so that he can much focus on writing business logic and less focus on managing infrastructure. Serverless computing help team to increase their productivity and launch product in the market quickly. It also allows organizations to better optimize resources and stay focused on innovation.

### Elastic Computing:
Elastic computing is the ability to quickly scale/de-scale the computer processing, memory, storage and other resources dynamically based on demand without worrying about capacity planning and engineering for peak usage.

It is typically controlled by system monitoring tools which has the ability to match the amount of resources allocated with the amount of resources actually needed without disrupting operations.

Using elastic computing, a company avoids paying for unused capacity or idle resources and doesn’t have to worry about investing in the purchase or maintenance of additional resources and equipment.

Elastic computing is totally automated process and doesn’t need human administration around the clock. It also offers continuous availability of services by avoiding unnecessary slowdowns or service interruptions.

### Artificial Intelligence (AI):
Artificial intelligence is the capability of a computer system to imitate (copy) the human intelligence. A computer system uses Maths and Logic to simulates the reasoning that humans use to learn from new information and make decisions. There are various AI services/models designed and available for developers and data scientists. Using those AI services/models, you can build and deploy your own AI solutions.

### Business Intelligence (BI):
BI is the procedural and technical infrastructure that used to collect, store and analyzes the data produced by sources. BI parses this data and produce easy-to-digest reports, information and trends that help people to make better decisions.

There are various tools available in the market which help a lot in BI process. e.g. Spreadsheet, Power BI reporting tool, Data mining tools, Online analytical processing (OLAP) etc.

### Machine Learning (ML):
The process of using mathematical models to predict outcomes versus relying on a set of instructions. This is made possible by identifying patterns within data, building an analytical model, and using it to make predictions and decisions. Machine learning bears similarity to how humans learn, in that increased experience can increase accuracy.

### Machine Learning Algorithms (MLA):
Machine learning algorithms are pieces of code that help people explore, analyze, and find meaning in complex data sets. Each algorithm is a finite set of unambiguous step-by-step instructions that a machine can follow to achieve a certain goal. In a machine learning model, the goal is to establish or discover patterns that people can use to make predictions or identifying anomalies or categorize information.

Machine learning algorithms use parameters that are based on training data. Training data is a subset of data that represents the larger set. As the training data expands to represent the world more realistically, the algorithm calculates more accurate results.

Machine learning algorithms are commonly divided into those used for supervised learning and those used for unsupervised learning.

The most commonly used algorithms use regression and classification to predict target categories, find unusual data points, predict values, and discover similarities.

### Database Sharding:
Database sharding is a type of horizontal partitioning that splits large databases into smaller databases, which are faster and easier to manage. A shard is an individual partition that exists on separate database server instance to spread load.

As both the database size and number of transactions keep increasing based on the traffic on your application which cause delay in response time during query execution at database. To solve this problem data shard is needed.

### Cloud Storage:
Cloud storage is a service that lets you store data by transferring it over the Internet or another network to an offsite storage system maintained by a third party. Cloud storage is cost-effective, scalable and accessible from any location compare to on-premise storage. There are three type of cloud storage like Private Cloud Storage, Public Cloud Storage and Hybrid Cloud Storage.

### Computer Grids:
Computer grid is a group of networked computers that work together as a virtual supercomputer to perform large tasks such as analyzing huge sets of data or weather modeling.

Through cloud computing, you can assemble and use vast computer grids for specific time periods and purposes, paying only for your usage and saving the time and expense of purchasing and deploying the necessary resources yourself.

Unlike with parallel computing, grid computing projects typically have no time dependency associated with them. They use computers that are part of the grid only when idle, and operators can perform tasks unrelated to the grid at any time.

### DevOps:
DevOps is the union of people, process and technology to enable continuous delivery of value to customers. The practice of DevOps brings development team, operations team, quality engineering team and security team together to coordinate and collaborate to produce better and more reliable products quickly.

By adopting a DevOps culture along with DevOps practices and tools, teams gain the ability to better respond to customer needs, increase confidence in the applications they build, and achieve business goals faster.

DevOps culture enable strong collaboration between teams, clear visibility towards the goals and align everyone to achieve the goals.

DevOps culture also enable the scope of responsibility and accountability. For example developers become responsible and accountable not only for development phase but also for operation phase.

DevOps culture does not impact the agile process. Teams be remain agile by releasing the software in short cycles. Shorter release cycles make planning and risk management easier since progress is incremental.

DevOps culture establish a growth mindset in the individuals. We may fail fast and incorporate the learnings to improve the processes continuously to increase the customer satisfaction. DevOps is a journey, so there is always room to grow.

To opt DevOps culture, definitely you have to follow the DevOps practices through the application life cycle. Important DevOps practices are:

#### 1. Continuous integration and continuous delivery (CI/CD):
Continuous Integration is the process of merge changes back to the main branch as often as possible. The integration may occur several times a day, verified by automated test cases and a build sequence. It help to identify the bugs early and reduce the bug count on test/production environments.

Continuous delivery is the process of deploying all the changes (including code changes, configuration changes etc.) to test/production environment. Continuous Delivery help deployment easier and faster.

#### 2. Configuration management:
Configuration management is the process of managing the state of resources in a system including servers, virtual machines, and databases. Using configuration management tools, teams can roll out changes in a controlled, systematic way, reducing the risks of modifying system configuration. Teams use configuration management tools to track system state and help avoid configuration drift, which is how a system resource’s configuration deviates over time from the desired state defined for it.

#### 3. Continuous monitoring:
Continuous monitoring is the process of having real-time visibility into the performance and health of the entire application stack, from the underlying infrastructure running the application to higher-level software components. This visibility consists of the collection of telemetry and metadata as well as the setting of alerts for predefined conditions which warrant attention from an operator. Telemetry comprises event data and logs collected from various parts of the system, which are stored where they can be analyzed and queried.

High-performing DevOps teams ensure they set actionable, meaningful alerts and collect rich telemetry so they can draw insights from vast amounts of data. These insights help the team mitigate issues in real time and see how to improve the application in future development cycles.

#### 4. Version Control:
Version control is the practice of managing code in version control system. It track the revisions and change history to make code easy to review and recover. It also allow multiple developers to collaborate in authoring code and merge code changes that happen in the same files, handle conflicts, and roll back changes to earlier states.

#### 5. Agile software development:
Agile is a software development approach that emphasizes team collaboration, customer and user feedback, and high adaptability to change through short release cycles. Teams that practice Agile provide continual changes and improvements to customers, collect their feedback, then learn and adjust based on customer needs. Agile is substantially different from other more traditional frameworks such as waterfall, which includes long release cycles defined by sequential phases. Kanban and Scrum are two popular frameworks associated with Agile.

#### 5. Infrastructure as code:
Infrastructure as a code means create your required infrastructure through the code written using PowerShell or Azure CLI or Terraform. This code can be stored and versioned in version control systems, where people can review and re-utilize. The purpose of infrastructure as code is to enable developers or operations teams to automatically manage, monitor and provision resources, rather than manually configure discrete hardware devices and operating systems. It very helpful to reduce the risk of human error especially for complex and large environments.

## Difference between On-Premises and Private Cloud

### On-premise environment
1. In on-premise environment, all the required infrastructures are setup within the premises of the company and in fully control of the company.
2. It is costly because you have to setup and manage each and everything on your own.
3. It is not easy to scale as n when basis.
4. Internet connectivity is not needed all the time because it not exposed to internet.
5. Updating the softwares and disaster recovery is difficult.

### Private cloud
1. In private cloud all the required infrastructures are set up outside of the company premises and managed by third party cloud service providers.
2. Private cloud is a kind of isolated/single-tenant environment and can be used by the same tenant only for which it is provisioned.
3. It is cost effective than on-premise environment because everything is setup and managed by cloud service provider and you have to pay only for usage.
4. It is easy to scale as n when basis.
5. Internet connectivity is needed all the time because it is exposed to internet.
6. Easy to update the softwares and recover from any disaster. 
    
