---
title: "Delete an Assignment from a Project"
type: docs
url: /delete-an-assignment-from-a-project/
weight: 70
---

## **Introduction**
This example allows you to delete a project assignment along with all references to it.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}|DELETE|Deletes a project assignment with all references to it|[DeleteAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/DeleteAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/assignments/63" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"
```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Code": 200,
  "Status": "OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-DeleteAssignment.cs" >}}

{{< /tab >}}


{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-DeleteAssignment.php" >}}

{{< /tab >}}


{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "4e1ebfbac301828bbb12a9dddc25187f" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a6b3d3367787147c5eb3be5b7048d77e" >}}

{{< /tab >}}

{{< /tabs >}}
