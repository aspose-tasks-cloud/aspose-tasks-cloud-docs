---
title: "Aspose.Tasks Cloud 21.4 Release Notes"
type: docs
url: /aspose-tasks-cloud-21-4-release-notes/
weight: 6
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 21.4](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 

## **All Changes**

|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
| TASKSNET-4705 | Add writing of existing values of enterprise extended attributes | Enhancement |
| TASKSNET-4769 | Remove an ability to set Tsk.Id when using CalculationMode.Manual and CalculationMode.Automatic | Enhancement |
| TASKSNET-4715 | Fix broken page range printing | Bug |
| TASKSNET-4704 | Fix missing column lines while printing to PDF | Bug |
| TASKSNET-4703 | Fix printing of extra columns lines when printing to PDF | Bug |
| TASKSNET-4700 | Fix wrong Resource Usage when exporting MPP - Microsoft Project 365 | Bug |
| TASKSNET-4699 | Task names disappearing when saving MPP file | Bug |
| TASKSNET-4673 | Fix disappearing of task names after MPP resave | Bug |
| TASKSNET-4721 | Fix incorrect timephased data shown when .MPP file is opened in MS Project | Bug |
| TASKSNET-4793 | Fix exported value of "Outline Code *" attributes when project is saved to non-MPP formats | Bug |
| TASKSNET-4772 | Fix parsing of "Round" operator in formulas | Bug |
| TASKSNET-4770 | Fix wrong calendar exception usage | Bug |
| TASKSNET-4751 | Fix OverflowException while reading MPP file | Bug |
| TASKSNET-4749 | Fix tasks splitting in case of splits beginning \ ending in middle of the day | Bug |
| TASKSNET-4697 | Fix incorrect ids of task children | Bug |
| TASKSNET-4695 | Fix incorrect resource unit price while converting to CSV | Bug |
| TASKSNET-4694 | Fix incorrect unit of work time in 2010 and 2007 formats while exporting to CSV | Bug |
| TASKSNET-4693 | Fix task splitting in MPP export not working as expected | Bug |
| TASKSNET-4374 | Fix file resaved with Aspose.Tasks cannot be opened by MSP 2016 | Bug |

## **Additional notes**

Related issue: TASKSNET-4769 - Remove an ability to set Tsk.Id when using CalculationMode.Manual and CalculationMode.Automatic.

The logic for Tsk.Id field was changed: it can no longer be set directly and is calculated by Aspose.Tasks (in the same manner as MS Project doesn't allow "Id" column to be set).
The above is true for CalculationMode.Manual and CalculationMode.Automatic modes.

You can use CalculationMode.None to set the value Tsk.Id on your own risk, but these values can overwritten when project is recalculated.

