# gcp-interview-questions
## By default, how long PubSub Subscription will retain unacknowledged messages.
	> 14 days
	> 31 days
	> 7 days    -- correct 
	> None of it

## There is a requirement to do a DML experiment on a table, which modify a large number of rows, but analysts are not sure about the results. What options will you suggest to test this experiment without corrupting the data (Choose all correct answers).

	> Take a snapshot of the that table and create a new table from the snapshot and run DML statements on it.
	> Use "copy table" operation to create a replica table and run DML statements on it.
	> Take a clone of that table and run DML statements on it.
  
  	all are correct

## How many days, BigQuery retains historical table data by default?
	> 7 days    -- correct
	> 14 days
	> 21 days
	> 28 days


## Is it possible to implement an object life cycle rule only on a folder inside a gcs bucket?
	> false

## You can stop publicly sharing an object in cloud storage bucket by implementing which below actions?(Choose all correct answers)
	> By removing project owners from Access Policy
	> By removing project viewers from Access Policy
	> By moving the object to archive storage
	> By removing allUsers identifier from Access Policy  -- correct


## Cloud Storage offers which storage classes(Choose all correct answers):
	Coldline
	Nearline
	Archive
	Standard
        All are correct
## Google Cloud Storage buckets must have a globally unique names.
	true

## John is granted the Compute Instance Admin role on a folder, Can John be Compute Insatance Admin in all projects of that folder?
	true

## A GCP folder can contain:
	Only Projects
	Only Folders
	Projects and Folders

## Which GCP Compute VM instance type is more expensive?
	Preemptible VM instance
	Sole-tenanct VM instance -- correct
	Multi-tenant VM instance

## Is it possible to create subnets in different regions in single GCP VPC?
	true

## Is it possible to deploy a dataflow pipeline inside a VPC?
	true

## Cloud SQL provides a cloud-based alternative to which databases(Select all appropriate answers):
	MySQL   -- correct
	PostgreSQL  -- correct 
	MS SQL Server --correct
	Oracle

## A developer in your team needs to run a huge batch processing job, which is fault-tolerant and can withstand instance failures. Which type of instance is suitable to reduce the cost of the whole task.
	multi-tenant VM instance
	sole-tenant VM instance
	Preemptible VM instance  -- correct

## We can add or remove network interfaces from an existing VM.
	false

## What is the default priority of a GCP VPC Firewall rule?
	0
	65535
	1000  -- correct
	1


## A Compute Instance can have multiple network interfaces in Same VPC.
	false

## We can add more disk space to Composer environment as and when needed, after creation.
	false

## We can create a Cloud Composer environment with less than 3 nodes.
	false

## How do you remove a Airflow DAG from Cloud Composer Environment?
	By Deleting the DAG from composer environemt's bucket.  -- correct
	By Deleting DAG from Composer environment's web console.
	By Deleting DAG from Composer's GKE worker pod.

## Where does BigQuery Stores cashed query results?
	Temporary Table  -- correct
	Memory
	Clustered Table
	Cloud Storage Bucket

## Object Versioning cannot be enabled on a GCS bucket that currently has a retention policy.
	true


## How many versions are allowed for an Object created in GCS Cloud Storage bucket.
	Unlimited  -- correct
	2
	4
	6

## Which following criteria must be satisfied for an instance to have outgoing internet access(Select all appropriate answers):
	The network must have a valid default internet gateway route or custom route whose destination IP range is 0.0.0.0/0.
	Firewall rules must allow egress traffic from the instance.
	The instance must have an external IP address or The instance must be able to use Cloud NAT or an instance-based proxy that is the target for a static 0.0.0.0/0 route.

	all are correct

## John is granted the Compute Instance Admin role on a folder, Can John Modify all the compute instances in all the projects under that folder?
	John can manage all the compute instances in all the projects under that folder. -- correct
	John can manage all the compute instances only under projects, whch are created after his role assignment, under that folder.
	John can only manage compute instances, which are creating after his role assignment, in all the projects under that folder.


## GCP Folder functionality is only available to Google Workspace and Cloud Identity customers that have an organization resource.
	true

## allAuthenticatedUsers IAM identifier represents:
	All service accounts and all users on the internet who have authenticated with a Google Account(including personal Gmail accounts).  -- correct
	Only accounts that are conected to a Google Workspace account or Cloud Identity domain.
	Only accounts that are using personal Gmail accounts.
	Only accounts that are connected to a Cloud Identity domain.

## Which below statement correctly describes, BigQuery Active storage:
	Any table or table partition that has been modified in the last 90 days.  -- correct
	Any table or table partition that has been modified in the last 7 days.
	Any table or table partition that has been modified in the last 30 days.
	All the data that is stored in BigQuery.

## BigQuery Long-term storage includes any table or table partition that has not been modified for how many consecutive days.
	90 days  -- correct
	60 days
	30 days
	45 days

## BigQuery uses a columnar data structure
	true

