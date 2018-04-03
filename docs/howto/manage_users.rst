.. _manage_users:

Manage Users
============

Application roles needed to manage learning users: :ref:`Tenant Admin <tenant_administrator>`

Authentication and Authorization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO Marko - opisati tipove authN i AthZ: AAD, ADFS

User management features described below depend on the selected identity provider. Identity provider is selected in the tenant configuration (TBD: link).


View All Users
^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. In the **Actions** column there are **Details** and **Edit** icons for each user.
#. Click **Details** icon to view a user's details.
#. **Details** form is displayed below containing information about user's external identifier, application roles assigned, first import date and last modified date.

Create a New User
^^^^^^^^^^^^^^

.. note:: This action is only available for ADFS identity provider.

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. Click **Add** button.
#. **Add user** form opens below.
#. Fill in required fields and click **Save**.

Update User's Data
^^^^^^^^^^^^^^

#. Go to **Manage** > **Users**.
#. In the list of users select edit icon in the **Actions** column of the user you wish to edit.
#. **Edit User** form opens below.
#. All fields are editable except **Id** and **E-mail** which are read-only.  
#. Click **Save**.

Deactive a User
^^^^^^^^^^^^^^^^^

.. note:: This action is only available for ADFS identity provider.

Deactivation disables a user from logging or performing any activity in the system. 

#. Go to **Manage** > **Users**.
#. In the list of users select edit icon in the **Actions** column of the user you wish to edit.
#. **Edit User** form opens below.
#. Change toggle button **Status**  to *OFF*.
#. Click **Save**.

User Sync
**********

When configuring tenant for the first time, initial sync with AAD is performed. All user data including application roles are mapped and added to the database.

User sync is also performed once per day. Any updates on AAD which include newly added users or update of existing user's first name, last name, display name or email will be updated in the database. 
