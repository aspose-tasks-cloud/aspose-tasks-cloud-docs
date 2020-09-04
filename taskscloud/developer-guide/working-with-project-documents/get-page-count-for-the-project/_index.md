---
title: "Get Page Count for the Project"
type: docs
url: /get-page-count-for-the-project/
weight: 60
---

# **Introduction**
This example allows you to get page count for the project to be rendered using specified time interval and given timescale. You can also specify Presentation format and Page size
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/pagecount|GET|Get the page count for the project|[GetPageCount](https://apireference.aspose.cloud/tasks/#/TasksDocument/GetPageCount)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/pagecount?pageSize=6&presentationFormat=4&timescale=1&startDate=2004-01-01&endDate=2019-01-01" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjUyMDk3NTksImV4cCI6MTU2NTI5NjE1OSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.hl4CZ8kKgceOuRjwydQh87CCflf9Arca8io3L0OruC7N3rhSouJLZWDtyeGrtornpLerpVSN\_yokWJTdTBtHHW7i\_vt46wSJy5evh03ccWxUjXWsc3Tbt-T4sfWOtIYreET7hwE\_A-5AJoRPsyR8TKOHIGsbRZ2H5nX3XdEZgfcEFCV77RiHyIET4tlYtdplnjaFCBRHXCidgtbLzm0Bislejr5onrYS0DRz7XCxfndwaCfzxE0ylL1vHUkv41ZSmq1MnCVcmA2ZVno8-JeDjL1d8CdqORNCab5Yj\_Sz7S7z\_kDesrBGZ1uc4gpSYd6rz67apeG\_Wa6J8aKi3W9bnw"  

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"PageCount":4,"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks-html/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetPageCount.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< /tabs >}}
