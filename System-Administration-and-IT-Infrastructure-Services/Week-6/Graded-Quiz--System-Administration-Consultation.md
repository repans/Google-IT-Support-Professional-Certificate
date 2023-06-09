# System Administration Consultation

### 1. **Learning Goals:**

1. Use the systems administration concepts you learned in the course to provide technical improvements to current processes.
2. Implement solutions based on an organization’s restrictions, like financial resources, number of users, etc.

**Overview:** You’ll take what you learned in the System Administration and IT Infrastructure Services course and apply that knowledge to real-world situations.

**Assignment:** For this writing project, you’ll be presented with three scenarios for different companies. You’ll be doing the systems administration for each company’s IT infrastructure. For each scenario, present improvements to processes based on the company’s needs and current restrictions. There’s no right or wrong answer to your consultation, but your responses should explain the problem, the improvement, and the rationale behind them. Please write a 200-400 word process review for each company presented to you.


### Scenario 1: 

You’re doing systems administration work for Network Funtime Company. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.

**Software Company:**

Network Funtime Company is a small company that builds open-source software. The company is made up software engineers, a few designers, one person in Human Resources (HR), and a small sales team. Altogether, there are 100 employees. They recently hired you as a system administrator to come in and become their IT department.

When a new person is hired on, the HR person purchases a laptop for them to do their work. The HR representative is unfamiliar with what type of hardware is out there; if a new employee requests a laptop, the HR person will purchase the cheapest option for a laptop online. Because of this, almost everyone has a different laptop model. The company doesn’t have too much revenue to spend, so they don’t order laptops until someone gets hired at the company. This leads to a few days of wait time from when someone starts to when they can actually work on a laptop.

The company doesn’t label their computers with anything, so if a computer is missing or stolen, there’s no way to audit it. There’s no inventory system to keep track of what’s currently in the fleet.

Once a computer is purchased, the HR person hands it to the new employee to set up. Software engineers that use Linux have to find a USB drive and add their preferred distribution to the laptop. Anytime someone needs something from HR -- whether it’s office related or tech related -- they email the HR representative directly.

When a new employee gets a machine, they’re given logins to use cloud services. They get a personal orientation with HR to make sure they can login. This requires the HR person to block off a few hours for every new employee. If an employee forgets the login to their machine, they have no way to retrieve a password and they have to reimagine their machine. Employees don’t have a strict password requirement to set for their computers.

The company currently has many of their services in the cloud, such as email, word processors, spreadsheet applications, etc. They also use the application, Slack, for instant communication.


> Process Review for Network Funtime Company
> 
> Network Funtime Company, a small software company with 100 employees, has several areas in their IT infrastructure that can be improved. Here are five process improvements and their rationale:
> 
> 1. **Standardizing Laptop Models:**
> The current practice of purchasing different laptop models based on price leads to inconsistency and creates support challenges. Implementing a standard laptop model will streamline IT support and maintenance. Choosing a reliable and cost-effective model that meets the company's requirements will simplify hardware management and troubleshooting.
> 
> 2. **Implementing an Inventory System:**
> The company's lack of an inventory system makes it difficult to track and audit computers. Introducing an inventory system will allow for efficient asset management and enable quick identification of missing or stolen devices. Tagging each computer with a unique identifier will facilitate tracking and enhance security measures.
> 
> 3. **Centralized Provisioning and Configuration:**
> Instead of leaving new employees to set up their own machines, establish a centralized provisioning and configuration process. This ensures consistency and reduces the burden on HR and employees. IT can create standardized system images or utilize configuration management tools to automate software installations and configurations.
> 
> 4. **Self-Service Password Reset:**
> Implement a self-service password reset mechanism for employees to retrieve their forgotten passwords. This eliminates the need for reimaging machines and reduces the HR representative's involvement in password management. It improves productivity by enabling employees to regain access to their machines promptly.
> 
> 5. **Password Policy Enforcement:**
> Enforce a strict password policy across all machines to enhance security. This policy should include minimum complexity requirements, password expiration, and regular password change reminders. Implementing these measures will strengthen the company's overall security posture.
> 
> By implementing these process improvements, Network Funtime Company can enhance efficiency, standardization, and security in their IT infrastructure. Standardizing laptop models, implementing an inventory system, centralizing provisioning and configuration, introducing self-service password reset, and enforcing a password policy will streamline operations, improve support, and mitigate security risks. These changes can be implemented within the company's financial constraints while delivering significant benefits to their IT operations.


