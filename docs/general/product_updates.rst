.. _product_updates:


Product Updates
================


Performa 365 v2.0.11  (10/22/2018)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 10/22/2018

New:

* Waiting list automatic enrollment
   Users on waiting lists will be enrolled to schedule automatically if the seats become available.
   

Performa 365 v2.0.10  (10/14/2018)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:
   
* RPT-ER01 Course Rating report
   Report to show ratings for a selected course.


Improved:

* Course activity tile
   Course activity tile now shows if the activity is required, optional, skipped or overdue.

* Survey results
   Survey results can now be easily accessed from actions in the activity management (Course Manage -> Activities).

* Documentation - E-mail Notifications
   Detailed documentation about e-mail notification service configuration and e-mail notification templates. 

* Documentation - User Management
   Detailed documentation about user management for both supported auth providers (Azure AD and ADFS), including details on external user management.


Fixed:

* Exam results
   Learner's exam are not displayed correctly in Course > Manage > Enrolled learners sections.
   
* Survey opening
   Problem with opening a survey if survey title contains special characters, such as +.


Removed:

* Office mix
   Office mix activityhas been removed  due to Microsoft's announcement about  `Office Mix end of service <https://support.office.com/en-us/article/important-information-about-office-mix-preview-end-of-service-c1c04f84-a7bb-4602-9645-258017155258>`_.
      
..


Performa 365 v2.0.9  (9/18/2018)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fixed:

* Exam attempt
   Fixed bug where users couldn't restart exam after failing when unlimited attempts were enabled.

* Upcoming activities on home page
   Activities are now properly displayed in the "Upcoming activities" section on the home page.
   
* Manage link visibility
   Assignment Admins can no longer access "Manage" section of application.

..


Performa 365 v2.0.8  (07/25/2018)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fixed:

* Email notifications
   If a certificate is created after successful course completion, auto-generated email sent to users will remind them that the certificate can be found on their user profile.

..


Performa 365 v2.0.7  (7/10/2018)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* Clone course functionality added
   New functionality creates a copy of an existing course. Cloned course has new name, activities and other data remain the same.      Enrolled learners, schedules and documents are not cloned.
* Email notifications
   Email is sent to administratively enrolled/disenrolled users. If a course has due date, administratively enrolled learners will receive an email as a reminder. Learners who are self-enrolled in a course will receive email notifications as a reminder for upcoming activities.

..


Performa 365 v2.0.6  (05/14/18)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* New report added
   Learners' test results are now displayed in new report. 

..



Performa 365 v2.0.5  (04/24/18)
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

..



Performa 365 v2.0.4  (11/28/17)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fixed:

* User profile image
   Crop image tool available only when user uploads new image
* Enrolled status on education tile
   Fixed bug where unenrolled education has enrolled status displayed on education tile.


..



Performa 365 v2.0.3  (11/14/17)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* Health Check Service
    Health Check Service implemented for application monitoring.

Fixed:

* Program (de)activate and delete functionality
    Activation of program is not allowed if at least one education is deactivated.
* Edit education - current image display
    Added options for displaying current image and uploading new one.

..



Performa 365 v2.0.2  (10/9/17)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Fixed:

* YouTube links
    Fixed YouTube links on video activities.

..



Performa 365 v2.0.1  (9/22/17)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

New:

* Tenant management
    Configuration wizard implemented for managing application tenants.
* Release history
    Release history added.
