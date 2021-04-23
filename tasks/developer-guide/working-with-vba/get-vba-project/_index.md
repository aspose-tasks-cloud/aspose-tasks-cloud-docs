---
title: "Get VBA Project"
description: "Aspose.Tasks Cloud allows you to get vba project in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetVbaProject.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getVbaProject.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "07d0280d9d97b5c70e18f62948166c78" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a8e269a4af19b5a5a90277ce3b31a7ff" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetVbaProject.go" >}}

{{< /tab >}}

{{< /tabs >}}
