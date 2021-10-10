---
title: "Get Timescaled Data for Task"
description: "Aspose.Tasks Cloud allows you to get timescaled data for task in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
keywords: "Timescaled Data, Task"
type: docs
url: /get-timescaled-data-for-task/
weight: 30
---

## **Introduction**
This example shows how to get timescaled data for a task with the specified UId using Aspose.Tasks Cloud API in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/timeScaleData|GET|Get timescaled data for a task with the specified Uid.|[GetTaskTimephasedData](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTaskTimephasedData)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/NewProductDev/tasks/27/timeScaleData?type=TaskWork" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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
      "start": "2020-09-19T12:44:08.169Z",
      "finish": "2020-09-19T12:44:08.169Z",
      "unit": "Minute",
      "value": "string",
      "timephasedDataType": "AssignmentRemainingWork"
    }
  ]
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetTaskTimephasedData.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getTaskTimephasedData.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "a7b683d3a695f8f407014a3b2524a67f" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "72f98159f9bad8159eb8803d5af4d05c" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetTaskTimephasedData.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-GetTaskTimephasedData.java" >}}

{{< /tab >}}

{{< /tabs >}}
