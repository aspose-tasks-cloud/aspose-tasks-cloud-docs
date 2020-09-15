---
title: "Update a Specific Task"
type: docs
url: /update-a-specific-task/
weight: 50
---

# **Introduction**
This example explains how to update a task of specified UID. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}|PUT|Update the Task Reference of|[PutTask](https://apireference.aspose.cloud/tasks/#/TasksTask/PutTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/1?mode=0&recalculate=true" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjY3NTg4MzQsImV4cCI6MTU2Njg0NTIzNCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.sZMk1kfvcJOkiDHK0mlKwZNRwT0lHb1UiaK97gOFIPeuEt\_03IIvjB9k75tGXehJ1OLE2thdpgli58BjlMlitOpozOE5niCM\_uehk-D4Dlu2k8r00KNZsMszPd4AENzj42NMtvkUziV\_G-lPT1ypaWRIOUC5Z1ZS2gxl7-MN39PQpz95REuSAJXjnFw-KIB-oUzHe-wlw-GJ0U0GqYGfsuYOiySQ\_X8\_uEt9cnwycrIdMJEYr-llFgmRxLKA1qtDxtsUyvTBpNJPufC3am8KsI44ELtKwIuVWcoI5JXbN4zEiioDHk-SomgmicXEQvVFiOV4yQD5nR0YQ2onPESyOw" -H "Content-Type: application/json" -d "{ \"Uid\": 10, \"Id\": 2, \"Name\": \"New task Name\", \"Duration\": \"13:01:00\", \"Start\": \"2000-10-10T00:00:00\", \"Finish\": \"2001-10-10T00:00:00\", \"PercentComplete\": 0, \"PercentWorkComplete\": 0, \"IsActive\": true, \"ConstraintType\": \"AsSoonAsPossible\", \"Cost\": 100, \"DurationVariance\": \"33.08:00:00\", \"EarlyFinish\": \"2003-03-18T08:00:00\", \"EarlyStart\": \"2003-01-07T08:00:00\", \"FixedCostAccrual\": \"End\", \"GUID\": \"6c0f1864-17ca-437f-9668-7fd103ddee3e\", \"LateFinish\": \"2003-03-18T08:00:00\", \"LateStart\": \"2003-01-07T08:00:00\", \"IsLevelAssignments\": true, \"CanLevelingSplit\": true, \"IsMarked\": false, \"IsMilestone\": false, \"IsCritical\": true, \"SubprojectName\": null, \"IsSummary\": false, \"SubtasksUids\": [], \"OutlineLevel\": 2, \"IsOverAllocated\": true, \"RegularWork\": \"4.04:00:00\", \"RemainingCost\": 3526.25, \"RemainingDuration\": \"4.04:10:10\", \"RemainingWork\": \"20.20:00:00\", \"IsResumeValid\": false, \"Type\": \"FixedUnits\", \"Wbs\": \"1.1\", \"Priority\": 500, \"Work\": \"10:10:10\", \"WorkVariance\": 30000.0, \"NotesText\": \"Second task note with some formatting!\", \"NotesRTF\": \"{\\\\rtf1\\\\ansi\\\\ansicpg1252\\\\deff0\\\\deflang1033{\\\\fonttbl{\\\\f0\\\\fswiss\\\\fprq2\\\\fcharset0 Arial;}}\\r\\\\\viewkind4\\\\uc1\\\\pard\\\\f0\\\\fs16 Second task note \\\\b with some formatting!\\\\b0\\\\par\\r\}\\r\\\u0000\", \"LevelingDelayFormat\": \"ElapsedDay\", \"Predecessors\": \"\", \"Successors\": \"\", \"IsExpanded\": true, \"EarnedValueMethod\": \"PercentComplete\", \"Baselines\": [], \"ExtendedAttributes\": [{ \"FieldId\": \"188743732\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743733\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743735\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743736\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743738\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743739\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743741\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743742\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743744\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743745\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743767\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743768\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743769\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743770\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743771\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743786\", \"AttributeType\": \"Cost\" }, { \"FieldId\": \"188743787\", \"AttributeType\": \"Cost\" }, { \"FieldId\": \"188743788\", \"AttributeType\": \"Cost\" }], \"OutlineCodes\": [], \"ActualDuration\": \"4.04:01:01\", \"ActualFinish\": \"2001-10-10T00:00:00\", \"ActualStart\": \"2000-10-10T00:00:00\", \"BudgetWork\": \"20:00:00\", \"ActualCost\": 12}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {"status": "ok","code":200}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-EditTask.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "d56967b652b543b7880ec438f1af7820" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "bce02db292797085b408ff8b7e230ce7" >}}

{{< /tab >}}

{{< /tabs >}}
