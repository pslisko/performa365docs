Work with Certificates
=======================

About
*******

Certificates are used to create personalized documents given to users after successfuly completing a course. They are optional and defined when adding/editing a course by setting **Certificate generation** to *ON* in the second step of :ref:`Add Course <add_course>` wizard.

Create a Certificate
*********************

To make a document you will be using in your course as a certificate of completion, you need to have an MS Word document (.doc or .docx type of file). This file needs to be uploaded to :ref:`Templates <manage_document_templates>` by :ref:`Education Process Admin <education_process_administrator>`.

This file must contain some variables to be able to generate personalized content for each users. Variables are typed in the document surrounded by double curly brackets, as explained below.

Variables used for generated document
**************************************

Certificate template can contain following variables:

* {{EducationName}} – course name
* {{UserDisplayName}} – user's display name
* {{CompletionDate}} – date of course completion
* {{CompletionTime}} – time of course completion
* {{EducationDurationDays}} – total course duration in days (rounded)
* {{EducationDurationHours}} – total course duration in days (rounded)
* {{EducationDurationHoursMinutes}} – total course duration, in hours and minutes

View Certificates as a Learner
******************************

Learners who have successfuly finished a course and were issued a certificate, can view their certificate by going to **My Profile**.
On the profile page, **Finished Courses** contains list of all completed courses and dates of completion for each course. Courses with ceritificates of completion will have those documents displayed as links **Show certificate**. Clicking on this link will download learner's certificate.
