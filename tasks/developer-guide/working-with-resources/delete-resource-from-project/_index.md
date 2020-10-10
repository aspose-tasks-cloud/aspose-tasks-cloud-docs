---
title: "Delete Resource From Project"
type: docs
url: /delete-resource-from-project/
weight: 20
---

## **Introduction**
This example allows you to delete a resource using Aspose.Tasks Cloud API in your applications.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources/{resourceUid}|DELETE|Delete an Assignment from a MS Project|[DeleteResource](https://apireference.aspose.cloud/tasks/#/TasksResources/DeleteResource)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/resources/1" -H "accept: application/json"

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
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Resources-DeleteResource-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-deleteResource.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "9c962bc5504452579884a1c131bd5a9e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "07d78654b167adaec0092ee353df17a9" >}}

{{< /tab >}}

{{< /tabs >}}
