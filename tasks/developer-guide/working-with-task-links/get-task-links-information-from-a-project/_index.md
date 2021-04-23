---
title: "Get Task Links Information from a Project"
description: "Aspose.Tasks Cloud allows you to get task links information from a project in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /get-task-links-information-from-a-project/
weight: 10
---

## **Introduction**
This example allows you to retrieve a Project's Tasks links information using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/taskLinks|GET|Read Task Links|[GetTaskLinks](https://apireference.aspose.cloud/tasks/#/TasksTaskLinks/GetTaskLinks)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/taskLinks" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java
{
  "code": 0,
  "status": "string",
  "taskLinks": [
    {
      "link": {
        "href": "string",
        "rel": "string",
        "type": "string",
        "title": "string"
      },
      "index": 0,
      "predecessorUid": 0,
      "successorUid": 0,
      "linkType": "FinishToFinish",
      "lag": 0,
      "lagFormat": "Minute"
    }
  ]
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetTaskLinks.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getTaskLinks.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "0d8fcd760c1c8c6d8ab66530c8779d20" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "0009a7d47e87b73a12bda5200ff45ce2" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetTaskLinks.go" >}}

{{< /tab >}}

{{< /tabs >}}
