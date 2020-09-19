---
title: "Modify Time Phased Data in Assignment"
type: docs
url: /modify-time-phased-data-in-assignment/
weight: 40
---

## **Introduction**
This example explains how to edit time phase data collection in assignments using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}|PUT|Update a Resource in a MS Project file using a identifier|[PutAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/PutAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/sample.mpp/assignments/1?mode=None&recalculate=false" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"taskUid\": 0, \"resourceUid\": 0, \"guid\": \"string\", \"uid\": 1, \"percentWorkComplete\": 0, \"actualCost\": 100, \"actualFinish\": \"2020-09-19T12:46:01.704Z\", \"actualOvertimeCost\": 0, \"actualOvertimeWork\": \"10:10:10\", \"actualStart\": \"2020-09-19T12:46:01.704Z\", \"actualWork\": \"10:10:10\", \"acwp\": 0, \"confirmed\": true, \"cost\": 100, \"costRateTableType\": \"A\", \"costVariance\": 0, \"cv\": 0, \"delay\": 0, \"finish\": \"2020-09-19T12:46:01.704Z\", \"finishVariance\": 0, \"hyperlink\": \"string\", \"hyperlinkAddress\": \"string\", \"hyperlinkSubAddress\": \"string\", \"workVariance\": 0, \"hasFixedRateUnits\": true, \"fixedMaterial\": true, \"levelingDelay\": 0, \"levelingDelayFormat\": \"Minute\", \"linkedFields\": true, \"milestone\": true, \"notes\": \"string\", \"overallocated\": true, \"overtimeCost\": 0, \"overtimeWork\": \"string\", \"peakUnits\": 0, \"regularWork\": \"string\", \"remainingCost\": 0, \"remainingOvertimeCost\": 0, \"remainingOvertimeWork\": \"string\", \"remainingWork\": \"string\", \"responsePending\": true, \"start\": \"2020-09-19T12:46:01.704Z\", \"stop\": \"2020-09-19T12:46:01.704Z\", \"resume\": \"2020-09-19T12:46:01.704Z\", \"startVariance\": 0, \"summary\": true, \"sv\": 0, \"units\": 0, \"updateNeeded\": true, \"vac\": 10, \"work\": \"80:0:0\", \"workContour\": \"Flat\", \"bcws\": 0, \"bcwp\": 0, \"bookingType\": \"Committed\", \"actualWorkProtected\": \"string\", \"actualOvertimeWorkProtected\": \"string\", \"creationDate\": \"2020-09-19T12:46:01.704Z\", \"assnOwner\": \"string\", \"assnOwnerGuid\": \"string\", \"budgetCost\": 0, \"budgetWork\": \"string\", \"rateScale\": \"Undefined\", \"baselines\": [ { \"baselineNumber\": \"Baseline\", \"work\": \"string\", \"cost\": 0, \"bcws\": 0, \"bcwp\": 0, \"start\": \"2020-09-19T12:46:01.704Z\", \"finish\": \"2020-09-19T12:46:01.704Z\" } ], \"extendedAttributes\": [ { \"fieldId\": \"string\", \"attributeType\": \"Null\", \"valueGuid\": \"string\", \"lookupValueId\": 0, \"durationValue\": { \"timeSpan\": \"string\", \"timeUnit\": \"Minute\" }, \"numericValue\": 0, \"dateValue\": \"2020-09-19T12:46:01.704Z\", \"flagValue\": true, \"textValue\": \"string\" } ], \"timephasedData\": [ { \"uid\": 1, \"start\": \"2019-09-10T12:46:01.704Z\", \"finish\": \"2019-09-10T14:46:01.704Z\", \"unit\": \"Minute\", \"value\": \"4:0:0\", \"timephasedDataType\": \"AssignmentRemainingWork\" } ]}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {
  "code": 0,
  "status": "string",
  "assignment": {
    "taskUid": 0,
    "resourceUid": 0,
    "guid": "string",
    "uid": 0,
    "percentWorkComplete": 0,
    "actualCost": 0,
    "actualFinish": "2020-09-19T12:53:11.646Z",
    "actualOvertimeCost": 0,
    "actualOvertimeWork": "string",
    "actualStart": "2020-09-19T12:53:11.646Z",
    "actualWork": "string",
    "acwp": 0,
    "confirmed": true,
    "cost": 0,
    "costRateTableType": "A",
    "costVariance": 0,
    "cv": 0,
    "delay": 0,
    "finish": "2020-09-19T12:53:11.646Z",
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
    "start": "2020-09-19T12:53:11.646Z",
    "stop": "2020-09-19T12:53:11.646Z",
    "resume": "2020-09-19T12:53:11.646Z",
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
    "creationDate": "2020-09-19T12:53:11.646Z",
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
        "start": "2020-09-19T12:53:11.646Z",
        "finish": "2020-09-19T12:53:11.646Z"
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
        "dateValue": "2020-09-19T12:53:11.646Z",
        "flagValue": true,
        "textValue": "string"
      }
    ],
    "timephasedData": [
      {
        "uid": 0,
        "start": "2020-09-19T12:53:11.646Z",
        "finish": "2020-09-19T12:53:11.646Z",
        "unit": "Minute",
        "value": "string",
        "timephasedDataType": "AssignmentRemainingWork"
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
{{< tabs tabTotal="3" tabID="5" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "bf5abcaf69eb7206a27121e93429accb" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "1f51b34600b31b08bcb318fbb51037db" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "b49b3a6bfac1d8f536ad610af65df02d" >}}

{{< /tab >}}

{{< /tabs >}}
