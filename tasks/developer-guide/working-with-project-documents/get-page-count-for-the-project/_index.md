---
title: "Get Page Count for the Project"
type: docs
url: /get-page-count-for-the-project/
weight: 60
---

## **Introduction**
This example allows you to get page count for the project to be rendered using specified time interval and given timescale. You can also specify Presentation format and Page size
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/pagecount|GET|Get the page count for the project|[GetPageCount](https://apireference.aspose.cloud/tasks/#/TasksDocument/GetPageCount)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/pagecount?pageSize=6&presentationFormat=4&timescale=1&startDate=2004-01-01&endDate=2019-01-01" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "pageCount": 0
}
```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetPageCount.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "28bbfdfb1186fb6a78b05b24c51b7ad4" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "15aac9e27cfa622da5e92281f6835c65" >}}

{{< /tab >}}

{{< /tabs >}}
