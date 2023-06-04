# Directory Services
##### Graded Quiz • 50 min • 10 total points 
-------- 

### 1. Directory services store information in a hierarchical structure. Which statements about Organizational Units (OUs) of a directory service hierarchy are true? (Choose all that apply)

- [ ] Parent OUs inherit characteristics of their sub-members.
- [x] Sub-member OUs inherit the characteristics of their parent OU.
- [x] Changes can be made to one sub-OU without affecting other sub-OUs within the same parent.
- [x] Specific files within an OU, or container, are called "objects."

### 2. Which directory service software would be used exclusively on a Windows network?

- [ ] OpenLDAP
- [ ] DSP
- [x] Active Directory
- [ ] DISP

### 3. Instead of assigning access for each user account individually, ________ is a more efficient and easier-to-manage approach.

- [ ] active directory
- [ ] LDAP
- [x] centralized management
- [ ] centralized authentication

### 4. In LDAP, what does dn stand for at the beginning of the entry?

- [ ] Distinguished number
- [ ] Distinct name
- [x] Distinguished name
- [ ] Domain name

### 5. Which of these is a common protocol and a type of SASL authentication?

- [x] Kerberos
- [ ] SSL
- [ ] SSH
- [ ] SFTP

### 6. In active directory, what is the top most level in the hierarchy?

- [x] Forest
- [ ] ADAC
- [ ] Domain
- [ ] Top

### 7. Which of these statements are true about Domain Controllers (DCs)? (Choose all that apply)

- [x] Delegation can be used in Active Directory.
- [x] The default Organizational Unit (OU), called Domain Controllers, contains all Domain Controllers in the domain.
- [ ] Changes that are safe to be made by multiple Domain Controllers at once are tasked by granting them Flexible Single-Master Operations.
- [ ] Always use the Domain Admin or Enterprise Admin for day-to-day use.

### 8. To authenticate user accounts on a computer against AD, what must be done to the computer first?

- [x] Join it to the domain
- [ ] Configure the firewall
- [ ] Enable the administrator account
- [ ] Configure remote logging

### 9. A particular computer on your network is a member of several GPOs. GPO-A has precedence set to 1. GPO-B has precedence set to 2, and GPO-C has precedence set to 3. According to the given levels of precedence, what will be the resultant set of policy (RSOP) for this machine?

- [x] GPO-A will take precedence and overwrite any conflicting settings.
- [ ] GPO-B will take precedence and overwrite any conflicting settings.
- [ ] GPO-C will take precedence and overwrite any conflicting settings.
- [ ] The computer will default to local policy due to the confusion.

### 10. You'd like to change the minimum password length policy in the Default Domain Policy group policy preference (GPO). What's the best way to go about doing this?

- [x] Open the Group Policy Management Console by running gpmc.msc from the CLI
- [ ] Manually edit config files in SYSVOL
- [ ] Open ADAC and edit policy settings there
- [ ] Edit the Windows Registry to change group policy settings

-------------
(Another Set)

### 1. Directory services store information in a hierarchical structure. Which statements about Organizational Units (OUs) of a directory service hierarchy are true? (Choose all that apply)

- [x] Specific files within an OU, or container, are called "objects".
- [x] Sub-member OUs inherit the characteristics of their parent OU.
- [ ] Parent OUs inherit characteristics of their sub-members.
- [x] Changes can be made to one sub-OU without affecting other sub-OUs within the same parent.

### 2. Which of the following are examples of Lightweight Directory Access Protocol (LDAP)-based directory server software? (Choose all that apply)

- [ ] ADUC
- [ ] RDP
- [x] Microsoft's Active Directory
- [x] OpenLDAP

### 3. Which of these are advantages of centralized management using directory services? (Choose all that apply)   

- [x] Configuration management is centralized.
- [ ] Configuration can take place on each device.
- [x] Role-Based Access Control (RBAC) can organize user groups centrally.
- [x] Access and authorization are managed in one place.

### 4. A Lightweight Directory Access Protocol (LDAP) entry reads as follows: dn: CN=John Smith ,OU=Sysadmin,DC=jsmith,DC=com. \n. What is the organizational unit of this entry?

- [ ] John Smith 
- [x] Sysadmin
- [ ] jsmith
- [ ] CN=John Smith ,OU=Sysadmin,DC=jsmith,DC=com

