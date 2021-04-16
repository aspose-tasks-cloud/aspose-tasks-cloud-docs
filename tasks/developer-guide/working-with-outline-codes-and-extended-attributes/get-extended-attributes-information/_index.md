---
title: "Get Extended Attributes Information"
type: docs
url: /get-extended-attributes-information/
weight: 50
---

## **Introduction**
This example explains how to read extended attribute information from a MS Project File, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/extendedAttributes|GET|Read extended attribute information from a MS Project file|[GetExtendedAttributes](https://apireference.aspose.cloud/tasks/#/TasksExtendedAttributes/GetExtendedAttributes)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/extendedAttributes" -H "accept: application/json" 

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "extendedAttributes": {
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
        "index": 0,
        "fieldName": "string",
        "alias": "string",
        "fieldId": "string"
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

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetExtendedAttributes.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getExtendedAttributes.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "1498346f818a80aaa0a1996775baf525" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a6ab8a15d50208a5096eae5e0c9453c7" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetExtendedAttributes.go" >}}

{{< /tab >}}

{{< /tabs >}}
