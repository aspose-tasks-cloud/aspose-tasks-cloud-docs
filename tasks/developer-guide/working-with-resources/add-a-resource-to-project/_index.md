---
title: "Add a Resource To Project"
description: "Aspose.Tasks Cloud allows you to add a resource to project in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /add-a-resource-to-project/
weight: 30
---

## **Introduction**
This example allows you to add a resource to a Project using Aspose.Tasks Cloud API in your applications. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
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
{{< tabs tabTotal="6" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostResource.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-postResource.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "810fb8411964a204a18d1bd3bec0905f" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "4355375b5bb8328adf1c872093c31eca" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PostResource.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PostResource.java" >}}

{{< /tab >}}

{{< /tabs >}}