### 5. Which of the following are ways to authenticate to an LDAP server? (Choose all that apply)

- [x] Anonymous bind
- [x] Simple bind
- [ ] PGP
- [x] SASL

### 6. In Active Directory, which of the following can be functions of the Domain? (Choose all that apply)

- [ ] A DNS server
- [ ] A container
- [x] A server that holds a replica of the Active Directory database
- [x] A Kerberos authentication server

### 7. If a system administrator needs to give access to a resource to everyone in a domain, what group in Active Directory can they use?

- [ ] Resource Users
- [ ] All Users
- [ ] Enterprise Admins
- [x] Domain Users

### 8. Which of these statements are true about managing through Active Directory? (Choose all that apply)

- [ ] Distribution groups can be used to assign permission to resources.
- [ ] ADAC uses PowerShell.
- [x] Domain Local, Global, and Universal are examples of group scopes.
- [x] The default group's Domain Users and Domain Admins are security groups.

### 9. What is the difference between a group policy and a group policy preference?

- [ ] A preference is editable only by admins, but anyone can edit a policy.
- [ ] A policy is editable only by admins, but anyone can edit a group policy preference.
- [ ] Preferences are reapplied every 90 minutes, and policies are more of a settings template.
- [x] Policies are reapplied every 90 minutes, and preferences are a settings template that the user can change on the computer.

### 10. A client discovers the address of a domain controller by making a DNS query for which record?

- [ ] A record
- [ ] TXT record
- [ ] AAAA record
- [x] SRV record

-----------------
(Another Set)

### 1. How are things organized in a directory server?

- [ ] By a series of nested groups
- [ ] By a relational database structure
- [ ] By a flat text file
- [x] By a hierarchical model of objects and containers

### 2. Which directory service software would be used exclusively on a Windows network?

- [ ] DISP
- [x] Active Directory
- [ ] DSP
- [ ] OpenLDAP

### 3. What roles does a directory server play in centralized management? (Choose all that apply)

- [x] Centralized authentication
- [x] Confidentiality
- [ ] Accounting
- [x] Authorization

### 4. A Lightweight Directory Access Protocol (LDAP) entry reads as follows: dn: CN=John Smith ,OU=Sysadmin,DC=jsmith,DC=com. \n. What is the common name of this entry?

- [ ] jsmith
- [x] John Smith
- [ ] Sysadmin
- [ ] CN=John Smith ,OU=Sysadmin,DC=jsmith,DC=com

### 5. Which of these is a common protocol and a type of SASL authentication?

- [x] Kerberos
- [ ] SFTP
- [ ] SSL
- [ ] SSH

### 6. In Active Directory, which of the following can be functions of the Domain? (Choose all that apply)

- [ ] A container
- [x] A DNS server
- [x] A Kerberos authentication server
- [x] A server that holds a replica of the Active Directory database

### 7. If a system administrator needs to give access to a resource to everyone in a domain, what group in Active Directory can they use?

- [ ] Resource Users
- [ ] Enterprise Admins
- [ ] All Users
- [x] Domain Users

### 8. Which of these statements are true about managing through Active Directory? (Choose all that apply)

- [x] Domain Local, Global, and Universal are examples of group scopes.
- [x] The default group's Domain Users and Domain Admins are security groups.
- [ ] ADAC uses PowerShell.
- [ ] Distribution groups can be used to assign permission to resources.

### 9. What is the difference between a group policy and a group policy preference?

- [ ] Preferences are reapplied every 90 minutes, and policies are more of a settings template.
- [ ] A preference is editable only by admins, but anyone can edit a policy.
- [x] Policies are reapplied every 90 minutes, and preferences are a settings template that the user can change on the computer.
- [ ] A policy is editable only by admins, but anyone can edit a group policy preference.

### 10. You'd like to change the minimum password length policy in the Default Domain Policy group policy preference (GPO). What's the best way to go about doing this?

- [x] Open the Group Policy Management Console by running gpmc.msc from the CLI
- [ ] Open ADAC and edit policy settings there
- [ ] Edit the Windows Registry to change group policy settings
- [ ] Manually edit config files in SYSVOL


---

> [System Administration and IT Infrastructure Services](https://www.coursera.org/learn/system-administration-it-infrastructure-services/) {Week-4} 

