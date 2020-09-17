---
title: "Get Resource Assignments"
type: docs
url: /get-resource-assignments/
weight: 30
---

## **Introduction**
This example explains how to get resource assignments. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources/{resourceUid}/assignments|GET|Get resource's assignments|[GetResourceAssignments](https://apireference.aspose.cloud/tasks/#/TasksResources/GetResourceAssignments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/resources/1/assignments" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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
        "actualFinish": "2020-09-17T14:34:32.397Z",
        "actualOvertimeCost": 0,
        "actualOvertimeWork": "string",
        "actualStart": "2020-09-17T14:34:32.397Z",
        "actualWork": "string",
        "acwp": 0,
        "confirmed": true,
        "cost": 0,
        "costRateTableType": "A",
        "costVariance": 0,
        "cv": 0,
        "delay": 0,
        "finish": "2020-09-17T14:34:32.397Z",
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
        "start": "2020-09-17T14:34:32.397Z",
        "stop": "2020-09-17T14:34:32.397Z",
        "resume": "2020-09-17T14:34:32.397Z",
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
        "creationDate": "2020-09-17T14:34:32.398Z",
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
            "start": "2020-09-17T14:34:32.398Z",
            "finish": "2020-09-17T14:34:32.398Z"
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
            "dateValue": "2020-09-17T14:34:32.398Z",
            "flagValue": true,
            "textValue": "string"
          }
        ],
        "timephasedData": [
          {
            "uid": 0,
            "start": "2020-09-17T14:34:32.398Z",
            "finish": "2020-09-17T14:34:32.398Z",
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
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetResourceAssignments.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "698e459243193fcc5d4e9080a2fc23c4" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "6cd42bcbb97644c50ba982d5fd607add" >}}

{{< /tab >}}

{{< /tabs >}}
