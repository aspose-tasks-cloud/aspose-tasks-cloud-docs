---
title: "Get a Document Property by Name"
type: docs
url: /get-a-document-property-by-name/
weight: 20
---

## **Introduction**
This example explains how to get a document property by name. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/documentproperties/{propertyName}|GET|Read property by name|[GetDocumentProperty](https://apireference.aspose.cloud/tasks/#/TasksDocumentProperties/GetDocumentProperty)|

### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/documentproperties/Title" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetDocumentProperty.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "db21486e30f9a5ae7d2d3ce91c94ec2a" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "274ea057be9155ce7b1b2391a1f069ba" >}}

{{< /tab >}}

{{< /tabs >}}
