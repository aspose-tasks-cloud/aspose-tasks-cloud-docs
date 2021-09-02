---
title: "Delete a Calendar from Project"
description: "Aspose.Tasks Cloud allows you to delete a calendar from project in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /delete-a-calendar-from-project/
weight: 60
---

## **Introduction**
This example allows you to delete a calendar from project, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}|DELETE|Deletes a project calendar|[DeleteCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/DeleteCalendar)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/2" -H "accept: application/json"

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
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}


{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-DeleteCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-deleteCalendar.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "2fd8a6deff1f4b547e61630eb6042376" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "e0009d7563b9cbcffa4c02d65f6fb7be" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-DeleteCalendar.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-DeleteCalendar.java" >}}

{{< /tab >}}

{{< /tabs >}}
