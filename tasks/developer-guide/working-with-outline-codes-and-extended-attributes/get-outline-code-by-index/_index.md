---
title: "Get Outline Code By Index"
type: docs
url: /get-outline-code-by-index/
weight: 20
---

## **Introduction**
This example allows you to get Outline Code by index using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/outlineCodes/{index}|GET|Read outline codes by index information from a MS Project file|[GetOutlineCodeByIndex](https://apireference.aspose.cloud/tasks/#/TasksOutlineCodes/GetOutlineCodeByIndex)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/outlineCodes/1" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "outlineCode": {
    "guid": "string",
    "fieldId": "string",
    "fieldName": "string",
    "alias": "string",
    "phoneticAlias": "string",
    "values": [
      {
        "valueId": 0,
        "fieldGuid": "string",
        "type": "Null",
        "parentValueId": 0,
        "value": "string",
        "description": "string",
        "isCollapsed": true
      }
    ],
    "enterprise": true,
    "enterpriseOutlineCodeAlias": 0,
    "resourceSubstitutionEnabled": true,
    "leafOnly": true,
    "allLevelsRequired": true,
    "onlyTableValuesAllowed": true,
    "masks": [
      {
        "level": 0,
        "type": "Null",
        "length": 0,
        "separator": "string"
      }
    ],
    "showIndent": true
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

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetOutlineCodeByIndex.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getOutlineCodeByIndex.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "8063d999260e8db44b685d7bc25fdefa" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "19ffc760e4231be39030ec751d5592cf" >}}

{{< /tab >}}

{{< /tabs >}}
