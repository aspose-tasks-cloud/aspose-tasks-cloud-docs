---
title: "Aspose.Tasks Cloud 23.3 Release Notes"
description: "The page contains the release notes for Aspose.Tasks Cloud 23.3."
type: docs
url: /aspose-tasks-cloud-23-3-release-notes/
weight: 6
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 23.3](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 

## **All Changes**

|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
| TASKSNET-10724 | Fix escaping of text values when writing project to XER format. | Enhancement |
| TASKSNET-3704 | Fix cost calculations for case when multiple rates are effective on a day. | Enhancement |
| TASKSNET-10756 | Fix reading of task priority column for MPX files where Priority column was saved using enum values. | Enhancement |
| TASKSNET-10723 | Fix Exception when reading a project from XER file | Bug |
| TASKSNET-10759 | Fix calculation of summary task's Duration property for project read from Primavera format: it should correspond to 'Original Duration', not to 'At Completion Duration'. | Bug |
| TASKSNET-10757 | Fix writing of MPX file to fix import errors reported by Microsoft Project 98 when importing MPX file created by Aspose.Tasks. | Bug |
| TASKSNET-10746 | Fix missing constraint dates when saving the specific project | Bug |
| TASKSNET-10745 | Fix IndexOutOfRangeException when saving the specific file to MPX format | Bug |
| TASKSNET-10743 | Fix reading of timephased data from MPP format | Bug |
| TASKSNET-10734 | Fix standard calendar's days are shown as non-working in MS Project when opening a project created without a template | Bug |
| TASKSNET-10740 | Fix reading of Link lag value when reading project from XER file | Bug |
| TASKSNET-10721 | Fix addition of new table for a project saved without a template file | Bug |

## **Examples and additional notes**

**Related issue: TASKSNET-10759 - Fix calculation of summary task's Duration property for project read from Primavera format: it should correspond to 'Original Duration', not to 'At Completion Duration'.**

Before 23.3 there were inconsistency with 'Duration' property for tasks read from Primavera P6 XML or XER format.
Duration of non-summary tasks was set to Primavera's 'Original Duration' column, whilst duration of summary tasks was calculated as 'At Completion Duration'.

We fixed the behavior in 23.3 and now 'Duration' for summary and non-summary tasks should correspond to 'Original Duration' column of Primavera P6.
The value of 'At Completion Duration' property can be get as a sum of task.ActualDuration and task.RemainingDuration.