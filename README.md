# Azure Administration Practices

## Project Description
In preparation for the Azure Administrator Certification exam (AZ-104), I've been actively utilizing the Azure Cloud Platform to deepen my understanding of key administration tasks. Here are the tasks I have completed so far and will update and add more in the future once I finish more practices.

## Key Accomplishments
- **Virtual Machine Deployment**:
  - Deployed Windows Server 2022 and Ubuntu Linux Server VMs in Azure.
  - Connected to Azure VMs from a local host using RDP and SSH (via CLI and PuTTY).
  
- **Web Server Configuration**:
  - Installed and configured IIS on a Windows Server VM to host a web server.
  - Set up nginx on a Linux Server VM for web server deployment.

- **Disk Management**:
  - Configured and verified OS-level and temporary disks on Windows Server VMs.
  - Added an additional data disk and created a snapshot of it for future use.
  - Attached the disk snapshot to another VM, successfully mounting it as a new disk.
  
- **Encryption and Key Management**:
  - Explored Azure disk encryption options, including Platform-Managed Keys (PMK) and Customer-Managed Keys (CMK).
  - Deployed Azure Key Vault and assigned access control roles to define and manage custom encryption keys.
  - Configured a Disk Encryption Set (DES) and successfully transitioned disk encryption from PMK to CMK.
  - Practiced full disk encryption for both OS and data disks, verifying successful encryption using CMKs
  - Learned to manage networkAcls.bypass settings via Azure CLI to allow trusted Azure services to access Key Vault, ensuring successful disk encryption operations.

## Future Updates
- I will update the list once I finish some more practices.

## Resources
- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)
