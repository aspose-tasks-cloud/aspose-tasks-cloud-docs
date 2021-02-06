---
title: "Aspose.Tasks Cloud 19.10 Release Notes"
type: docs
url: /aspose-tasks-cloud-19-10-release-notes/
weight: 20
---
{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 19.10](https://products.aspose.cloud/tasks/cloud)

{{% /alert %}} 

## **Major Features**


- Support for Microsoft Project Online, MPP files saved with Microsoft Office 365 cloud has been supported.
- The support of setting CSS prefix for HTML export has been added.
- Health check endpoint now avaliable in public API
- CORS policy now allows any headers and methods
- Fix issues in OpenAPI spec

|**Public API and Backwards Incompatible Changes**|||
| :- | :- | :- |
|*The following API endpoints were added:*||*Description:*|
|PUT https://api.aspose.cloud/v3.0/tasks/{fileName}/importfromprojectonline?siteUrl={serverAddr}&format={format}||Imports project from Project Online and saves it to specified file. Where: {serverAddr} - The url of sharepoint site. For example, "<https://your_company_name.sharepoint.com>". {format} - Format of the resulting file. The import to Mpp format is not supported. {fileName} - The name of the resulting file. Full list of arguments you can see at  OpenApi specification|
|GET https://api.aspose.cloud/v3.0/tasks/projectonline/projectlist?siteUrl={serverAddr}||Gets the list of published projects in the current Project Online account. Where: {serverAddr} - The url of sharepoint site. For example, "<https://your_company_name.sharepoint.com>".|
|*The following objects and properties were added:*||*Description:*|
|DTO object ProjectInfo||You can expect array of this objects as output at "GET <https://api.aspose.cloud/v3.0/tasks/projectonline/projectlist>" route. It's a brief info about the published project available on Project Online.|
|ProjectInfo.Id||The unique identifier of the project.|
|ProjectInfo.Name||` `The name of the project.|
|ProjectInfo.CreatedDate||The date and time when the project was created.|
|ProjectInfo.IsCheckedOut||Value indicating whether the project is checked out.|
|ProjectInfo.LastPublishedDate||The most recent date when the project was published.|
|ProjectInfo.LastSavedDate||The most recent date when the project was saved.|
|ProjectInfo.Description||The description of the project.|
|Header x-project-online-token||Required header for Project Server interactions. Must contain authorization token for the SharePoint|
|HtmlSaveOptions.CssStylePrefix||Gets or sets css style prefix.|
|DocumentProperty DateFormat||New property to view or set DateFormat. Available values see below. |
|DateFormat.DateMmDdYyHhMmAM = 0,||Available values for DateFormat enum.|
|DateFormat.DateMmDdYy = 1,|||
|DateFormat.DateMmmmDdYyyyHhMmAM = 2,|||
|DateFormat.DateMmmmDdYyyy = 3,|||
|DateFormat.DateMmmDdHhMmAM = 4,|||
|DateFormat.DateMmmDdYyy = 5,|||
|DateFormat.DateMmmmDd = 6,|||
|DateFormat.DateMmmDd = 7,|||
|DateFormat.DateDddMmDdYyHhMmAM = 8,|||
|DateFormat.DateDddMmDdYy = 9,|||
|DateFormat.DateDddMmmDdYyy = 10,|||
|DateFormat.DateDddHhMmAM = 11,|||
|DateFormat.DateMmDd = 12,|||
|DateFormat.DateDd = 13,|||
|DateFormat.DateHhMmAm = 14,|||
|DateFormat.DateDddMmmDd = 15,|||
|DateFormat.DateDddMmDd = 16,|||
|DateFormat.DateDddDd = 17,|||
|DateFormat.DateWwwDd = 18,|||
|DateFormat.DateWwwDdYyHhMmAm = 19,|||
|DateFormat.DateMmDdYyyy = 20,|||
|DateFormat.Custom = 21,|||
|DateFormat.Default = 255,|||
|DateFormat.DateDdMmYyyy = 256|||
|DocumentProperty CustomDateFormat||Project view custom date format. Used to format dates when DocumentProperty DateFormat property is set to DateFormat.Custom|

