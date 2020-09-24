---
title: "Get work week collection of calendar"
type: docs
url: /get-work-week-collection-of-calendar/
weight: 30
---

## **Introduction**
This example explains how to get the collection of work weeks of the specified calendar. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/workWeeks|GET|Read work week information for a give Calendar within a MS Project File|[GetCalendarWorkWeeks](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendarWorkWeeks)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java
curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/workWeeks" -H "accept: application/json" 
```
{{< /tab >}}

{{< tab tabNum="2" >}}

```java
{
  "code": 0,
  "status": "string",
  "calendarWorkWeeks": [
    {
      "name": "string",
      "fromDate": "2020-09-18T10:29:50.766Z",
      "toDate": "2020-09-18T10:29:50.766Z",
      "weekDays": [
        {
          "dayType": "Exception",
          "dayWorking": true,
          "fromDate": "2020-09-18T10:29:50.767Z",
          "toDate": "2020-09-18T10:29:50.767Z",
          "workingTimes": [
            {
              "fromTime": "2020-09-18T10:29:50.767Z",
              "toTime": "2020-09-18T10:29:50.767Z"
            }
          ]
        }
      ]
    }
  ]
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="3" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendarWorkWeeks.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "1c9b883b7494105d23bc698ed86f19d4" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "19bbbecc45363d6611c08aa77150c0e8" >}}

{{< /tab >}}

{{< /tabs >}}
