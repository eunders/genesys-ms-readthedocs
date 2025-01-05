=============
GeneSys Admin
=============

Introduction
-------------

Welcome to the documentation for the GeneSys Admin web application. Use the menu below to navigate through the key features and functionalities.


Accessing GeneSys Admin
-----------------------

To access the GeneSys Admin web application, please follow these steps:

1. **Login**: Go to the GeneSys Admin website and log in with your credentials.

Navigating the Dashboard
====================
.. image:: /_static/home.png
    :alt: Optional alt text for the image
    :align: center
    :width: 800px


The GeneSys Admin dashboard serves as a central hub for managing various aspects of the application.

Menu Bar
--------

The menu bar on the left-hand side provides access to the following options:

1. **View Leads**: Displays a list of all existing leads.
2. **Create Lead**: Allows users to add new leads to the system.
3. **Import Leads**: Facilitates the import of leads from external sources.


This section provides a detailed overview of the "Leads" feature, including navigation, CRUD operations, table columns, and additional functionalities.

==================
Navigating to Leads
==================

To access the "Leads" section:

1. On the **Home Page**, locate the **Sidebar Menu**.
2. Click on the **Leads** menu item. This will expand a dropdown menu.
3. Select **View Leads** to open the leads management page.

====================
Viewing Leads
====================

.. image:: /_static/viewlead.png
    :alt: Optional alt text for the image
    :align: center
    :width: 800px

The **View Leads** page displays all saved leads in a table format. The table includes the following columns:

Lead Table Columns
------------------

.. image:: /_static/createlead.png
    :alt: Optional alt text for the image
    :align: center
    :width: 800px

1. **Contact ID**:  
   - A unique identifier assigned to each lead.  
   - This column helps to differentiate between leads easily.

2. **Email**:  
   - The email address of the lead.  
   - This column allows users to view and verify contact information.

3. **First Name**:  
   - The first name of the lead.  
   - This field provides clarity on the lead's identity.

4. **Last Name**:  
   - The last name of the lead.  
   - Together with the first name, it fully identifies the lead.

5. **Phone Number**:  
   - The contact phone number of the lead.  
   - This column is used for direct communication with the lead.

6. **Tag**:  
   - A label or keyword associated with the lead.  
   - Tags can help categorize or filter leads for better management.

7. **Created At**:  
   - The date and time when the lead was created.  
   - This field helps track when the lead was added.

8. **Updated At**:  
   - The date and time when the lead was last updated.  
   - Useful for identifying recent changes.

9. **CRM Campaign**:  
   - A text column containing the name or type of CRM campaign associated with the lead.  
   - This helps link leads to specific marketing campaigns.

10. **Lead Owner**:  
    - A dropdown column allowing selection of the lead's owner.  
    - The dropdown is searchable for convenience.

11. **Organization**:  
    - The organization the lead is associated with.  
    - This provides context on the lead's professional background.

12. **Designation**:  
    - The professional title or role of the lead within their organization.  
    - Helps understand the lead’s position in their company.

13. **Country**:  
    - A searchable dropdown that provides a list of countries to select from.  
    - Users can easily assign a country to the lead for regional tracking.

14. **Lead Type**:  
    - A dropdown containing predefined lead types.  
    - Examples include "Prospect," "Customer," or "Partner."

15. **Product**:  
    - The product or service associated with the lead.  
    - This column helps link leads with specific offerings.

16. **Lead Status**:  
    - A dropdown containing predefined statuses for the lead.  
    - Examples include "New," "In Progress," "Closed."

17. **Source**:  
    - Indicates how the lead was acquired (e.g., "Website," "Referral," "Event").  
    - Helps track lead generation channels.

18. **Follow-up Date**:  
    - A date and time column for scheduling follow-up actions.  
    - Ensures timely communication with leads.

19. **Action**:  
    - This column contains interactive icons for various actions:  
        - **View Icon**: Opens a detailed view of the lead.  
        - **Delete Icon**: Removes the lead from the system.  
        - **Update Icon**: Opens the lead form for editing.

====================
Managing Leads
====================

Create a Lead
---------------------

   - Navigate to the **View Leads** page.
   - Click the **Create CRM Contact** button.
   - Fill in the required fields and click **Save.**

View a Lead
-----------

   - Navigate to the **View Leads** page.
   - Leads are displayed in a table format with all relevant details.

Update a Lead
---------------

   - On the **View Leads** page, locate the lead you want to modify.
   - Click the **Edit** button in the **Actions** column.
   - Make the necessary changes and click **Save.**

Delete a Lead
---------------

   - On the **View Leads** page, locate the lead you want to delete.
   - Click the **Delete** button in the **Actions** column.
   - Confirm the deletion to remove the lead permanently.


Users
=====

The "Users" module focuses on user account management, empowering administrators to control access, assign roles, and maintain user details. Refer to the **Users** section for detailed instructions on managing users.

====================
Navigating to Users
====================

To access the "Users" section:

1. On the **Home Page**, locate the **Sidebar Menu**.
2. Click on the **Users** menu item. This will expand a dropdown menu.
3. Select **View Users** to open the user management page.

====================
Viewing Users
====================

.. image:: /_static/viewusers.png
    :alt: Optional alt text for the image
    :align: center
    :width: 800px

