# IMPLEMENTATION OF ROLE BASED ACCESS CONTROL (RBAC) IN ACTIVE DIRECTORY
This project shows implementation of RBAC in active directory using groups , users and shared file folder. 

RBAC is an act of regulating access to a computer or network resources based on the roles of individual users within an organization.  
Active directory is a centralized directory service used by adminsistrators to manage users , computers and other resources on a network.
## Lab Environment ##
For this project, I created a local active directory domain and joined a windows client computer to the domain.
The local Active Directory domain used in this lab is aybanty.local and my client computer is joined to the domain.  
**here is a picture of my local domain name on active directory which is aybanty.local**
![alt text](image.png) 
 **window joined to the local domain**    
 ![alt text](image-1.png)  
  ## Rbac implementation ##

  In active directory, i created a list of users to be divided into groups where the groups are allowed a shared access  to a file folder or more  whereby only members of the same group can access the same folder content and a different group cannot access the same folder unless given acccess e.g A folder assigned to group A cant be accessed by group B.
  ## Project sections ##
 01 login and folder creation :This section covers the creation of users, groups, folders, and setting of the access permission.  

 02  Accessing shared folder  : This shows only authorized user or group can access a resource.