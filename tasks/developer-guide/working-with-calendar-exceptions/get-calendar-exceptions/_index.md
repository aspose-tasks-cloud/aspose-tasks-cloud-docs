---
title: "Get Calendar Exceptions"
type: docs
url: /get-calendar-exceptions/
weight: 10
---

## **Introduction**
This example allows you to read information about calendar exceptions.
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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Perl" tabName3="Java" tabName4="Python" tabName5="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendarExceptions.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-GetCalendarExceptions-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-RetreiveCalendarInformationExample-RetreiveCalendarInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "7326e2e1f4f5527e82a8a472b12e9b16" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "c93e684781e1827971678fefad66876d" >}}

{{< /tab >}}

{{< /tabs >}}
