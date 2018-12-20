.. _product_updates:


Product Updates
================

Performa 365 v2.0.15
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 12/19/18

New:

* User interface customization
   The appearance of the application can now be modified to better suit your company's visual identity. Customization includes changing   the header color and adding the company's logo.
   
   
Fixed:

* Redirecting upon exam completion
   After finishing an exam, the learner is now redirected to the activities page of the corresponding course.
   

Performa 365 v2.0.14
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 12/01/18

Improved:

* Schedule enrollment
   When users successfully enroll into schedule, they will be redirected to the activities page of the related course.
   
   
Fixed:

* Classroom attendace
   Total number of enrolled attendees is now displayed correctly.
   

Performa 365 v2.0.13
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 11/21/18

Improved:

* Tenant configuration
   Some features have been removed to simplify the process of creating/editing application tenants.
   
* Links to online manual
   Sections of application have been connected to corresponding manual chapters via links.
   

Performa 365 v2.0.12
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 11/06/18

Improved:

* Schedule details (on classroom or virtual classroom activity) 
   Both enrolled users and users on the waiting list are now displayed in ascending order by enrollment date.
   
* HTML5 activity 
   When adding/editing HTML5 type of activity, user is provided with a link to the manual chapter explaining the process in more detail. There is also a message explaining that placing new .zip file in the drag-and-drop control will overwrite the existing .zip file. If changes are made in other fields and this control is left empty, the existing .zip file will remain active.
   
* Exam activity tile
   Exam details and completion message have been updated with more clear explanation.
   

Performa 365 v2.0.11
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 10/22/18

New:

* Waiting list automatic enrollment
   Users on waiting lists will be enrolled to schedule automatically if the seats become available.
   

Performa 365 v2.0.10  
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 10/14/18

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


Performa 365 v2.0.9
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 09/18/18


Fixed:

* Exam attempt
   Fixed bug where users couldn't restart exam after failing when unlimited attempts were enabled.

* Upcoming activities on home page
   Activities are now properly displayed in the "Upcoming activities" section on the home page.
   
* Manage link visibility
   Assignment Admins can no longer access "Manage" section of application.

..


Performa 365 v2.0.8
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 07/25/18


Fixed:

* Email notifications
   If a certificate is created after successful course completion, auto-generated email sent to users will remind them that the certificate can be found on their user profile.

..


Performa 365 v2.0.7
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 07/10/18

New:

* Clone course functionality added
   New functionality creates a copy of an existing course. Cloned course has new name, activities and other data remain the same.      Enrolled learners, schedules and documents are not cloned.
* Email notifications
   Email is sent to administratively enrolled/disenrolled users. If a course has due date, administratively enrolled learners will receive an email as a reminder. Learners who are self-enrolled in a course will receive email notifications as a reminder for upcoming activities.

..


Performa 365 v2.0.6
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 05/14/18


New:

* New report added
   Learners' test results are now displayed in new report. 

..



Performa 365 v2.0.5
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 04/24/18


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



Performa 365 v2.0.4
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 11/28/17


Fixed:

* User profile image
   Crop image tool available only when user uploads new image
* Enrolled status on education tile
   Fixed bug where unenrolled education has enrolled status displayed on education tile.


..



Performa 365 v2.0.3
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 11/14/17

New:

* Health Check Service
    Health Check Service implemented for application monitoring.

Fixed:

* Program (de)activate and delete functionality
    Activation of program is not allowed if at least one education is deactivated.
* Edit education - current image display
    Added options for displaying current image and uploading new one.

..



Performa 365 v2.0.2
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 10/09/17


Fixed:

* YouTube links
    Fixed YouTube links on video activities.

..



Performa 365 v2.0.1
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Release date: 09/22/17


New:

* Tenant management
    Configuration wizard implemented for managing application tenants.
* Release history
    Release history added.
