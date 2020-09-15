---
title: "Delete a Calendar from Project"
type: docs
url: /delete-a-calendar-from-project/
weight: 60
---

# **Introduction**
This example allows you to delete a calendar from project.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}|DELETE|Deletes a project calendar|[DeleteCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/DeleteCalendar)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/2" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU3MzQzNTYsImV4cCI6MTU2NTgyMDc1NiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.l84BMnrhpKql3maMy-X762KPj349xPMGIgVxxOtN8jlbYHtxKl397CWQZFhmJMzyX5n9Yv4Y9Svwv5xPxD10jydA-RhiBBUKD6bQuLXjMeNfxpIxX2LZA4QswYUYDLslRVCxLajpAqjJ3P25ERccvfD4btxFBm2ftGH5GcBHX7HL3R4bz9zasrfiVcQG8gzKV2O3\_AE-eFX2YqC2J\_HNUpWKs0\_nogHqRz9SHcxmSe4D3n8NvSA4nyxI6VWPPJQiERpBBirKBWLlFk3RYapsDaQIhWFowjq7lWJbVMNi4UuoXaid9rimHtG8EpVWxDq1XRNiMZSdol60OXa-T\_V\_6g"

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
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-DeleteCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-DeleteCalendarFromProjectExample-DeleteCalendarFromProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Calendars-DeleteProjectCalendar-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Calendars-delete\_project\_calendar-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-calendars-DeleteCalendarFromProjectExample-DeleteCalendarFromProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-DeleteCalendar-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "2fd8a6deff1f4b547e61630eb6042376" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "e0009d7563b9cbcffa4c02d65f6fb7be" >}}

{{< /tab >}}

{{< /tabs >}}
