---
title: "Edit Specific Resource Assignment"
type: docs
url: /edit-specific-resource-assignment/
weight: 60
---

## **Introduction**
This example explains how to edit a resource assignment within a MS Project file using a resource identifier, with Aspose.Tasks Cloud. Aspose.Tasks Clous is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}|PUT|Update a Resource in a MS Project file using a identifer|[PutAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/PutAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant_type=client_credentials&client_id=XXXXX&client_secret=XXXXX" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/assignments/1?mode=1&recalculate=true" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"TaskUid\": 0, \"ResourceUid\": 0, \"Uid\": 0, \"PercentWorkComplete\": 0, \"ActualCost\": 0, \"ActualFinish\": \"2019-07-12T22:10:41.984Z\", \"ActualOvertimeCost\": 0, \"ActualOvertimeWork\": \"string\", \"ActualStart\": \"2019-07-12T22:10:41.984Z\", \"ActualWork\": \"string\", \"Acwp\": 0, \"Confirmed\": true, \"Cost\": 0, \"CostVariance\": 0, \"Cv\": 0, \"Delay\": 0, \"Finish\": \"2019-07-12T22:10:41.984Z\", \"FinishVariance\": 0, \"Hyperlink\": \"string\", \"HyperlinkAddress\": \"string\", \"HyperlinkSubAddress\": \"string\", \"WorkVariance\": 0, \"HasFixedRateUnits\": true, \"FixedMaterial\": true, \"LevelingDelay\": 0, \"LinkedFields\": true, \"Milestone\": true, \"Notes\": \"string\", \"Overallocated\": true, \"OvertimeCost\": 0, \"OvertimeWork\": \"string\", \"PeakUnits\": 0, \"RegularWork\": \"string\", \"RemainingCost\": 0, \"RemainingOvertimeCost\": 0, \"RemainingOvertimeWork\": \"string\", \"RemainingWork\": \"string\", \"ResponsePending\": true, \"Start\": \"2019-07-12T22:10:41.984Z\", \"Stop\": \"2019-07-12T22:10:41.984Z\", \"Resume\": \"2019-07-12T22:10:41.984Z\", \"StartVariance\": 0, \"Summary\": true, \"Sv\": 0, \"Units\": 0, \"UpdateNeeded\": true, \"Vac\": 0, \"Work\": \"string\", \"Bcws\": 0, \"Bcwp\": 0, \"ActualWorkProtected\": \"string\", \"ActualOvertimeWorkProtected\": \"string\", \"CreationDate\": \"2019-07-12T22:10:41.984Z\", \"AssnOwner\": \"string\", \"AssnOwnerGuid\": \"string\", \"BudgetCost\": 0, \"BudgetWork\": \"string\", \"Baselines\": [ { \"Work\": \"string\", \"Cost\": 0, \"Bcws\": 0, \"Bcwp\": 0, \"Start\": \"2019-07-12T22:10:41.984Z\", \"Finish\": \"2019-07-12T22:10:41.984Z\" } ], \"ExtendedAttributes\": [ { \"FieldId\": \"string\", \"ValueGuid\": \"string\", \"LookupValueId\": 0, \"DurationValue\": { \"TimeSpan\": \"string\" }, \"NumericValue\": 0, \"DateValue\": \"2019-07-12T22:10:41.984Z\", \"FlagValue\": true, \"TextValue\": \"string\" } ]}"

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
    "actualFinish": "2020-09-17T14:39:11.957Z",
    "actualOvertimeCost": 0,
    "actualOvertimeWork": "string",
    "actualStart": "2020-09-17T14:39:11.957Z",
    "actualWork": "string",
    "acwp": 0,
    "confirmed": true,
    "cost": 0,
    "costRateTableType": "A",
    "costVariance": 0,
    "cv": 0,
    "delay": 0,
    "finish": "2020-09-17T14:39:11.957Z",
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
    "start": "2020-09-17T14:39:11.957Z",
    "stop": "2020-09-17T14:39:11.957Z",
    "resume": "2020-09-17T14:39:11.957Z",
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
    "creationDate": "2020-09-17T14:39:11.957Z",
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
        "start": "2020-09-17T14:39:11.957Z",
        "finish": "2020-09-17T14:39:11.957Z"
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
        "dateValue": "2020-09-17T14:39:11.957Z",
        "flagValue": true,
        "textValue": "string"
      }
    ],
    "timephasedData": [
      {
        "uid": 0,
        "start": "2020-09-17T14:39:11.957Z",
        "finish": "2020-09-17T14:39:11.957Z",
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
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Pyhton" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostAssignment.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-PutAssignment.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "c072419ccc74ff9a4da89ca4865f2cfe" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "9146d85a417234e85ff11bb792b014b3" >}}

{{< /tab >}}

{{< /tabs >}}
