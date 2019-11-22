Table of Contents
=================
 * 4.2 [Project Creation Page](##42-project-creation-page)
   * 4.2.1 [Description](###421-description)
   * 4.2.2 [Stimulus/Response Sequences](###422-stimulus-response-sequences)
   * 4.2.3 [Functional Requirements](###423-functional-requirements)
     * 4.2.3.1 [Create Project button](#4231-create-project-button)
     * 4.2.3.2 [Create Job Template button](#4232-create-job-template-button)
     * 4.2.3.3 [Create Stage button](#4233-create-stage-button)
     * 4.2.3.4 [View button](#4234-view-button)
     * 4.2.3.5 [Clear button](#4235-clear-button)
     * 4.2.3.6 [Copy project config button](#4236-copy-project-config-button)
     * 4.2.3.7 [Paste project config button](#4237-paste-project-config-button)

## 4.2	Project Creation Page
### 4.2.1	Description
- Path :  /manager/ projectForm
- Access : Managers
- In Manager Role option to create project
### 4.2.2	Stimulus/Response Sequences
-	Create Project button : Provide create project button to create project
-	Create Job Template button : Provide create job template button to create job template
-	Create Stage button : Provide create stage button to create stage
-	Edit button : Provide edit button to update job template and stage template
-	Delete button : Provide delete button for job template and stage template
-	Copy project config button : Provide copy project config button
-	Paste project config button : Provide paste project config button
-	Clear button : Provide the clear button
### 4.2.3	Functional Requirements
#### 4.2.3.1	Create Project button
Click on create project button should display the page.
To create project the mandatory fields are:
-	Prefix : To be entered, varchar with characters
-	Project Name : To be entered
-	Client : To be entered
-	Project Manager : Drop downs of project manager should be displayed
-	Job Template : To create the project there should be atleast one job template
-	Stage Template : To create job template there should be atleast one stage template
-	Create project button : By clicking this button, application should check for mandatory entries and display appropriate message Project Created Successfully
#### 4.2.3.2	Create Job Template button
Click on create job template button should display create job template page.
To create job template the mandatory fields are:
-	Job Template Name : To be entered
-	SLA Days : To be entered numeric
-	Job Template Fields : Field name and Field type
-	The field name to be entered
-	The field type drop downs should be displayed. It consists of text field, numeric field, float field, date field, date + time field and percentage
-	Checkbox : For unique and mandatory there should be checkbox
-	(+) button : Click on this, the row should be added
-	(-) button : Click on this, the row should be deleted
-	Create button : By clicking this button, application should check for mandatory entries and template should be created
-	Cancel button : Click on this, the page should get cancelled
-	Edit : Provide edit for each job template. Click on this button should enable update button and structure to be displayed in editable format
-	Delete : Provide delete for each job template. Click on this button should delete the template
#### 4.2.3.3	Create Stage button
Click on create stage button should display create stage template page.
To create stage template the mandatory fields are:
-	Stage Template Name : To be entered
-	Stage Template Fields : Field name and Field type
-	The field name to be entered
-	The field type drop downs should be displayed. It consists of text field, numeric field, float field, date field, date + time field and percentage
-	Checkbox : Provide checkbox for mandatory, splittable and skippable
-	Stage Outcome Fields : Outcome name and outcome
-	The outcome name to be entered
-	The outcome drop downs should be displayed. It consists of next stage, same stage and complete
-	(+) button : Click on this, the row should be added
-	(-) button : Click on this, the row should be deleted
-	Create button : By clicking this button, application should check for mandatory entries and stage template should be created
-	Cancel button : Click on this, the page should get cancelled
-	Edit : Provide edit for each stage template. Click on this button should enable update button and structure to be displayed in editable format
-	Delete : Provide delete for each stage template. Click on this button should delete stage template
#### 4.2.3.4	View button
-	Provide view button
-	By clicking this button drop downs should be displayed
#### 4.2.3.5	Clear button
-	Provide clear button
-	By clicking this button data should get cleared
#### 4.2.3.6	Copy project config button
-	Provide copy project config button
-	Click on this should copy the project config
#### 4.2.3.7	Paste project config button
-	Provide paste project config button
-	Click on this should display the page
-	Provide submit button
-	Provide clear button
-	Provide close button
