# Azure_intro_assessment

## Part 1: Azure dashboard screenshot
<img width="1297" alt="Azure Dashboard Eugene Hsiung" src="https://github.com/EugeneHsiung/azure_intro_assessment/assets/141866888/75052b6e-42a3-41ec-af13-bfb5a00e6228">


## Part 2: Azure Exploration

#### Storage Services: 

1. **Azure Backup**: This service provides a simple, secure, and cost-effective backup method to back up or recover lost information in the Microsoft Azure cloud. It can restore and backup files, folders, SQL databases, etc. The backup protects from ransomware attacks through various preventive measures and tools. This backup also has three types of replication (Locally redundant storage, Geo-redundant storage, Zone- redundant storage) to keep the storage and data available. Python can leverage Azure backups by installing the SDK kit and having Python manage the backup storages by adding or deleting the storages. Python can then also be used to manage the backup policy to edit the duration of the information.
   
2. **Microsoft Azure confidential ledger**: This service is highly secure and manages sensitive data records. It runs on hardware-backed secure enclaves. This offers data integrity, tamper-proofing, and immutability, ensuring records are not modified. On the ledger, one can store business transactions, trusted assets, administration control settings, and operational and security events. Similar to the Azure backup, Python could be used to manage the data, retrieve the data, and verify the integrity of the data. The Python code could also be used to add the functions of who can access the data or analyze the ledger data. 

#### Compute Services:

1. **Azure CycleCloud** This service manages the Big Data workloads and high-performance computing (HPCs). This allows the user to create, deploy, and optimize clusters for running tasks on the Microsoft Azure cloud. Users are allowed to control the amount and types of virtual machines (VMs). Depending on the workload requirements, users are able to add or remove VMs from clusters. Python can be used to interact with Azure CycleCloud through the SDK by creating, scaling, starting, or stopping clusters in Azure CycleCloud. This service can also be used for managing software updates. 
   
2. **Azure Batch** This service is used for the execution and management of HPCs. Users are able to define batches that contain multiple tasks which can be used on a VM. This allows auto-scaling as the Azure batch will scale based on the number of tasks created. Data can also be moved from different storage accounts. Python can utilize this service by creating and monitoring batch jobs on Azure Batch. Python can be used to monitor task status and the outputs. 

#### Database Services: 

1. **Azure Database for MySQL** This service hosts MySQL in the cloud which has high security, scalability, and availability. Azure Database for MySQL provides high availability by replicating the data across various zones and has built-in patching, updates, security, and backup. This is useful with large-scale applications. Python can be used and interacted with Azure Database for MySQL through the execution of SQL tasks. Data manipulation can also be done by creating, reading, updating, or deleting the data. 
   
2. **Azure Database for MariaDB** This service is designed to hold MariaDB databases in the cloud and offers high security and availability. Similar to Azure Database for MySQL, Azure Database for MariaDB has built-in services that include patching, security, and backups. This service also allows the scaling of the databases. Python can interact with Azure Database for MariaDB by also executing tasks and data manipulation similar to how one would use python with Azure Database for MySQL. 
