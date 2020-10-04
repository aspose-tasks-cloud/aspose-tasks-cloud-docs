---
title: "Get Outline Codes Information"
type: docs
url: /get-outline-codes-information/
weight: 10
---

## **Introduction**
This example allows you to retrieve Outline codes information using Aspose.Tasks Cloud API in your applications. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/outlineCodes|GET|Read TaskOutline Codes from a MS Project File|[GetOutlineCodes](https://apireference.aspose.cloud/tasks/#/TasksOutlineCodes/GetOutlineCodes)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/outlineCodes" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java
{
  "code": 0,
  "status": "string",
  "outlineCodes": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "list": [
      {
        "link": {
          "href": "string",
          "rel": "string",
          "type": "string",
          "title": "string"
        },
        "index": 0
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
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-RetrieveCodeInformation-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-GetOutlineCodes-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "6a7997d7ce98aa224018166c317f9185" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "b9b5a2e9421c4f6d5332102622f08c85" >}}

{{< /tab >}}

{{< /tabs >}}
