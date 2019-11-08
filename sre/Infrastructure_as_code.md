## Dynamic infrastructure platform
------------------------------------------
system that provides computing resources like servers, storage, networks programmatically.  like aws , gcp
Iaas (infrastructure as service )

<span style="color:green">**characteristic**</span>
* programmable
* on-demand (element can be added or removed)
* self-service (provisioning)
  
<span style="color:green">**core resources provided by Iass**</span>
* compute resources
* storage
* Network Resources
  
<span style="color:green">**Type of storage**</span>
* block storage:- \
  volume mounted on servers as if they are local disk \
  ex:- AWS EBS, OpenStack Cinder,GCE Persistance disk
* object storage:- \
  storage where files can be accessible from different part of infrastructure, even by internet publicly. \
  ex: AWS S3, Google cloud storage
* Networked filesystems \
  file sharing network protocols like NFS , SMB/CIFS are used share storage more directly over network. \
  This filesystems are used mostly for streaming data, distributed file systems. \
  Used for data availability across multiple nodes \
  ex:- Gluster file system, HDFS (Hadoop Distributed File System) , Ceph

<span style="color:green">**Network Resources**</span>
* Dynamic infrastructure need to manage connectivity between own elements and external elements. 
* Things like Network routing, load balancing, firewall , inbound and outbound rules are the basic requirement for any provider. 
  

<span style="color:green">**cloud service models**</span>
* Software as a service (SaaS) :- email
* Platform as a service (Paas) :- manages DB from AWS
* Infrastructure as a service (Iaas) :- AWS, GCP
