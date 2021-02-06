---
title: "Add Calendar to Project"
type: docs
url: /add-calendar-to-project/
weight: 40
---

## **Introduction**
This example explains how to add a new calendar to a project, using Aspose.Tasks Cloud. Aspose.Tasks Clous is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars|POST|Add a calendar to a project|[PostCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PostCalendar)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Name\": \"new test\", \"Uid\": 0, \"Days\": [ { \"DayWorking\": true, \"DayType\":\"Monday\", \"FromDate\": \"2019-08-11T10:11:51.711Z\", \"ToDate\": \"2019-08-17T22:11:51.711Z\", \"WorkingTimes\": [ { \"FromTime\": \"2019-08-13T10:11:51.711Z\", \"ToTime\": \"2019-08-13T22:11:51.711Z\" } ] } ], \"IsBaseCalendar\": false, \"IsBaselineCalendar\": false}"    

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "calendarItem": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "uid": 0,
    "name": "string"
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

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-postCalendar.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "7a060769eda1675f5ac9a86d2a6fe94b" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "239a60a5e932bab6114a6c7d77b66522" >}}

{{< /tab >}}

{{< /tabs >}}
