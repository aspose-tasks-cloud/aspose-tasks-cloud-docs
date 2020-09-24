---
title: "Get VBA Project"
type: docs
url: /get-vba-project/
weight: 10
---

## **Introduction**
This example explains how to get VBA project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/vbaproject|GET|Read VBA Project from a MPP File|[GetVbaProject](https://apireference.aspose.cloud/tasks/#/TasksVbaProject/GetVbaProject)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/vbaproject" -H "accept: application/json" 

```
{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "vbaProject": {
    "compilationArguments": "string",
    "description": "string",
    "helpContextId": 0,
    "helpFile": "string",
    "modules": [
      {
        "attributes": [
          {
            "key": "string",
            "value": "string"
          }
        ],
        "name": "string",
        "sourceCode": "string"
      }
    ],
    "name": "string",
    "references": [
      {
        "libIdentifier": "string",
        "name": "string"
      }
    ]
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="3" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetVbaProject.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "07d0280d9d97b5c70e18f62948166c78" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "a8e269a4af19b5a5a90277ce3b31a7ff" >}}

{{< /tab >}}

{{< /tabs >}}
