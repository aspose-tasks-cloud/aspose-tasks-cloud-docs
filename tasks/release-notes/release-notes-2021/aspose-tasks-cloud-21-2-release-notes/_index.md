---
title: "Aspose.Tasks Cloud 21.2 Release Notes"
type: docs
url: /aspose-tasks-cloud-21-2-release-notes/
weight: 6
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 21.2](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 

## **All Changes**

|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
| TASKSNET-4500 | Add an ability to read and write Activity_Id (task_code in XER) for Primavera XML, XER and DB formats | Enhancement |
| TASKSNET-4632 | Fix Actual Duration while setting Actual Finish date of the task | Enhancement |
| TASKSNET-4467 | Improve support of XML baseline for MSP 2019 | Enhancement |
| TASKSNET-4561 | Fix exception when trying to access TimephasedData for assignment of material resource | Bug |
| TASKSNET-4554 | Fix "NullReferenceException" when trying to render the specific project to HTML | Bug |
| TASKSNET-4548 | Fix System.OverflowException when trying to save password-protected project | Bug |
| TASKSNET-4547 | Fix "Index was outside the bounds of the array." exception when open document MPP file | Bug |
| TASKSNET-4544 | Fix "Index was out of range. Must be non-negative and less than the size of the collection. (Parameter 'index')" exception when get pages count MPP file | Bug |
| TASKSNET-4543 | Fix 'Stream does not support reading' exception when saving to HTML | Bug |
| TASKSNET-4526 | Fix ResourceAssignments are not read from password protected files for MSP 2010+ files | Bug |
| TASKSNET-4628 | Fix incorrect error message shown when trying to read a list of projects from empty Project Online account | Bug |
| TASKSNET-4588 | Fix exception when trying to add a new task in XER project | Bug |
| TASKSNET-4601 | Fix duplicated resources when reading XER of P6XML file | Bug |
| TASKSNET-4668 | Fix recalculation of projects with external links | Bug |
| TASKSNET-4667 | Fix ArgumentOutOfRangeException while recalculate a project | Bug |
| TASKSNET-4666 | Fix NullReferenceException while recalculate the project | Bug |
| TASKSNET-4604 | Fix current timescale position is reset when the project is saved by Aspose.Tasks | Bug |
| TASKSNET-4051 | Fix calculating of duration while convert MPP format | Bug |

## **Public API and Backwards Incompatible Changes**
*The following objects and properties were added:*

|**Objects/Properties**|**Description**|
| :- | :- |
|Task.ActivityId|Represents activity id field - a task's unique identifier used by Primavera (only applicable to Primavera projects).|