The **View Users** page displays all saved users in a table format. The table includes the following columns:

User Table Columns
------------------ 

.. image:: /_static/createusers.png
    :alt: Optional alt text for the image
    :align: center
    :width: 800px

1. **User ID**:  
   - An auto-generated unique identifier assigned to each user.  
   - This column helps to differentiate between users easily.

2. **Email**:  
   - The email address of the user.  
   - This column allows users to view and verify contact information.

3. **First Name**:  
   - The first name of the user.  
   - This field provides clarity on the user’s identity.

4. **Last Name**:  
   - The last name of the user.  
   - Together with the first name, it fully identifies the user.

5. **Role**:  
   - The user’s role in the system (e.g., Admin, Manager, Staff).  
   - Helps assign appropriate permissions and responsibilities.

6. **Created At**:  
   - The date and time when the user account was created.  
   - Useful for tracking new accounts.

7. **Updated At**:  
   - The date and time when the user account was last updated.  
   - Useful for identifying recent changes.

8. **Product**:  
   - The product or service associated with the user.  
   - Useful for linking users to specific offerings.

9. **Organization**:  
   - The organization the user is associated with.  
   - Provides context on the user’s professional background.

10. **CRM Campaign**:  
    - A text column containing the name or type of CRM campaign linked to the user.  
    - Helps connect users to specific campaigns.

11. **CRM Campaign Identifier**:  
    - A unique identifier for the CRM campaign.  
    - Enables precise tracking of campaign associations.

12. **CRM Campaign Timestamp**:  
    - The date and time related to the CRM campaign activity.  
    - Useful for campaign timeline tracking.

13. **CRM Source**:  
    - Indicates the origin of the CRM campaign (e.g., "Website," "Referral").  
    - Helps track campaign sources.

14. **Action**:  
    - This column contains interactive icons for various actions:  
        - **View Icon**: Opens a detailed view of the user.  
        - **Delete Icon**: Removes the user from the system.  
        - **Update Icon**: Opens the user form for editing.


====================
Managing Users
====================

Create a User
---------------------

   - Navigate to the **View Users** page.
   - Click the **Create User** button.
   - Fill in the required fields and click **Save.**

View a User
-----------

   - Navigate to the **View Users** page.
   - Users are displayed in a table format with all relevant details.

Update a User
---------------

   - On the **View Users** page, locate the user you want to modify.
   - Click the **Edit** button in the **Actions** column.
   - Make the necessary changes and click **Save.**

Delete a User
---------------

   - On the **View Users** page, locate the user you want to delete.
   - Click the **Delete** button in the **Actions** column.
   - Confirm the deletion to remove the user permanently.

============
Master Data 
============

Roles
------

The **Roles** feature under the **Master Data** section provides tools for managing user roles within the GeneSys Admin application. Roles help define user permissions and access levels, enabling administrators to assign responsibilities effectively.

Roles Management
=================

The **Roles** menu contains the following options:

1. **View Roles**: Displays a list of all created roles in a table format.
2. **Create Role**: Allows administrators to add new roles to the system.

Viewing Roles
=============

To view existing roles:

1. Navigate to the **Master Data > Roles** section.
2. Select **View Roles** from the dropdown menu.

.. image:: /_static/viewroles.png
    :alt: View Roles Table
    :align: center
    :width: 800px

A table listing all stored roles will appear, displaying the following columns:

- **Role ID**: A unique, auto-generated identifier for each role.
- **Name**: The name of the role.
- **Description**: A brief description of the role.
- **Created At**: The date and time the role was created.
- **Updated At**: The date and time the role was last updated.
- **Actions**: Interactive icons to update, delete, or view detailed information about a role.

Creating a Role
===============

To create a new role:

1. Navigate to the **Master Data > Roles** section.
2. Select **Create Role** from the dropdown menu.
3. Fill in the required fields:
   - **Name**: Enter a unique name for the role.
   - **Description**: Provide a brief description of the role.
4. Click **Save** to store the new role.

.. image:: /_static/createroles.png
    :alt: Create Role Form
    :align: center
    :width: 800px



Updating a Role
===============

To update an existing role:

1. Navigate to the **View Roles** page.
2. Locate the role you want to modify.
3. Click the **Edit** icon in the **Actions** column.
4. Update the necessary fields and click **Save**.

Deleting a Role
===============

To delete an existing role:

1. Navigate to the **View Roles** page.
2. Locate the role you want to delete.
3. Click the **Delete** icon in the **Actions** column.
4. Confirm the deletion to permanently remove the role.

==================================
Role-Based Access Control (RBAC)
==================================

The **RBAC** feature under **Master Data** includes:

.. image:: /_static/rbac.png
    :alt: View Roles Table
    :align: center
    :width: 800px

- **Grant Access**: Assign roles and permissions to users.
- **Roles**: Manage roles as described above.
- **Rules**: Define custom rules for access control.
- **Permissions**: Specify detailed permissions for each role.


The **Roles** feature in the GeneSys Admin application simplifies user management by providing a structured way to define and assign permissions. Use the intuitive interface to create, view, and modify roles effectively, enhancing security and operational efficiency.


.. toctree::
   :maxdepth: 2
   :caption: Contents:

  