---
title: "Get Specific Calendar of a Project"
type: docs
url: /get-specific-calendar-of-a-project/
weight: 20
---

## **Introduction**
This example allows you to retrieve a project calendar information of specified UID.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}|GET|Read information for a specific calendar by UID|[GetCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendar)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "calendar": {
    "name": "string",
    "uid": 0,
    "days": [
      {
        "dayType": "Exception",
        "dayWorking": true,
        "fromDate": "2020-09-18T10:28:19.868Z",
        "toDate": "2020-09-18T10:28:19.868Z",
        "workingTimes": [
          {
            "fromTime": "2020-09-18T10:28:19.868Z",
            "toTime": "2020-09-18T10:28:19.868Z"
          }
        ]
      }
    ],
    "isBaseCalendar": true,
    "isBaselineCalendar": true
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-RetreiveCalendarInformationExample-RetreiveCalendarInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Calendars-GetProjectCalendars-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Calendars-get_project_calendars-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-calendars-RetreiveCalendarInformationExample-RetreiveCalendarInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-RetrieveCalendarInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "d0d4fdd8be8ef30822a118dce82a8693" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "fc590b9d24cc725817f34d92451106f7" >}}

{{< /tab >}}

{{< /tabs >}}
