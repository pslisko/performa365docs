.. _manage_users:

Manage Users
============

Application roles needed to manage learning users: :ref:`Tenant Admin <tenant_administrator>`

User Authentication
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Users in Performa 365 can be authenticated using their Azure Active Directory (AAD) account or Active Directory account via Federation Services (ADFS). 

User management features described below depend on the selected identity provider:

* :ref:`User management for AAD identity provider<AAD>`
* :ref:`User management for ADFS identity provider<ADFS>`

.. _AAD:

User management for AAD identity provider
================================================

When AAD identity provider is used, users for Performa 365 are mostly managed through AAD.

Add a New User
^^^^^^^^^^^^^^

#. To add a new user to Performa 365, simply add the user to the "Learners" group in AAD. Exact name of the group which corresponds to the learner role in AAD can be obtained through your system admin. If additional roles are needed, just add the same user account to additional groups.
#. To enforce this change, run user sync manully by clicking the **Start user sync** tile in the **System settings** section of the **Manage** page.

Deactivate a User
^^^^^^^^^^^^^^^^^

Deactivation disables a user from logging on or performing any activity in the system. To deactivate an existing user, simply remove the user from all Performa 365-related user groups in AAD.

The changes will be propagated from AAD to Performa 365 automatically, using the User Sync procedure. Alternativelly, you can run the user sync manually to enforce change immediately: click the **Start user sync** tile in the **System settings** section of the **Manage** page.


User Sync
^^^^^^^^^^^^

.. note:: This action is only available for AAD identity provider.

User Sync process is executed once per day and syncs all users from the mapped user groups to Performa 365. Any updates in AAD, including newly added users or users with updated information such as first name, last name, display name and email, will be reflected in Performa 365 as well.

View All Users
^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **Users** tile.
#. **Users** page is shown containing a list of all users and action button **Add**.
#. In the **Actions** column there are **Details** and **Edit** icons for each user.
#. Click **Details** icon to view additional details, such as user's roles and dates of the first import (from AAD) and last modification.

Update User's Information
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. Go to **Manage** > **Users**.
#. Select edit icon in the **Actions** column of the user you wish to edit.
#. **Edit User** form opens below. In this form, only the information which are not synced from the AAD can be changes.
#. User's data which are automatically synced from the AAD areare read-only.
#. Information you can change through the form are those in the editable fields.
#. Make changes and click **Save**.


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

Deactivate a User
^^^^^^^^^^^^^^^^^

Deactivation disables a user from logging on or performing any activity in the system. 

#. Go to **Manage** > **Users**.
#. Select edit icon in the **Actions** column for the user you wish to deactivate.
#. **Edit User** form opens below.
#. Change toggle button **Status**  to *OFF*.
#. Click **Save**.
