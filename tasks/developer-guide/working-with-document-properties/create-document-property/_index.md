---
title: "Create Document Property"
description: "Aspose.Tasks Cloud allows you to create document property in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /create-document-property/
weight: 30
---

## **Introduction**
This example explains how to create document property, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/documentproperties/{propertyName}|POST|Create a property in a MS Project File|[PostDocumentProperty](https://apireference.aspose.cloud/tasks/#/TasksDocumentProperties/PostDocumentProperty)|

### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home_move_plan.mpp/documentproperties/Title" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"link\": { \"href\": \"string\", \"rel\": \"string\", \"type\": \"string\", \"title\": \"string\" }, \"name\": \"Title\", \"value\": \"New title value\"}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {
  "code": 0,
  "status": "string",
  "property": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "name": "string",
    "value": "string"
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostDocumentProperty.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-postDocumentProperty.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "610639991b41e96363997321b1865acf" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "7b700f88cf2a478e1878321eee7c375d" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PostDocumentProperty.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PostDocumentProperty.java" >}}

{{< /tab >}}

{{< /tabs >}}
