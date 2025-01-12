
==================================
Role-Based Access Control (RBAC)
==================================

|project_name| implements a role hierarchy to control access to various features and sections of the application. Below is the hierarchical structure of roles:


Roles Hierarchy
===============

The |project_name| application uses a Role-Based Access Control (RBAC) system with the following hierarchy:

```
ADMIN
↓
TENANT-ADMIN
↓
MANAGER
↓
ACCOUNTANT ,
SALES-REP ,
SUPPORT-REP
```

- **Admin**
  - Full access to all features and sections.
  - Parent role for all other roles.

  ↓

  - **Tenant Admin**
    - Full access but subordinate to Admin.

    ↓

    - **Manager**
      - Access to all features except login logs and system logs.

      ↓

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




The **RBAC** feature under **Master Data** includes:

.. image:: /_static/en/rbac.png
    :alt: View Roles Table
    :align: center
    :width: 800px

- **Grant Access**: Assign roles and permissions to users.
- **Roles**: Manage roles as described above.
- **Rules**: Define custom rules for access control.
- **Permissions**: Specify detailed permissions for each role.


The **Roles** feature in the |project_name| application simplifies user management by providing a structured way to define and assign permissions. Use the intuitive interface to create, view, and modify roles effectively, enhancing security and operational efficiency.
