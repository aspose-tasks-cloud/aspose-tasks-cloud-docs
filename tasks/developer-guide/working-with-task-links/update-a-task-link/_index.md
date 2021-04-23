---
title: "Update a Task Link"
description: "Aspose.Tasks Cloud allows you to update a task link in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /update-a-task-link/
weight: 30
---

## **Introduction**
This example allows you to update a task link in a Project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/taskLinks|PUT|Update a existing task link|[PutTaskLink](https://apireference.aspose.cloud/tasks/#/TasksTaskLinks/PutTaskLink)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/taskLinks/0" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"link\": { \"href\": \"string\", \"rel\": \"string\", \"type\": \"string\", \"title\": \"string\" }, \"index\": 1, \"predecessorUid\": 0, \"successorUid\": 0, \"linkType\": \"FinishToFinish\", \"lag\": 0, \"lagFormat\": \"Minute\"}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "taskLink": {
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
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutTaskLink.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putTaskLink.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "765de786e9815b9db6e2525ceb0cda8f" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "9cbeae487fe48f61c0c696116936d7cf" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutTaskLink.go" >}}

{{< /tab >}}

{{< /tabs >}}
