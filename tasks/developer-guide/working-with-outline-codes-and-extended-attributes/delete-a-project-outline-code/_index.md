---
title: "Delete A Project Outline Code"
type: docs
url: /delete-a-project-outline-code/
weight: 30
---

## **Introduction**
This example allows you to delete a project Outline Code using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :-: | :-: | :-: | :-: |
|/tasks/{name}/outlineCodes/{index}|DELETE|Deletes a project outline code|[DeleteOutlineCodeByIndex](https://apireference.aspose.cloud/tasks/#/TasksOutlineCodes/DeleteOutlineCodeByIndex)|

### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/ExtendedAttribute.mpp/outlineCodes/1" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-DeleteProjectCode-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-DeleteOutlineCodeByIndex-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "17b7bef46479513630b46d1707940ee5" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "fd28c620b64c53ee66e4a4c5c210966a" >}}

{{< /tab >}}

{{< /tabs >}}
