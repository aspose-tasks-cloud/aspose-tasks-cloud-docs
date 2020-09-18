---
title: "Add Calendar to Project"
type: docs
url: /add-calendar-to-project/
weight: 40
---

# **Introduction**
This example explains how to add a new calendar to a project.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars|POST|Add a calendar to a project|[PostCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PostCalendar)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU3MzQzNTYsImV4cCI6MTU2NTgyMDc1NiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.l84BMnrhpKql3maMy-X762KPj349xPMGIgVxxOtN8jlbYHtxKl397CWQZFhmJMzyX5n9Yv4Y9Svwv5xPxD10jydA-RhiBBUKD6bQuLXjMeNfxpIxX2LZA4QswYUYDLslRVCxLajpAqjJ3P25ERccvfD4btxFBm2ftGH5GcBHX7HL3R4bz9zasrfiVcQG8gzKV2O3_AE-eFX2YqC2J_HNUpWKs0_nogHqRz9SHcxmSe4D3n8NvSA4nyxI6VWPPJQiERpBBirKBWLlFk3RYapsDaQIhWFowjq7lWJbVMNi4UuoXaid9rimHtG8EpVWxDq1XRNiMZSdol60OXa-T_V_6g" -H "Content-Type: application/json" -d "{ \"Name\": \"new test\", \"Uid\": 0, \"Days\": [ { \"DayWorking\": true, \"DayType\":\"Monday\", \"FromDate\": \"2019-08-11T10:11:51.711Z\", \"ToDate\": \"2019-08-17T22:11:51.711Z\", \"WorkingTimes\": [ { \"FromTime\": \"2019-08-13T10:11:51.711Z\", \"ToTime\": \"2019-08-13T22:11:51.711Z\" } ] } ], \"IsBaseCalendar\": false, \"IsBaselineCalendar\": false}"    

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

   "CalendarItem":{

      "Link":{

         "Href":"/calendars/2",

         "Rel":"self",

         "Type":null,

         "Title":null

      },

      "Uid":2,

      "Name":"new test"

   },

   "Code":201,

   "Status":"Created"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-AddNewCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-AddCalendarToProjectExample-AddCalendarToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Calendars-PostProjectCalendar-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Calendars-add_new_calendar-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-calendars-AddCalendarToProjectExample-AddCalendarToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-AddCalendar-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "7a060769eda1675f5ac9a86d2a6fe94b" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "239a60a5e932bab6114a6c7d77b66522" >}}

{{< /tab >}}

{{< /tabs >}}
