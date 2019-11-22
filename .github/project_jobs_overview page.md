Table of Contents
=================

* 4.1 [Project Jobs Overview Page](#41project-jobs-overview-page)
  * 4.1.1 [Description](#411-description)
  * 4.1.2 [Stimulus /Response Sequences](#412stimulus-response-sequences)
  * 4.1.3 [Functional Requirements](#413functional-requirements)
    * 4.1.3.1 [Search button](#4131search-button)
    * 4.1.3.2 [View all button](#4132view-all-button)
    * 4.1.3.3 [Delete button](#4133delete-button)
    * 4.1.3.4 [Create button](#4134create-button)
    * 4.1.3.5 [Pagination](#4135pagination)
    * 4.1.3.6 [Job template](#4136job-template)
    * 4.1.3.7 [Job list](#4137job-list)
    * 4.1.3.8 [View](#4138view)
    * 4.1.3.9 [Job id](#4139job-id)

## 4.1 Project Jobs Overview Page
### 4.1.1	Description
- Path :  /project/ {project Id}
- Access : Managers, Leaders of project
- Display upto 5 jobs of each template
### 4.1.2	Stimulus/Response Sequences
-	Job list : It displays job template and each job template should display assignee, job id, next stage for each job
-	Search button : Provide search button to search each column
-	Job template : Columns should be rearrangeable
-	View all button : Provide view all button which takes to full list for job template
-	Delete button : Provide delete button for each job
-	Create button : Provide create button to create job in each job template card single or bulk
-	Pagination : Provide the pagination
### 4.1.3	Functional Requirements
#### 4.1.3.1	Search button
Provide search button to search each column.
By clicking this button, application should display search bar below each column.
#### 4.1.3.2	View all button
Provide view all button.
By clicking this button, it takes to full list for job template.
#### 4.1.3.3	Delete button
Provide delete button for each job.
By clicking this button, should able to delete job.
#### 4.1.3.4	Create button
Provide create button to create job in each job template card single or bulk.
By clicking this button, application will check for mandatory entries and display appropriate message to indicate if job was created successfully.
#### 4.1.3.5	Pagination
Provide the pagination to show the entries page wise.
By clicking on this it should display number of entries.
#### 4.1.3.6	Job template
The project has number of job templates.
The columns should be rearrangeable.
#### 4.1.3.7	Job list
The job template should display number of jobs in the job list.
#### 4.1.3.8	View
Provide view for the project in the form of drop downs.
By clicking this it should display number of job template.
#### 4.1.3.9	Job id
Provide job id for each job.
By clicking on this it should display job status page.
