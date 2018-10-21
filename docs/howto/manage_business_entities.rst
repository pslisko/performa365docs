.. _business_entities:

Manage Business Entities
========================

Application roles needed to manage business entities: :ref:`Education Process Admin <education_process_administrator>`

.. _about_business_entities:

About Business Entities
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Business Entities allows you to manage companies/institutions and their departments used in the learning process. Typically, here you can manage your organization (department) hierarchy as well as add external organizations if you use them in your processes. Addititionally, if your company or institution  is part of a larger group, such "business group" can also be added as a parent entity. 

In total, this module supports 3 levels of business entities: 

* Business group
* Company/Institution
* Department

Entity on each level can have unlimited number of parents so there is no practical limit on organisation hierarchy.  

Add a Business Entity
^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. In the **Education process management** section on the **Manage** page click **Business Entities** tile.
#. **Business Entities** page is shown containing a list of all defined business entities and action button **Add**.
#. Click **Add** to add a new business entity.
#. **Add Business Entity** form opens below.
#. Enter **Name** of your business entity or organization unit. 
#. Enter optional **External identifier** such as tax number. This field is typically used for integration with your in-house systems when business entities and organizations registry is fetched automatically. 
#. Choose the appropriate **Level** - Business group, Company/Institution or Department.
#. Choose **Parent entity** from the dropdown menu. If your business entity doesn't have a parent, enter '-' in **Parent entity** field.
#. **Save** button is enabled when all required fields are filled.
#. Click **Save**.

Edit a Business Entity
^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. Go to **Manage** > **Business Entities**.
#. In the list of business entities select edit icon in the **Actions** column of the business entity you wish to edit.
#. **Edit Business Entity** form opens below. 
#. You can change your old data in all fields except **Id** and **External identifier** which are read only.

.. note:: Changing the entity status to OFF (Deactivated) will disable usage of this entity in all related entities (such as parent entity on this form, business entity field in :ref:`Locations management <manage_locations>` etc.)