### Scenario 2:

You’re doing systems administration work for W.D. Widgets. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Please write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.

**Sales Company:**

W.D. Widgets is a small company that sells widgets. They’re mostly made up of salespeople who work with lots of clients. You’ve taken over as the sole IT person for this company of 80-100 people.

When HR tells you to provision a machine for a new employee, you order the hardware directly from a business vendor. You keep one or two machines in stock, in case of emergency. The users receive a username that you generate for them. You then give them an orientation on how to login when they start. You currently manage all of your machines using Windows Active Directory. The company uses only Windows computers. When a new computer is provisioned, you have to install lots of sales-specific applications manually onto every machine. This takes a few hours of your time for each machine. When someone has an IT-related request, they email you directly to help them.

Almost all software is kept in-house, meaning that you’re responsible for the email server, local machine software, and instant messenger. None of the company’s services are kept on the cloud.

Customer data is stored on a single file server. When a new salesperson starts, you also map this file server onto their local machine, so that they can access it like a directory. Whoever creates a folder on this server owns that folder and everything in it. There are no backups to this critical customer data. If a user deletes something, it may be lost for everyone.

The company generates a lot of revenue and is rapidly growing. They’re expecting to hire hundreds of new employees in the next year or so, and you may not be able to scale your operations at the pace you’re working.


> Process Review for W.D. Widgets
> 
> As the sole IT person for W.D. Widgets, there are several process improvements that can be made to address the company's IT infrastructure needs and limitations. Here are five recommended improvements and their rationale:
> 
> Implementing Automated Software Deployment:
> Manually installing sales-specific applications on each new machine is time-consuming and inefficient. Implementing an automated software deployment solution, such as a software deployment tool or a configuration management system, will significantly reduce the time and effort required to provision new machines. This will free up your time to focus on other critical IT tasks and allow for faster onboarding of new employees.
> 
> 1. **Centralizing User Request Management:**
> Currently, users email you directly for IT-related requests, which can lead to delays and a high volume of email communication. Implementing a centralized ticketing system, such as a help desk or IT service management (ITSM) tool, will streamline user request management. Users can submit requests through the system, allowing you to prioritize and track them more efficiently. This ensures timely resolution of issues and provides transparency in the IT support process.
> 
> 2. **Introducing Cloud-Based Services:**
> Moving the company's services, such as email, file storage, and instant messaging, to the cloud can bring numerous benefits. Cloud-based services offer scalability, reliability, and easier access for remote employees. It reduces the burden of maintaining in-house servers and ensures data backups are performed automatically. Implementing cloud-based solutions also supports the company's rapid growth plans by providing a flexible and scalable IT infrastructure.
> 
> 3. **Implementing Backup and Data Recovery Solutions:**
> The critical customer data stored on the file server needs to be protected. Implementing a robust backup and data recovery solution is crucial to prevent data loss in case of accidental deletion, hardware failure, or other unforeseen events. Regular backups, both on-site and off-site, should be scheduled to ensure data integrity and availability. This safeguards the company's valuable customer information and mitigates potential business risks.
> 
> 4. **Planning for Scalability:**
> With the expected hiring of hundreds of new employees, it's essential to plan for the scalability of IT operations. Consider implementing infrastructure solutions that can accommodate the anticipated growth, such as scalable server architecture, network infrastructure upgrades, and proper capacity planning. Automating routine tasks, leveraging cloud services, and implementing scalable hardware and software solutions will help you handle the increased workload effectively.
> 
> By implementing these process improvements, W.D. Widgets can enhance productivity, scalability, and data security within their IT infrastructure. Automated software deployment, centralized user request management, cloud-based services, backup and data recovery solutions, and scalability planning will optimize IT operations, improve efficiency, and support the company's growth objectives. These improvements will enable you to manage the IT needs of a larger workforce effectively and ensure the continuity of critical business operations.


