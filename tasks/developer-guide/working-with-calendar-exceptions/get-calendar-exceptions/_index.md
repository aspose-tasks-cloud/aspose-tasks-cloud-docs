---
title: "Get Calendar Exceptions"
type: docs
url: /get-calendar-exceptions/
weight: 10
---

## **Introduction**
This example allows you to read information about calendar exceptions, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/calendarExceptions|GET|Read Calendar Exception Information|[GetCalendarExceptions](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendarExceptions)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/calendarExceptions" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "calendarExceptions": [
    {
      "index": 0,
      "enteredByOccurrences": true,
      "fromDate": "2020-09-19T09:47:07.348Z",
      "toDate": "2020-09-19T09:47:07.348Z",
      "occurrences": 0,
      "name": "string",
      "type": "Daily",
      "period": 0,
      "daysOfWeek": [
        "Exception"
      ],
      "monthItem": "Day",
      "monthPosition": "First",
      "month": "January",
      "monthDay": 0,
      "dayWorking": true,
      "workingTimes": [
        {
          "fromTime": "2020-09-19T09:47:07.348Z",
          "toTime": "2020-09-19T09:47:07.348Z"
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
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetCalendarExceptions.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getCalendarExceptions.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "7326e2e1f4f5527e82a8a472b12e9b16" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "c93e684781e1827971678fefad66876d" >}}

{{< /tab >}}

{{< /tabs >}}
