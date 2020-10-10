---
title: "Get Recurring Information for the Task"
type: docs
url: /get-recurring-information-for-the-task/
weight: 60
---

## **Introduction**
This example explains how to you to get a recurring information for the task of specified UID.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/recurringInfo|GET|Read recurring information from a MS Project File|[GetTaskRecurringInfo](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTaskRecurringInfo)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/0/recurringInfo" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "recurringInfo": {
    "recurrencePattern": "Daily",
    "startDate": "2020-09-18T07:49:45.964Z",
    "endDate": "2020-09-18T07:49:45.964Z",
    "duration": "string",
    "occurrences": 0,
    "useEndDate": true,
    "dailyRepetitions": 0,
    "dailyUseWorkdays": true,
    "weeklyRepetitions": 0,
    "weeklyDays": "None",
    "monthlyUseOrdinalDay": true,
    "monthlyOrdinalNumber": "First",
    "monthlyOrdinalDay": "Sunday",
    "monthlyOrdinalRepetitions": 0,
    "monthlyDay": 0,
    "monthlyRepetitions": 0,
    "yearlyUseOrdinalDay": true,
    "yearlyDate": "2020-09-18T07:49:45.964Z",
    "yearlyOrdinalNumber": "First",
    "yearlyOrdinalDay": "Sunday",
    "yearlyOrdinalMonth": "January"
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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskRecurringInfo.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getRecurringInfo.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "e9275942e7bd7ebd7f80d0102cbc56e0" >}}


{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "7d282d74bb00eff5213377d33f3ac8c3" >}}

{{< /tab >}}

{{< /tabs >}}