###  Question 3
You’re doing systems administration work for Dewgood. Evaluate their current IT infrastructure needs and limitations, then provide at least five process improvements and rationale behind those improvements. Please write a 200-400 word process review for this consultation. Remember, there’s no right or wrong answer, but make sure to provide your reasoning.

**Non-profit Company:**

Dewgood is a small, local non-profit company of 50 employees. They hired you as the sole IT person in the company. The HR person tells you when they need a new computer for an employee. Currently, computers are purchased directly in a physical store on the day that an employee is hired. This is due to budget reasons, as they can’t keep extra stock in the store.

The company has a single server with multiple services on it, a file server, and email. They don’t currently have a messaging system in place. When a new employee is hired, you have to do an orientation with them for login. You’re also responsible for installing all the software they need on their machine, and mapping the file server to their computer. The computers are managed through Windows Active Directory. When an employee leaves, they’re currently not disabled in the directory service.

The company uses an open-source ticketing system to handle all internal requests as well as external non-profit requests. But the ticketing system is confusing and difficult to use, so lots of the employees reach out to you directly to figure out how to do things. In fact, so many things are difficult to find that employees typically ask around when they have a question.

There are nightly backups in place of the file server. You store this information on a disk backup and take it home with you everyday to keep it safe in case something happens onsite. There’s also a small company website that’s hosted on the single server at the company. This website is a single html page that explains the mission of the company and provides contact information. The website has gone down many times, and no one knows what to do when it happens.


> Process Review for Dewgood
> 
> As the sole IT person for Dewgood, there are several process improvements that can be made to address the company's IT infrastructure needs and limitations. Here are five recommended improvements and their rationale:
> 
> 1. **Implementing Centralized Computer Provisioning:**
> Instead of purchasing computers on the day of an employee's hiring, establish a centralized computer provisioning process. Maintain a small inventory of standard computer models based on budget constraints. When HR informs you about a new hire, allocate a pre-configured computer from the inventory. This eliminates the need for last-minute purchases and ensures consistency in hardware specifications. It also allows you to perform necessary software installations and configurations in advance, reducing orientation time and enabling employees to start working immediately.
> 
> 2. **Segregating Server Services:**
> Currently, all services, including the file server, email, and website, are hosted on a single server. Segregate these services onto separate servers to enhance performance, security, and manageability. Dedicated servers for email, file storage, and hosting the website will provide better resource allocation and isolation. It allows for easier maintenance and troubleshooting, minimizes the impact of issues on other services, and improves overall system reliability.
> 
> 3. **Implementing a Messaging System:**
> Introduce a messaging system, such as an instant messaging platform or collaboration tool, to facilitate internal communication. A dedicated messaging system improves real-time communication, promotes collaboration among employees, and reduces the need for email communication. Choose a user-friendly platform with easy-to-navigate features, ensuring widespread adoption and reducing the dependency on direct communication with the IT department for simple queries.
> 
> 4. **Enhancing Ticketing System Usability:**
> Address the issues with the existing ticketing system by evaluating alternative solutions or improving the current system's usability. Implement a user-friendly ticketing system that simplifies the process for internal and external requests. Ensure clear instructions and documentation are provided to employees, enabling them to self-serve for common issues or questions. This reduces the number of direct inquiries to the IT department, allowing you to focus on critical tasks and minimize interruptions.
> 
> 5. **Implementing Offsite Backup and Website Monitoring:**
> While nightly backups are in place, storing the backup disk offsite at your home introduces risk and potential delays in case of emergencies. Implement a secure offsite backup solution, such as cloud-based backup services, to ensure data integrity and accessibility even in the event of a disaster at the office. Additionally, set up website monitoring tools that provide alerts when the website goes down. This allows you to proactively address any issues promptly, minimizing downtime and ensuring the availability of the company's website.
> 
> By implementing these process improvements, Dewgood can enhance productivity, efficiency, and data security within their IT infrastructure. Centralized computer provisioning, server service segregation, messaging system implementation, ticketing system usability enhancements, and offsite backup and website monitoring will optimize IT operations, streamline communication, and minimize risks. These improvements enable you to provide better support to employees, safeguard critical data, and ensure a reliable IT environment for Dewgood's non-profit activities.

