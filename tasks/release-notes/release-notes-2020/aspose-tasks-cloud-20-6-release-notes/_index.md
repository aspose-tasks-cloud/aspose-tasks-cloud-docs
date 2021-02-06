---
title: "Aspose.Tasks Cloud 20.6 Release Notes"
type: docs
url: /aspose-tasks-cloud-20-6-release-notes/
weight: 20
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 20.6](https://products.aspose.cloud/tasks/cloud)

{{% /alert %}} 
## **Major Features**
- Render comments when saving as image, HTML or PDF
- Option to use username and password to connect Project Online (Server)
- Add assignments to project file with specifying its cost
- Accelerated adding new tasks to project, when calculation mode is set to automatic
- Ability to add project in Microsoft Project Server
- Improved performance of autorecalculation for large sets of tasks and timephased data calculation
- Support reading of shared resource assignments
## **Public API and Backwards Incompatible Changes**
The following API endpoints were added:

|**API endpoints**|**Description**|
| :- | :- |
|POST <br>https://api.aspose.cloud/v3.0/tasks/projectOnline/{siteUrl}/{name}|Creates new project in Project Server\Project Online instance|
|PUT <br>https://api.aspose.cloud/v3.0/tasks/projectOnline/{siteUrl}/{name}|Updates existing project in Project Server\Project Online instance. The existing project will be overwritten|

*The following objects and properties were added:*

|**Objects/Properties**|**Description**|
| :- | :- |
|Task.Warning|Represents the flag which indicates that task has schedule discrepancies|
|DTO object ProjectServerSaveOptionsDTO|Allows to specify additional options when project is saved to Project Server or Project Online|
|ProjectServerSaveOptionsDTO.ProjectName|Sets name of a project which is displayed in Project Server \ Project Online projects list. Should be unique within Project Server \ Project Online instance. Is the value is omitted, the value of Prj.Name property will be used instead|
|ProjectServerSaveOptionsDTO.ProjectGuid|Sets unique identifier of a project. Should be unique within Project Server \ Project Online instance|
|ProjectServerSaveOptionsDTO.Timeout|Gets or sets timeout used when waiting for processing of save project request by a Project Server's queue processing service. The default value for this property is 1 minute. The processing time may be longer for large projects or in case when Project Server instance is too busy responding to other requests within Project Server \ Project Online instance|
|ProjectServerSaveOptionsDTO.PollingInterval|Sets interval between queue job status requests. The default value is 2 seconds|
|ResourceAssignment.Guid|Global unique identifier of an assignment|
|DocumentProperty CustomDateFormat|Project view custom date format. Used to format dates when DateFormat property is set to Aspose.Tasks.DateFormat.Custom|

*The following API endpoints were extended:*

|**API endpoints**|**Description**|
| :- | :- |
|PUT <br>https://api.aspose.cloud/v3.0/tasks/{name}/importfromprojectonline|This route now accepts optional argument "userName" paired with a new header "x-sharepoint-password" which contains username and password values from your sharepoint site to get access to project server (online). Use this auth flow instead of passing a token if you don't have it|
|GET <br>https://api.aspose.cloud/v3.0/tasks/projectOnline/projectList|This route now accepts optional argument "userName" paired with a new header "x-sharepoint-password" which contains username and password values from your sharepoint site to get access to project server (online). Use this auth flow instead of passing a token if you don't have it|
|POST <br>https://api.aspose.cloud/v3.0/tasks/{name}/assignments|This route now accepts new optional argument "cost" to add cost for a new assignment|

