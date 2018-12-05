.. _email_notifications:

Manage E-mail Notifications
=============================

Application roles needed to manage learning users: :ref:`Tenant Admin <tenant_administrator>`

To manage e-mail notifications, navigate to the **Manage** page and select the **E-mail notifications** tile in the **System settings**. **E-mail notification** page is shown containing three sections: **E-mail service settings**, **E-mail notification settings** and **E-mail notification history** .


Configure E-mail Service
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Current E-mail service settings are displayed. Click **Edit** to make changes:

*E-mail service settings* section:

    * *E-mail service type* - Currently only SMTP is supported.
    * *Server address* - IP or FQDN address of the e-mail server (service).
    * *Port* - Port used by the e-mail service, for SMTP typically 25 or 587 or 465.
    * *SMTP Authentication* - ON/OFF: turn ON if your SMTP service required authentication.
    * *Account name* - If SMTP authentication turned ON, type the account name used for SMTP authentication.
    * *Password* - If SMTP authentication turned ON, type the password used for SMTP authentication.
    * *Enable SSL* - ON/OFF: turn ON if your SMTP service requires SSL connection
    
*E-mail settings* section:

    * *From address* - E-mail from address which will be used for sending e-mail notifications, for example: performa365@essperta.com.
    * *From title* - E-mail from address "friendly name", for example: Performa 365. E-mail receiver will see the from field as: Performa 365 (performa365@essperta.com). This field is optional.
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

      * *on event* (e.g., when learners successfully complete a course, they will be sent an e-mail notification informing them the course has been finished. Additional items can be included in the notification, such as certificate of completion.)
      * *on schedule* (e.g. learners can be reminded of an upcoming schedule by the notification sent on selected day at specified time).
#. **Status** column contains checkboxes which show that the corresponding notification is enabled/disabled.
#. Clicking on *Edit* icon in the last column **Actions** opens a form below the notifications list. Each notification can be customized by changing the fields in this form.
#. First two fields, **E-mail notification** and **Type** are read only.
#. **Subject** field is required and can be customized. The text in this field will be rendered as subject of your e-mail notification.
#. **Cc** is optional. E-mail addresses listed here will receive a copy of this email notification.
#. **Body** is required and can be customized. Placeholders (variables in curly brackets such as {{FirstName}}) should be left inside the body of the notification.)
#. **Sending type** has three options for sending notifications on schedule. Depending on the option chosen, time, day of the week or date can be specified as well in the following steps.
#. **Number of retries in case of failure** is required. It is set to 3 by default but can be changed if needed.
#. Setting **Status** to *ON* will enable notification which means it will be sent on event/schedule. Setting it to *OFF* disables the notification from being sent. 

E-mail Notifications Messages
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. _N1.2:

*N1.2 Course enrollment notification*
**************************************

This notification is sent to learners when they have been administratively enrolled to a course.
Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learner's first name
	* {{EducationName}} - name of the course the learner is enrolled to
	* {{AssignmentDueDate}} - the date on which the course is expected to be completed
	* {{EnrollmentReason}} - explanation why the learner was enrolled to the course

.. _N1.3:

*N1.3 Course cancellation notification*
******************************************

This notification is sent to learners when the course they were administratively enrolled to had been cancelled. This notification is not sent if learners disenroll themselves from the course they were self enrolled to.
Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learner's first name
	* {{EducationName}} - name of the cancelled course
	* {{DisenrollmentReason}} - explanation why the course they were administratively enrolled to had been cancelled

Region #disenrollmentReason - #enddisenrollmentReason is used to conditionally display text. If the disenrollment reason had been given, it will be shown in the message. If the disenrollment reason had not been defined, message within the region will be omitted.

.. _N1.4:

*N1.4 Course activity schedule enrollment notice*
**************************************************

This notification is sent to learners when they enroll into schedule for classroom/virtual classroom activity.
Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learners's first name
	* {{ActivityName}} - classroom/virtual classroom activity related to the schedule
	* {{EducationName}} - course name
	* {{StartDate}} - schedule start date
	* {{StartTime}} - schedule start time
	* {{Location}} - schedule location

.. _N1.5:

*N1.5 Schedule change notification*
**************************************

If there are any changes in schedule start time, start date or location, this notification will be sent to both learners and schedule instructors.
Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learner's/schedule instructor's first name
	* {{ActivityName}} - activity related to schedule change
	* {{EducationName}} - course name
	* {{StartDate}} - initial start date
	* {{StartTime}} - initial start time
	* {{NEWStartDate}} - new start date 
	* {{NEWStartTime}} - new start time
	* {{Location}} - initial location
	* {{NEWLocation}} - new location

Regions #scheduleChange - #endScheduleChange and #locationChange - #endlocationChange are used to conditionally display text. E-mail notification will contain text in those regions depending on what has been changed: schedule date/time, location or both. 

.. _N1.8:

*N1.8 Schedule reminder*
***************************

.. note:: This notification is periodically sent to learners to remind them of an upcoming schedule. The notification will be sent 3 days before the schedule start date. It can be configured how frequently to send the notification: every day, on selected day of the week or on selected day of the month. 

Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learner's first name
	* {{ActivityName}} - classroom/virtual classroom activity name
	* {{EducationName}} - course name
	* {{StartDate}} - schedule start date
	* {{StartTime}} - schedule start time
	* {{Location}} - schedule location

.. _N1.11:

*N1.11 Reminder for unfinished courses* 
*****************************************

.. note:: This notification is periodically sent to learners to remind them they have an unfinished course with due date coming soon. The notification will be sent 3 days before the date the course is expected to be completed. It can be configured how frequently to send the notification: every day, on selected day of the week or on selected day of the month. 

Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learner's first name
	* {{EducationName}} - name of the course
	* {{DueDate}} - the date on which the course is expected to be completed
	
If there is more than one unfinished course in user's learning plan, all courses and their belonging due dates will be listed inside region #educations- #end.

.. _N1.12:

*N1.12 Notification of schedule assignment to the lecturer*
*************************************************************

This message is sent to schedule instructors when they are assigned a schedule in a course.
Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - schedule instructor's first name
	* {{EducationName}} - name of the course
	* {{StartDate}} - schedule start date
	* {{StartTime}} - schedule start time
	* {{EndTime}} - schedule end time
	* {{Location}} - schedule location
	* {{EducationUrl}} - link to the course the schedule is related to

.. _N1.14:

*N1.14 Notification of completed course*
******************************************

This message is sent to learners when they complete the course.
Variables that can be used in the body of this e-mail notification are:

	* {{FirstName}} - learner's first name
	* {{EducationName}} - name of the course that was completed
	* {{EducationFinishedDate}} - date on which the course was completed

.. note:: This notification will have a certificate of completion attached to it if the course settings include certificate generation. Also, in the settings for this notification, toggle button **Send attachment** must be set to *ON*.

View E-mail Notification History
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. In the **System settings** section on the **Manage** page click **E-mail notifications** tile.
#. **E-mail notification** page is shown containing three sections: **E-mail service settings**, **E-mail notification settings** and **E-mail notification history** .
#. Click on **E-mail notification history**.
#. List of all E-mail notifications that have been sent is displayed below. 
#. For each notification sent the following data is displayed in the list: Name (type) of notification, recepient's e-mail address, status and time when the notification was sent.
#. Clicking on *Details* icon in the **Actions** column enables you to see complete body of the notification sent.
