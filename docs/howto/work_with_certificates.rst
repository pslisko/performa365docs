Work With Certificates
=======================

About
*******

Certificates are used to create personalized documents given to users after successfuly completing a course. They are optional and defined when adding/editing a course by setting **Certificate generation** to *ON* in the :ref:`second step of **Add Course** wizard <add_course>`.

Create a Certificate
*********************

To make a document you will be using in your course as a certificate of completion, you need to have an MS Word document (.doc or .docx type of file). This file needs to be uploaded to :ref:`Templates <manage_document_templates>` by :ref:`Education Process Admin <education_process_administrator>`.

This file must contain some variables to be able to generate personalized content for each users. Variables are typed in the document surrounded by double curly brackets, as explained below.

Variables used for generated document
**************************************

Certificate template can contain following variables:

* {{EducationName}} – education name
* {{UserDisplayName}} – user's display name
* {{CompletionDate}} – date of education completion
* {{CompletionTime}} – time of education completion
* {{EducationDurationDays}} – total education duration in days (rounded)
* {{EducationDurationHours}} – total education duration in days (rounded)
* {{EducationDurationHoursMinutes}} – total education duration, in hours and minutes

View Certificates as a Learner
******************************

Learners who have successfuly finished a course that 
