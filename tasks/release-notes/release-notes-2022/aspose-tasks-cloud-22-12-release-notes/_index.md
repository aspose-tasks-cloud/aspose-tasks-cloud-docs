---
title: "Aspose.Tasks Cloud 22.12 Release Notes"
type: docs
url: /aspose-tasks-cloud-22-12-release-notes/
weight: 6
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 22.12](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 

## **All Changes**
|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
| TASKSNET-10699 | Add an API for read-only access to Primavera-specific task's properties for projects read from XER\P6XML formats | Enhancement |
| TASKSNET-10696 | Change sort order of summary tasks for a project read from XER format | Enhancement |
| TASKSNET-10657 | Fix 'TimephasedData value is not in correct format' exception when reading the specific file | Bug |
| TASKSNET-10652 | Fix reading of filter criteria when value is fractional number | Bug |
| TASKSNET-10614 | Fix Percent and Duration differences for Milestone and Summary tasks read from Primavera XER format | Bug |
| TASKSNET-10693 | Fix reading of rates from XER format | Bug |
| TASKSNET-10692 | Fix incorrect values of Work and Cost fields for assignments with Units count not equal to 1 in project read from XER file. | Bug |
| TASKSNET-10691 | Fix incorrect PercentageComplete value for task with zero duration for project read from XER file | Bug |
| TASKSNET-10683 | Fix timephased data for baselines are not shown when project is opened using MS Project | Bug |
| TASKSNET-10678 | Fix resetting of the dates when opening .XER file using trial version of Aspose.Tasks  | Bug |
| TASKSNET-10667 | Fix reading of timephased data for task's numbered baselines. | Bug |
| TASKSNET-4334 | Fix writing of baseline's TimephasedData for files with large number of timephased data items in baseline's TimephasedData collection | Bug |

## **Public API and Backwards Incompatible Changes**
| **The following API endpoints were added:** | **Description** |
| :- | :- |
| GET on https://api.aspose.cloud/v3.0/tasks/{name}/tasks/{taskUid}/primaveraProperties | Get primavera properties for a task with the specified Uid. |

|**The following objects and properties were added:**|**Description**|
| :- | :- |
| Document property "DefaultTaskEVMethod" | The default earned value method for tasks. |
| Document property "EarnedValueMethod" | The default method for calculating earned value. |
| Document property "ExtendedCreationDate" | Date used for calculation and reporting. |
| Document property "IsFiscalYearStart" | Determines whether the fiscal year numbering is used. |
| Document property "IsAdminProject" | Determines whether a project is an administrative project. |
| Document property "AutoAddNewResourcesAndTasks" | Determines whether new resources or tasks automatically added to a resource or task pool. |
| Document property "BaselineForEarnedValue" | The specific baseline used to calculate Variance values. |
| Document property "CurrencyCode" | The three letter currency character code as defined in ISO 4217. Example of valid values is "USD". |
| Document property "CanSpreadActualCost" | Determines whether actual costs are spread to the status date. |
| Document property "CanSpreadPercentComplete" | Determines whether a percent complete is spread to the status date. |
| Document property "Template" | Project's template. |
| PrimaveraTaskProperties | PrimaveraTaskProperties DTO |
| PrimaveraTaskProperties.SequenceNumber | The sequence number of the WBS item (summary tasks). It is used to sort summary tasks in Primavera. |
| PrimaveraTaskProperties.ActivityId | Activity id field - a task's unique identifier used by Primavera. |
| PrimaveraTaskProperties.RemainingEarlyFinish | Remaining early finish date - the date when the remaining work for the activity is scheduled to be finished. |
| PrimaveraTaskProperties.RemainingEarlyStart | Remaining early start date - the date when the remaining work for the activity is scheduled to begin. |
| PrimaveraTaskProperties.RemainingLateStart | Remaining late start date. |
| PrimaveraTaskProperties.RemainingLateFinish | Remaining late finish date. |
| PrimaveraTaskProperties.RawDurationType | Raw text representation (as in source file) of 'Duration Type' field of the activity. |
| PrimaveraTaskProperties.RawActivityType | Raw text representation (as in source file) of 'Activity Type' field of the activity. |
| PrimaveraTaskProperties.RawCompletePercentType | Raw text representation (as in source file) of '% Complete Type' field of the activity. |
| PrimaveraTaskProperties.RawStatus | Raw text representation (as in source file) of 'Status' field of the activity. |

## **Examples and additional notes**

**Related issue: TASKSNET-10699 - Add an API for read-only access to Primavera-specific task's properties for projects read from XER\P6XML formats**

It not a secret that in API of Aspose.Tasks model of Project (including Tasks, Resources, Assignments and related entities) was built with MS Project's model in mind.
Primavera has slightly different model of Project and, as a consequence, some Primavera fields don't have corresponding properties in public API of Aspose.Tasks.
To partially address this issue we added PrimaveraTaskProperties object which will contain read-only values of Primavera-specific fields read from source XER of P6XML file.