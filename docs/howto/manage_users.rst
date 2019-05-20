.. _manage_users:

Manage Users
============

Application roles needed to manage learning users: :ref:`Tenant Admin <tenant_administrator>`

**User Authentication**

Users in Performa 365 can be authenticated using their Azure Active Directory (AAD) account or Active Directory account via Federation Services (ADFS). 

User management features described below depend on the selected identity provider:

* :ref:`User management for AAD identity provider<AAD>`
* :ref:`User management for ADFS identity provider<ADFS>`

.. _AAD:

User management for AAD identity provider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

When AAD identity provider is used, users for Performa 365 are mostly managed through AAD.

Add a New User (Internal)
******************************

This procedure applies to internal users, typically employees or subcontractors of your company, who already have accounts in your AAD.

To add a new internal user to Performa 365, simply add user's AAD account to the AAD user group which corresponds to the **Learner** role. AAD user group to Performa 365 role mapping can be obtained through your system admin. If additional roles are needed for the new user, just add the user's account to additional groups.

New users will be automatically propagated from AAD to Performa 365. Please check the details of the :ref:`User Sync<UserSync>` procedure to learn about synchronization frequency and user attributes being propagated. If needed, changes can be propagated immediatelly by clicking on the **Start user sync** tile in the **System settings** section of the **Manage** page.

Add a New User (External)
*****************************

This procedure applies to external users, typically external trainers for your organization or external attendees of trainings your organization is providing.

To add a new external user to Performa 365, create a new `guest user in your AAD <https://docs.microsoft.com/en-us/azure/active-directory/b2b/user-properties>`_. Guest user can provide their existing Microsoft account or you can create a new Microsoft account for them. Once this account is added to your AAD as guest user, just add this user to the user group in AAD which corresponds to the **Learner** role and potentically additional groups/roles.

Add an Offline User
*****************************

This procedure applies to external users, typically external attendees or instructors in trainings provided by your organization. The main difference between offline and regular users is that these users will not be able to log into the system. You will add these users only for keeping track of course progress. This functionality will typically be used by HR department to quickly add external users without the need for involving IT department and asking them to add user to organization's active directory. 

To add an offline user to the system follow these steps:

#. Navigate to **Manage** > **Users**.
#. Click on **Add** and fill in all required fields. 

After adding, offline users will appear in searches if you want to select these users to be added as instructors in course schedules.


Update a User's Information
****************************

To update a user's basic information (first name, last name, display name or e-mail), update these information in AAD. These changes will be propagated periodically from AAD to Performa 365, using the automatic :ref:`User Sync<UserSync>` procedure. If needed, changes can be propagated immediatelly by clicking the **Start user sync** tile in the **System settings** section of the **Manage** page.

To update additional user's information, follow the procedure below:

#. Navigate to **Manage** > **Users**.
#. Select edit icon in the **Actions** column for the user you wish to update.
#. **Edit User** form opens below. In this form, only the information which are not synced from the AAD can be changed.
#. Make changes and click **Save**.

Deactivate a User
*******************

Deactivation disables a user from logging on or performing any activity in the system. To deactivate an existing user, simply remove this user from all Performa 365-related user groups in AAD.

View All Users
*******************

#. Navigate to **Manage** > **Users**.
#. **Users** page is shown containing a list with all users.
#. Click the **Details** icon in the **Actions** column to view additional details, such as user's roles and dates of the first import (from AAD) and last modification.

.. _UserSync:

User Sync
**************

User Sync procedure is executed every hour to synchronize all users from Performa 365-related AAD user groups to Performa 365. Any updates in AAD, including newly added users or users with updated information will be synchronized.

This procedure will propagate the following users' attributes from AAD to Performa 365:

 * First name
 * Last name
 * Name (Display name)
 * User name (E-mail address)
 * Job title
 * Department

.. note:: Each unique department, as read from the Department field in AAD, will be created as new Department in Performa 365. As department hierarchy is not available in AAD, please use the :ref:`Manage Business Entities<business_entities>` functionality to set the appropriate relations beween business entities such as group of companies, company and departments.

.. _ADFS:

User management for ADFS identity provider
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

When ADFS identity provider is used, users for Performa 365 are mostly managed through Performa 365 user interface.

Add a New User
*******************

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. Click **Add** button.
#. **Add user** form opens below.
#. Fill in required fields and click **Save**.

Update a User's Information
******************************

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users.
#. Select edit icon in the **Actions** column for the user you wish to update.
#. **Edit User** form opens below.
#. Make changes and click **Save**.

Deactivate a User
*********************

Deactivation disables a user from logging on or performing any activity in the system. 

#. Go to **Manage** > **Users**.
#. Select edit icon in the **Actions** column for the user you wish to deactivate.
#. **Edit User** form opens below.
#. Change toggle button **Status**  to *OFF*.
#. Click **Save**.

View All Users
**********************

#. Navigate to **Manage** > **Users**.
#. **Users** page is shown containing a list with all users.
#. Click the **Details** icon in the **Actions** column to view additional details, such as user's roles and dates of the first import  and last modification.

Manage User Groups
**********************
