---
title: "Update a Specific Resource To Project"
type: docs
url: /update-a-specific-resource-to-project/
weight: 30
---

## **Introduction**
This example allows you to update a resource with the specific ID to a Project, using Aspose.Tasks Cloud API in your applications. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks​/{name}​/resources​/{resourceUid}|PUT|Updates resource with the specified Uid|[PutResource](https://apireference.aspose.cloud/tasks/#/TasksResources/PutResource)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Resource6/resources/6?mode=Automatic&recalculate=true" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"name\": \"string\", \"uid\": 0, \"id\": 0, \"guid\": \"string\", \"type\": \"Material\", \"isNull\": true, \"initials\": \"string\", \"phonetics\": \"string\", \"ntAccount\": \"string\", \"windowsUserAccount\": \"string\", \"workgroup\": \"Default\", \"materialLabel\": \"string\", \"code\": \"string\", \"group\": \"string\", \"emailAddress\": \"string\", \"hyperlink\": \"string\", \"hyperlinkAddress\": \"string\", \"hyperlinkSubAddress\": \"string\", \"maxUnits\": 0, \"peakUnits\": 0, \"overAllocated\": true, \"availableFrom\": \"2020-11-14T19:06:51.443Z\", \"availableTo\": \"2020-11-14T19:06:51.443Z\", \"start\": \"2020-11-14T19:06:51.443Z\", \"finish\": \"2020-11-14T19:06:51.443Z\", \"canLevel\": true, \"accrueAt\": \"Start\", \"work\": \"string\", \"regularWork\": \"string\", \"overtimeWork\": \"string\", \"actualWork\": \"string\", \"remainingWork\": \"string\", \"actualOvertimeWork\": \"string\", \"remainingOvertimeWork\": \"string\", \"percentWorkComplete\": 0, \"standardRate\": 0, \"standardRateFormat\": \"Minute\", \"cost\": 0, \"overtimeRateFormat\": \"Minute\", \"overtimeCost\": 0, \"costPerUse\": 0, \"actualCost\": 0, \"actualOvertimeCost\": 0, \"remainingCost\": 0, \"remainingOvertimeCost\": 0, \"workVariance\": 0, \"costVariance\": 0, \"sv\": 0, \"cv\": 0, \"acwp\": 0, \"calendarUid\": 0, \"notesText\": \"string\", \"notes\": \"string\", \"notesRTF\": \"string\", \"bcws\": 0, \"bcwp\": 0, \"isGeneric\": true, \"isInactive\": true, \"isEnterprise\": true, \"bookingType\": \"Committed\", \"actualWorkProtected\": \"string\", \"actualOvertimeWorkProtected\": \"string\", \"activeDirectoryGuid\": \"string\", \"creationDate\": \"2020-11-14T19:06:51.443Z\", \"costCenter\": \"string\", \"isCostResource\": true, \"teamAssignmentPool\": true, \"assignmentOwner\": \"string\", \"assignmentOwnerGuid\": \"string\", \"isBudget\": true, \"budgetWork\": \"string\", \"budgetCost\": 0, \"overtimeRate\": 0, \"baselines\": [ { \"baselineNumber\": \"Baseline\", \"work\": \"string\", \"cost\": 0, \"bcws\": 0, \"bcwp\": 0 } ], \"extendedAttributes\": [ { \"fieldId\": \"string\", \"attributeType\": \"Null\", \"valueGuid\": \"string\", \"lookupValueId\": 0, \"durationValue\": { \"timeSpan\": \"string\", \"timeUnit\": \"Minute\" }, \"numericValue\": 0, \"dateValue\": \"2020-11-14T19:06:51.443Z\", \"flagValue\": true, \"textValue\": \"string\" } ], \"outlineCodes\": [ { \"fieldId\": \"string\", \"valueId\": 0, \"valueGuid\": \"string\" } ]}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "resource": {
    "name": "string",
    "uid": 0,
    "id": 0,
    "guid": "string",
    "type": "Material",
    "isNull": true,
    "initials": "string",
    "phonetics": "string",
    "ntAccount": "string",
    "windowsUserAccount": "string",
    "workgroup": "Default",
    "materialLabel": "string",
    "code": "string",
    "group": "string",
    "emailAddress": "string",
    "hyperlink": "string",
    "hyperlinkAddress": "string",
    "hyperlinkSubAddress": "string",
    "maxUnits": 0,
    "peakUnits": 0,
    "overAllocated": true,
    "availableFrom": "2020-11-14T19:10:23.880Z",
    "availableTo": "2020-11-14T19:10:23.880Z",
    "start": "2020-11-14T19:10:23.880Z",
    "finish": "2020-11-14T19:10:23.880Z",
    "canLevel": true,
    "accrueAt": "Start",
    "work": "string",
    "regularWork": "string",
    "overtimeWork": "string",
    "actualWork": "string",
    "remainingWork": "string",
    "actualOvertimeWork": "string",
    "remainingOvertimeWork": "string",
    "percentWorkComplete": 0,
    "standardRate": 0,
    "standardRateFormat": "Minute",
    "cost": 0,
    "overtimeRateFormat": "Minute",
    "overtimeCost": 0,
    "costPerUse": 0,
    "actualCost": 0,
    "actualOvertimeCost": 0,
    "remainingCost": 0,
    "remainingOvertimeCost": 0,
    "workVariance": 0,
    "costVariance": 0,
    "sv": 0,
    "cv": 0,
    "acwp": 0,
    "calendarUid": 0,
    "notesText": "string",
    "notes": "string",
    "notesRTF": "string",
    "bcws": 0,
    "bcwp": 0,
    "isGeneric": true,
    "isInactive": true,
    "isEnterprise": true,
    "bookingType": "Committed",
    "actualWorkProtected": "string",
    "actualOvertimeWorkProtected": "string",
    "activeDirectoryGuid": "string",
    "creationDate": "2020-11-14T19:10:23.880Z",
    "costCenter": "string",
    "isCostResource": true,
    "teamAssignmentPool": true,
    "assignmentOwner": "string",
    "assignmentOwnerGuid": "string",
    "isBudget": true,
    "budgetWork": "string",
    "budgetCost": 0,
    "overtimeRate": 0,
    "baselines": [
      {
        "baselineNumber": "Baseline",
        "work": "string",
        "cost": 0,
        "bcws": 0,
        "bcwp": 0
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
        "dateValue": "2020-11-14T19:10:23.880Z",
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
    ]
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

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutResource.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putResource.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "Examples-PutResource.py" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a512cbc1b45ae6e3494454dfbceecaa4" "Examples-PutResource.ts" >}}

{{< /tab >}}

{{< /tabs >}}
