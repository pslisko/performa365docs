.. _business_entities:

Manage Business Entities
========================

Application roles needed to manage business entities: :ref:`Education Process Admin <education_process_administrator>`

.. _about_business_entities:

About Business Entities
^^^^^^^^^^^^^^^^^^^^^^^^^^^

TODO Marko


Add a Business Entity
^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. In the **Education process management** section on the **Manage** page click **Business Entities** tile.
#. **Business Entities** page is shown containing a list of all defined business entities and action button **Add**.
#. Click **Add** to add a new business entity.
#. **Add Business Entity** form opens below.
#. Enter **Name** of your business entity or organization unit. 
#. Enter optional **External identifier** such as tax number. This field is typically used for integration with your in-house systems when business entities and organizations registry is fetched automatically. 
#. Choose the appropriate **Level** - Business group, Business entity or Organization unit per description in :ref:`About Business Entities <about_business_entities>`.
#. Choose **Parent entity** from the dropdown menu. If your business entity doesn't have a parent, enter '-' in **Parent entity** field.
#. **Save** button is enabled when all required fields are filled.
#. Click **Save**.

Edit a Business Entity
^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. Go to **Manage** > **Business Entities**.
#. In the list of business entities select edit icon in the **Actions** column of the business entity you wish to edit.
#. **Edit Business Entity** form opens below. 
#. You can change your old data in all fields except **Id** and **External identifier** which are read only.

.. note:: Changing a status to OFF (Deactivated) will disable usage of this business entity or organization unit in all related entities (such as parent entity on this form, business entity field in :ref:`Locations management <manage_locations>` etc.)
