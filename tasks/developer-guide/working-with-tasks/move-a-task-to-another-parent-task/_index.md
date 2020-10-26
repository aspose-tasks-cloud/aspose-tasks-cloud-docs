---
title: "Move a Task to another Parent Task"
description: "Aspose.Tasks Cloud SDK for Python permits to move sub-task or child task from one parent to another parent task in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Java, Android, Python, Perl, PHP, Ruby, Jquery and many more."
keywords: "move a task to another parent task, REST API, move child task, child tasks in project management, using Python, Perl, MS Project Management, project management, move sub-task in mpp, mpt, xml, change parent of task"
type: docs
url: /move-a-task-to-another-parent-task/
weight: 80
---

## **Introduction**
Generally tasks are categorized as a parent task or a child task. A child tasks can be moved between the parent tasks. The following article further explains how to move a child task from one parent to another parent task using our REST API, which can be used with any language, like .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/move|PUT|Move one task to another parent task|[PutMoveTask](https://apireference.aspose.cloud/tasks/#/TasksTask/PutMoveTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/sample.mpp/tasks/10/move?parentTaskUid=6" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutMoveTask.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putMoveTask.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "3bdc1509d6f86275e105ee2c5800fe58" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "1f56a1fbd619ed14c477ab02c805e9eb" >}}

{{< /tab >}}

{{< /tabs >}}
