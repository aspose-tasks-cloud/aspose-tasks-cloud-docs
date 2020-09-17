---
title: "Edit Document Property"
type: docs
url: /edit-document-property/
weight: 40
---

# **Introduction**
This example explains how to edit document property. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/documentproperties/{propertyName}|PUT|Update a property in a MS Project File|[PutDocumentProperty](https://apireference.aspose.cloud/tasks/#/TasksDocumentProperties/PutDocumentProperty)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home_move_plan.mpp/documentproperties/Title" 

-H "accept: application/json" 

-H "Content-Type: application/json" 

-H "x-aspose-client: Containerize.Swagger" 

-d "{ \"link\": { \"href\": \"string\", \"rel\": \"string\", \"type\": \"string\", \"title\": \"string\" }, \"name\": \"string\", \"value\": \"string\"}"

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
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "15665a7b58fffa7cc81b7b924df93186" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "de0d4be9c3e671154d01101d74579c41" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "54674008b0d4161980bfefc6838e3c31" >}}

{{< /tab >}}

{{< /tabs >}}
