---
title: "Add a new Task to a Project"
type: docs
url: /add-a-new-task-to-a-project/
weight: 40
---

## **Introduction**
This example explains how to add a new task to a project.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks|POST|Add a new Task|[PostTask](https://apireference.aspose.cloud/tasks/#/TasksTask/PostTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks?mode=0&recalculate=true" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Uid\": 10, \"Id\": 2, \"Name\": \"New task Name\", \"Duration\": \"13:01:00\", \"Start\": \"2000-10-10T00:00:00\", \"Finish\": \"2001-10-10T00:00:00\", \"PercentComplete\": 0, \"PercentWorkComplete\": 0, \"IsActive\": true, \"ConstraintType\": \"AsSoonAsPossible\", \"Cost\": 100, \"DurationVariance\": \"33.08:00:00\", \"EarlyFinish\": \"2003-03-18T08:00:00\", \"EarlyStart\": \"2003-01-07T08:00:00\", \"FixedCostAccrual\": \"End\", \"GUID\": \"6c0f1864-17ca-437f-9668-7fd103ddee3e\", \"LateFinish\": \"2003-03-18T08:00:00\", \"LateStart\": \"2003-01-07T08:00:00\", \"IsLevelAssignments\": true, \"CanLevelingSplit\": true, \"IsMarked\": false, \"IsMilestone\": false, \"IsCritical\": true, \"SubprojectName\": null, \"IsSummary\": false, \"SubtasksUids\": [], \"OutlineLevel\": 2, \"IsOverAllocated\": true, \"RegularWork\": \"4.04:00:00\", \"RemainingCost\": 3526.25, \"RemainingDuration\": \"4.04:10:10\", \"RemainingWork\": \"20.20:00:00\", \"IsResumeValid\": false, \"Type\": \"FixedUnits\", \"Wbs\": \"1.1\", \"Priority\": 500, \"Work\": \"10:10:10\", \"WorkVariance\": 30000.0, \"NotesText\": \"Second task note with some formatting!\", \"NotesRTF\": \"{\\\\rtf1\\\\ansi\\\\ansicpg1252\\\\deff0\\\\deflang1033{\\\\fonttbl{\\\\f0\\\\fswiss\\\\fprq2\\\\fcharset0 Arial;}}\\r\\\\\viewkind4\\\\uc1\\\\pard\\\\f0\\\\fs16 Second task note \\\\b with some formatting!\\\\b0\\\\par\\r\}\\r\\\u0000\", \"LevelingDelayFormat\": \"ElapsedDay\", \"Predecessors\": \"\", \"Successors\": \"\", \"IsExpanded\": true, \"EarnedValueMethod\": \"PercentComplete\", \"Baselines\": [], \"ExtendedAttributes\": [{ \"FieldId\": \"188743732\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743733\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743735\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743736\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743738\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743739\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743741\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743742\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743744\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743745\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743767\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743768\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743769\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743770\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743771\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743786\", \"AttributeType\": \"Cost\" }, { \"FieldId\": \"188743787\", \"AttributeType\": \"Cost\" }, { \"FieldId\": \"188743788\", \"AttributeType\": \"Cost\" }], \"OutlineCodes\": [], \"ActualDuration\": \"4.04:01:01\", \"ActualFinish\": \"2001-10-10T00:00:00\", \"ActualStart\": \"2000-10-10T00:00:00\", \"BudgetWork\": \"20:00:00\", \"ActualCost\": 12}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Code": "200",
  "Status": "OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-AddTask.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-working-AddTaskToAProjectExample-AddTaskToAProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Tasks-PostTaskLink-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Tasks-add_new_task_link_to_project-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-working-AddTaskToAProjectExample-AddTaskToAProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Tasks-AddTask-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "897f5dc8ce2faa65b059cbb8f5f59486" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "633d17ae712f014c53e01b8dc4dc2391" >}}

{{< /tab >}}

{{< /tabs >}}
