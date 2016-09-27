# kaist-cs492b
This repo is Kaist university lecture cs492b training hands on document.  
Short URL : https://aka.ms/cs492b

## Cloud and Microsoft Azure
Overview presentation of Cloud and Microsoft Azure  
Microsoft Azure : https://azure.microsoft.com

## Azure Portal
The Microsoft Azure portal is a central place where you can provision and manage your Azure resources.  
Azure new portal : https://portal.azure.com/  
Azure classic portal : https://manage.windowsazure.com  
Microsoft Azure portal overview  
https://azure.microsoft.com/en-us/documentation/articles/azure-portal-overview/

## Azure VM sizes
This article describes the available sizes and options for the Azure virtual machines you can use to run your Windows apps and workloads.  
Sizes for virtual machines in Azure  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-sizes/

## Azure pricing & usage management
Estimate your expected monthly bill using our Pricing Calculator, and track your actual account usage and bill at any time using the billing portal.  
https://azure.microsoft.com/en-us/pricing/

## Azure Linux VM creation
This link shows you how to use the Azure portal to create a Linux Virtual Machine quickly. The only requirements are an Azure account and SSH public and private key files.  

Create a Linux VM on Azure using the Portal  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-quick-create-portal/  

Appendix :  
Create a virtual machine running Windows in the Azure classic portal  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-classic-tutorial/  
How to set up endpoints on a classic Windows virtual machine in Azure  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-classic-setup-endpoints/

## SSH key creation
With an SSH keypair you can create Virtual Machines on Azure that default to using SSH keys for authentication, eliminating the need for passwords to log in.  
Create SSH keys on Linux and Mac for Linux VMs in Azure  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-mac-create-ssh-keys/

## Reset SSH access
Manage users, SSH, and check or repair disks on Azure Linux VMs using the VMAccess Extension  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-using-vmaccess-extension/

## Python script execution
In this class VM - Ubuntu environment, Python 2.7 and Python 3.5 is already on it.  
```
whereis python
```

To copy Python files on SSH connection, I suggest SCP command  
https://en.wikipedia.org/wiki/Secure_copy  

Or, to upload Python scripts or any files, you can choice to install tiny ftpd, vsftpd  
```
sudo apt-get install vsftpd
```
If you need custom configuration for vsftpd, set up vsftpd.conf and ftpuser file located in /etc directory(depends on Linux dist).  
http://www.krizna.com/ubuntu/setup-ftp-server-on-ubuntu-14-04-vsftpd/

By default, all VM inbound port is blocked, except SSH(port 22). To open another VM inbound port(ex. HTTP 80 port), process in Azure Portal "Network Security Group".  
Opening ports to a VM in Azure using the Azure Portal  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-nsg-quickstart-portal/  
Opening ports to a VM in Azure using the Azure Classic Portal  
https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-classic-setup-endpoints/  

## HDInsight or Hadoop VM
Azure HDInsight uses the Hortonworks Data Platform (HDP) Hadoop distribution. HDInsight deploys and provisions managed Apache Hadoop clusters in the cloud, providing a software framework designed to process, analyze, and report on big data with high reliability and availability.  
What is Hadoop in the cloud? An introduction to the Hadoop ecosystem in HDInsight  
https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-introduction/  

## Azure Batch
Azure Batch enables you to run large-scale parallel and high-performance computing (HPC) applications efficiently in the cloud.  
https://azure.microsoft.com/en-us/documentation/articles/batch-technical-overview/  

It's a platform service that schedules compute-intensive work to run on a managed collection of virtual machines, and can automatically scale compute resources to meet the needs of your jobs.  

Get started with the Azure Batch Python client  
https://azure.microsoft.com/en-us/documentation/articles/batch-python-tutorial/

## Technical community
Microsoft Forum category with "Microsoft Azure Platform"  
https://social.msdn.microsoft.com/Forums  

stackoverflow tag with "Azure"  
http://stackoverflow.com/questions/tagged/azure  