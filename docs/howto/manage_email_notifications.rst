.. _email_notifications:

Manage E-mail Notifications
=============================

Application roles needed to manage learning users: :ref:`Tenant Admin <tenant_administrator>`

To manage e-mail notifications, navigate to the **Manage** page and select the **E-mail notifications** tile in the **System settings**. **E-mail notification** page is shown containing three sections: **E-mail service settings**, **E-mail notification settings** and **E-mail notification history** .


Configure E-mail Service
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Current E-mail service settings are displayed. Click **Edit** to make changes:

*E-mail service settings* section:

    * *E-mail service type* - Currently only is SMTP supported.
    * *Server address* - IP or FQDN address of the e-mail server (service).
    * *Port* - Port used by the e-mail service, for SMTP typically 25 or 587 or 465.
    * *SMTP Authentication* - ON/OFF: turn ON if your SMTP service required authentication.
    * *Account name* - If SMTP authentication turned ON, type the account name used for SMTP authentication.
    * *Password* - If SMTP authentication turned ON, type the password used for SMTP authentication.
    * *Enable SSL* - ON/OFF: turn ON if your SMTP service requires SSL connection
    
*E-mail settings* section:

    * *From address* - E-mail from address which will be used for sending e-mail notifications, for example: performa365@essperta.com.
    * *From title* - E-mail from address "friendly name", for example: Performa 365. E-mail receiver will seethe from field as: Performa 365 (performa365@essperta.com). This field is optional.
    * *Reply-to address* - If "from address" does not have a corresponding mailbox, use can use the reply-to address to specify where e-mail will be sent if user replies to any notification received from the system. This field is optional.
    * *Bcc* - Bcc address can be used it you want all send notification to be sent to a specific mailbox. Typically used as an additional repository of all sent e-mails. This field is optional.
    * *Default font name* - A font to be used in all e-mail notifications. For example: Calibri.
    * *Default font size* - Font size to be used in all e-mail notifications sent. For example: 14.
    * *Default font color* - Font color to be used in all e-mail notifications sent. For example: Black.
    

Configure E-mail Notifications
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **E-mail notifications** tile.
#. **E-mail notification** page is shown containing three sections: **E-mail service settings**, **E-mail notification settings** and **E-mail notification history** .
#. Click on **E-mail notification settings**.
#. List of all available E-mail notifications is displayed below.
#. The leftmost column **E-mail notifications** contains the name of the notification. This name cannot be changed.
#. Second column **Type** indicates whether the message is sent automatically:

      * *on event* (e.g., when learners successfully complete a course, they will be sent an e-mail message informing them the course has been finished. Additional items can be included in the message, such as certificate of completion.)
      * *on schedule* (e.g. learners can be reminded of an upcoming schedule by the message sent on selected day at specified time).
#. **Status** column contains checkboxes which show that the corresponding notification is enabled/disabled.
#. Clicking on *Edit* icon in the last column **Actions** opens a form below the notifications list. Each message can be customized by changing the fields in this form.
#. First two fields, **E-mail notification** and **Type** are read only.
#. **Subject** field is required and can be customized. The text in this field will be rendered as subject of your e-mail message.
#. **Cc** is optional. E-mail addresses listed here will receive a copy of this email message.
#. **Body** is required and can be customized. Placeholders (variables in curly brackets such as {{FirstName}}) should be left inside the body of the message. 
#. **Sending type** has three options for sending messages on schedule. Depending on the option chosen, time, day of the week or date can be specified as well in the following steps.
#. **Number of retries in case of failure** is required. It is set to 3 by default but can be changed if needed.
#. Setting **Status** to *ON* will enable message which means it will be sent on event/schedule. Setting it to *OFF* disables the message from being sent. 

View E-mail Notification History
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **E-mail notifications** tile.
#. **E-mail notification** page is shown containing three sections: **E-mail service settings**, **E-mail notification settings** and **E-mail notification history** .
#. Click on **E-mail notification history**.
#. List of all E-mail notifications that have been sent is displayed below. 
#. For each message sent the following data is displayed in the list: Name (type) of message, recepient's e-mail address, status and time when the message was sent.
#. Clicking on *Details* icon in the **Actions** column enables you to see complete body of the message sent.
