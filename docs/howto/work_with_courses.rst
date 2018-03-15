Work With Courses
======================

Working With Courses as an Administrator
*********************************************
**********************************************


Adding a New Course
********************

Application roles needed to add a new course: :ref:`Catalog Administrators <catalog_administrator>`.

A new course is added by clicking *New Course* action button on the **Catalog** page. This button is only visible to Catalog Administrators.

..
The *New Course* button opens a three-step wizard. All required fields are marked with an asterisk and must be filled in to continue to the next step.

**Step one**

#. **Name** is required and must be unique. The system will notify the user if a course with the same name already exists.
#. **Description** is optional. It is aimed at learners and displayed on course's homepage. Therefore, it should contain information such as curriculum, requirements, duration, etc.
#. **Business areas** is required. More than one business area can be selected when creating new course. To be able to choose business areas from the list, they must first be created by :ref:`Education Process Administrator <education_process_administrator>`. To learn more go to: :ref:`How to > Manage Business Areas <manage_business_areas>`.
#. **Primary delivery model** describes how the course is executed. It is a required, single choice field. The catalog administrator must choose between three options: *classroom*, *virtual (e-learning)* and *blended learning*.
#. **Languages** are optional and more than one can be chosen from the drop-down menu.
#. **Owners** are selected by typing at least 3 characters in the text field to start the search. Search returns display name and e-mail of the users. More than one user can be selected from this list as course owner. This field is required.
#. **Visibility** is a required field which determines how the course is displayed in the catalog. To learn more visit :ref:`How to > Use the catalog <courses>`.
#. **Title image** is displayed on the course page and in the course tile on the catalog page. It is optional and can be up to 10MB in size.
#. **Status** can be set to either *ON* or *OFF*. Courses with status set to *ON* are active and present in the course catalog, setting the status to *OFF* will deactivate the course and it will be visible in the **Catalog** only to Catalog Administrators. A course cannot be deactivated if there are learners enrolled to it.

**Step two**

#. **Discussion group** field is optional. It can be filled with the feed ID of the dedicated yammer group.
#. **Course owners can enroll learners** indicates that learners can be enrolled to the course by both Course owners and Enrollment administrators (if set to *ON*) or only by Enrollment administrators (if set to *OFF*). It is set to *ON* by default.
#. When **Sequential activities** is set to *ON* learners must take learning activities in the predefined order. Setting it to *OFF* will allow learners to take learning activities in the arbitrary order.
#. **Completion confirmation** is required. It should be set to either *Learner* (learners individually confirm course completion) or *Learner or education owner* (learners or education owner confirm course completion).
#. If **Certificate generation** is set to *ON*, learner will be given a certificate after the successful course completion. If certificates of completion are not given to learners, it should be set to *OFF*. 
#. **Template** is visible only if **Certificate generation** is set to *ON*. Template is required and is chosen from the drop-down menu. To be able to choose a template from the list, they must first be added by :ref:`Education Process Administrator <education_process_administrator>`. To learn more go to: :ref:`How to > Manage Document Templates <manage_document_templates>`.

**Step three**

#. If **All activities completed** is course's success criteria, this toggle button should be set to *ON*. 
#. **All activities successfully completed** can be set to either *ON* or *OFF*. If **All activities completed** is set to *OFF*, this also will be set to *OFF*.
#. **Scored points percentage** can be chosen as success criteria by setting it to *ON*. In that case, a new control appears for entering the required points percentage.

Clicking the **Finish** action button after completing these steps will create a new course.

Editing a Course
*****************

Application roles needed to edit a course: 
* :ref:`Catalog Administrators <catalog_administrator>`
* :ref:`Education Owner <education_owner>`

#. Select the course from the **Catalog** page. The course can be found using search and filtering options on the **Catalog** page.
#. Click the tile of the course you wish to edit.
#. You will be redirected to the course page. 
#. Each course page has a sub-menu with following menu items: **Home**, **Activities**, **Documents** and **Manage**. **Manage** is only visible to Catalog administrators, Education owners and users who are instructors in at least one course schedule.
#. Click on **Manage** menu item to open a dropdown menu. 
#. Choose **Edit course**
#. A three-step wizard opens, identical to the one for adding a new course. 

.. note:: When editing a course, Catalog Adminitrator or Education owner can change almost anything they wish, but changes that concern learners will only be applied to those enrolled after the update. Also, a course cannot be deactivated if there are learners enrolled to it.


Deleting a Course
******************

#. Choose **Delete course** from the **Manage** dropdown menu in course's submenu.
#. A dialog window opens asking the user to confirm the action. 
#. Click *Yes*.

.. note:: Deleting a course will unenroll all enrolled learners and delete the related learning materials.

.. note:: You will not be able to delete a course if there is at least one learner enrolled by assignment or at least one learner who has completed the course. 

