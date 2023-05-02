---
title: "Aspose.Tasks Cloud 23.5 Release Notes"
description: "The page contains the release notes for Aspose.Tasks Cloud 23.5."
type: docs
url: /aspose-tasks-cloud-23-5-release-notes/
weight: 6
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 23.5](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 

## **All Changes**

|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
| TASKSNET-10773 | Fix persistence of Assignment's guid when reading and writing a project from\to XER and P6XML formats. | Bug |
| TASKSNET-10772 | Fix calculation of task's calendar when reading Task dependent activity from file in XER format | Bug |
| TASKSNET-10770 | Fix reading and generation of timephased data for assignments of tasks with elapsed duration | Bug |
| TASKSNET-10766 | Fix 'System.ArgumentException' when calling ResourceAssignment.GetTimephasedData | Bug |
| TASKSNET-10725 | Fix exception when saving the specific project to XER format | Bug |
| TASKSNET-10663 | Fix incorrect 'Duration % complete' shown in Primavera P6 when opening project saved by Aspose.Tasks. | Bug |
| TASKSNET-4701 | Fix incorrect Primavera percentage complete value | Bug |
| TASKSNET-10804 | Fix reading and writing of Leveling Delay field from \ to MPP format | Bug |
| TASKSNET-10796 | Fix writing of Task.Hyperlink to MPP file | Bug |
| TASKSNET-10786 | Fix writing of changes in base calendars | Bug |
| TASKSNET-10767 | Fix duration of some tasks are changed after recalculating project saved by Aspose.Tasks | Bug |

## **Public API and Backwards Incompatible Changes**
|**The following objects and properties were added:**|**Description**|
| :- | :- |
| Task.ExternalUid | Gets or set the external task's Unique identifier when the task is external. |
| TaskLink.LinkLagTimeSpan | Gets or sets lag duration, depending on LagFormat. |
| PrimaveraTaskProperties.PhysicalPercentComplete | Gets the value of Physical Percent Complete. |
| PrimaveraTaskProperties.DurationPercentComplete | Gets the value of duration percent complete. |
| PrimaveraTaskProperties.UnitsPercentComplete | Gets the value of units percent complete. |
| PrimaveraTaskProperties.ActualLaborUnits | Gets the value of actual labor units. |
| PrimaveraTaskProperties.ActualNonLaborUnits | Gets the value of actual non labor units. |
| PrimaveraTaskProperties.RemainingLaborUnits | Gets the value of remaining labor units. |
| PrimaveraTaskProperties.RemainingNonLaborUnits | Gets the value of remaining non labor units. |

## **Examples and additional notes**

**Related issue: TASKSNET-10722 - Fix creation of external task links**

New task's property was added : Task.ExternalUid.
MS Project requires Unique Id of External task to be set in order to properly link tasks between projects.