# summary class 14

## Access Controls
it implements everywhere in computer system. websites have limited access to pages based on the credentials of a user.
it is important to limit access to client. Access Control is limiting what actions a user can preform on a given resource. the server return for the user token when signin or signup then the user return this token to get access with limited access control.

## Application Flow and Access Control
### Back End (API Layer)
the step to do that first manage the login cycle with the front-end application then maintain the User’s database and maintain roles for each user, authenticate users (basic and bearer) next create, manage, and apply Role Based Access Controls, maintain and reference their capabilities, based on their role, restrict access to features (like routes) based on capabilities, express Middleware could be used to restrict access to routes and mongoose Middleware/Hooks could be use to restrict access to business logic.
### Front End (Client Layer)
First you need to initiate the login process and store login tokens as cookies then manage login state, capabilities and control physical & visual access (hide/show/alter) to components based on RBAC rules finally alter behaviors based on RBAC rules.

## Role-Based Access Control [RBAC]
is assigning system access to users based on their role within an organization.
**There are some alternatives for/variations of RBAC, including:**
- Access control lists (ACL)
used to allow users from one department to make changes to a document, while only allowing users from other departments to read the document.
- Attribute-based access control (ABAC)

### Five Steps To implement RBAC
1- Inventory your systems
for example include an email system, customer database, contact management system, etc.
2- Analyze your workforce and create roles
for example, have a basic user role, which includes the access any employee would need, such as email and the intranet site.
3- Assign people to roles
after the second step you have a list of roles and their access rights, figure out which roles each employee belongs in, and set their access.
4- Never make one-off changes
change the roles as you need or add new ones when really necessary.
5- Audit
As an example, many healthcare organizations, given the need for regulatory compliance in controlling access to medical records, use RBAC to define exactly what access to medical records each type of clinician may need. while a doctor might have almost unlimited access to the records of patients he/she manages, a receptionist might be limited to basic contact information needed to manage appointments.