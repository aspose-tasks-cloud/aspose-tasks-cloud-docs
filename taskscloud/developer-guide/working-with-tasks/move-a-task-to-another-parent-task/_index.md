---
title: "Move a Task to another Parent Task"
type: docs
url: /move-a-task-to-another-parent-task/
weight: 80
---

# **Introduction**
This example explains how to move one task to another parent task. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/move|PUT|Move one task to another parent task|[PutMoveTask](https://apireference.aspose.cloud/tasks/#/TasksTask/PutMoveTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/sample.mpp/tasks/10/move?parentTaskUid=6" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

  "code": 0,

  "status": "string"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-MoveTask.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "3bdc1509d6f86275e105ee2c5800fe58" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "1f56a1fbd619ed14c477ab02c805e9eb" >}}

{{< /tab >}}

{{< /tabs >}}
