---
title: "Add Calendar Exception"
type: docs
url: /add-calendar-exception/
weight: 20
---

## **Introduction**
This example allows you to add a new calendar exception to a calendar, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/calendarExceptions|POST|Add a Calendar Exception|[PostCalendarException](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PostCalendarException)|
### **cUL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/calendarExceptions" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Index\": 0, \"EnteredByOccurrences\": true, \"FromDate\": \"2019-08-13T23:16:59.908Z\", \"ToDate\": \"2019-08-13T23:16:59.908Z\", \"Occurrences\": 0, \"Name\": \"New Test\", \"Period\": 0, \"DaysOfWeek\": [ 0 ], \"MonthDay\": 0, \"DayWorking\": true, \"WorkingTimes\": [ { \"FromTime\": \"2019-08-13T23:16:59.909Z\", \"ToTime\": \"2019-08-13T23:16:59.909Z\" } ]}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Code": "200",
  "Status": "OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostCalendarException.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-postCalendarException.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "cf4b68e9e3e97b3bfecb5fca1186fd33" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "834ee6310c3993e7ac69d5ab4816e486" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PostCalendarException.go" >}}

{{< /tab >}}

{{< /tabs >}}
