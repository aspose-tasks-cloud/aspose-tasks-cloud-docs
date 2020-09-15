---
title: "Update Calendar Exception"
type: docs
url: /update-calendar-exception/
weight: 30
---

# **Introduction**
This example explains you how to update calendar exception.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/calendarExceptions/{index}|PUT|Update a Calendar Exceptions|[PutCalendarException](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PutCalendarException)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/calendarExceptions/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU3MzkyNTIsImV4cCI6MTU2NTgyNTY1MiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.BjuV75wIhcBN3gPy0m3tnLOU90W2hfD2MhBvssR3I\_sWh-SQf5eZfXIZppdQ\_OSijwZyLyiekvl2Ix0LNlCbNNamhyswlTiTqpyEy-zidoGpN\_K0fFfKqGJL7dzRJ5snr5G1\_lyP0ZmYKURG3TRAiULYM7RDlM9gyhkxPtcurBZlGpTxC-3VWmkzejw685\_WKPv9vGnXWIBglqHuGySG8ai4m5dmJckwPORbRaI9wb-r4ix9ytPwHFtsv3rtm9JSReB9khxIm9qLPLYbHgazKDZzmakegZDlGbu7SEwMLG--73JInd\_zE0Jc8evy4arLWBK94Sv0HFVUc-xyQ4PeRQ" -H "Content-Type: application/json" -d "{ \"Index\":1, \"EnteredByOccurrences\":true, \"FromDate\":\"2019-08-13T00:00:00\", \"ToDate\":\"2019-08-13T23:59:00\", \"Occurrences\":0, \"Name\":\"New Test\", \"Type\":\"Daily\", \"Period\":1, \"DaysOfWeek\":[ ], \"MonthItem\":\"Undefined\", \"MonthPosition\":\"Undefined\", \"Month\":\"Undefined\", \"MonthDay\":0, \"DayWorking\":true, \"WorkingTimes\":[ { \"FromTime\":\"0010-01-01T23:16:00Z\", \"ToTime\":\"0010-01-01T23:16:00Z\" } ] }"    

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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Perl" tabName3="Java" tabName4="Python" tabName5="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-PutCalendarException.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-UpdateCalendarException-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}



{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-UpdateCalendarExceptionExample-1.java" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "8b5f140e35a59c5a232fa0fc79d40724" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "86061cf7b844b0e79cde1ae857928a4d" >}}

{{< /tab >}}

{{< /tabs >}}
