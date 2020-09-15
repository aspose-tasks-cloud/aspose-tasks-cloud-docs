---
title: "Get a Document Property by Name"
type: docs
url: /get-a-document-property-by-name/
weight: 20
---

# **Introduction**
This example explains how to get a document property by name. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/documentproperties/{propertyName}|GET|Read property by name|[GetDocumentProperty](https://apireference.aspose.cloud/tasks/#/TasksDocumentProperties/GetDocumentProperty)|

### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/documentproperties/Title" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjUyMDk3NTksImV4cCI6MTU2NTI5NjE1OSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.hl4CZ8kKgceOuRjwydQh87CCflf9Arca8io3L0OruC7N3rhSouJLZWDtyeGrtornpLerpVSN\_yokWJTdTBtHHW7i\_vt46wSJy5evh03ccWxUjXWsc3Tbt-T4sfWOtIYreET7hwE\_A-5AJoRPsyR8TKOHIGsbRZ2H5nX3XdEZgfcEFCV77RiHyIET4tlYtdplnjaFCBRHXCidgtbLzm0Bislejr5onrYS0DRz7XCxfndwaCfzxE0ylL1vHUkv41ZSmq1MnCVcmA2ZVno8-JeDjL1d8CdqORNCab5Yj\_Sz7S7z\_kDesrBGZ1uc4gpSYd6rz67apeG\_Wa6J8aKi3W9bnw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

   "Property":{

      "Name":"Title",

      "Value":"Home Move",

      "link":{

         "Href":"/documentProperties/Title",

         "Rel":"self",

         "Type":null,

         "Title":null

      }

   },

   "Code":200,

   "Status":"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
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
