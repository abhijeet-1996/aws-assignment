# EC2 (Elastic Compute Cloud)

* EC2 is like laptop/desktop.
* We can create a remote machine i.e. EC2 as per our requirement like OS, Storage, RAM, Processor, etc
* EC2 is remote machine hence we can modify its specification as per our requirement.
* When we stop an instance of EC2, then Amazon will charge only for HDD/SSD
* To delete EC2 we have to do terminate instance.
* EC2 is IAAS (Infrastructure as A Service)

# Models of cloud services :
1) SaaS	(Software as a Srvice)
2) PaaS	(Platform as a Service)
3) IaaS (Infrastructure as a Service)
* **SaaS**

Different softwares are provided directly, no need to download and install at client side. User is not responsible for hardware or software update. Can be used for short term projects that require quick and affordable collaboration. Examples : Tableau, Splunk, Storm,etc.

* **PaaS**

Instead of providing software, it provides platform for software creation. Developer has to focus only on software development without the worrying about O.S., Storage, Saoftware updates, etc. Examples : Hosted db RDS., AWS Elastic Beanstalk,etc.

* **IaaS**

Raw computing resources. Provides access to resources like - servers,storage and netwroking. Examples : VM: Ec-2, Volume,etc.

* **Firewall**

Monitors all incoming and outgoung traffic and accepts, rejests or drops the traffic based on predefined security rules. Designed to prevent unautorized access to or from a private network. 

# Security Group
* in security group there is concept of _**Firewall**_
* Firewall controls the data traffic.
* In security group we have inbound and outbound rules.
 ## _**Inbound rule**_
* In inbound rule we control incoming data traffic.
 ## _**Outbound rule**_
* In outbound rule we control outgoing data traffic.

# S3 (Storage Secured Service)

We can store any type of data in form of object. Unlimited storage space available. Bucket needs to be created where we can store our data. S3 does not require region separation. Bucket name has to be unique across AWS. Bucket is like a folder, we can create folders inside it. We can upload or download files to or from these folders, but we cannot create a file here. Guarantee of backup from AWS. Can connect with EC2 also. We can host a website here.
