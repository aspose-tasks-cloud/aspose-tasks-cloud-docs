---
title: "Add a Resource To Project"
type: docs
url: /add-a-resource-to-project/
weight: 30
---

## **Introduction**
This example allows you to add a resource to a Project using Aspose.Tasks Cloud API in your applications.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources|POST|Add a named resource to a MS Project Document|[PostResource](https://apireference.aspose.cloud/tasks/#/TasksResources/PostResource)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/sample-project.mpp/resources?resourceName=Resource6&beforeResourceId=1" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "resourceItem": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "uid": 0,
    "id": 0,
    "name": "string"
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Resources-AddResource-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Resources-PostProjectResource-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "810fb8411964a204a18d1bd3bec0905f" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "4355375b5bb8328adf1c872093c31eca" >}}

{{< /tab >}}

{{< /tabs >}}
