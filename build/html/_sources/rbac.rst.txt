
==================================
Role-Based Access Control (RBAC)
==================================

|project_name| implements a role hierarchy to control access to various features and sections of the application. Below is the hierarchical structure of roles:

Key Concepts
=============

**Roles**

- A "role" is a set of permissions grouped together.  
- **Purpose**: Define what a user can do based on their role.
- **Example**: Tenant-Admin, Manager, Accountant, Sales-Rep, Support-Rep, Teacher, Affiliate, User, Guest.  

**Permissions**

- A "permission" is a specific action a user is allowed to perform.  
- **Purpose**: Control access to particular features or actions in the application. 
- **Example**: Edit User, View Dashboard, Delete User.  
  

**Users**

- Individuals who use the application.  
- **Purpose**: Users are assigned one role to define what they can access.  

How RBAC Works
===============

- **Assign Roles to Users** : 
   Each user is assigned one roles based on their responsibilities in the application.  

- **Define Permissions for Roles** :
   Permissions are linked to roles to specify what actions each role can perform.  

- **Restrict Access** :
   The application checks a user’s role and associated permissions before allowing them to perform specific actions.  

Example Scenarios
==================

Managing a Blog
---------------
- **Admin**: Can create, edit, delete, and publish articles.  
- **Editor**: Can edit and publish articles but cannot delete them.  
- **Viewer**: Can only view articles.  

E-Commerce Site
---------------
- **Customer**: Can browse products, add items to a cart, and place orders.  
- **Manager**: Can manage products and view sales reports.  
- **Admin**: Has all permissions, including managing users and settings.  



Roles Hierarchy
===============

The |project_name| application uses a Role-Based Access Control (RBAC) system with the following hierarchy.
Permissions and roles can be structured hierarchically, with higher roles inheriting permissions from lower roles.  

**Example**: An Tenant-Admin role might inherit permissions from the Manager Manager, Accountant, Sales-Rep, Support-Rep, Teacher, Affiliate, User, Guest. 

```
TENANT-ADMIN
↓
MANAGER
↓
ACCOUNTANT ,
SALES-REP ,
SUPPORT-REP
```

  - **Tenant Admin**
   - Full access to all features and sections.
   - Parent role for all other roles.

      - **Manager**
       - Access to all features except login logs and system logs.

      - **Accountant**
        - Access limited to the dashboard view only.

      - **Sales-Rep**
        - Access to:
          - Dashboard
          - Contact Requests (in Site section)
          - Leads and Lead Calendar (in CRM section)

      - **Support-Rep**
        - Access to:
          - Dashboard
          - Contact Requests (in Site section)
          - Leads and Lead Calendar (in CRM section)


Access Control
==============

This section provides a breakdown of role-based permissions and functionalities.


**Tenant-Admin Access**:

- Full access to all features, including:
  - Dashboard
  - Users
  - Roles
  - CRM (Leads, Calendar, Campaigns)
  - Contact Requests
  - Reviews
  - System Logs
  - Login Logs

**Manager Access**:


- Inherits Tenant-Admin permissions except for:
  - Login Logs
  - System Logs

**Accountant Access**:


- Limited to:
  - Dashboard viewing only

**Sales-Rep and Support-Rep Access**:


- Access to:
  - Dashboard
  - Contact Requests
  - Leads (Calendar, View Leads, Create Leads, Import Leads)
