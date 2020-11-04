---
title: "Aspose.Tasks Cloud 20.11 Release Notes"
type: docs
url: /aspose-tasks-cloud-20-11-release-notes/
weight: 8
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 20.11](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 
## Major Features

- Add an ability to create multiple tasks in single api call.


## **All Changes**

|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
|TASKSCLOUD-397|Support to add multiple tasks in an API Call. | New Feature |
|TASKSNET-4371|Fix incorrect reading of MPP with a large number of long assignments | Bug |
|TASKSNET-4370|Fix bad performance while deleting of resources when CalculationMode.Manual is set | Bug | 
|TASKSNET-4189|Fix an issue with a file modification and resaving | Bug |
|TASKSNET-4154|Fix invalid recalculated Start and Finish values for assignment with zero duration. | Bug | 
|TASKSNET-4350|Fix missing ActualFinish. | Bug | 
|TASKSNET-4390|Fix file resaved with Aspose.Tasks cannot be opened by MSP 2016. | Bug | 
|TASKSNET-4447|Fix IsMilestone set to true after project’s recalculation. | Bug | 
|TASKSNET-4438|Fix TasksException “TaskEntity.Start is DateTime.MinValue…” when project is recalculated. | Bug |
|TASKSNET-4414|Fix saving of task’s WBS code to Project Server \ Project Online. | Bug | 
|TASKSNET-4412|Fix “Key already exists” exception when saving and reading large file to\from ProjectServer. | Bug |
|TASKSNET-4411|Fix concurrency issues when accessing Project Server. | Bug | 
|TASKSNET-4286|Fix reading \ writing of Task.NotesText from \ to Project Server. | Bug | 

## **Public API and Backwards Incompatible Changes**

| **The following API endpoints were added:** | **Description** |
| :- | :- |
| POST on https://api.aspose.cloud/v3.0/tasks/{name}/tasks/batch | Create multiple tasks by single request. |

