---
title: "Edit a Project Calendar"
type: docs
url: /edit-a-project-calendar/
weight: 50
---

# **Introduction**
This example explains how to edit an existing project calendar.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars|PUT|Update a Calendar in a Project|[PutCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PutCalendar)|

### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars?calendarUid=1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU3MzQzNTYsImV4cCI6MTU2NTgyMDc1NiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.l84BMnrhpKql3maMy-X762KPj349xPMGIgVxxOtN8jlbYHtxKl397CWQZFhmJMzyX5n9Yv4Y9Svwv5xPxD10jydA-RhiBBUKD6bQuLXjMeNfxpIxX2LZA4QswYUYDLslRVCxLajpAqjJ3P25ERccvfD4btxFBm2ftGH5GcBHX7HL3R4bz9zasrfiVcQG8gzKV2O3_AE-eFX2YqC2J_HNUpWKs0_nogHqRz9SHcxmSe4D3n8NvSA4nyxI6VWPPJQiERpBBirKBWLlFk3RYapsDaQIhWFowjq7lWJbVMNi4UuoXaid9rimHtG8EpVWxDq1XRNiMZSdol60OXa-T_V_6g" -H "Content-Type: application/json" -d "{ \"Name\": \"standard\", \"Uid\": 1, \"Days\": [ { \"DayWorking\": true, \"DayType\":\"Monday\", \"FromDate\": \"2019-08-13T22:17:33.805Z\", \"ToDate\": \"2019-08-13T22:17:33.805Z\", \"WorkingTimes\": [ { \"FromTime\": \"2019-08-13T22:17:33.805Z\", \"ToTime\": \"2019-08-13T22:17:33.805Z\" } ] } ], \"IsBaseCalendar\": true, \"IsBaselineCalendar\": true}"

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
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-PutCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "bda12c0d44c6abf7a57c205bedcfead9" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "a628374682411b62b33211ef2ef897db" >}}

{{< /tab >}}

{{< /tabs >}}
