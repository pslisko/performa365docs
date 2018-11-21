.. _courses:

Work with Courses
======================

.. _add_course:

Add a New Course
********************

Application roles needed to add a new course: :ref:`Catalog Admin <catalog_administrator>`.

A new course is added by clicking *New Course* action button on the **Catalog** page. This button is only visible to Catalog Admins.

..
The *New Course* button opens a three-step wizard. All required fields are marked with an asterisk and must be filled in to continue to the next step.

**Step one**

#. **Name** is required and must be unique. The system will notify the user if a course with the same name already exists.
#. **Description** is optional. It is aimed at learners and displayed on course's homepage. Therefore, it should contain information such as curriculum, requirements, duration, etc.
#. **Business areas** is required. More than one business area can be selected when creating new course. To be able to choose business areas from the list, they must first be created by :ref:`Education Process Admin <education_process_administrator>`. To learn more go to: :ref:`How to > Manage Business Areas <manage_business_areas>`.
#. **Primary delivery model** describes how the course is executed. It is a required, single choice field. The catalog admin must choose between three options: *classroom*, *virtual (e-learning)* and *blended learning*.
#. **Languages** are optional and more than one can be chosen from the drop-down menu.
#. **Owners** are selected by typing at least 3 characters in the text field to start the search. Search returns display name and e-mail of users. More than one user can be selected from this list as a course owner. This field is required.
#. **Visibility** is a required field which determines how the course is displayed in the catalog. To learn more visit :ref:`How to > Use the catalog <courses>`.
#. **Title image** is displayed on the course page and in the course tile on the catalog page. It is optional and can be up to 10MB in size.
#. **Status** can be set to either *ON* or *OFF*. Courses with status set to *ON* are active and present in the course catalog, setting the status to *OFF* will deactivate the course and it will be visible in the **Catalog** only to Catalog Admins. A course cannot be deactivated if there are learners enrolled to it.

**Step two**

#. **Discussion group** field enables you to connect the course with an existing Yammer group. If this is needed, enter the Yammer group feedID (a numeric value found in the URL when Yammer group is opened).
#. **Course owners can enroll learners** indicates that learners can be enrolled in the course by both Course owners and Enrollment administrators (if set to *ON*) or only by Enrollment administrators (if set to *OFF*). This toggle button is set to *ON* by default.
#. When **Sequential activities** is set to *ON* learners must take learning activities in the predefined order. Setting it to *OFF* will allow learners to take learning activities in the arbitrary order.
#. **Completion confirmation** is required. It should be set to either *Learner* (learners individually confirm course completion) or *Learner or course owner* (course completion can be confirmed by course owner as well).
#. If **Certificate generation** is set to *ON*, learner will get an auto-generated certificate after the successful course completion. If certificates of completion should not be created, set this option to *OFF*. 
#. **Template** is visible only if **Certificate generation** is set to *ON*. In that case, a template is required and is chosen from the drop-down menu. To be able to choose a template from the list, they must first be added by :ref:`Education Process Admin <education_process_administrator>`. To learn more go to: :ref:`How to > Manage Document Templates <manage_document_templates>`.

**Step three**

This steps defines success criteria for a course. To finish the course successfully, learner must meet all criteria for the list below which are set to *ON*. At least one criteria must be set to *ON*.

#. If **All activities completed** is course's success criteria, this toggle button should be set to *ON*. 
#. **All activities successfully completed** can be set to either *ON* or *OFF*. If **All activities completed** is set to *OFF*, this also will be set to *OFF*.
#. **Scored points percentage** can be chosen as success criteria by setting it to *ON*. In that case, a new control appears for entering the required percentage.
#. Click **Finish**.

.. note:: Course success is different from course completion. Course can be completed as soon as all mandatory activities are finished. However, it will be successful only when all success criteria are met. The status indicator next to the progress bar on the course page shows the details about course comletion and success at all times.  

.. _edit_course:

Edit a Course
*****************

Application roles needed to edit a course: 

* :ref:`Catalog Admin <catalog_administrator>`

* :ref:`Course Owner <course_owner>`

