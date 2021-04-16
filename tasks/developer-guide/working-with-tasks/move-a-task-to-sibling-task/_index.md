---
title: "Move a Task to Sibling Task"
type: docs
url: /move-a-task-to-sibling-task/
weight: 90
---

## **Introduction**
This example explains how to move a task to another position under the same parent and the same outline level, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/moveToSibling|PUT|Move a task to another position under the same parent and the same outline level|[PutMoveTaskToSibling](https://apireference.aspose.cloud/tasks/#/TasksTask/PutMoveTaskToSibling)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/tasks/41/moveToSibling?beforeTaskUid=40" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java
{
   "Code":200,
   "Status":"OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutMoveTaskToSibling.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putMoveTaskToSibling.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "80896afba4a178d400e78ba30f954f46" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "8152e642a0ef361de0c534314304ec6c" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutMoveTaskToSibling.go" >}}

{{< /tab >}}

{{< /tabs >}}
