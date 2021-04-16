---
title: "Add Non-Existing Document Property"
type: docs
url: /add-non-existing-document-property/
weight: 50
---

## **Introduction**
This example explains how to add non-existing document property, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/documentproperties/{propertyName}|POST|Set/create document property|[PostDocumentProperty](https://apireference.aspose.cloud/tasks/#/TasksDocumentProperties/PostDocumentProperty)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home_move_plan.mpp/documentproperties/new%20property" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"link\": { \"href\": \"string\", \"rel\": \"string\", \"type\": \"string\", \"title\": \"string\" }, \"name\": \"new property\", \"value\": \"new property value\"}"

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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostDocumentPropertyNonExisting.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-postDocumentPropertyNonExisting.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "e663ff26c2349ef4a294cdea8b43ab23" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "7bcdeb1a0b8bde23351a07d316498f3c" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PostDocumentPropertyNonExisting.go" >}}

{{< /tab >}}

{{< /tabs >}}
