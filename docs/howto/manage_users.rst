.. _manage_users:

Manage Users
============

Application roles needed to manage learning users: :ref:`Tenant Admin <tenant_administrator>`

User Authentication
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Users in Performa 365 can be authenticated using their Azure Active Directory (AAD) account or Active Directory Federation Services (AD FS) account. 

User management features described below depend on the selected identity provider:

* :ref:`User management for AAD identity provider<AAD>`
* :ref:`User management for AAD identity provider<ADFS>`

.. _AAD:

User management for AAD identity provider
================================================

View All Users
^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. In the **Actions** column there are **Details** and **Edit** icons for each user.
#. Click **Details** icon to view a user's details.
#. **Details** form is displayed below containing information about user's external identifier, application roles assigned, first import date and last modified date.

.. note:: Availability of **Edit** action depends on your tenant configuration. For more info, contact your service provider.

Update User's Information
^^^^^^^^^^^^^^

#. Go to **Manage** > **Users**.
#. Select edit icon in the **Actions** column for the user you wish to edit.
#. **Edit User** form opens below.
#. Id, First Name, Last Name, Display Name and E.mail are read-only, depending on your identity provider and tenant configuration).
#. Do the changes.
#. Click **Save**.

Deactivate a User
^^^^^^^^^^^^^^^^^

Deactivation disables a user from logging on or performing any activity in the system. 

#. Go to **Manage** > **Users**.
#. Select edit icon in the **Actions** column for the user you wish to deactivate.
#. **Edit User** form opens below.
#. Change toggle button **Status**  to *OFF*.
#. Click **Save**.

User Sync
^^^^^^^^^^^^

.. note:: This action is only available for AAD identity provider.

User Sync process is executed once per day and syncs all users from the mapped user groups to Performa 365. Any updates in AAD, including newly added users or users with updated information such as first name, last name, display name and email, will be reflected in Performa 365 as well.

.. _ADFS:

User management for ADFS identity provider
================================================

View All Users
^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. In the **Actions** column there are **Details** and **Edit** icons for each user.
#. Click **Details** icon to view a user's details.
#. **Details** form is displayed below containing information about user's external identifier, application roles assigned, first import date and last modified date.

Create a New User
^^^^^^^^^^^^^^

.. note:: This action is only available for AD FS identity provider.

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. Click **Add** button.
#. **Add user** form opens below.
#. Fill in required fields and click **Save**.
