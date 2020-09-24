---
title: "Get a Specific Task of a Project"
type: docs
url: /get-a-specific-task-of-a-project/
weight: 20
---

## **Introduction**
This example explains how to retrieve a project task of a specified UID.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}|GET|Read a specific task of a project|[GetTask](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/0" -H "accept: application/json" 

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
    "start": "2020-09-18T07:38:29.309Z",
    "finish": "2020-09-18T07:38:29.309Z",
    "startText": "string",
    "finishText": "string",
    "percentComplete": 0,
    "percentWorkComplete": 0,
    "isActive": true,
    "actualCost": 0,
    "actualDuration": "string",
    "actualFinish": "2020-09-18T07:38:29.309Z",
    "actualOvertimeCost": 0,
    "actualOvertimeWork": "string",
    "actualWorkProtected": "string",
    "actualOvertimeWorkProtected": "string",
    "actualStart": "2020-09-18T07:38:29.309Z",
    "budgetWork": "string",
    "budgetCost": 0,
    "constraintDate": "2020-09-18T07:38:29.309Z",
    "constraintType": "AsSoonAsPossible",
    "contact": "string",
    "cost": 0,
    "cv": 0,
    "deadline": "2020-09-18T07:38:29.309Z",
    "durationVariance": "string",
    "earlyFinish": "2020-09-18T07:38:29.309Z",
    "earlyStart": "2020-09-18T07:38:29.309Z",
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
    "lateFinish": "2020-09-18T07:38:29.309Z",
    "lateStart": "2020-09-18T07:38:29.309Z",
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
    "preLeveledFinish": "2020-09-18T07:38:29.309Z",
    "preLeveledStart": "2020-09-18T07:38:29.309Z",
    "isRecurring": true,
    "regularWork": "string",
    "remainingCost": 0,
    "remainingDuration": "string",
    "remainingOvertimeCost": 0,
    "remainingOvertimeWork": "string",
    "remainingWork": "string",
    "resume": "2020-09-18T07:38:29.309Z",
    "isResumeValid": true,
    "stop": "2020-09-18T07:38:29.309Z",
    "isRollup": true,
    "startSlack": 0,
    "startVariance": 0,
    "calendarUid": 0,
    "isManual": true,
    "manualStart": "2020-09-18T07:38:29.309Z",
    "manualFinish": "2020-09-18T07:38:29.309Z",
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
    "commitmentStart": "2020-09-18T07:38:29.309Z",
    "commitmentFinish": "2020-09-18T07:38:29.309Z",
    "commitmentType": 0,
    "baselines": [
      {
        "baselineNumber": "Baseline",
        "work": "string",
        "cost": 0,
        "bcws": 0,
        "bcwp": 0,
        "start": "2020-09-18T07:38:29.309Z",
        "finish": "2020-09-18T07:38:29.309Z",
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
        "dateValue": "2020-09-18T07:38:29.309Z",
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
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskByUid.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-working-RetrieveTaskInformationExample-RetrieveTaskInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Tasks-GetProjectTask-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Tasks-get_project_task-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-working-RetrieveTaskInformationExample-RetrieveTaskInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Tasks-RetrieveInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "b8aad03ad1f76b0f1f08c26a0310132a" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "d70c4b44d564711e6ec193f76a6beb62" >}}

{{< /tab >}}

{{< /tabs >}}
