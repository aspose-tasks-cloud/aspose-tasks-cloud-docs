---
title: "Move a Task to Sibling Task"
type: docs
url: /move-a-task-to-sibling-task/
weight: 90
---

# **Introduction**
This example explains how to move a task to another position under the same parent and the same outline level. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/moveToSibling|PUT|Move a task to another position under the same parent and the same outline level|[PutMoveTaskToSibling](https://apireference.aspose.cloud/tasks/#/TasksTask/PutMoveTaskToSibling)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v http://api.aspose.cloud/v1.1/tasks/NewProductDev.mpp/tasks/41/moveToSibling?beforeTaskUid=40&fileName=resultingFile.mpp&appsid=xxxx&signature=xxxx \
    -X PUT \
    -H "Content-Type: application/json" \
    -H "Accept: application/json"

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
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-MoveTaskToSibling.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "80896afba4a178d400e78ba30f954f46" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "8152e642a0ef361de0c534314304ec6c" >}}

{{< /tab >}}

{{< /tabs >}}
