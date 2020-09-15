---
title: "Get Timescaled Data for Resource"
type: docs
url: /get-timescaled-data-for-resource/
weight: 20
---

# **Introduction**
This example shows how to get timescaled data for a resource with the specified UId using Aspose.Tasks Cloud API in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources/{resourceUid}/timeScaleData|GET|Get timescaled data for a resource with the specified Uid|[GetResourceTimephasedData](https://apireference.aspose.cloud/tasks/#/TasksResources/GetResourceTimephasedData)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/NewProductDev/resources/1/timeScaleData?type=ResourceWork" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "code": 0,

  "status": "string",

  "items": [

    {

      "uid": 0,

      "start": "2020-04-18T14:33:04.203Z",

      "finish": "2020-04-18T14:33:04.203Z",

      "unit": "Minute",

      "value": "string",

      "timephasedDataType": "AssignmentRemainingWork"

    }

  ]

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskTimephasedData.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "265236f47d833b5e7c76da9f81f150a6" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "ea04ca6b05f6c1426cde22692c6161b4" >}}

{{< /tab >}}

{{< /tabs >}}
