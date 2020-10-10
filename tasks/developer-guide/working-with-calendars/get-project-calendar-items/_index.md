---
title: "Get Project Calendar Items"
type: docs
url: /get-project-calendar-items/
weight: 10
---

## **Introduction**
This example explains how to read information regarding a project calendar items. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars|GET|Read Calendar information from|[GetCalendars](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendars)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java
{
  "code": 0,
  "status": "string",
  "calendars": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "list": [
      {
        "link": {
          "href": "string",
          "rel": "string",
          "type": "string",
          "title": "string"
        },
        "uid": 0,
        "name": "string"
      }
    ]
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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendars.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getCalendars.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "67fa9bd24001288c7086f92cd2f9ecda" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "e86fd5ec8d6d12e25fe69b696ea2fb72" >}}

{{< /tab >}}

{{< /tabs >}}
