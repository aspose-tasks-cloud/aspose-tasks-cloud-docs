---
title: "Get Timescaled Data for Assignment"
type: docs
url: /get-timescaled-data-for-assignment/
weight: 10
---

# **Introduction**
This example shows how to get timescaled data for an assignment with the specified UId using Aspose.Tasks Cloud API in your application. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}/timeScaleData|GET|Get timescaled data for an assignment with the specified Uid|[GetAssignmentTimephasedData](https://apireference.aspose.cloud/tasks/#/TasksAssignments/GetAssignmentTimephasedData)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/NewProductDev/assignments/27/timeScaleData?type=AssignmentWork" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Items": [

    {

      "Uid": 27,

      "Start": "2012-06-22T08:00:00+07:00",

      "Finish": "2012-06-23T08:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-06-23T08:00:00+07:00",

      "Finish": "2012-06-24T08:00:00+07:00",

      "Unit": "Day",

      "Value": "0",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-06-24T08:00:00+07:00",

      "Finish": "2012-06-25T08:00:00+07:00",

      "Unit": "Day",

      "Value": "0",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-06-25T08:00:00+07:00",

      "Finish": "2012-06-25T17:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-06-28T08:00:00+07:00",

      "Finish": "2012-06-29T08:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-06-29T08:00:00+07:00",

      "Finish": "2012-06-30T08:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-06-30T08:00:00+07:00",

      "Finish": "2012-07-01T08:00:00+07:00",

      "Unit": "Day",

      "Value": "0",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-07-01T08:00:00+07:00",

      "Finish": "2012-07-02T08:00:00+07:00",

      "Unit": "Day",

      "Value": "0",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-07-02T08:00:00+07:00",

      "Finish": "2012-07-03T08:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-07-03T08:00:00+07:00",

      "Finish": "2012-07-04T08:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-07-04T08:00:00+07:00",

      "Finish": "2012-07-05T08:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-07-05T08:00:00+07:00",

      "Finish": "2012-07-05T17:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    },

    {

      "Uid": 27,

      "Start": "2012-07-06T08:00:00+07:00",

      "Finish": "2012-07-06T17:00:00+07:00",

      "Unit": "Day",

      "Value": "40000",

      "TimephasedDataType": "TaskCost"

    }

  ],

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks-html/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskTimephasedData.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< /tabs >}}
