---
title: "Update a Specific Task"
type: docs
url: /update-a-specific-task/
weight: 50
---

## **Introduction**
This example explains how to update a task of specified UID, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}|PUT|Update the Task Reference of|[PutTask](https://apireference.aspose.cloud/tasks/#/TasksTask/PutTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/1?mode=0&recalculate=true" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Uid\": 10, \"Id\": 2, \"Name\": \"New task Name\", \"Duration\": \"13:01:00\", \"Start\": \"2000-10-10T00:00:00\", \"Finish\": \"2001-10-10T00:00:00\", \"PercentComplete\": 0, \"PercentWorkComplete\": 0, \"IsActive\": true, \"ConstraintType\": \"AsSoonAsPossible\", \"Cost\": 100, \"DurationVariance\": \"33.08:00:00\", \"EarlyFinish\": \"2003-03-18T08:00:00\", \"EarlyStart\": \"2003-01-07T08:00:00\", \"FixedCostAccrual\": \"End\", \"GUID\": \"6c0f1864-17ca-437f-9668-7fd103ddee3e\", \"LateFinish\": \"2003-03-18T08:00:00\", \"LateStart\": \"2003-01-07T08:00:00\", \"IsLevelAssignments\": true, \"CanLevelingSplit\": true, \"IsMarked\": false, \"IsMilestone\": false, \"IsCritical\": true, \"SubprojectName\": null, \"IsSummary\": false, \"SubtasksUids\": [], \"OutlineLevel\": 2, \"IsOverAllocated\": true, \"RegularWork\": \"4.04:00:00\", \"RemainingCost\": 3526.25, \"RemainingDuration\": \"4.04:10:10\", \"RemainingWork\": \"20.20:00:00\", \"IsResumeValid\": false, \"Type\": \"FixedUnits\", \"Wbs\": \"1.1\", \"Priority\": 500, \"Work\": \"10:10:10\", \"WorkVariance\": 30000.0, \"NotesText\": \"Second task note with some formatting!\", \"NotesRTF\": \"{\\\\rtf1\\\\ansi\\\\ansicpg1252\\\\deff0\\\\deflang1033{\\\\fonttbl{\\\\f0\\\\fswiss\\\\fprq2\\\\fcharset0 Arial;}}\\r\\\\\viewkind4\\\\uc1\\\\pard\\\\f0\\\\fs16 Second task note \\\\b with some formatting!\\\\b0\\\\par\\r\}\\r\\\u0000\", \"LevelingDelayFormat\": \"ElapsedDay\", \"Predecessors\": \"\", \"Successors\": \"\", \"IsExpanded\": true, \"EarnedValueMethod\": \"PercentComplete\", \"Baselines\": [], \"ExtendedAttributes\": [{ \"FieldId\": \"188743732\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743733\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743735\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743736\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743738\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743739\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743741\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743742\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743744\", \"AttributeType\": \"Start\" }, { \"FieldId\": \"188743745\", \"AttributeType\": \"Finish\" }, { \"FieldId\": \"188743767\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743768\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743769\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743770\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743771\", \"AttributeType\": \"Number\" }, { \"FieldId\": \"188743786\", \"AttributeType\": \"Cost\" }, { \"FieldId\": \"188743787\", \"AttributeType\": \"Cost\" }, { \"FieldId\": \"188743788\", \"AttributeType\": \"Cost\" }], \"OutlineCodes\": [], \"ActualDuration\": \"4.04:01:01\", \"ActualFinish\": \"2001-10-10T00:00:00\", \"ActualStart\": \"2000-10-10T00:00:00\", \"BudgetWork\": \"20:00:00\", \"ActualCost\": 12}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "task": {
    "uid": 0,
    "id": 0,
    "name": "string",
    "durationText": "string",
    "duration": "string",
    "start": "2020-09-18T07:47:57.779Z",
    "finish": "2020-09-18T07:47:57.779Z",
    "startText": "string",
    "finishText": "string",
    "percentComplete": 0,
    "percentWorkComplete": 0,
    "isActive": true,
    "actualCost": 0,
    "actualDuration": "string",
    "actualFinish": "2020-09-18T07:47:57.779Z",
    "actualOvertimeCost": 0,
    "actualOvertimeWork": "string",
    "actualWorkProtected": "string",
    "actualOvertimeWorkProtected": "string",
    "actualStart": "2020-09-18T07:47:57.779Z",
    "budgetWork": "string",
    "budgetCost": 0,
    "constraintDate": "2020-09-18T07:47:57.779Z",
    "constraintType": "AsSoonAsPossible",
    "contact": "string",
    "cost": 0,
    "cv": 0,
    "deadline": "2020-09-18T07:47:57.779Z",
    "durationVariance": "string",
    "earlyFinish": "2020-09-18T07:47:57.779Z",
    "earlyStart": "2020-09-18T07:47:57.779Z",
    "isEffortDriven": true,
    "isExternalTask": true,
    "externalTaskProject": "string",
    "externalId": 0,
    "finishSlack": 0,
    "finishVariance": 0,
    "fixedCost": 0,
    "fixedCostAccrual": "Start",
    "freeSlack": 0,
    "guid": "string",
    "hideBar": true,
    "ignoreResourceCalendar": true,
    "lateFinish": "2020-09-18T07:47:57.779Z",
    "lateStart": "2020-09-18T07:47:57.779Z",
    "isLevelAssignments": true,
    "canLevelingSplit": true,
    "levelingDelay": 0,
    "isMarked": true,
    "isMilestone": true,
    "isCritical": true,
    "isSubproject": true,
    "isSubprojectReadOnly": true,
    "subprojectName": "string",
    "isSummary": true,
    "subtasksUids": [
      0
    ],
    "outlineLevel": 0,
    "isOverAllocated": true,
    "isEstimated": true,
    "overtimeCost": 0,
    "overtimeWork": "string",
    "physicalPercentComplete": 0,
    "preLeveledFinish": "2020-09-18T07:47:57.779Z",
    "preLeveledStart": "2020-09-18T07:47:57.779Z",
    "isRecurring": true,
    "regularWork": "string",
    "remainingCost": 0,
    "remainingDuration": "string",
    "remainingOvertimeCost": 0,
    "remainingOvertimeWork": "string",
    "remainingWork": "string",
    "resume": "2020-09-18T07:47:57.779Z",
    "isResumeValid": true,
    "stop": "2020-09-18T07:47:57.779Z",
    "isRollup": true,
    "startSlack": 0,
    "startVariance": 0,
    "calendarUid": 0,
    "isManual": true,
    "manualStart": "2020-09-18T07:47:57.779Z",
    "manualFinish": "2020-09-18T07:47:57.779Z",
    "manualDuration": "string",
    "totalSlack": 0,
    "type": "FixedUnits",
    "wbs": "string",
    "priority": 0,
    "work": "string",
    "workVariance": 0,
    "notesText": "string",
    "notesRTF": "string",
    "acwp": 0,
    "bcws": 0,
    "bcwp": 0,
    "levelingDelayFormat": "Minute",
    "predecessors": "string",
    "successors": "string",
    "ignoreWarnings": false,
    "isExpanded": true,
    "displayOnTimeline": true,
    "displayAsSummary": true,
    "hyperlink": "string",
    "hyperlinkAddress": "string",
    "hyperlinkSubAddress": "string",
    "earnedValueMethod": "PercentComplete",
    "isPublished": true,
    "statusManager": "string",
    "commitmentStart": "2020-09-18T07:47:57.779Z",
    "commitmentFinish": "2020-09-18T07:47:57.779Z",
    "commitmentType": 0,
    "baselines": [
      {
        "baselineNumber": "Baseline",
        "work": "string",
        "cost": 0,
        "bcws": 0,
        "bcwp": 0,
        "start": "2020-09-18T07:47:57.779Z",
        "finish": "2020-09-18T07:47:57.779Z",
        "duration": "string",
        "fixedCost": 0,
        "durationFormat": "Minute",
        "estimatedDuration": true
      }
    ],
    "extendedAttributes": [
      {
        "fieldId": "string",
        "attributeType": "Null",
        "valueGuid": "string",
        "lookupValueId": 0,
        "durationValue": {
          "timeSpan": "string",
          "timeUnit": "Minute"
        },
        "numericValue": 0,
        "dateValue": "2020-09-18T07:47:57.779Z",
        "flagValue": true,
        "textValue": "string"
      }
    ],
    "outlineCodes": [
      {
        "fieldId": "string",
        "valueId": 0,
        "valueGuid": "string"
      }
    ],
    "warning": false
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutTask.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putTask.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "d56967b652b543b7880ec438f1af7820" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "bce02db292797085b408ff8b7e230ce7" >}}

{{< /tab >}}

{{< /tabs >}}
