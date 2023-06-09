# Centralized Management and LDAP

###### Practice Quiz • 8 min • 5 total points

---

### 1. Which of these are examples of centralized management? Check all that apply.

- [x] Role-based access control
- [x] Centralized configuration management
- [ ] Copying configurations to various systems
- [ ] Local authentication

> Right on! Role-based access control makes it easier to administer access rights by changing role membership and allowing for inheritance to grant permissions (instead of granting each permission individually for each user account). Centralized configuration management is an easier way to manage configurations for services and hardware. By centralizing this, it becomes easier to push changes to multiple systems at once.


### 2. Which of these are components of an LDAP entry? Check all that apply.

- [ ] Uncommon Name
- [x] Common Name
- [x] Distinguished Name
- [ ] Organizational User

> The Common Name contains a descriptor of the object, like the full name for a user account. A Distinguished Name is the unique name for the entry, and includes the attributes and values associated with the entry.


### 3. What does the LDAP Bind operation do exactly?

- [ ] Modifies entries in a directory server
- [ ] Looks up information in a directory server
- [x] Authenticates a client to the directory server
- [ ] Changes the password for a user account on the directory server

> Awesome! A client authenticates to a directory server using the Bind operation. This could either be: (1) an anonymous bind; (2) a simple bind, where the password is sent in plaintext; or (3) an SASL bind, which involves a secure challenge-response authentication scheme.


### 4. Which of the following are authentication types supported by the LDAP Bind operation? Check all that apply.

- [x] Anonymous
- [x] Simple
- [ ] Complex
- [x] SASL

> Bind operations support three different mechanisms for authentication: (1) Anonymous, which doesn't actually authenticate at all, and allows anyone to query the server; (2) Simple, which involves sending the password in plaintext; and (3) SASL, or Simple Authentication and Security Layer, which involves a secure challenge-response authentication mechanism.


### 5. Which of the following are services provided for the Directory Services?

- [x] Centralized Authentication
- [x] Accounting
- [x] Authorization
- [ ] Local authentication

> Directory services provide centralized authentication, authorization, and accounting, also known as AAA.

---

> [System Administration and IT Infrastructure Services](https://www.coursera.org/learn/system-administration-it-infrastructure-services/) {Week-4}

