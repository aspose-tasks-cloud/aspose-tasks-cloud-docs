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
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getCalendar.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "d0d4fdd8be8ef30822a118dce82a8693" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "fc590b9d24cc725817f34d92451106f7" >}}

{{< /tab >}}

{{< /tabs >}}
