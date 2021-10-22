---
title: "Aspose.Tasks Cloud 21.10 Release Notes"
type: docs
url: /aspose-tasks-cloud-21-10-release-notes/
weight: 6
---

{{% alert color="primary" %}} 

This page contains release notes for [Aspose.Tasks Cloud 21.10](https://products.aspose.cloud/tasks/cloud).

{{% /alert %}} 

## **All Changes**

|**Key**|**Summary**|**Issue Type**|
| :- | :- | :- |
| TASKSNET-10378 | Fix calculation of formula results when operand is #ERROR value | Enhancement |
| TASKSNET-10344 | Fix 'The start time should be not greater than the finish one' exception when creating project from Primavera .xer file | Bug |
| TASKSNET-10345 | Fix reading of values of lookup extended attributes | Bug |
| TASKSNET-10376 | Fix "Value was either too large or too small for a Decimal." exception when get pages count | Bug |
| TASKSNET-10368 | Fix reading of values of Actual Work's Timephased Data | Bug |
| TASKSNET-10361 | Fix "File reading error." exception when open document | Bug |

## **Public API and Backwards Incompatible Changes**

|**The following public properties were added:**|**Description**|
| :- | :- |
| ExtendedAttribute.IsErrorValue | Gets whether calculation of extended attribute's value resulted in an error. |

## **Additional notes**

**Related issue: TASKSNET-10378 - Fix calculation of formula results when operand is #ERROR value**

Read-only property ExtendedAttribute.IsErrorValue was added to provide an ability to check whether the value of calculated custom attribute cannot be calculated (due to error in input arguments or an error in the formula).

