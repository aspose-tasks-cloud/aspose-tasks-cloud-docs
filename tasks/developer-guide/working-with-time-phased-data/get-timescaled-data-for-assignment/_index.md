---
title: "Get Timescaled Data for Assignment"
type: docs
url: /get-timescaled-data-for-assignment/
weight: 10
---

## **Introduction**
This example shows how to get timescaled data for an assignment with the specified UId using Aspose.Tasks Cloud API in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}/timeScaleData|GET|Get timescaled data for an assignment with the specified Uid|[GetAssignmentTimephasedData](https://apireference.aspose.cloud/tasks/#/TasksAssignments/GetAssignmentTimephasedData)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/assignments/27/timeScaleData?type=TaskWork" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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
      "start": "2020-09-19T12:37:30.964Z",
      "finish": "2020-09-19T12:37:30.964Z",
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
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetAssignmentTimephasedData.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getAssignmentTimephasedData.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "9e069aa6974fa0e9b3dd81e45f4fab84" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "0b02ea998643db3c00540e0d4a486858" >}}

{{< /tab >}}

{{< /tabs >}}
