.. _master-data:

Master Data
===========
Master Data refers to the core data essential to operations in a specific business or business unit.

The **Master Data** section in |project_name| provides tools for managing critical system data that is essential for platform functionality. It allows users with sufficient roles to manage keywords, translations, and other configurable system settings for optimal operation.

.. _navigating-master-data:

Navigating to Master Data
-------------------------
To access the **Master Data** section:

1. **Go to the Home Page** of |project_name|.
2. **Locate the Master Data** menu on the sidebar.
3. **Click on the Master Data menu item**, which will expand a dropdown list of available tools.

.. _features-master-data:

Features of Master Data
-----------------------
The Master Data section includes tools for:

1. **Managing Keywords** – Useful for search optimization and categorization.
2. **Handling Translations** – Supports multilingual capabilities to enhance user accessibility.

.. _keywords:

1. Keywords
----------
The **Keywords** module helps manage keywords for better search functionality and content categorization within |project_name|.

Viewing Keywords
^^^^^^^^^^^^^^^^
- Users can view a list of all existing keywords in a structured table format.
- The table includes the following columns:

  - **Keyword ID** – A unique identifier for the keyword.
  - **Name** – The actual keyword text.
  - **Created At** – Timestamp of keyword creation.
  - **Updated At** – Timestamp of last modification.

Creating a New Keyword
^^^^^^^^^^^^^^^^^^^^^^
To add a new keyword:

1. Navigate to **Master Data > Keywords**.
2. Click on **Create Keyword**.
3. Enter the **Name** of the new keyword.
4. Click **Save** to add it to the system.

.. _translations:

2. Translations
---------------
The **Translations** module manages multilingual support, ensuring localized experiences for users in different regions.

Viewing Translations
^^^^^^^^^^^^^^^^^^^^
- Users can view a list of all existing translations in a structured table format.
- The table includes the following fields:

  - **Translation ID** – A unique identifier for the translation entry.
  - **Key** – The key used for referencing the translation in the system.
  - **Created At** – Timestamp when the translation was added.
  - **Updated At** – Timestamp of the last update.

Creating a New Translation
^^^^^^^^^^^^^^^^^^^^^^^^^^
To add a new translation:

1. Navigate to **Master Data > Translations**.
2. Click on **Create Translation**.
3. Enter the **Key** (reference text).
4. Click **Save** to store the translation.

Role-Based Access Control (RBAC)
---------------------------------

RBAC in |bold_project_name| ensures secure and organized access management by assigning roles and permissions to users based on their responsibilities. It follows a hierarchical structure where **roles** define what actions a user can perform.

**Key Concepts of RBAC**


1.	**Roles** – Define sets of permissions for different types of users (e.g., Manager, Sales-Rep, Tenant-Admin).
2.	**Permissions** – Allow specific actions, such as viewing , editing, or deleting data.
3.	**Rules** – Optional conditions that restrict permissions based on context (e.g., a user can only edit their own records, a user can view leads assigned to him only).
4.	**Assignments** – Link roles to users dynamically, allowing flexible access control.

**Roles in** |bold_project_name|


  -	**Tenant-Admin**: Full control over tenant-level settings, user management, and configurations.
  -	**Manager**: Can oversee operations, manage accounts, and assign tasks.
  - **Accountant**: Can manage sales records etc.
  - **Sales-Rep/Support-Rep**: Limited access to leads, contacts, and opportunities.

**How RBAC Works in** |bold_project_name| 

	- **Assign Roles to Users** : A Tenant-Admin can assign roles to users and manage permissions.
  -	**Define Permissions for Roles** : Permissions are linked to roles to specify what actions each role can perform.
  - **Restrict Access** : The application checks a user’s role and associated permissions before allowing them to perform specific actions.

.. _additional-functionalities:

Additional Functionalities
--------------------------
- The Master Data module ensures **consistency across the platform** by providing centralized management of key system elements.
- It integrates seamlessly with other |project_name| features, including **user management, leads, CRM, and campaign tools**.
- REST API endpoints are available for programmatic interaction with **Master Data**.
