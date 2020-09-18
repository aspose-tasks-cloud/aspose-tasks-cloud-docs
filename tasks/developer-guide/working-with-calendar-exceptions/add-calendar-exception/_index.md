---
title: "Add Calendar Exception"
type: docs
url: /add-calendar-exception/
weight: 20
---

# **Introduction**
This example allows you to add a new calendar exception to a calendar.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/calendarExceptions|POST|Add a Calendar Exception|[PostCalendarException](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PostCalendarException)|
### **cUL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/calendarExceptions" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU3MzQzNTYsImV4cCI6MTU2NTgyMDc1NiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.l84BMnrhpKql3maMy-X762KPj349xPMGIgVxxOtN8jlbYHtxKl397CWQZFhmJMzyX5n9Yv4Y9Svwv5xPxD10jydA-RhiBBUKD6bQuLXjMeNfxpIxX2LZA4QswYUYDLslRVCxLajpAqjJ3P25ERccvfD4btxFBm2ftGH5GcBHX7HL3R4bz9zasrfiVcQG8gzKV2O3_AE-eFX2YqC2J_HNUpWKs0_nogHqRz9SHcxmSe4D3n8NvSA4nyxI6VWPPJQiERpBBirKBWLlFk3RYapsDaQIhWFowjq7lWJbVMNi4UuoXaid9rimHtG8EpVWxDq1XRNiMZSdol60OXa-T_V_6g" -H "Content-Type: application/json" -d "{ \"Index\": 0, \"EnteredByOccurrences\": true, \"FromDate\": \"2019-08-13T23:16:59.908Z\", \"ToDate\": \"2019-08-13T23:16:59.908Z\", \"Occurrences\": 0, \"Name\": \"New Test\", \"Period\": 0, \"DaysOfWeek\": [ 0 ], \"MonthDay\": 0, \"DayWorking\": true, \"WorkingTimes\": [ { \"FromTime\": \"2019-08-13T23:16:59.909Z\", \"ToTime\": \"2019-08-13T23:16:59.909Z\" } ]}"

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
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Perl" tabName3="Android" tabName4="Python" tabName5="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-AddCalendarException.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-PostCalendarExceptions-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-AddCalendarExceptionExample-1.java" >}}



{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "cf4b68e9e3e97b3bfecb5fca1186fd33" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "834ee6310c3993e7ac69d5ab4816e486" >}}

{{< /tab >}}

{{< /tabs >}}
