---
title: "Edit a Project Calendar"
type: docs
url: /edit-a-project-calendar/
weight: 50
---

## **Introduction**
This example explains how to edit an existing project calendar.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars|PUT|Update a Calendar in a Project|[PutCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PutCalendar)|

### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars?calendarUid=1" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Name\": \"standard\", \"Uid\": 1, \"Days\": [ { \"DayWorking\": true, \"DayType\":\"Monday\", \"FromDate\": \"2019-08-13T22:17:33.805Z\", \"ToDate\": \"2019-08-13T22:17:33.805Z\", \"WorkingTimes\": [ { \"FromTime\": \"2019-08-13T22:17:33.805Z\", \"ToTime\": \"2019-08-13T22:17:33.805Z\" } ] } ], \"IsBaseCalendar\": true, \"IsBaselineCalendar\": true}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
   "Code":200,
   "Status":"OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putCalendar.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "bda12c0d44c6abf7a57c205bedcfead9" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a628374682411b62b33211ef2ef897db" >}}

{{< /tab >}}

{{< /tabs >}}
