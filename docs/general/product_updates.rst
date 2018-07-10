.. _product_updates:

Product Updates
================

07/10/2018

Performa 365 v2.0.6
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* Clone course functionality added
   New functionality creates a copy of an existing course. Cloned course has new name, activities and other data remain the same.      Enrolled learners, schedules and documents are not cloned.
* Email notifications
Email is sent to administratively enrolled/disenrolled users. If a course has due date, administratively enrolled learners will receive an email as a reminder.
   Learners who are self-enrolled in a course will receive email notifications as a reminder for upcoming activities.


Performa 365 v2.0.6
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* New report added
   Learners' test results are now displayed in new report. 

04/24/18

Performa 365 v2.0.5
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* User Sync Service
   User Sync service is available for AAD identity provider. It is executed once per day and syncs all users from the mapped user groups to Performa 365.

Fixed:

* Exam questions scroller
   Scroll buttons replaced with slider for faster navigation.
* User management "Add" action
   Adding users in "Manage Users" (only available for AD FS identity provider) is disabled if "User management allowed" is set to "OFF" in tenant configuration. 

Changed:

* Course sidebar
   Course status replaced with progress bar, success replaced with emojis. Clicking on an emoji gives additional info.
* Health Analyzer Update
   Health Analyzer configured to check User Sync.


11/28/17

Performa 365 v2.0.4
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fixed:

* User profile image
   Crop image tool available only when user uploads new image
* Enrolled status on education tile
   Fixed bug where unenrolled education has enrolled status displayed on education tile.



11/14/17

Performa 365 v2.0.3
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* Health Check Service
    Health Check Service implemented for application monitoring.

Fixed:

* Program (de)activate and delete functionality
    Activation of program is not allowed if at least one education is deactivated.
* Edit education - current image display
    Added options for displaying current image and uploading new one.



10/9/17

Performa 365 v2.0.2
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fixed:

* YouTube links
    Fixed YouTube links on video activities.


9/22/17

Performa 365 v2.0.1
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* Tenant management
    Configuration wizard implemented for managing application tenants.
* Release history
    Release history added.
