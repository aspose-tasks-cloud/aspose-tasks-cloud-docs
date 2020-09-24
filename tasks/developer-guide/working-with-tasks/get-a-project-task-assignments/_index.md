---
title: "Get a Project Task Assignments"
type: docs
url: /get-a-project-task-assignments/
weight: 70
---

## **Introduction**
This example explains how to read information for a Project's task assignments.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/assignments|GET|Read information for a Project Task Assignments|[GetTaskAssignments](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTaskAssignments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/1/assignments" -H "accept: application/json" 

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "assignments": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "list": [
      {
        "taskUid": 0,
        "resourceUid": 0,
        "guid": "string",
        "uid": 0,
        "percentWorkComplete": 0,
        "actualCost": 0,
        "actualFinish": "2020-09-18T09:56:17.067Z",
        "actualOvertimeCost": 0,
        "actualOvertimeWork": "string",
        "actualStart": "2020-09-18T09:56:17.067Z",
        "actualWork": "string",
        "acwp": 0,
        "confirmed": true,
        "cost": 0,
        "costRateTableType": "A",
        "costVariance": 0,
        "cv": 0,
        "delay": 0,
        "finish": "2020-09-18T09:56:17.067Z",
        "finishVariance": 0,
        "hyperlink": "string",
        "hyperlinkAddress": "string",
        "hyperlinkSubAddress": "string",
        "workVariance": 0,
        "hasFixedRateUnits": true,
        "fixedMaterial": true,
        "levelingDelay": 0,
        "levelingDelayFormat": "Minute",
        "linkedFields": true,
        "milestone": true,
        "notes": "string",
        "overallocated": true,
        "overtimeCost": 0,
        "overtimeWork": "string",
        "peakUnits": 0,
        "regularWork": "string",
        "remainingCost": 0,
        "remainingOvertimeCost": 0,
        "remainingOvertimeWork": "string",
        "remainingWork": "string",
        "responsePending": true,
        "start": "2020-09-18T09:56:17.067Z",
        "stop": "2020-09-18T09:56:17.067Z",
        "resume": "2020-09-18T09:56:17.067Z",
        "startVariance": 0,
        "summary": true,
        "sv": 0,
        "units": 0,
        "updateNeeded": true,
        "vac": 0,
        "work": "string",
        "workContour": "Flat",
        "bcws": 0,
        "bcwp": 0,
        "bookingType": "Committed",
        "actualWorkProtected": "string",
        "actualOvertimeWorkProtected": "string",
        "creationDate": "2020-09-18T09:56:17.067Z",
        "assnOwner": "string",
        "assnOwnerGuid": "string",
        "budgetCost": 0,
        "budgetWork": "string",
        "rateScale": "Undefined",
        "baselines": [
          {
            "baselineNumber": "Baseline",
            "work": "string",
            "cost": 0,
            "bcws": 0,
            "bcwp": 0,
            "start": "2020-09-18T09:56:17.067Z",
            "finish": "2020-09-18T09:56:17.067Z"
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
            "dateValue": "2020-09-18T09:56:17.067Z",
            "flagValue": true,
            "textValue": "string"
          }
        ],
        "timephasedData": [
          {
            "uid": 0,
            "start": "2020-09-18T09:56:17.067Z",
            "finish": "2020-09-18T09:56:17.067Z",
            "unit": "Minute",
            "value": "string",
            "timephasedDataType": "AssignmentRemainingWork"
          }
        ]
      }
    ]
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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskAssignments.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-assinments-RetrieveAssignmentInformationExample-RetrieveAssignmentInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Assignments-GetProjectAssignments-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Assignments-get_project_assignments-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-assinments-RetrieveAssignmentInformationExample-RetrieveAssignmentInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Assignments-RetrieveAssignmentInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "5a669f28f52ee82a33e0b0e64643d26e" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "48428bbef0874075ee109f6c398424e8" >}}

{{< /tab >}}

{{< /tabs >}}
