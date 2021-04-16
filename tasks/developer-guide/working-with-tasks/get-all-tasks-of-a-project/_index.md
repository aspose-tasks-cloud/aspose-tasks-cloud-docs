---
title: "Get all Tasks of a Project"
type: docs
url: /get-all-tasks-of-a-project/
weight: 10
---

## **Introduction**
This example explains how read task information from a MS Project File, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks|GET|Read project's tasks|[GetTasks](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTasks)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "tasks": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "taskItem": [
      {
        "link": {
          "href": "string",
          "rel": "string",
          "type": "string",
          "title": "string"
        },
        "uid": 0,
        "id": 0,
        "name": "string",
        "start": "2020-09-18T07:18:50.238Z",
        "finish": "2020-09-18T07:18:50.238Z",
        "duration": "string"
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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetTasks.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getTasks.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "605fdb3499b69bd1906a2781061ea56e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "e4a793b894a658785d4a7c64e12dc93d" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetTasks.go" >}}

{{< /tab >}}

{{< /tabs >}}