#. Go to **Catalog** > **Courses**. Courses can be found using search and filtering options on the **Catalog** page.
#. Click the tile of the course you wish to edit.
#. You will be redirected to the course page. 
#. Each course page has a sub-menu with following menu items: **Home**, **Activities**, **Documents** and **Manage**. **Manage** is only visible to Catalog admins, Course owners and users who are instructors in at least one course schedule.
#. Click on **Manage** menu item to open a dropdown menu. 
#. Choose **Edit course** from the dropdown menu.
#. A three-step wizard opens, identical to the one for adding a new course. 
#. Complete the wizard and click **Finish**.

.. note:: When editing a course, Catalog Admin or Course Owner can change almost any option, however changes that concern learners will only be applied to newly enrolled learners (enrolled after the change).

.. _delete_course:

Delete a Course
******************

Application roles needed to delete a course: 

* :ref:`Catalog Admin <catalog_administrator>`


#. Go to **Catalog** > **Courses**. 
#. Click the tile of the course you wish to delete.
#. You will be redirected to the course page. 
#. Choose **Delete course** from the **Manage** dropdown menu in course's submenu.
#. A dialog window opens asking the user to confirm the action. 
#. Click *Yes*.

.. note:: Deleting a course will unenroll all enrolled learners and delete the related learning materials.

.. note:: You will not be able to delete a course if there is at least one learner enrolled by assignment or at least one learner who has completed the course. 

Clone a Course
******************

.. tip::  With the cloning process, it is possible to quickly generate new course according to the cloning course template. 

Application roles needed to clone a course: 

* :ref:`Catalog Admin <catalog_administrator>`


#. Go to **Catalog** > **Courses**. 
#. Click the tile of the course you wish to clone.
#. You will be redirected to the course page. 
#. Choose **Clone course** from the **Manage** dropdown menu in course's submenu.
#. A dialog window opens asking the user to enter a name for the course being cloned. 
#. Enter the name for the new course and click *Confirm*.

.. note:: Cloned course will have all the attributes and activities of the course being cloned but will not have its documents or schedules (for physical or virtual classroom activities). Survey type of activities cannot be cloned either.

View All Enrolled Learners
****************************

#. Go to **Catalog** > **Courses**. 
#. Click the tile of the course you wish to view learners from.
#. You will be redirected to the course page. 
#. Choose **Enrolled Learners** from the **Manage** dropdown menu in course's submenu.
#. **Learners** page opens containing list of learners enrolled in this course.
#. To view learner's details click on *Details* in the **Action** column.
#. User's details panel opens below containing information on user's points scored, success and status.

Work with Documents
****************************

Each course contains its own document repository. Course owners and instructors can use this repository to upload course materials while learners can view/download them.

Application roles needed to work with documents: 

* :ref:`Course owner <course_owner>`
* :ref:`Instructor <instructor>`


View Documents as a Learner
******************************

#. Go to **Catalog** > **Courses**. Courses can be found using search and filtering options on the **Catalog** page.
#. Click the tile of your enrolled course.
#. You will be redirected to the course page. 
#. Each course page has a sub-menu with following menu items: **Home**, **Activities**, **Documents** and **Manage**. **Manage** is only visible to catalog admins, course owners and instructors (in case of virtual or classic classroom activities).
#. Click on **Documents**. 
#. **Documents** page opens containing all available files for that course. Each document is represented by the tile.
#. Click on the document tile to view/download the content.


Work With Documents as a Course Owner or Instructor
****************************************************

#. Go to **Catalog** > **Courses**. Courses can be found using search and filtering options on the **Catalog** page.
#. Click the tile of your enrolled course.
#. You will be redirected to the course page. 
#. Each course page has a sub-menu with following menu items: **Home**, **Activities**, **Documents** and **Manage**. **Manage** is only visible to Catalog admins, Course owners and users who are instructors in at least one course schedule.
#. Click on **Documents**. 
#. **Documents** page opens containing all available files for that course. Each document is represented by the tile.
#. Course owners and instructors have access to the corresponding SharePoint library. In the course sidebar on the right there is a section "Manage learning materials". Inside this section there is a link button "Open the SharePoint library." Course owner can upload any kind of learning material and create additional subfolders. Instructors can only upload materials to a pre-created folder for their classroom schedule.
#. Click on the link button "Open the SharePoint library" to open the location on SharePoint and manage learning materials for this course.

