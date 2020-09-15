---
title: "Aspose.Tasks Cloud 20.8 Release Notes"
type: docs
url: /aspose-tasks-cloud-20-8-release-notes/
weight: 10
---

{{% alert color="primary" %}} 

This page contains release notes for Aspose.Tasks Cloud 20.8

{{% /alert %}} 
## **Major Features**
- Specify the non-default path for Project Server's PWA URL
- Modify timephasedData collection in assignments.
## **Public API and Backwards Incompatible Changes**
*The following objects and properties were added:*

|**Objects/Properties**|**Description**|
| :- | :- |
|ResourceAssignment.TimephasedData|Represents a collection of TimephasedData objects.|

*The following API endpoints were extended:*

|**API endpoints**|**Description**|
| :- | :- |
|PUT https://api.aspose.cloud/v3.0/tasks/{name}/importfromprojectonline|<p></p><p></p><p>This routes now accepts full URL of PWA endpoint to specify where your service instance located in, e.g. http://project\_server\_instance.local/sites/pwa</p>|
|GET https://api.aspose.cloud/v3.0/tasks/projectOnline/projectList||
|POST https://api.aspose.cloud/v3.0/tasks/projectOnline/{siteUrl}/{name}||
|PUT https://api.aspose.cloud/v3.0/tasks/projectOnline/{siteUrl}/{name}||

