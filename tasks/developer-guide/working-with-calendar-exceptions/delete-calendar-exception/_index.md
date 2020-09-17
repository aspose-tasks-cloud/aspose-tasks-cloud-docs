---
title: "Delete Calendar Exception"
type: docs
url: /delete-calendar-exception/
weight: 40
---

# **Introduction**
This example allows you to delete calendar exception from calendar exceptions collection.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/calendarExceptions/{index}|DELETE|Delete a calendar Exception|[DeleteCalendarException](https://apireference.aspose.cloud/tasks/#/TasksCalendar/DeleteCalendarException)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/calendarExceptions/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU4MTM4MzMsImV4cCI6MTU2NTkwMDIzMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.i-jvPiyFTxus_07QqK7tPLNffcFb_iwyCIFpdL81pCTqWmh5-Bolcj293rgYJoaQeDsLyoCXcQNN9C-BUUb_xWfOsJNX1zw_GE-G5J-DOKbuBxJqYC1z2LK3LNxeRgHyK4ubKQktSctiMxDOeMBBge20PRCNvTZHxgagUAQ5Va3KWA43F9F3GaB2AtS09t8IB1ADQThhn6YpP5mBzkiX7gkYU0BGETt2oZ0sZjGFbKUDlTasUc4sWj-rTbsClNoLFYvYJ55jvZW3QefO8hndVsngM8U7Z3jDvuGVlAyBoklwGlADaSR_u00Of5ybzbfcMWjM8cSS83tJZwQ4fL3xKQ"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{  

  "Code": 200,

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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-DeleteCalendarException.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-DeleteCalendarException-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-DeleteCalendarFromProjectExample-DeleteCalendarFromProjectExample.java" >}}



{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "51e5a7e482f4658d82d73056b2328b42" >}}



{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "ac3310017797b93ac001081bbfcb0002" >}}

{{< /tab >}}

{{< /tabs >}}
