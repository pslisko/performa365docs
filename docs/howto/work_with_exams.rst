.. _exams:

Work with Exams
================

Application roles needed to manage exams: 

* :ref:`Exam Admin <exam_administrator>`
* :ref:`Exam Creator <exam_creator>`

About
******

Exam Admins and Exam Creators can view exams on the **Catalog** page by clicking on the action button **Exams** in the submenu. This button is only visible to these application roles. Exam Administrators can see all available exams, Exam Creators can only see exams if they have ownership to them.

..
The ribbon below the submenu contains action button *Add exam*. The right side of the ribbon has icons for sorting exams by name and opening a panel with search and filtering options. This panel also has a checkbox to show/hide deactivated exams.


Add an Exam
**************

Both Exam Admins and Exam Creators can create exams. 

#. Click on **Catalog** in the main navigation bar. 
#. On the **Catalog** page choose **Exams (admin)** in the submenu.
#. Click on action button **Add exam** in the ribbon.
#. **Add exam** form opens.
#. Fill in all required fields and click **Save**.
#. After successfully adding the exam, you will be redirected to the **Exams** page. Your exam will be added to the list of exams.

Edit an Exam
**************

Exam Admins can edit all exams, Exam Creators can only edit an exam if they have ownership to the exam.

#. Click on **Catalog** in the main navigation bar. 
#. On the **Catalog** page choose **Exams (admin)** in the submenu.
#. List of exams is displayed on the page. Each exam is represented by the tile with the menu icon in the upper right corner. Clicking on this icon opens a dropdown menu.
#. Choose *Edit* from the dropdown menu of the exam you wish to update.
#. Change the desired fields and click **Save**.
#. After successfully editing the exam, you will be redirected to the **Exams** page.

.. note:: If an exam is deactivated (**Status** is set to *OFF*) enrolled learners will still be able to take the exam but it will not be possible to create new course activities using this exam. 

Delete an Exam
**************

Exam Admins can delete all exams, Exam Creators can only delete an exam if they have ownership to the exam.

#. Click on **Catalog** in the main navigation bar. 
#. On the **Catalog** page choose **Exams (admin)** in the submenu.
#. List of exams is displayed on the page. Each exam is represented by the tile with the menu icon in the upper right corner. Clicking on this icon opens a dropdown menu.
#. Choose delete from the dropdown menu of the exam you wish to delete.
#. A dialog window opens asking the user to confirm the action.
#. Click **Yes**.
#. After successfully deleting the exam, you will be redirected to the **Exams** page.

.. note:: An exam which is a part of a course activity cannot be deleted. 

..
Work with Question Groups
***************************
***************************

Each exam consists of one or more question groups (pools). Question groups are used to group questions by topic or difficulty level. This will allow multiple exam configurations, such as randomization of question from all available questions groups etc.   

.. attention:: To be able to create exam questions, at least one active question group must be created first.

Add a Question Group
*********************

Exam Admins can add question groups to all exams, Exam Creators can only add question groups to an exam if they have ownership to the exam.

#. Click on **Catalog** in the main navigation bar. 
#. On the **Catalog** page choose **Exams (admin)** in the submenu.
#. List of exams is displayed on the page. Each exam is represented by the tile with the menu icon in the upper right corner. Clicking on this icon opens a dropdown menu.
#. Choose *Details* from the dropdown menu of the exam you wish to add question groups to.
#. **Exams > Question Groups** page opens. This page has all available question groups displayed as a list of tiles. Below the tiles there is **Add new question group** action button.
#. Click **Add new question group**.
#. **New exam group** wizard opens. The first step asks you to enter **Name** and **Description**. Toggle button **Status** is set to *ON* by default. Setting it to *OFF* will disable the question group. That means you will be able to add questions to this question group, but you won't be able to add questions from it to exam activities.
#. Fill in the fields of the first step and click **Next** to continue to the second step.
#. Exam questions are added it the second step. If the exam group doesn't have any questions yet, only action button **Add question** will be displayed on the top of the page.
#. Click **Add question** to add new question to the question group.
#. A new form opens for each individual question. You can add as many questions as you like to each question group.
#. Enter the text of your question in the textbox **Question text**. This field is required.
#. You can add attachments to each question by clicking **Add attachments** action button. Attached files can be up to 10MB in size. 
#. To assign points for correct answer and/or negative points for incorrect answer, enter the value by clicking numeric up-and-down control or typing it into the box. Please note that you must also enter "-" before the number for negative points if you enter the value manually.
#. Choose **Question Type** from the drop-down menu. There are three types you can choose from: **Single choice**, **Multiple choice** and **Free text**.
#. If you choose **Single choice**, input box opens for entering question answers. Single choice questions must have one answer with radio button selected. All answers must have values. To add more answers click **Add answer**.
#. If you choose **Multiple choice**, input box opens for entering question answers. Multiple choice questions must have at least one answer with checkbox selected. All answers must have values. To add more answers click **Add answer**.
#. If you choose **Free text**, input box opens for entering question answers. Free text questions must have at least one answer with some text as value. To add more answers click **Add answer**.
#. Add as many questions as you like by clicking **Add question** at the bottom of the wizard.
#. Each question has **Enabled** checkbox in the upper left corner. This checkbox is selected by default. Unchecking it will hide the question and it won't be displayed when creating exam activity with this question group.
#. To delete individual questions click the trash bin icon in the upper right corner.
#. You can change the order of your questions by clicking on arrows in the upper right corner.
#. When you are done adding questions, click **Finish**. New question group will be added to exam's question groups.

Edit a Question Group
*********************

Exam Admins can edit question groups of all exams, Exam Creators can only edit question groups of an exam if they have ownership to the exam.

#. Click on **Catalog** in the main navigation bar. 
#. On the **Catalog** page choose **Exams (admin)** in the submenu.
#. List of exams is displayed on the page. Each exam is represented by the tile with the menu icon in the upper right corner. Click on this icon to open a dropdown menu.
#. Choose *Details* from the dropdown menu to edit exam's question groups.
#. **Exams > Question Groups** page opens. This page has all available question groups displayed as a list of tiles. Each tile has menu icon in the upper right corner. Find the question group you wish to edit and click on it's menu icon to open a dropdown menu.
#. Choose *Edit* from the dropdown menu.
#. **Edit exam group** wizard opens. This wizard is identical to the one for adding new question groups.
#. You can change general information in the first step as well as questions within this question group in the second step.
#. When you are done, click **Finish**. The question group will be updated.

.. note:: Change of settings and questions within question group does not affect previously created exams.


Delete a Question Group
*********************

Exam Admins can delete question groups of all exams, Exam Creators can only delete question groups of an exam if they have ownership to the exam.

#. Click on **Catalog** in the main navigation bar. 
#. On the **Catalog** page choose **Exams (admin)** in the submenu.
#. List of exams is displayed on the page. Each exam is represented by the tile with the menu icon in the upper right corner. Click on this icon to open a dropdown menu.
#. Choose *Details* from the dropdown menu of the exam you wish to edit question groups.
#. **Exams > Question Groups** page opens. This page has all available question groups displayed as a list of tiles. Each tile has menu icon in the upper right corner. Click on this icon to open a dropdown menu.
#. Choose *Edit* from the dropdown menu.
#. **Edit exam group** wizard opens. This wizard is identical to the one for adding new question groups.
#. You can change general information in the first step as well as questions for this group in the second step.
#. When you are done, click **Finish**. The question group will be updated.

.. note:: A question group which is a used in an active course activity cannot be deleted. 
